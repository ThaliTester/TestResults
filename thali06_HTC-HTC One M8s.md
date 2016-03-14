#### Test 6275440319c4f54_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
W/Uploader( 1804): No account for auth token provided
,W/Uploader( 1804):  no longer exists, so no auth token.
W/Uploader( 1804): No account for auth token provided
E/cutils-trace( 6714): Error opening trace file: Permission denied (13)
W/Uploader( 1804): No account for auth token provided
D/CustomizationManager( 6714): ====startRecUseTime====
D/htc.customization.log.level( 6714):  is 
W/CustomizationLogLevel( 6714): Level value is invalid, use default level 2
D/CustomizationManager( 6714):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6714): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6714): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6714): Parsing tag category name = system
I/CustomizationCIDLoader( 6714): Parsing tag category name = application
I/CustomizationCIDLoader( 6714): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6714): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6714): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6714): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6714): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6714): add string-array item, value = 42507
I/CustomizationCIDLoader( 6714): add string-array item, value = 21902
I/CustomizationCIDLoader( 6714): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6714): add string-array item, value = 23420
I/CustomizationCIDLoader( 6714): add string-array item, value = 22299
I/CustomizationCIDLoader( 6714): add string-array item, value = 24002
I/CustomizationCIDLoader( 6714): add string-array item, value = 23210
I/CustomizationCIDLoader( 6714): add string-array item, value = 23205
I/CustomizationCIDLoader( 6714): add string-array item, value = 23806
I/CustomizationCIDLoader( 6714): add string-array item, value = 23430
I/CustomizationCIDLoader( 6714): add string-array item, value = 23408
I/CustomizationCIDLoader( 6714): add string-array item, value = 27205
I/CustomizationCIDLoader( 6714): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6714): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6714):  Read CID file spent 0.111 (s)
D/CustomizationManager( 6714):  All configurations done spent 0.112 (s)
I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Uploader( 1804): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1804): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1804): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1804): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1804): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1804): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1804): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1804): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
--------- beginning of system
I/ActivityManager(  935): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6714 on display 0
D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/PMS     (  935): acquireHCC(d32f088): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 935 1000 null
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/PMS     (  935): acquireHCC(352a0a21): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 935 1000 null
I/RemoteViews( 1220): reapply : com.google.android.gms 1 40
I/ActivityManager(  935): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6732 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  935): Display changed displayId=0
D/DotMatrix( 1335): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1335): [EventService] mbHDMIConnect: false, mCoverOn:false
W/Uploader( 1804): No account for auth token provided
I/TrimMemoryManager( 1628): [trimMemory] 20
I/WebViewFactory( 6732): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/PMS     (  935): releaseWL(26708158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): acquireWL(23fc275d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(23fc275d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): acquireWL(354948d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
I/LibraryLoader( 6732): Time to load native libraries: 10 ms (timestamps 4626-4636)
I/LibraryLoader( 6732): Expected native library version number "",actual native library version number ""
D/PMS     (  935): releaseWL(354948d2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
V/WebViewChromiumFactoryProvider( 6732): Binding Chromium to main looper Looper (main, tid 1) {31393cc8}
I/LibraryLoader( 6732): Expected native library version number "",actual native library version number ""
I/chromium( 6732): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6732): Initializing chromium process, singleProcess=true
W/art     ( 6732): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6732): ApplicationContext is null in ApplicationStatus
W/chromium( 6732): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6732): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6732): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6732): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6732): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6732): Local Branch: 
I/Adreno-EGL( 6732): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6732): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6732):                  d74aa161a12b9c6fc6332151
W/System.err(  935): java.lang.Throwable: stack dump
W/System.err(  935): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  935): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  935): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  935): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  935): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a6bae1b:true
D/BluetoothAdapter( 6732): 487153012: getState(). Returning 12
W/art     ( 6732): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6732): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6732): CordovaWebView is running on device made by: HTC
W/art     ( 6732): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6732): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  935): Activity pause timeout for ActivityRecord{28828e46 u0 com.test.thalitest/.MainActivity t12}
W/HtcSystemUPManager(  935): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/art     (  935): Explicit concurrent mark sweep GC freed 34946(1931KB) AllocSpace objects, 5(692KB) LOS objects, 33% free, 16MB/24MB, paused 1.664ms total 137.485ms
W/chromium( 6732): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/StatusBarManagerService(  935): setSystemUiVisibility(0xc0000600)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  935): hiding MENU key
D/StatusBarManagerService(  935): setSystemUiVisibility(0x8600)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  935): hiding MENU key
D/FindExtension( 6732): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6732): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@15ec7d09, mServedView=org.apache.cordova.engine.SystemWebView{21c02b0e VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@6c4c92f
I/InputMethodManagerService(  935): Disable input method client, pid=1628
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
D/StatusBarManagerService(  935): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6732): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  935): Displayed com.test.thalitest/.MainActivity: +800ms (total +837ms)
W/BindingManager( 6732): Cannot call determinedVisibility() - never saw a connection for the pid: 6732
D/JsMessageQueue( 6732): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6732): JniHelper::setJavaVM(0xab3908f8), pthread_self() = -1402181984,
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@276d16c3 added. We now have 1 listener(s)
,D/BluetoothManagerService(  935): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): setBluetoothMacAddress: 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6732): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6732): setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6732): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6732): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): load: ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Bluetooth MAC address: 90:E7:C4:F6:69:77
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11373be added. We now have 1 listener(s),
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6732): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  935): New client listening to asynchronous messages
E/WifiTrafficPoller(  935): ADD_CLIENT: 8
,D/BluetoothAdapter( 6732): 487153012: getState(). Returning 12
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6732): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6732): setScanMode: 1 -> 2
,D/BluetoothAdapter( 6732): 487153012: getState(). Returning 12
,I/chromium( 6732): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6732): Initializing JXcore engine,
W/jxcore-log( 6732): JXcore engine is ready
,W/jxcore-log( 6732): Starting JXcore engine,
,D/PMS     (  935): releaseHCC(d32f088): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  935): releaseHCC(352a0a21): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
D/HtcUPManager( 1220): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1545): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2a46645d,
,I/ActivityManager(  935): Killing 5518:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=5518
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 5518
,W/jxcore-log( 6732): Platform android,
W/jxcore-log( 6732): 
,W/jxcore-log( 6732): Process ARCH arm
W/jxcore-log( 6732): 
,I/jxcore-log( 6732): JXcore Cordova bridge is ready!
I/jxcore-log( 6732): 
W/jxcore-log( 6732): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6732): execute: REQUEST_ACCESS_COARSE_LOCATION,
,D/BluetoothAdapter( 6732): 487153012: getState(). Returning 12
V/io.jxcore.node.JXcoreExtension( 6732): isBleMultipleAdvertisementSupported: SUPPORTED
I/jxcore-log( 6732): WARN testUtils BLE multiple advertisement issue: null
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): INFO testUtils Toggling radios to: true,
I/jxcore-log( 6732): 
,D/BluetoothAdapter( 6732): enable(): BT is already enabled..!
,I/jxcore-log( 6732): Unit Test app is loaded,
I/jxcore-log( 6732): 
,D/WifiManager( 6732): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10195,
D/WifiService(  935): setWifiEnabled: true pid=6732, uid=10195
E/WifiService(  935): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  935): MONITOR_LOG
,I/WifiService(  935): isSprintWifiRestricted(): false
W/Settings:Agent(  935): name: wifi_on
I/WifiService(  935): isMdmWifiRestricted(): false
W/Settings:Agent(  935): value: 2
W/Settings:Agent(  935): >> traceCallingStack()
W/Settings:Agent(  935): Process.myPid(): 935
W/Settings:Agent(  935): Process.myTid(): 1788
W/Settings:Agent(  935): Process.myUid(): 1000
W/Settings:Agent(  935): 
W/Settings:Agent(  935): 
W/System.err(  935): java.lang.Throwable: stack dump
,I/chromium( 6732): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66),
,W/System.err(  935): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  935): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  935): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  935): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  935): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  935): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  935): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  935): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  935): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  935): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  935): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  935): 
W/Settings:Agent(  935): << traceCallingStack(): 21(ms)
D/WifiController(  935): handleMessage: E msg.what=155656
D/WifiManager( 6732): disconnect: Base Package Name=com.test.thalitest, uid=10195
D/WifiController(  935): processMsg: DeviceActiveState
D/WifiController(  935): processMsg: StaEnabledState
D/WifiController(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131145
D/WifiManager( 6732): reconnect: Base Package Name=com.test.thalitest, uid=10195
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_DISCONNECT 0 0
,W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DISCONNECT'
D/wpa_supplicant( 1317): wlan0: Cancelling scan request
D/wpa_supplicant( 1317): wlan0: Request to deauthenticate - bssid=f4:f2:6d:22:99:3e pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 1317): TDLS: Tear down peers
D/wpa_supplicant( 1317): wpa_driver_nl80211_disconnect(reason_code=3)
,D/wpa_supplicant( 1317): wlan0: Event DEAUTH (12) received
,D/wpa_supplicant( 1317): wlan0: Deauthentication notification
D/wpa_supplicant( 1317): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1317): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
,I/wpa_supplicant( 1317): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1317): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
E/wpa_supplicant( 1317): enter disconnect check
I/wpa_supplicant( 1317): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1317): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1317): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
E/WifiMonitor(  935): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
D/HTCRequest(  935): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2422
D/Tethering(  935): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
V/Tethering(  935): TetherInterfaceSM: wlan0: exit InitialState
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  935): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiMonitor(  935): WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  935): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbnetService(  935): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  935): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  935): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/PMS     (  935): acquireWL(71cb594): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
D/UsbnetService(  935): BroadcastReceiver::onReceive-
D/wpa_supplicant( 1317): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1317): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 1317): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1317): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1317): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x55a510af88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1317):    addr=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1317): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1317): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1317): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1317): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1317): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1317): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 1317): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1317): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1317): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1317): wlan0: State: DISCONNECTED -> DISCONNECTED
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
D/wpa_supplicant( 1317): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1317): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1317): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1317): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1317): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1317): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1317): nl80211: Ignore disconnect event triggered during reassociation
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  935): transitionTo: destState=DisconnectingState
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  935): invokeExitMethods: ConnectedState
E/WifiStateMachine(  935): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  935): release()
E/WifiStateM,achine(  935): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  935): setScanAlarm false period 20000 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  935): invokeExitMethods: L2ConnectedState
E/WifiStateMachine(  935): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  935): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  935): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1317): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1317): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1317): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/TetherSettings( 6024): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 6024): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6024): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 6024): Cust_ConnectToPC   : spcsc>false,
D/        ( 6024): Cust_ConnectToPC   : IPT>true
,D/PMS     (  935): releaseWL(71cb594): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/        ( 6024): Cust_ConnectToPC   : Singel_USB>false
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
,W/Settings( 6024): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,D/wpa_supplicant( 1317): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
,D/wpa_supplicant( 1317): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/SmartNS_Utility( 6024): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 6024): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6024): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  935): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1317): Power_Mode_Type mode = 0
I/wpa_supplicant( 1317): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiDataStallTracker(  935): setDhcpActive: false
,V/NativeCrypto( 1804): Read error: ssl=0x5598d48c30: I/O error during system call, Connection timed out
D/WifiP2pService(  935): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  935): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  935): acquireWL(b04983d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
W/ContextImpl( 6024): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
E/WifiStateMachine(  935): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  935): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/WifiStateMachine(  935): NetworkAgent != null
,E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 13
V/NetworkPolicy(  935): mWifiStateReceiver: meteredHint=false,EPS mode=false
,E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
D/WifiDataStallTracker(  935): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiDataStallTracker(  935): stopDataStallAlarm 
,E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 14
E/WifiDataStallTracker(  935): ENABLE_DATA_MONITOR_POLL false Token 3
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
,I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/SmartNS_Utility( 6024): setISNotification
,E/WifiStateMachine(  935): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1317): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1317): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
V/NativeCrypto( 1804): SSL shutdown failed: ssl=0x5598d48c30: I/O error during system call, Broken pipe
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1317): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/SmartNS_Utility( 6024): usb_cable_connect = 1
D/wpa_supplicant( 1317): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1317): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=4
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectingState
E/WifiStateMachine(  935): invokeEnterMethods: DisconnectingState
E/WifiStateMachine(  935):  Enter DisconnectingState State scan interval 300000 mEnableBackgroundScan= true screenOn=false
E/WifiStateMachine(  935): Start Disconnecting Watchdog 1
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131146
E/WifiStateMachine(  935): processMsg: DisconnectingState
,D/SmartNS_Utility( 6024): usb_denied = 0
E/WifiStateMachine(  935):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_RECONNECT 0 0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/wpa_supplicant( 1317): wlan0: Control interface command 'RECONNECT'
D/wpa_supplicant( 1317): Fast associate: Old scan results
D/wpa_supplicant( 1317): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 1317): wpa_supplicant_scan enter
D/wpa_supplicant( 1317): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 1317): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 1317): WPS: Building WPS IE for Probe Request
D/wpa_supplicant( 1317): WPS:  * Version (hardcoded 0x10)
D/wpa_supplicant( 1317): WPS:  * Request Type
D/wpa_supplicant( 1317): WPS:  * Config Methods (4288)
D/wpa_supplicant( 1317): WPS:  * UUID-E
D/wpa_supplicant( 1317): WPS:  * Primary Device Type
D/wpa_supplicant( 1317): WPS:  * RF Bands (3)
D/wpa_supplicant( 1317): WPS:  * Association State
D/wpa_supplicant( 1317): WPS:  * Configuration Error (0)
D/wpa_supplicant( 1317): WPS:  * Device Password ID (0)
D/wpa_supplicant( 1317): WPS:  * Manufacturer
D/wpa_supplicant( 1317): WPS:  * Model Name
D/wpa_supplicant( 1317): WPS:  * Model Number
D/wpa_supplicant( 1317): WPS:  * Device Name
D/wpa_supplicant( 1317): WPS:  * Version2 (0x20)
D/wpa_supplicant( 1317): P2P: * P2P IE header
D/wpa_supplicant( 1317): P2P: * Capability dev=25 group=00
D/wpa_supplicant( 1317): P2P: * Listen Channel: Regulatory Class 81 Channel 1
,D/ConnectivityService(  935): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
D/wpa_supplicant( 1317): wlan0: Add radio work 'scan'@0x55a510d680
D/wpa_supplicant( 1317): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1317): wlan0: Starting radio work 'scan'@0x55a510d680 after 0.000065 second wait
D/wpa_supplicant( 1317): wlan0: nl80211: scan request
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1317): Scan requested (ret=0) - scan timeout 30 seconds
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1317): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/wpa_supplicant( 1317): wlan0: nl80211: Scan trigger
D/wpa_supplicant( 1317): wlan0: Event SCAN_STARTED (49) received
D/wpa_supplicant( 1317): wlan0: Own scan request started a scan in 0.000205 seconds
I/wpa_supplicant( 1317): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147460
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiStateMachine(  935): processMsg: DisconnectingState
,E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  935): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor(  935): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/SmartNS_PSService( 6024): usb notificaiton:true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): ValidatedState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Validated
E/WifiStateMachine(  935):  DisconnectingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=219715
E/WifiStateMachine(  935): processMsg: ConnectModeState
,E/WifiStateMachine(  935):  ConnectModeState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=219717
E/WifiStateMachine(  935): ConnectModeState: Network connection lost 
E/WifiStateMachine(  935): transitionTo: destState=DisconnectedState
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
E/WifiStateMachine(  935): invokeExitMethods: DisconnectingState
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=4,Top=DisconnectedState
E/WifiStateMachine(  935): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  935): DisconnectedState call setCountryCode()
E/WifiStateMachine(  935):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 1317): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 1317): wlan0: Cancelling scan request
,I/ActionCombine( 6024): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/PMS     (  935): releaseWL(b04983d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:2
,D/wpa_supplicant( 1317): wlan0: nl80211: sched_scan request
D/SmartNS_Utility( 6024): usb_cable_connect = 1
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:2
D/SmartNS_Utility( 6024): usb_denied = 0
I/SmartNS_PSService( 6024): usb notificaiton:true
,E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1220): reapply : com.android.settings 3 36
D/SmartNS_NSReceiver( 6024): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/wpa_supplicant( 1317): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1317): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 1317): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 1317): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 1317): wlan0: nl80211: New scan results available
D/wpa_supplicant( 1317): nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700
D/wpa_supplicant( 1317): wlan0: Event SCAN_RESULTS (3) received
I/wpa_supplicant( 1317): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1317): wlan0: Scan completed in 0.071382 seconds
D/wpa_supplicant( 1317): nl80211: Received scan results (1 BSSes)
I/wpa_supplicant( 1317): [NULL] f4:f2:6d:22:99:3e freq=2422 level=-49
D/wpa_supplicant( 1317): wlan0: BSS: Start scan result update 7
D/wpa_supplicant( 1317): wlan0: BSS: Remove id 11 BSSID 00:16:a6:1e:e0:a4 SSID '' due to no match in scan
D/wpa_supplicant( 1317): BSS: last_scan_res_used=1/32
D/wpa_supplicant( 1317): wlan0: New scan results available (own=1 ext=0)
D/wpa_supplicant( 1317): WPS: AP f4:f2:6d:22:99:3e type 0 added
D/wpa_supplicant( 1317): WPS: AP[0] f4:f2:6d:22:99:3e type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1317): wlan0: Radio work 'scan'@0x55a510d680 done in 0.073372 seconds
D/wpa_supplicant( 1317): wlan0: Selecting BSS from priority group 732
D/wpa_supplicant( 1317): wlan0: 0: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-49 wps
D/wpa_supplicant( 1317): 0: f4:f2:6d:22:99:3e ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1317): wlan0:    selected based on RSN IE
W/wpa_supplicant( 1317): [EAP-MSG] EAP wpa_supplicant_check_sim@842: eap_methods not available
E/WifiStateMachine(  935): handleMessage: X,
D/wpa_supplicant( 1317):    selected WPA/WAPI AP f4:f2:6d:22:99:3e ssid='NG700'
D/wpa_supplicant( 1317): wlan0:    selected BSS f4:f2:6d:22:99:3e ssid='NG700'
E/WifiStateMachine(  935): handleMessage: E msg.what=131101
D/wpa_supplicant( 1317): wlan0: Considering connect request: reassociate: 1  selected: f4:f2:6d:22:99:3e  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0x55a510cc00  current_ssid=0x0
E/WifiStateMachine(  935): processMsg: DisconnectedState
D/wpa_supplicant( 1317): wlan0: Request association with f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 03
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=28): 33 1a ef 11 1b ff ff ff 00 00 00 00 00 00 00 00 00 00 00 00 00 00 04 06 e6 e7 0d 00
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 03 0d 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 34 16 03 0d 06 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317): WPA: WMM Parameter Element - hexdump(len=24): 00 50 f2 02 01 01 88 00 03 a4 00 00 27 a4 00 00 42 43 5e 00 62 32 2f 00
D/wpa_supplicant( 1317): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): TDLS: TDLS is allowed in the target BSS
D/wpa_supplicant( 1317): wlan0: Add radio work 'connect'@0x55a510d680
D/wpa_supplicant( 1317): wlan0: First radio work item in the queue - schedule start immediately
D/wpa_supplicant( 1317): wlan0: Starting radio work 'connect'@0x55a510d680 after 0.000033 second wait
I/wpa_supplicant( 1317): check if in concurrent case
I/wpa_supplicant( 1317): wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2422 MHz)
E/WifiStateMachine(  935):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
D/wpa_supplicant( 1317): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1317): wlan0: Cancelling sched scan
D/wpa_supplicant( 1317): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1317): wlan0: Cancelling scan request
D/wpa_supplicant( 1317): wpas_start_assoc_cb, 1892
D/wpa_supplicant( 1317): wpas_start_assoc_cb, 1895
D/wpa_supplicant( 1317): wpas_start_assoc_cb, 1910
D/wpa_supplicant( 1317): wlan0: WPA: clearing own WPA/RSN IE
W/ContextImpl(  935): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14146 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:14311 com.android.server.wifi.WifiStateMachine.access$6000:268 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8091 
D/wpa_supplicant( 1317): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 1317): RSN: PMKSA cache search - network_ctx=0x55a510cc00 try_opportunistic=0
D/wpa_supplicant( 1317): RSN: Search for BSSID f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): RSN: No PMKSA cache entry found
D/wpa_supplicant( 1317): wlan0: RSN: using IEEE 802.11i/D9.0
E/WifiStateMachine(  935):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/wpa_supplicant( 1317): wla,n0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/WifiStateMachine(  935): [MLHD] enter handleMediaLinkEvent DefaultState
D/wpa_supplicant( 1317): wlan0: WPA: Selected mgmt group cipher 32
D/WifiStateMachine(  935): Default got CMD_TETHER_STATE_CHANGE
D/wpa_supplicant( 1317): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1317): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 1317): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 1317): wlan0: WPA: using KEY_MGMT WPA-PSK
E/WifiStateMachine(  935): handleMessage: X
D/wpa_supplicant( 1317): wlan0: WPA: not using MGMT group cipher
D/wpa_supplicant( 1317): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1317): wlan0: State: SCANNING -> ASSOCIATING
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
D/wpa_supplicant( 1317): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1317): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
E/WifiStateMachine(  935): processMsg: DisconnectedState
D/wpa_supplicant( 1317): Limit connection to BSSID f4:f2:6d:22:99:3e freq=2422 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1317): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 1317): nl80211: Unsubscribe mgmt frames handle 0x888888dd2d984989 (mode change)
D/wpa_supplicant( 1317): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a510c100
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0104
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=040a
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=040b
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=040c
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=040d
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=090a
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:16:a6:1e:e0:a4]
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=090b
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=090c
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:16:a6:1e:e0:a4
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=090d
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=219784  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0409506f9a09
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=7f506f9a09
E/WifiMonitor(  935): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  935): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0801
E/WifiStateMachine(  935): processMsg: ConnectModeState
D/WifiMonitor(  935): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=040e
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=49 dispatchEvent: WPS-AP-AVAILABLE 
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=06
W/WifiMonitor(  935): couldn't identify event type - WPS-AP-AVAILABLE 
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0a07
D/WifiMonitor(  935): Event [IFNAME=wlan0 Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2422 MHz)]
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0a11
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=50 dispatchEvent: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2422 MHz)
D/wpa_supplicant( 1317): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a510c100 match=0a1a
D/wpa_supplicant( 1317): nl80211: Connect (ifindex=29)
D/wpa_supplicant( 1317):   * bssid=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317):   * bssid_hint=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317):   * freq=2422
D/wpa_supplicant( 1317):   * freq_hint=2422
D/wpa_supplicant( 1317):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 1317):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 1317):   * WPA Versions 0x2
D/wpa_supplicant( 1317):   * pairwise=0xfac04
D/wpa_supplicant( 1317):   * group=0xfac04
D/wpa_supplicant( 1317):   * akm=0xfac02
D/wpa_supplicant( 1317):   * Auth Type 0
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 1317): nl80211: set key mgmt offload, suite 2, support 0x0, psk 0x0x55a510cc3a
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSID
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=219785  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/WifiStateMachine(  935): handleMessage: X
D/WifiNetworkAgent(  935): NetworkAgent: NetworkAgent channel lost
I/RemoteViews( 1220): reapply : com.android.settings 1 36
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: DisconnectedState
D/wpa_supplicant( 1317): nl80211: Connect request send successfully
D/wpa_supplicant( 1317): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1317): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1317): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1317): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1317): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 1317): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 1317): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=219786  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  935): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  935): setDetailed state send new extra info"NG700"
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  935): NetworkAgent == null
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: DISCONNECTED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 16
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=219789  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147461
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=12 known=1 got=12 dur:86 bcn=0
E/WifiStateMachine(  935): processMsg: ConnectModeState
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 17
E/WifiStateMachine(  935):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=12 known=1 got=12 dur:86 bcn=0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=12 known=1 got=12 dur:86 bcn=0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  935):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=12 known=1 got=12 dur:86 bcn=0
D/WifiStateMachine(  935): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1317): wlan0: Control interface command 'LIST_DONGLES'
E/WifiStateMachine(  935): [1,457,968,525,425 ms] noteScanEnd no scan source
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/wpa_supplicant( 1317): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
E/WifiStateMachine(  935): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@88eac92 sup_state=SCANNING debouncing=false
E/WifiAutoJoinController (  935): NG700_GUEST f0:f2:6d:22:99:3e rssi=-47 cap [WPA2-PSK-CCMP][ESS] is not scored
E/WifiAutoJoinController (  935): NG700 f4:f2:6d:22:99:3e rssi=-49 cap [WPA2-PSK-CCMP][WPS][ESS] is not scored
E/WifiConfigStore(  935): updateSavedNetworkHistory(): try "NG700"WPA_PSK SSID="NG700" NG700 [WPA2-PSK-CCMP][WPS][ESS] ajst=0
E/WifiConfigStore(  935): updateSavedNetworkHistory: HTC improve mode
E/WifiConfigStore(  935):         got known scan result f4:f2:6d:22:99:3e key : "NG700"WPA_PSK num: 1 rssi=-49 freq=2422
E/WifiAutoJoinController (  935): ktwtestwifi 00:1f:27:54:70:c0 rssi=-55 cap [WPA2-EAP-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  935): TEST_KTW01 00:1f:27:54:70:c1 rssi=-56 cap [WPA2-EAP-TKIP][ESS] is not scored
E/WifiAutoJoinController (  935): RA-WINGS 00:1f:27:54:dd:e3 rssi=-74 cap [ESS] is not scored
E/WifiAutoJoinController (  935): RA-WINGS 00:22:0d:46:1c:a3 rssi=-77 cap [ESS] is not scored
E/WifiAutoJoinController (  935): RA-WINGS 00:1f:27:54:e0:43 rssi=-81 cap [ESS] is not scored
E/WifiAutoJoinController (  935):  00:1f:27:54:dd:e0 rssi=-73 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  935):  00:16:a6:1f:06:5c rssi=-74 cap [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS] is not scored
E/WifiAutoJoinController (  935):  00:1f:27:54:dd:e4 rssi=-74 cap [WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  935):  00:1f:27:54:e0:40 rssi=-79 cap [WPA-EAP-TKIP][WPA2-EAP-CCMP][ESS] is not scored
E/WifiAutoJoinController (  935): ageScanResultsOut delay 40000 size 12 now 1457968525430
E/WifiAutoJoinController (  935): newSupplicantResults size=11 known=1 true
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS-NO_EVENTS"
D/wpa_supplicant( 1317): wlan0: Control interface command 'STATUS-NO_EVENTS'
D/WISPrService( 6024): >>>>>WISPrService start isConnected = true<<<<<
E/WifiAutoJoinController (  935): attemptAutoJoin() status=wpa_state=ASSOCIATING
E/WifiAutoJoinController (  935): p2p_device_address=92:e7:c4:e6:4c:f8
E/WifiAutoJoinController (  935): address=XX:XX:XX:XX:XX:XX
E/WifiAutoJoinController (  935): uuid=12345678-9abc-def0-1234-56789abcdef1 split=4
E/WifiAutoJoinController (  935): attemptAutoJoin: bail out due to sup state wpa_state=ASSOCIATING
E/WifiConfigStore(  935):  writeKnownNetworkHistory() num networks:1 needWrite=false
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131213
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState CMD_TARGET_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219801
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935): processMsg: ConnectModeState
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935):  ConnectModeState CMD_TARGET_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219801
E/WifiStateMachine(  935): processMsg: DriverStartedState
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935):  DriverStartedState CMD_TARGET_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219802
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935):  SupplicantStartedState CMD_TARGET_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=219802
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=219803  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  935): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  935): setDetailed state send new extra info0x
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =SCANNING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 18
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  935): NetworkAgent == null
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=219808  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935): handleMessage: X
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 19
E/WifiTrafficPoller(  935): ADD_CLIENT: 9
D/WifiService(  935): New client listening to asynchronous messages
E/WifiStateMachine(  935): handleMessage: E msg.what=131131
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  935): handleMessage: X
W/WISPrService( 6024): can not find out wificonfig: SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6024): trigger connection
D/WISPrService( 6024): continue
D/ConnectivityService(  935): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  935): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524292
I/SecurityController( 1220): onLost 100
,D/usbnet  (  935): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  935): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/usbnet  (  935):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService(  935): Removing idletimer
D/WIFI    (  935):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  935): acquireWL(2ced3983): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 935 1000 null
D/WIFI    (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/CSLegacyTypeTracker(  935): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/usbnet  (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  935): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/ConnectivityService(  935): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WISPrService( 6024): start DataConnection
E/ConnectivityService(  935): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  935): ensureActiveMobilePolicyLocked()
D/libc    ( 6024): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/PMS     (  935): acquireWL(26d99700): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
D/libc    ( 6024): [NET] android_getaddrinfofornet-, err=8
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/Tethering(  935): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  935): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
D/NetworkPolicy(  935): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateIfacesLocked()
E/ConnectivityService(  935): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/DATA_ICON( 1220): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
V/NetworkPolicy(  935): updateNotificationsLocked()
D/libc    ( 6024): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6024): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6024): [NET] android_getaddrinfo_proxy+
D/libc    ( 6024): [NET] android_getaddrinfo_proxy get netid:0
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6024): [NET] android_getaddrinfo_proxy-, NODATA
D/NetworkManagementService(  935): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/PMS     (  935): releaseWL(26d99700): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
,D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATING, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,I/ActivityManager(  935): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=6800 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/libc    ( 6024): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6024): [NET] android_getaddrinfofornet-, err=8
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
,D/WISPrService( 6024): exception: java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1317): Wireless event: cmd=0x8c02 len=271
I/wpa_supplicant( 1317): WEXT: Custom wireless event: 'BEACONIEs='
,D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
D/wpa_supplicant( 1317): Wireless event: cmd=0x8c02 len=137
I/wpa_supplicant( 1317): WEXT: Custom wireless event: 'BEACONIEs='
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1317): Wireless event: cmd=0x8b15 len=24
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 wext ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=5 linkmode=1 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1317): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
D/wpa_supplicant( 1317): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1317): nl80211: Connect event
,D/wpa_supplicant( 1317): nl80211: Associated on 2422 MHz
D/wpa_supplicant( 1317): nl80211: Associated with f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): nl80211: Operating frequency for the associated BSS from scan results: 2422 MHz
D/wpa_supplicant( 1317): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 1317): wlan0: Association info event
D/wpa_supplicant( 1317): req_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): resp_ies - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): wlan0: freq=2422 MHz
D/wpa_supplicant( 1317): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): FT: Stored MDIE and FTIE from (Re)Association Response - hexdump(len=0):
D/wpa_supplicant( 1317): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1317): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1317): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1317): wlan0: Associated to a new BSS: BSSID=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 1317): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
I/wpa_supplicant( 1317): wlan0: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
D/wpa_supplicant( 1317): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 1317): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 1317): TDLS: Remove peers on association
D/wpa_supplicant( 1317): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1317): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1317): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1317): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1317): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1317): EAPOL: enable timer tick
D/wpa_supplicant( 1317): EAPOL: SUPP_BE entering state IDLE
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/wpa_supplicant( 1317): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 1317): wlan0: Cancelling scan request
D/wpa_supplicant( 1317): wlan0: Process pending EAPOL frame that was received just before association notification
D/wpa_supplicant( 1317): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wlan0: Setting authentication timeout: 10 sec 0 usec
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1317): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 1317): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1317): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 1317): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 1317):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1317):   key_nonce - hexdump(len=32): 18 8b 6e 58 1d 18 5e 9e ba e4 16 2a 15 1f f4 f1 ac 46 1a 06 66 af cc 12 01 29 7e e4 92 f5 d8 cb
D/wpa_supplicant( 1317):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1317):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/wpa_supplicant( 1317):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1317): wlan0: WPA: RX message 1 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
D/wpa_supplicant( 1317): RSN: msg 1/4 key data - hexdump(len=0):
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  935): Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=53 dispatchEvent: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
D/WifiMonitor(  935): WifiMonitor: Got associated with event from string: Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
D/WifiMonitor(  935): handleAssociatedWithEvent. Data= Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
E/WifiStateMachine(  935): processMsg: DisconnectedState
D/HTCRequest(  935): WifiMonitor:getSSIDFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
D/HTCRequest(  935): WifiMonitor:getFrequencyFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
,D/HTCRequest(  935): WifiMonitor:getFreqFromEventString() 2422
D/HTCRequest(  935): WifiMonitor:getMacFromString Associated with f4:f2:6d:22:99:3e ssid='NG700' freq=2422
D/WifiMonitor(  935): handleAssociatedWithEvent. Parsed MAC Address =f4:f2:6d:22:99:3e
D/WifiMonitor(  935): handleAssociatedWithEvent. bLFR =false
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=219917  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  935): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  935): processMsg: ConnectModeState
D/wpa_supplicant( 1317): WPA: Renewed SNonce - hexdump(len=32): 95 17 85 80 25 d2 8d 06 ae a0 93 8d d6 24 2f ec 6c 51 4a d1 f2 aa 07 97 0b 6b 17 82 85 20 fd b2
D/wpa_supplicant( 1317): WPA: Nonce1 - hexdump(len=32): 95 17 85 80 25 d2 8d 06 ae a0 93 8d d6 24 2f ec 6c 51 4a d1 f2 aa 07 97 0b 6b 17 82 85 20 fd b2
D/wpa_supplicant( 1317): WPA: Nonce2 - hexdump(len=32): 18 8b 6e 58 1d 18 5e 9e ba e4 16 2a 15 1f f4 f1 ac 46 1a 06 66 af cc 12 01 29 7e e4 92 f5 d8 cb
D/wpa_supplicant( 1317): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 1317): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1317): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 1317): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 1317): WPA: KCK - hexdump(len=16): [REMOVED]
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=219918  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/wpa_supplicant( 1317): WPA: Derived Key MIC - hexdump(len=16): 4b b5 a8 c6 4b 1d 0d 88 ab 57 c6 27 c6 e7 43 5d
I/wpa_supplicant( 1317): htc_wext_set_keepalive +
I/wpa_supplicant( 1317): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1317): getPrivFuncNum +	
I/wpa_supplicant( 1317): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1317): htc_wext_set_keepalive fnum = 0x8bf6
E/WifiStateMachine(  935): handleMessage: X
I/wpa_supplicant( 1317): htc_wext_set_keepalive - ret = 0
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  935): interfaceLinkStateChanged wlan0, false
D/Tethering(  935): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  935): interfaceLinkStateChanged wlan0, true
D/Tethering(  935): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/WifiMonitor(  935): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2422
V/Tethering(  935): TetherInterfaceSM: wlan0: enter InitialState
D/UsbDeviceManager(  935): [USBNET] bCheckSuppFunc: cdc_network
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/PMS     (  935): acquireWL(fe255fb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  935): handleMessage: E msg.what=147500
E/WifiStateMachine(  935): processMsg: DisconnectedState
D/wpa_supplicant( 1317): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 1317): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 1317): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 1317): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 1317):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 1317):   key_nonce - hexdump(len=32): 18 8b 6e 58 1d 18 5e 9e ba e4 16 2a 15 1f f4 f1 ac 46 1a 06 66 af cc 12 01 29 7e e4 92 f5 d8 cb
E/WifiStateMachine(  935):  DisconnectedState what:147500 0 0
D/wpa_supplicant( 1317):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
,D/wpa_supplicant( 1317):   key_rsc - hexdump(len=8): 14 1b 05 00 00 00 00 00
E/WifiStateMachine(  935): processMsg: ConnectModeState
D/wpa_supplicant( 1317):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317):   key_mic - hexdump(len=16): 12 49 c8 3f 8e a0 c2 37 02 d0 e2 33 7b dd 80 40
D/wpa_supplicant( 1317): RSN: encrypted key data - hexdump(len=56): 0f 39 43 71 67 37 a9 8e 64 44 25 3e 14 93 0b 89 ef e3 2e 2d bc f6 66 cb 51 4c a0 5b 14 22 d3 39 ...
D/wpa_supplicant( 1317): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 1317): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1317): wlan0: WPA: RX message 3 of 4-Way Handshake from f4:f2:6d:22:99:3e (ver=2)
D/wpa_supplicant( 1317): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00 dd 16 00 0f ac 01 01 00 71 e3 ...
,D/wpa_supplicant( 1317): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 0c 00
D/wpa_supplicant( 1317): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 1317): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 1317): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1317): WPA: Derived Key MIC - hexdump(len=16): e0 57 02 88 f0 7c f2 31 ed 8a a6 f3 cb 23 ba ab
E/WifiStateMachine(  935):  ConnectModeState what:147500 0 0
D/WifiStateMachine(  935): Enter handleAssociatedWithEvent
D/WifiStateMachine(  935): Associated
D/wpa_supplicant( 1317): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 1317): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x55a510d390 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1317): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1317): nl80211: KEY_SEQ - hexdump(len=6): 00 00 00 00 00 00
,D/wpa_supplicant( 1317):    addr=f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1317): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/FlexNetS( 6614): updateSvcAllowedInSettings:false
D/wpa_supplicant( 1317): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 1317): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1317): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 1317): WPA: RSC - hexdump(len=6): 14 1b 05 00 00 00
D/wpa_supplicant( 1317): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=3 addr=0x557e4f1e68 key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1317): nl80211: KEY_DATA - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 1317): nl80211: KEY_SEQ - hexdump(len=6): 14 1b 05 00 00 00
D/wpa_supplicant( 1317):    broadcast key
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
I/wpa_supplicant( 1317): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 1317): wlan0: Cancelling authentication timeout
,E/wpa_supplicant( 1317): wlan0: BLACKLIST REMOVE f4:f2:6d:22:99:3e
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
D/wpa_supplicant( 1317): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/wpa_supplicant( 1317): wlan0: Radio work 'connect'@0x55a510d680 done in 0.142953 seconds
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
I/wpa_supplicant( 1317): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
I/wpa_supplicant( 1317): setConcurrentAPChannel: Set wifi.hotspot.channel to 3
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  935): Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=56 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
W/WifiMonitor(  935): couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  935): Event [IFNAME=wlan0 BLACKLIST REMOVE f4:f2:6d:22:99:3e]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=57 dispatchEvent: BLACKLIST REMOVE f4:f2:6d:22:99:3e
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
E/wpa_supplicant( 1317): wlan0: Connect to SSID: NG700
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
E/WifiMonitor(  935): handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1317): nl80211: Set wlan0 operstate 0->1 (UP)
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1317): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=6 (IF_OPER_UP)
,D/WifiMonitor(  935): Event [IFNAME=wlan0 Connect to SSID: NG700]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=59 dispatchEvent: Connect to SSID: NG700
W/WifiMonitor(  935): couldn't identify event type - Connect to SSID: NG700
I/wpa_supplicant( 1317): set send_ind_to_ndc = 0
I/wpa_supplicant( 1317): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1317): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1317): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1317): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1317): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1317): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1317): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1317): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1317): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1317): nl80211: Set supplicant port authorized for f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1317): EAPOL authentication completed - result=SUCCESS
I/wpa_supplicant( 1317): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/Tethering(  935): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  935): interfaceLinkStateChanged wlan0, true
D/Tethering(  935): interfaceStatusChanged wlan0, true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1317): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=6 linkmode=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiMonitor(  935): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/HTCRequest(  935): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  935): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/UsbnetService(  935): BroadcastReceiver::onReceive+
D/WifiMonitor(  935): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/UsbnetService(  935): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  935): BroadcastReceiver::onReceive-
D/WifiStateMachine(  935): mAssociatedMacAddress = f4:f2:6d:22:99:3e
D/WifiStateMachine(  935): Exit handleAssociatedWithEvent
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=219932  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): setDetailed state send new extra info"NG700"
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
V/NetworkPolicy(  935): updateNotificationsLocked()
E/WifiStateMachine(  935): NetworkAgent == null
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =AUTHENTICATING wifi info = SSID: NG700, BSSID: 00:00:00:00:00:00, Supplicant state: ASSOCIATED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 20
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  935): processMsg: ConnectModeState
D/PMS     (  935): releaseWL(fe255fb): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=219939  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine(  935): handleMessage: X
,E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: DisconnectedState
E/WifiStateMachine(  935):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=219940  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  935): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  935): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=219941  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147459
E/WifiStateMachine(  935): processMsg: DisconnectedState
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  935):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=219942
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=219942
E/WifiStateMachine(  935): Network connection established
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 21
D/WifiStateMachine(  935): fetchFrequency(), freq = 2422
E/WifiStateMachine(  935): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
E/WifiStateMachine(  935): NetworkAgent == null
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
D/FlexNetS( 6614): updateSvcAllowedInSettings:false
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 22
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): transitionTo: destState=ObtainingIpState
,E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 23
D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  935): invokeExitMethods: DisconnectedState
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET pno 0'
D/wpa_supplicant( 1317): CTRL_IFACE SET 'pno'='0'
E/WifiStateMachine(  935): setScanAlarm false period 0 initial delay 0mAlarmEnabledfalse
E/WifiStateMachine(  935): moveTempStackToStateStack: i=1,j=4
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=5
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=ObtainingIpState
E/WifiStateMachine(  935): invokeEnterMethods: L2ConnectedState
E/WifiStateMachine(  935): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935): NetworkAgent == null
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTING wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 24
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
D/ConnectivityService(  935): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  935): L2ConnectedState f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  935): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  935): Got NetworkAgent Messenger
W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/ConnectivityService(  935): NetworkAgent connected
D/wpa_supplicant( 1317): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1317): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1317): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 1317): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1317): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  935): invokeEnterMethods: ObtainingIpState
E/WifiStateMachine(  935): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  935): ObtainingIpAddress f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  935): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  935): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  935): QCOM Debug skip set_network part for security concern!
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
D/wpa_supplicant( 1317): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1317): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1317): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1317): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1317): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1317): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
,D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935): Start Dhcp Watchdog 2
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131101
E/WifiStateMachine(  935): processMsg: ObtainingIpState
E/WifiStateMachine(  935):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: GROUP_HANDSHAKE, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiStateMachine(  935):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  935): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  935): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=147462
E/WifiStateMachine(  935): processMsg: ObtainingIpState
E/WifiStateMachine(  935):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=219977  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=219978  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
E/WifiStateMachine(  935): processMsg: ConnectModeState,
E/WifiStateMachine(  935):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=219979  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131212
E/WifiStateMachine(  935): processMsg: ObtainingIpState
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiStateMachine(  935):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine(  935): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
E/WifiStateMachine(  935): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  935): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  935): handleMessage: X
D/WifiStateMachine(  935): handlePreDhcpSetup Held wake lock during DHCP
E/WifiStateMachine(  935): handleMessage: E msg.what=196612
D/PMS     (  935): acquireWL(2b15e265): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 935 1000 null
E/WifiStateMachine(  935): processMsg: ObtainingIpState
,D/WifiStateMachine(  935): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false,
E/WifiStateMachine(  935):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiDataStallTracker(  935): setDhcpActive: true
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
D/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 8192
D/WISPrService( 6024): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  935): setSuspendOptimizationsNative: 1 false -want false stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  935): do suspend false
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiP2pService(  935): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@881d4ed target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/WifiP2pService(  935): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@881d4ed target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER POWERMODE 1'
I/wpa_supplicant( 1317): INFO - Deny active power mode because already has gateway
D/FlexNetS( 6614): updateSvcAllowedInSettings:false
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1317): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1317): nl80211: Rekey offload event for BSSID f4:f2:6d:22:99:3e
D/wpa_supplicant( 1317): nl80211: Rekey offload - Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 1317): wlan0: Event DRIVER_GTK_REKEY (37) received
E/WifiStateMachine(  935): Unexpected BatchedScanResults :null
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WISPrService( 6024): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiStateMachine(  935): noteBatchedScanstop()
E/WifiStateMachine(  935): handleMessage: X
I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:0
,D/WifiService(  935): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,I/QuickSettingWifi( 1220): receive.wifiConnect:false wifiAPname:null elapse:1
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/TetherSettings( 6024): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 6024): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 6024): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 6024): Cust_ConnectToPC   : spcsc>false
W/ContextImpl( 6024): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 6024): Cust_ConnectToPC   : IPT>true
D/        ( 6024): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 6024): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 6024): hasRemovableStorageSlot: true
D/SmartNS_Utility( 6024): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 6024): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,I/SmartNS_Utility( 6024): setISNotification
D/SmartNS_Utility( 6024): usb_cable_connect = 1
,D/SmartNS_Utility( 6024): usb_denied = 0
I/SmartNS_PSService( 6024): usb notificaiton:true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 6024): usb_cable_connect = 1
D/SmartNS_Utility( 6024): usb_denied = 0
I/SmartNS_PSService( 6024): usb notificaiton:true
E/WifiStateMachine(  935): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1220): reapply : com.android.settings 1 36
,D/SmartNS_NSReceiver( 6024): Tethered state change:false isNSOpening:false
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1220): reapply : com.android.settings 1 36,
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false,
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/MdScPhnSt( 6800): [dae.2.]  listen tmrbb8
,D/MdProvGlob( 6677): add item 101 (2:g3d25) for 15:android.intent.action.ANY_DATA_STATE
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,D/FlexNetS( 6614): updateSvcAllowedInSettings:false
,E/dhcpcd  ( 6828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6828): version 5.5.6 starting
,E/dhcpcd  ( 6828): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6828): wlan0: using ClientID 01:90:**:c4:e6:4c:f8
I/dhcpcd  ( 6828): autoip env[11]:autoip=DISABLE
,D/MdProvGlob( 6677): remove item 101 (p3d2in78) for 15:android.intent.action.ANY_DATA_STATE
D/MdScDataSum( 6800): [dae.2.] summary 118:p3 ignore
,I/dhcpcd  ( 6828): wlan0: rebinding lease of 192.168.1.102,
I/dhcpcd  ( 6828): wlan0: sending REQUEST (xid 0x810eb420), next in 0.06 seconds
,I/ActivityManager(  935): Killing 6471:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  935): killProcessQuiet, pid=6471
,D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/dhcpcd  ( 6828): wlan0: acknowledged 192.168.1.102 from 192.168.1.1,
,I/dhcpcd  ( 6828): wlan0: leased 192.168.1.102 for 172800 seconds
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  935): handleMessage: E msg.what=131212
E/WifiStateMachine(  935): processMsg: ObtainingIpState
D/ConnectivityService(  935): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/dhcpcd  ( 6828): autoip env[11]:autoip=DISABLE
E/WifiStateMachine(  935):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): processMsg: DefaultState
,E/WifiStateMachine(  935):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine(  935): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine(  935): handleMessage: X
I/ActivityManager(  935): Recipient 6471
,I/dhcpcd  ( 6828): bind_interface: daemonise
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4,
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  935): handleMessage: E msg.what=196613
E/WifiStateMachine(  935): processMsg: ObtainingIpState,
E/WifiStateMachine(  935):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiP2pService(  935): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935): processMsg: L2ConnectedState
D/WifiP2pService(  935): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  935):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine(  935): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/PMS     (  935): releaseWL(2b15e265): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1317): Power_Mode_Type mode = 0
I/wpa_supplicant( 1317): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1317): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  935): setDhcpActive: false
E/WifiStateMachine(  935): handlePostDhcpSetup release wake lock during DHCP
E/WifiStateMachine(  935): WifiStateMachine DHCP successful
E/WifiStateMachine(  935): wifistatemachine handleIPv4Success <IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds>
D/ConnectivityService(  935): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  935): link address 192.168.1.102/24
E/WifiStateMachine(  935): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  935): gateway: /192.168.1.1
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
D/wpa_supplicant( 1317): wlan0: Control interface command 'DRIVER GATEWAY-ADD 16885952'
I/wpa_supplicant( 1317): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1317): htc_wext_set_keepalive +
I/wpa_supplicant( 1317): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1317): getPrivFuncNum +	
I/wpa_supplicant( 1317): getPrivFuncNum -, cmd = 0x8bf6
,I/wpa_supplicant( 1317): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1317): get_ip_address source addr = c0a80166
I/wpa_supplicant( 1317): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1317): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  935): [MLHD] enter handleMediaLinkEvent L2ConnectedState
E/WifiStateMachine(  935): handleMessage: X
E/WifiStateMachine(  935): handleMessage: E msg.what=131210
E/WifiStateMachine(  935): processMsg: ObtainingIpState
E/WifiStateMachine(  935):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1317): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1317): environment dirty rate=20 [5][1][0]
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 150
E/WifiStateMachine(  935): fetchRssiLinkSpeedAndFrequencyNative rssi=-52 linkspeed=150
,E/WifiConfigStore(  935): updateConfiguration freq=2422 BSSID=f4:f2:6d:22:99:3e RSSI=-50 "NG700"WPA_PSK
W/WifiHW  (  935): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
D/WIFI_ICON( 1220): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiWatchdogStateMachine(  935): RSSI current: 3 new: -52, 3
D/wpa_supplicant( 1317): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1317): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  935): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
E/WifiMonitor(  935): WifiMonitor:wlan0 cnt=61 dispatchEvent: BLACKLIST CLEAR 
,E/WifiStateMachine(  935): setDetailed state, old =CONNECTING and new state=CONNECTED hidden=false
,D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
E/WifiStateMachine(  935): NetworkAgent != null
D/ConnectivityService(  935): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -52, Link speed: 150, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiStateMachine(  935): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: f4:f2:6d:22:99:3e, Supplicant state: COMPLETED, RSSI: -52, Link speed: 150, Frequency: 2422, Net ID: 0, Metered hint: false
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 25
D/WifiDataStallTracker(  935): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/HtcWifiWanDetect(  935): WAN detection
D/ConnectivityService(  935): Adding iface wlan0 to network 101
,I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
V/NetworkPolicy(  935): mWifiStateReceiver: meteredHint=false,EPS mode=false
,D/HtcWifiWanDetect(  935): canDoWanDetection: mHtcWanDetectionDialogEnabled: true mHtcWanDetectionEnabled: true
,E/WifiDataStallTracker(  935): ENABLE_DATA_MONITOR_POLL true Token 4
E/WifiDataStallTracker(  935): ENABLE_DATA_MONITOR_POLL: Do NOT run data monitor 
,E/WifiStateMachine(  935): transitionTo: destState=ConnectedState
,D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  935): handleMessage: new destination call exit/enter
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  935): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
V/NetworkPolicy(  935): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  935): invokeExitMethods: ObtainingIpState
D/WIFI_ICON( 1220): updateWifiState: NETWORK_STATE_CHANGED connected
E/WifiStateMachine(  935): moveTempStackToStateStack: i=0,j=5
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  935): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=5,Top=ConnectedState
E/WifiStateMachine(  935): invokeEnterMethods: ConnectedState
E/WifiStateMachine(  935): updateDefaultRouteMacAddress found Ipv4 default :192.168.1.1
E/WifiTrafficPoller(  935): ENABLE_TRAFFIC_STATS_POLL false Token 26
E/WifiStateMachine(  935): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/IntentController( 1220): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 6024): >>>>>WISPrService start isConnected = true<<<<<
,E/WifiStateMachine(  935): ConnectedState Enter  mScreenOn=false scanperiod=20000,
E/ConnectivityService(  935): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  935): handleMessage: X
D/ConnectivityService(  935): Adding Route [fe80::/64 -> :: wlan0] to network 101
E/WifiStateMachine(  935): handleMessage: E msg.what=131131
D/ConnectivityService(  935): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  935): processMsg: ConnectedState
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  935):  ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  935): handleMessage: X
D/ConnectivityService(  935): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(),hints(known),family 0,flags 4
,D/ConnectivityService(  935): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
D/Nat464Xlat(  935): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/WISPrService( 6024): >>>>>WISPrService start isConnected = true<<<<<
D/ConnectivityService(  935): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x3139322e313638),sn(53),hints(known),family 0,flags 4
D/ConnectivityService(  935): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/ConnectivityService(  935): rematching NetworkAgentInfo [WIFI () - 101]
I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:NG700 elapse:2
D/ConnectivityService(  935):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/usbnet  (  935): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  935):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Connected
D/ConnectivityService(  935): currentScore = 0, newScore = 20
D/ConnectivityService(  935):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  935): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Validated
D/WIFI    (  935): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  935): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/WIFI    (  935):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935): sendGeneralBroadcast, restrictEnable=false
D/WIFI    (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  935):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935): sendGeneralBroadcastDelayed, restrictEnable=false
D/usbnet  (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,D/ConnectivityService(  935): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  935): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  935): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering(  935): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/PMS     (  935): acquireWL(1212f106): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null
V/NetworkPolicy(  935): ensureActiveMobilePolicyLocked()
,D/ConnectivityService(  935): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): ValidatedState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  935): Validated
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DATA_ICON( 1220): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:1/Status:0
D/ConnectivityService(  935): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  935): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  935):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
D/ConnectivityService(  935): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
,D/ConnectivityService(  935): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  935): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  935): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  935):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WIFI    (  935): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/WIFI    (  935):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkPolicy(  935): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/usbnet  (  935): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  935): updateNetworkEnabledLocked()
D/usbnet  (  935):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  935): updateIfacesLocked()
D/usbnet  (  935): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NetworkPolicy(  935): updateNotificationsLocked()
I/QuickSettingWifi( 1220): receive.wifiConnect:true wifiAPname:NG700 elapse:1
I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/PMS     (  935): releaseWL(1212f106): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524290
D/DATA_ICON( 1220): updateConnectivity android.net.conn.INET_CONDITION_ACTION Type:1/Status:100
,D/NetworkManagementService(  935): isBandwidthControlEnabled: doneSignal.getCount()= 0
I/SecurityController( 1220): onAvailable 101 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
,D/DATA_ICON( 1220): dataConnected: false/false
D/StatusBar.NetworkController( 1220): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/wpa_supplicant( 1317): EAPOL: startWhen --> 0
D/wpa_supplicant( 1317): EAPOL: disable timer tick
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  935): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  935): handleMessage: E msg.what=131212
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  935): processMsg: ConnectModeState
,E/WifiStateMachine(  935):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine(  935): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,fe80::92e7:c4ff:fee6:4cf8/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  935): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  935): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,E/WifiStateMachine(  935): handleMessage: X
D/ConnectivityService(  935): identical MTU - not setting
D/Nat464Xlat(  935): requiresClat: netType=1, connected=true, mIsClatEnabled=true, hasIPv4Address=true
D/ConnectivityService(  935): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  935): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524295
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  935):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  935): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1220): CM callback handler got msg 524295
,D/PMS     (  935): releaseWL(2ced3983): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  935): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider(  935): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  935): [AlarmQueuing] connectivity wifi: false
D/GpsLocationProvider(  935): [handleMessage] UPDATE_NETWORK_STATE
D/PMS     (  935): acquireWL(2824a3c7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 935 1000 null
D/GpsLocationProvider(  935): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/PMS     (  935): acquireWL(346a8df4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 935 1000 null
D/htcCheckinService(  935): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/PMS     (  935): releaseWL(346a8df4): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConnectivityHelper( 1628): [onReceive] WIFI(1): CONNECTED
,I/ActivityManager(  935): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6862 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,E/GpsLocationProvider(  935): No APN found to select.
,D/PMS     (  935): releaseWL(2824a3c7): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/art     (  409): Explicit concurrent mark sweep GC freed 8640(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 229us total 46.263ms
,D/MdScPhnSt( 6800): [c96.1.]  listen tmrbb8,
,D/MdScDataSum( 6800): [c96.1.] summary 118:p1 ignore,
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 247us total 22.356ms,
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 166us total 22.048ms,
,I/MusicStore( 6862): Database version: 120,
,D/VoldConnector(  935): SND -> {31 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  935): SND -> {32 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/,
W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  935): SND -> {33 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 6862): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 6862): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6862): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 6862): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 6862): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/System  ( 6862): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9e95ce: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 6862): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6862): GMSCore installation verified
,I/ConfigStore( 6862): Config Database version: 1,
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=6862, uid=10159, userID:0,
,D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
,D/MediaRouterService(  935): Client com.google.android.music (pid 6862): Registered,
,D/WifiDisplayAdapter(  935): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  935):     Client/Owner: Client
D/WifiDisplayAdapter(  935):     GroupId: 
D/WifiDisplayAdapter(  935):     Passphrase: 
D/WifiDisplayAdapter(  935):     SessionId: 0
D/WifiDisplayAdapter(  935):     IP Address: }
,I/MediaRouter( 6862): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,V/MusicLeanback( 6862): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true
,D/AutoSetting( 1545): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=6862, uid=10159, userID:0
,I/ActivityManager(  935): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6899 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a
,D/AutoSetting( 1545): service - onCreate()
,D/AutoSetting( 1545): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1545): service - onStartCommand() screen is off, don't request location,
,D/LocationManagerService(  935): request 81a9e11 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10052)
D/LocationManagerService(  935): provider request: passive ProviderRequest[ON interval=0]
,I/GHttpClientFactory( 6862): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6862): Using platform SSLCertificateSocketFactory
,D/PhoneMonitor( 6899): Register our PhoneStateListener,
,D/MobileConnectivityChangeReceiver( 6899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,D/MobileConnectivityChangeReceiver( 6899): onReceive CONNECTIVITY_CHANGE networkType=1
,D/Process (  935): killProcessQuiet, pid=6426
I/ActivityManager(  935): Killing 6426:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 6899): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false,
,D/PhoneMonitor( 6899): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false,
,I/ActivityManager(  935): Recipient 6426
,D/PMS     (  935): acquireWL(286ef87): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4366 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(2ab98add): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4366 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  935): releaseWL(286ef87): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4366): Checking schedule, now: 1457968529467 next: 1457968437139
,I/CheckinService( 4366): active receiver: enabled
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4366, uid=10024, userID:0
,I/CheckinService( 4366): Preparing to send checkin request,
I/EventLogService( 4366): Accumulating logs since 1457968404056,
,D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 4,
D/libc    (  935): [NET] android_getaddrinfofornet-, err=8
D/libc    (  935): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  935): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  935): [NET] android_getaddrinfo_proxy+
D/libc    (  935): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  397): [NET] android_getaddrinfofornet+,hn 11(0x7777772e687463),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/ChimeraCfgMgr( 4366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4366): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,D/ConnectivityService(  935): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/CheckinRequestBuilder( 4366): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  935): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6930 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a,
I/ActivityManager(  935): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4366): Failed to find provider info for com.google.android.wearable.settings
,D/GpsLocationProvider(  935): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  935): [AlarmQueuing] connectivity wifi: true
,D/PMS     (  935): acquireWL(1bb4487f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 935 1000 null,
D/PMS     (  935): acquireWL(b13c04c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 935 1000 null
,D/PMS     (  935): releaseWL(b13c04c): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/GpsLocationProvider(  935): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  935): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
,D/libc    ( 6519): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 6519): [NET] android_getaddrinfofornet-, err=8
,I/ConnectivityHelper( 1628): [onReceive] WIFI(1): CONNECTED
D/libc    ( 6519): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 6519): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6519): [NET] android_getaddrinfo_proxy+
D/libc    ( 6519): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/htcCheckinService(  935): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
I/NetworkMonitor( 6862): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  935): No APN found to select.
,D/PMS     (  935): releaseWL(1bb4487f): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/MdScPhnSt( 6800): [e34.1.]  listen tmrbb8
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/HtcWifiWanDetect(  935): Find DNS Address www.htc.com/23.59.123.86
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/MdScDataSum( 6800): [e34.1.] summary 118:p1 ignore
D/libc    (  935): [NET] android_getaddrinfo_proxy-, success
D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 6519): [NET] android_getaddrinfo_proxy-, success,
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6519): connection state changed from UNKNOWN to CONNECTED,
,W/CheckinRequestBuilder( 4366): awaiting user notification for token
,D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/ActivityManager(  935): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6956 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 6956): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6956): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/VoldConnector(  935): SND -> {34 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  935): SND -> {35 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl( 6930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/MultiDex( 6956): VM with version 2.1.0 has multidex support,
I/MultiDex( 6956): install
I/MultiDex( 6956): VM has multidex support, MultiDex support library is disabled.
,I/GAv4    ( 6930): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6930):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6930):   adb logcat -s GAv4
,D/VoldConnector(  935): SND -> {36 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
,E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 6930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,D/VoldConnector(  935): SND -> {37 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 6930): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files,
,V/JNIHelp ( 6956): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/GAv4    ( 6930): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6930): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6930): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,W/ActivityThread( 6956): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6956): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@238b2c04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6956): Installed default security provider GmsCore_OpenSSL
,I/art     (  935): Explicit concurrent mark sweep GC freed 54092(2MB) AllocSpace objects, 5(164KB) LOS objects, 33% free, 16MB/24MB, paused 2.620ms total 226.726ms
,I/RemoteViews( 1220): reapply : com.google.android.gms 2 40,
,W/global  ( 6930): [apache-http] Connection GC has been deprecated!,
,W/global  ( 6930): [apache-http] Connection GC has been deprecated!,
,I/jxcore-log( 6732): My device name is: HTC-HTC One M8s
I/jxcore-log( 6732): 
,I/WVCdm   (  403): CdmEngine::OpenSession
I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,D/DrmWidevineDash(  403): Service_Initialize: starts!
,D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE,
,I/WebViewFactory( 6930): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/QSEECOMAPI: (  403): Loaded image: APP id = 10
,D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49f6000
E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49f6000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  479): got the req here! ret=0,
D/DrmLibTime(  479): command id, time_cmd_id = 770
D/DrmLibTime(  479): time_getutcsec starts!
D/DrmLibTime(  479): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  479): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  479): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  479): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  479): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  479): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  479): QSEE Time Listener: Retrieved Android system time: 1457968530
D/DrmLibTime(  479): time_getutcsec returns 0, sec = 1457968530; nsec = 0
,D/DrmLibTime(  479): time_getutcsec finished! 
D/DrmLibTime(  479): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  479): before calling ioctl to read the next time_cmd
E/QC-time-services(  425): Daemon: Time-services: Waiting to acceptconnection
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9,
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/LibraryLoader( 6930): Time to load native libraries: 2 ms (timestamps 4648-4650)
I/LibraryLoader( 6930): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6930): Binding Chromium to main looper Looper (main, tid 1) {187e8b0f},
,I/LibraryLoader( 6930): Expected native library version number "",actual native library version number "",
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xf35ea928
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab6eb978, dataLength=8,
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab7b01b0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab6ea250, idLength=0xffd4de68
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,I/chromium( 6930): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xffd4de7e, maximum = 0xffd4de7f
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffd4deec
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=2009176412
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab6e1370
D/DrmWidevineDash(  403): message_length=1611, signature=0xab6e19c0, signature_length=0xffd4de4c
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,E/WifiStateMachine(  935): handleMessage: E msg.what=131168,
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine(  935): handleMessage: X
I/BrowserStartupController( 6930): Initializing chromium process, singleProcess=true
,W/art     ( 6930): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6930): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6930): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6930): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6930): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6930): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6930): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6930): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6930): Local Branch: 
I/Adreno-EGL( 6930): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6930): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6930):                  d74aa161a12b9c6fc6332151
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  403): CdmEngine::CloseSession
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 10
,D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
,W/AudioManagerAndroid( 6930): Requires BLUETOOTH permission
,I/NSApplication( 6930): Starting up...
,E/cutils-trace( 7016): Error opening trace file: Permission denied (13)
,I/dex2oat ( 7016): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7016): dex2oat: override thread count:4
,I/ActivityManager(  935): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7021 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/dex2oat ( 7016): dex2oat took 71.779ms (threads: 4),
,I/Adreno-EGL( 6956): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
,I/Adreno-EGL( 6956): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6956): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6956): Local Branch: 
I/Adreno-EGL( 6956): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6956): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6956):                  d74aa161a12b9c6fc6332151
,I/Adreno-EGL( 6956): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6956): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6956): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6956): Local Branch: 
I/Adreno-EGL( 6956): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6956): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6956):                  d74aa161a12b9c6fc6332151
,I/WVCdm   (  403): CdmEngine::OpenSession,
I/WVCdm   (  403): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  403): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  403): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  403): Service_Initialize: starts!
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
E/QSEECOMAPI: (  403): Error::Cannot open the file /vendor/firmware/widevine.mdt,
E/QSEECOMAPI: (  403): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  403): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  403): App is not loaded in QSEE
,D/QSEECOMAPI: (  403): Loaded image: APP id = 11,
D/DrmWidevineDash(  403): Service_Initialize: ends! returns 0,
,D/QSAPPSVER(  403): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  403): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  403): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49f6000
E/DrmWidevineDash(  403): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf49f6000
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  479): got the req here! ret=0,
D/DrmLibTime(  479): command id, time_cmd_id = 770
D/DrmLibTime(  479): time_getutcsec starts!
D/DrmLibTime(  479): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  479): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  479): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  479): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  479): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  479): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  479): QSEE Time Listener: Retrieved Android system time: 1457968530
D/DrmLibTime(  479): time_getutcsec returns 0, sec = 1457968530; nsec = 0
D/DrmLibTime(  479): time_getutcsec finished! 
D/DrmLibTime(  479): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  479): before calling ioctl to read the next time_cmd
E/QC-time-services(  425): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  403): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: starts! SID=0xf35ea928
D/DrmWidevineDash(  403): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  403): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  403): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: starts! randomData=0xab6eb978, dataLength=8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab7b01b0, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  403): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  403): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  403): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  403): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: starts! deviceID=0xab6ea290, idLength=0xf4c226f8
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  403): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: starts!, current = 0xf4c2270e, maximum = 0xf4c2270f
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GetHDCPCapability: ends! returns 0
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): hlos api version =  9
D/DrmWidevineDash(  403): tz api version =  9
D/DrmWidevineDash(  403): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4c2277c
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  403): PrepareKeyRequest: nonce=2494730121
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab6e14c0
D/DrmWidevineDash(  403): message_length=1642, signature=0xab6e9a48, signature_length=0xf4c226dc
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/Process (  935): killProcessQuiet, pid=6496
,I/ActivityManager(  935): Killing 6496:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  403): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  403): CdmEngine::CloseSession
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  403): L3 Terminate.
D/DrmWidevineDash(  403): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  403): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  403): Service_Uninitialize: starts!,
D/QSEECOMAPI: (  403): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  403): QSEECom_shutdown_app, app_id = 11
D/DrmWidevineDash(  403): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  403): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  935): Recipient 6496
,V/MusicLeanback( 6862): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6899): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6899): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1545): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1545): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate,
D/AutoSetting( 1545): service - onStartCommand() screen is off, don't request location
,D/PMS     (  935): acquireWL(2024eb61): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4366 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  935): releaseWL(2024eb61): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4366, uid=10024, userID:0,
,D/ChimeraCfgMgr( 4366): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,I/Kids    ( 4366): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000,
,D/GCM     ( 1804): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1804): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 4366): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4366, uid=10024, userID:0
,D/WearableService( 5314): callingUid 10024, callindPid: 5314
,E/MDM     ( 1819): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,D/LocationInitializer( 4366): Restart initialization of location
,I/CheckinRequestBuilder( 4366): Classify the device as Phone.,
,D/libc    ( 4366): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4366): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4366): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4366): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4366): [NET] android_getaddrinfo_proxy+,
D/libc    ( 4366): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4366): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 4366): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4366): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4366): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4366): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4366): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
D/libc    ( 4366): [NET] android_getaddrinfofornet-, err=8
,I/CheckinTask( 4366): Sending checkin request (10023 bytes),
,I/CheckinRequestBuilder( 4366): Checkin reason type: 8 attempt count: 1,
I/ActivityManager(  935): Cannot resolve ContentProvider=com.google.android.wearable.settings,
E/ActivityThread( 4366): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 1804): Explicit concurrent mark sweep GC freed 26525(1419KB) AllocSpace objects, 6(460KB) LOS objects, 47% free, 4MB/8MB, paused 686us total 46.101ms,
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/CheckinRequestBuilder( 4366): awaiting user notification for token,
,I/RemoteViews( 1220): reapply : com.google.android.gms 2 40
D/DotMatrix( 1335): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinRequestBuilder( 4366): Classify the device as Phone.
,I/CheckinTask( 4366): Checkin success: https://android.clients.google.com/checkin (1 requests sent),
,I/CheckinService( 4366): Checking schedule, now: 1457968532704 next: 1458505364699,
I/CheckinService( 4366): active receiver: disabled
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4366, uid=10024, userID:0
,I/CheckinService( 4366): Checking schedule, now: 1457968532729 next: 1458505364699,
I/CheckinService( 4366): active receiver: disabled
I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4366, uid=10024, userID:0,
,D/PMS     (  935): releaseWL(2ab98add): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  935): acquireWL(3a934437): PARTIAL_WAKE_LOCK  *alarm* 0x1 935 1000 WorkSource{10024}
V/AlarmManager(  935): sending alarm PendingIntent{906fda4: PendingIntentRecord{a1a270d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=227121, Int=0
,V/SetupWizard( 6899): Connected to Gservices successfully
,D/ChimeraCfgMgr( 4366): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 4366): [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
,D/GCM     ( 1804): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE,
D/PMS     (  935): acquireWL(616c6c2): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): releaseWL(3a934437): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,D/libc    ( 1804): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1804): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1804): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1804): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1804): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1804): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:101, mark:917605
,D/libc    (  397): [NET] _dns_getaddrinfo-, (NS_SUCCESS),
D/libc    (  397): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1804): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1804): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1804): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1804): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1804): [NET] android_getaddrinfofornet-, err=8
,D/PMS     (  935): acquireWL(44decd3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1804): Connected,
D/PMS     (  935): releaseWL(616c6c2): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(44decd3): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(11885010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1804 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1804): Message class com.google.f.a.a.p
,D/PMS     (  935): releaseWL(11885010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(f0e8d0e): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 6862 10159 null,
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=6862, uid=10159, userID:0,
,D/PMS     (  935): releaseWL(f0e8d0e): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 6862): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6862): Stop autocaching.
,E/GmsUtils( 6862): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,E/GmsUtils( 6862): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/ActivityManager(  935): Killing 6056:com.android.vending/u0a72 (adj 15): empty #17,
D/Process (  935): killProcessQuiet, pid=6056
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6056
,I/ActivityManager(  935): Killing 5966:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  935): killProcessQuiet, pid=5966
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 5966
,D/PMS     (  935): acquireWL(897dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 935 1000 null,
I/BatteryService(  935): n_update end
D/PMS     (  935): releaseWL(897dd40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
I/IntentController( 1220): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  935): updateBatteryInfo
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1220): closing low battery warning: level=100
D/DotMatrix( 1335): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  935): plugged=true pluggin=true
D/DotMatrix( 1335): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  935): runPSCheck
D/HeadsetStateMachine( 3002): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  935): Checking...
D/UsbnetService(  935): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  935): >> updateStatus
D/UsbnetService(  935): onReceive BATTERY_CHANGED
D/WifiController(  935): battery changed pluggedType: 2
D/UsbnetService(  935):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  935): BroadcastReceiver::onReceive-
D/WifiController(  935): handleMessage: E msg.what=155652
D/PowerUI ( 1220): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  935): processMsg: DeviceActiveState
D/WifiController(  935): processMsg: StaEnabledState
D/WifiController(  935): processMsg: DefaultState
D/WifiController(  935): handleMessage: X
,I/HtcPowerSaver(  935): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  935): << updateStatus
,I/BatteryController( 1220): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  935): acquireWL(d92e479): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 6519 10112 null,
,D/AccTypeManager( 1765): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  935): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1765): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/ResourcesManager(  935): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1628): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1628): Deferring update until onResume
D/Launcher( 1628): waitUntilResume // bindAppsUpdated
D/AccTypeManager( 1765): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
I/ActivityManager(  935): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7085 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
,D/PhoneApp( 1561): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  935): releaseWL(d92e479): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,E/ExternalAccountType( 1765): Unsupported attribute readOnly
,W/ResourcesManager( 6519): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6519): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/PackageManager(  935): Unable to load service info ResolveInfo{1844ee64 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  935): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  935): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  935): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  935): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  935): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  935): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  935): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,V/GmsNetworkLocationProvi( 1819): DISABLE,
,I/GCoreNlp( 1819): shouldConfirmNlp, NLP off. Ensuring opt-in disabled,
,I/BackupManagerService(  935): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LocationProviderProxy(  935): applying state to connected service,
,D/PMS     (  935): acquireWL(3b323eec): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  935): releaseWL(3b323eec): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  935): applying state to connected service
,D/PMS     (  935): acquireWL(1a18e2b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1819 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  935): releaseWL(1a18e2b5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(3ea9dd4a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): releaseWL(3ea9dd4a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(290fb36d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): releaseWL(290fb36d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationManagerService(  935): getProviders()=[passive],
,I/ActivityManager(  935): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7115 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
,I/[PluginManager]RegisterService( 1545): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
I/[PluginManager]RegisterService( 1545): handle notify Blinkfeed plugin client changed
I/art     ( 1819): Explicit concurrent mark sweep GC freed 17702(979KB) AllocSpace objects, 9(180KB) LOS objects, 46% free, 4MB/8MB, paused 980us total 106.848ms
E/DataBuffer( 1819): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c44f5a7)
,I/ActivityManager(  935): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7137 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/art     (  935): Explicit concurrent mark sweep GC freed 24038(1288KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/25MB, paused 1.774ms total 132.795ms
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=7137, uid=10072, userID:0
,W/global  ( 7137): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7137): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 7137): [apache-http] Connection GC has been deprecated!,
,W/global  ( 7137): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 7137): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  935): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7177 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 7137): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7137): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=7137, uid=10072, userID:0
,W/ResourcesManager( 7177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7177): VM with version 2.1.0 has multidex support
I/MultiDex( 7177): install
I/MultiDex( 7177): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 7137): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 7137): [1] 2.run: Finished loading 1 libraries.,
,D/Finsky  ( 7137): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/JNIHelp ( 7177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageBroadcastService( 4366): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms,
,I/PackageBroadcastService( 4366): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7137): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.,
,D/PMS     (  935): acquireWL(17cfa34c): PARTIAL_WAKE_LOCK  AsyncService 0x1 6125 10167 null,
D/PMS     (  935): acquireWL(3ff1df95): PARTIAL_WAKE_LOCK  Icing 0x1 4366 10024 WorkSource{10024 com.google.android.gms},
D/PMS     (  935): releaseWL(17cfa34c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/Icing   ( 4366): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  935): acquireWL(34da6c9b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6125 10167 null,
,W/ActivityThread( 7177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/PMS     (  935): releaseWL(34da6c9b): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
W/System  ( 7177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@238b2c04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7177): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 7085): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE,
D/GCM     ( 1804): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/PMS     (  935): releaseWL(3ff1df95): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,D/AuthorizationBluetoothService( 1804): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 4366): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 5314): callingUid 10024, callindPid: 5314
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4366, uid=10024, userID:0
,E/MDM     ( 1819): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 4366): Restart initialization of location,
,I/UpdateIcingCorporaServi( 7085): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,D/Process (  935): killProcessQuiet, pid=6549,
I/ActivityManager(  935): Killing 6549:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6549
,V/Finsky  ( 7137): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@3a846398 +
I/Prism.WidgetManager( 1628): onLoadItems() +
,W/ResourcesManager( 1628): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/Finsky  ( 7137): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  935): acquireWL(36ebb28b): PARTIAL_WAKE_LOCK  *alarm* 0x1 935 1000 WorkSource{10072}
V/AlarmManager(  935): sending alarm PendingIntent{15438f68: PendingIntentRecord{15f72a8a com.android.vending startService}}, i=null, t=0, cnt=1, w=1457968541261, Int=0
D/PMS     (  935): releaseWL(36ebb28b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7137): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,W/ResourcesManager( 1628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 7137): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/asset   ( 1628): Copying FileAsset 0x559920b2b0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,E/Prism.WidgetManager( 1628): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1628): onLoadItems() -
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@3a846398 -
,E/AndroidHttpClient( 7137): Leak found,
E/AndroidHttpClient( 7137): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 7137): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 7137): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 7137): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 7137): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 7137): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 7137): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 7137): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 7137): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 7137): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 7137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 7137): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 7137): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 7137): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 7137): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 7137): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 7137): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/PhoneApp( 1561): EVENT_QUERY_MO_PACKAGES,
,D/PhoneApp( 1561): -- N1 =0
,D/PhoneApp( 1561): -- N2 =0
,D/PhoneApp( 1561): -- N3 =0
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1804): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1804): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1804): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1804): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 7137): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 7137): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 7137): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 7137): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1),
,D/DeviceConnectionService( 1819): client connected with version: 7571000
,I/ActivityManager(  935): Waited long enough for: ServiceRecord{31bc5e31 u0 com.htc.sense.hsp/.weather.location.AutoSettingService},
,I/ActivityManager(  935): Killing 6644:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17,
D/Process (  935): killProcessQuiet, pid=6644
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6644
D/WifiService(  935): Client connection lost with reason: 4
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log( 6732): 
,D/Process (  935): killProcessQuiet, pid=6389
I/ActivityManager(  935): Killing 6389:com.htc.calendar/u0a10 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6389,
,D/Process (  935): killProcessQuiet, pid=6677
,I/ActivityManager(  935): Killing 6677:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6677,
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 6732): 
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native,
I/jxcore-log( 6732): 
,I/io.jxcore.node.ConnectivityInfo( 6732): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 6732):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6732):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6732):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6732): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 6732): INFO thaliMobileNativeWrapper Method networkChanged registered to native,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native,
I/jxcore-log( 6732): 
,D/PMS     (  935): acquireWL(382e4cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 935 1000 WorkSource{10072},
V/AlarmManager(  935): sending alarm PendingIntent{6fa85d1: PendingIntentRecord{1e16d836 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457968556474, Int=0
,D/PMS     (  935): releaseWL(382e4cf8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 7137): [717] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 7137): [1] 5.onFinished: Installation state replication succeeded.
,W/Atfwd_Sendcmd(  422): AtCmdFwd service not published, waiting... retryCnt : 3
,D/AutoSetting( 1545): service - handleMessage() stop self,
,D/AutoSetting( 1545): service - onDestroy() END,
D/AutoSetting( 1545): service - handleMessage() quit looper
,D/Process (  935): killProcessQuiet, pid=6800
I/ActivityManager(  935): Killing 6800:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6800,
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
I/jxcore-log( 6732): 
,I/jxcore-log( 6732): --= Surplus to requirements =--,
I/jxcore-log( 6732): 
I/jxcore-log( 6732): ****TEST TOOK:  ms ****,
,I/jxcore-log( 6732): 
I/jxcore-log( 6732): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6732): 
,E/cutils-trace( 7231): Error opening trace file: Permission denied (13)
,D/CustomizationManager( 7231): ====startRecUseTime====
,D/htc.customization.log.level( 7231):  is ,
W/CustomizationLogLevel( 7231): Level value is invalid, use default level 2,
,D/CustomizationManager( 7231):  Read ACC file spent 0.044 (s),
,D/CIDMapFileReader( 7231): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 7231): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 7231): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 7231): Parsing tag item name = HTC__032
D/CIDMapFileReader( 7231): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 7231): Parsing tag item name = HTC__002
D/CIDMapFileReader( 7231): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 7231): full path : /system/customize/CID/HTC__102.xml,
,I/CustomizationCIDLoader( 7231): Parsing tag category name = system,
I/CustomizationCIDLoader( 7231): Parsing tag category name = application
,I/CustomizationCIDLoader( 7231): Parsing tag category name = SettingsProvider,
I/CustomizationCIDLoader( 7231): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 7231): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 7231): Parsing tag category name = Settings
I/CustomizationCIDLoader( 7231): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 7231): add string-array item, value = 42507
I/CustomizationCIDLoader( 7231): add string-array item, value = 21902
I/CustomizationCIDLoader( 7231): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 7231): add string-array item, value = 23420
,I/CustomizationCIDLoader( 7231): add string-array item, value = 22299
I/CustomizationCIDLoader( 7231): add string-array item, value = 24002
I/CustomizationCIDLoader( 7231): add string-array item, value = 23210
I/CustomizationCIDLoader( 7231): add string-array item, value = 23205
I/CustomizationCIDLoader( 7231): add string-array item, value = 23806
,I/CustomizationCIDLoader( 7231): add string-array item, value = 23430
I/CustomizationCIDLoader( 7231): add string-array item, value = 23408
I/CustomizationCIDLoader( 7231): add string-array item, value = 27205
I/CustomizationCIDLoader( 7231): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 26006:D:1:0
,I/CustomizationCIDLoader( 7231): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 23205:D:0:0
,I/CustomizationCIDLoader( 7231): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 7231): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 7231):  Read CID file spent 0.089 (s),
D/CustomizationManager( 7231):  All configurations done spent 0.090 (s)
,D/PackageManager(  935): deletePackageAsUser: pkg=com.test.thalitest, pid=7231, uid=2000 userid=0,
,D/Process (  935): killProcessQuiet, pid=6732
I/ActivityManager(  935): Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
I/ActivityManager(  935): Killing 6732:com.test.thalitest/u0a195 (adj 0): stop com.test.thalitest
,D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  935): Skipping PackageSetting{1016220d com.example.hello/10374} due to missing metadata,
,I/ActivityManager(  935): Recipient 6732
D/WifiService(  935): Client connection lost with reason: 4
,I/WindowState(  935): WIN DEATH: Window{3210540b u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/InputEventReceiver( 1400): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{356e25e7 uid 10195 pid 6732} (c)'
,I/ActivityManager(  935):   Force finishing activity ActivityRecord{28828e46 u0 com.test.thalitest/.MainActivity t12},
,W/ActivityManager(  935): Spurious death for ProcessRecord{355eb337 6732:com.test.thalitest/u0a195}, curProc for 6732: null
,I/ActivityManager(  935): Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,D/DotMatrix( 1335): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/PMS     (  935): acquireWL(277740a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1819 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1335): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1335): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1819): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1765): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/SystemReader(  935): Cannot find grip_rejection_width, use default value instead
D/PMS     (  935): releaseWL(277740a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(307041c2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 935 1000 null,
D/AccTypeManager( 1765): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
V/NetworkPolicy(  935): ACTION_UID_REMOVED for uid=10195
,D/VoicemailCleanupService( 1707): Cleaning up data for package: com.test.thalitest
,I/[PluginManager]RegisterService( 1545): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,I/art     ( 1628): Explicit concurrent mark sweep GC freed 22056(1321KB) AllocSpace objects, 4(248KB) LOS objects, 34% free, 29MB/45MB, paused 1.226ms total 115.741ms
,I/InputMethodManagerService(  935): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1561): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Prism.PackageStateRece_( 1628): action: android.intent.action.PACKAGE_REMOVED
,I/Launcher( 1628): Deferring update until onResume
W/ResourcesManager(  935): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AccTypeManager( 1765): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  935): releaseWL(307041c2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/Launcher( 1628): waitUntilResume // bindAppsRemoved
V/NetworkPolicy(  935): writePolicyLocked()
,I/[PluginManager]RegisterService( 1545): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  935): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,E/ExternalAccountType( 1765): Unsupported attribute readOnly,
,V/NetworkPolicy(  935): updateNetworkEnabledLocked()
V/NetworkPolicy(  935): updateNotificationsLocked()
,I/art     (  935): Explicit concurrent mark sweep GC freed 35383(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 16MB/25MB, paused 1.846ms total 240.246ms
I/art     (  935): WaitForGcToComplete blocked for 166.082ms for cause Explicit
,W/PackageManager(  935): Unable to load service info ResolveInfo{2a4cbed2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  935): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  935): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  935): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  935): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  935): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  935): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  935): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  935): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  935): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/StatusBarManagerService(  935): setSystemUiVisibility(0x8700)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  935): hiding MENU key
,W/ContextImpl( 7251): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,D/StatusBarManagerService(  935): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  935): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  935): hiding MENU key,
D/FindExtension( 1628): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1628): Defer allocateBuffers to drawing time
,W/art     (  935): Suspending all threads took: 8.545ms,
,W/InputMethodManagerService(  935): Got RemoteException sending setActive(false) notification to pid 6732 uid 10195
D/StatusBarManagerService(  935): swetImeWindowStatus vis=0 backDisposition=0
D/JobSchedulerService(  935): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  935): Explicit concurrent mark sweep GC freed 7004(420KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 11.463ms total 158.359ms
D/TaskPersister(  935): removeObsoleteFile: deleting file=12_task.xml
I/PhoneStatusBar( 1220): setImeWindowStatus(false,false)
,D/Process (  935): killProcessQuiet, pid=6614,
I/ActivityManager(  935): Killing 6614:com.htc.bgp/u0a11 (adj 15): empty #17,
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  935): Recipient 6614
,E/NetworkScheduler.SchedulerReceiver( 1804): Invalid parameter app
D/PMS     (  935): acquireWL(2644871d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1804 10024 WorkSource{10024 com.google.android.gms},
E/NetworkScheduler.SchedulerReceiver( 1804): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  935): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7282 uid=10015 gids={50015, 9997, 1028, 1015, 1023, 2001, 1035, 5001} abi=arm64-v8a
,D/PMS     (  935): releaseWL(2644871d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PackageBroadcastService( 4366): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
D/ChimeraCfgMgr( 4366): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4366): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 4366): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 4366): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 4366): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  935): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7307 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/art     (  409): Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 230us total 34.197ms,
,I/LocationSettingsChecker( 4366): Removing dialog suppression flag for package com.test.thalitest
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 178us total 26.720ms,
,I/art     (  409): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 133us total 21.266ms,
,D/GOOGLEHELP_CompatibleDatabase( 4366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 4366): 0 metrics were deleted when clearing package com.test.thalitest.
,D/GOOGLEHELP_CompatibleDatabase( 4366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/GOOGLEHELP_CompatibleDatabase( 4366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
D/GOOGLEHELP_CompatibleDatabase( 4366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/PMS     (  935): acquireWL(324eeab7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4366 10024 null
,D/GOOGLEHELP_CompatibleDatabase( 4366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
,D/GOOGLEHELP_CompatibleDatabase( 4366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/PMS     (  935): releaseWL(324eeab7): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
I/ConfigService( 1804): onCreate
D/GOOGLEHELP_CompatibleDatabase( 4366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/ConfigFetchService( 4366): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GOOGLEHELP_CompatibleDatabase( 4366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 4366): Using Auth Proxy for data requests.
,W/BaseAppContext( 4366): Using Auth Proxy for data requests.,
,E/WifiStateMachine(  935): handleMessage: E msg.what=131165,
E/WifiStateMachine(  935): processMsg: ConnectedState
E/WifiStateMachine(  935):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  935): processMsg: L2ConnectedState
E/WifiStateMachine(  935):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  935): processMsg: ConnectModeState
E/WifiStateMachine(  935):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0,
E/WifiStateMachine(  935): processMsg: DriverStartedState
E/WifiStateMachine(  935):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  935): processMsg: SupplicantStartedState
E/WifiStateMachine(  935):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  935): processMsg: DefaultState
E/WifiStateMachine(  935):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine(  935): handleMessage: X,
,I/PeopleContactsSync( 4366): CP2 sync disabled
,D/PMS     (  935): acquireWL(cd351bc): PARTIAL_WAKE_LOCK  Icing 0x1 4366 10024 WorkSource{10024 com.google.android.gms}
,I/PackageManager(  935):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4366, uid=10024, userID:0
,I/Icing   ( 4366): doRemovePackageData com.test.thalitest,
D/PMS     (  935): releaseWL(cd351bc): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): acquireWL(26abb49a): PARTIAL_WAKE_LOCK  Icing 0x1 4366 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  935): releaseWL(26abb49a): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  935): acquireWL(3861cda8): PARTIAL_WAKE_LOCK  Icing 0x1 4366 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  935): releaseWL(3861cda8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,I/art     ( 1804): Explicit concurrent mark sweep GC freed 18579(1038KB) AllocSpace objects, 7(332KB) LOS objects, 47% free, 4MB/8MB, paused 701us total 39.244ms,
,W/DriveInitializer( 4366): Awaiting to be initialized,
W/DriveInitializer( 4366): Background init thread started
,E/SQLiteLog( 4366): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error,
E/SQLiteDBG( 4366): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5598eb4810
,E/DocListDatabase( 4366): Failed to delete from ContentFileDeletionLock112,
E/DocListDatabase( 4366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4366): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4366): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4366): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4366): 	at com.google.android.gms.drive.r.run(SourceFile:69)
,W/DriveInitializer( 4366): Background init thread ended
E/AndroidRuntime( 4366): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4366): Process: com.google.android.gms, PID: 4366
E/AndroidRuntime( 4366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4366): ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4366): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4366): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4366): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 4366): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4366): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5598eb4810
E/ActivityManager(  935): App crashed! Process: com.google.android.gms
,E/DriveAsyncService( 4366): disk I/O error (code 3850),
E/DriveAsyncService( 4366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4366): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
,E/DriveAsyncService( 4366): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4366): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4366): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4366): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4366): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/DriveAsyncService( 4366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4366): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  935): Can't write: system_app_crash
E/DropBoxManagerService(  935): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  935): ,	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  935): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  935): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  935): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  935): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  935): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  935): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  935): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  935): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  935): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  935): 	... 5 more
D/Process ( 4366): killProcess, pid=4366
,D/Process ( 4366): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,I/ActivityManager(  935): Recipient 4366
D/WifiService(  935): Client connection lost with reason: 4
,I/ActivityManager(  935): Process com.google.android.gms (pid 4366) has died
I/ConfigService( 1804): onDestroy
W/ActivityManager(  935): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  935): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  935): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,I/GAv4    ( 7307): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 7307):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7307):   adb logcat -s GAv4
,W/GAv4    ( 7307): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,W/GAv4    ( 7307): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak,
,E/SQLiteDatabase( 7307): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7307): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7307): 	,at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7307): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
,E/SQLiteDatabase( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7307): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7307): 	at gir$c.run(Unknown Source)
,W/AnalyticsTrackerProxyImpl( 7307): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/GAv4    ( 7307): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7307): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7307): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737),
,E/SQLiteDatabase( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7307): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 7307): ,	at fdw.a(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 7307): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 7307): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7307): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7307): 	at gir$c.run(Unknown Source)
E/GAv4    ( 7307): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 7307): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7307): 	,at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7307): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7307): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7307): 	at aen.run(PG:536)
,I/ActivityManager(  935): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=7350 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/ResourcesManager( 7350): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7350): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7350): VM with version 2.1.0 has multidex support,
I/MultiDex( 7350): install
I/MultiDex( 7350): VM has multidex support, MultiDex support library is disabled.
,D/VoldConnector(  935): SND -> {38 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/},
E/Vold    (  387): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/,
W/ContextImpl( 7307): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
W/ResourcesManager( 7307): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 7307): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PMS     (  935): acquireWL(36ca1ec): PARTIAL_WAKE_LOCK  AsyncService 0x1 6125 10167 null
,D/PMS     (  935): releaseWL(36ca1ec): PARTIAL_WAKE_LOCK  AsyncService 0x1 null,
,D/PMS     (  935): acquireWL(242a784a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6125 10167 null
E/SQLiteDatabase( 7307): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
,E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7307): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7307): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7307): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7307): 	at aej.c(PG:139)
E/SQLiteDatabase( 7307): 	at aej.b(PG:398)
E/SQLiteDatabase( 7307): 	at agf.f(PG:417)
E/SQLiteDatabase( 7307): 	at oe.run(PG:1112)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7307): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 7307): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7307): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7307): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7307): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7307): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7307): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 7307): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 7307): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7307): 	at java.lang.Thread.run(Thread.java:818)
,D/PMS     (  935): releaseWL(242a784a): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/UpdateIcingCorporaServi( 7085): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,V/JNIHelp ( 7307): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
I/ActivityManager(  935): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=7382 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,E/SQLiteDatabase( 7350): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.,
E/SQLiteDatabase( 7350): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7350): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7350): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 7350): ,	,at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 7350): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7350): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7350): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7350): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 7350): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 7350): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7350): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7350): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 7350): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 7350): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 7350): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7350): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7350): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 7085): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
E/SQLiteDBG( 7085): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5598c38d70
,W/System  ( 7307): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
I/ProviderInstaller( 7307): Installed default security provider GmsCore_OpenSSL
,E/SQLiteDatabase( 7307): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.,
E/SQLiteDatabase( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7307): 	,at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 7307): 	at ael.a(PG:1521)
E/SQLiteDatabase( 7307): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 7307): 	at aej.c(PG:139)
E/SQLiteDatabase( 7307): 	at aej.a(PG:358)
E/SQLiteDatabase( 7307): 	at aej.a(PG:345)
E/SQLiteDatabase( 7307): 	at agf.c(PG:884)
E/SQLiteDatabase( 7307): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 7307): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7307): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7307): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 7307): Failed to query Account133 object
E/AbstractDatabaseInstance( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 7307): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 7307): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 7307): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 7307): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 7307): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 7307): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 7307): 	at agf.c(PG:884)
E/AbstractDatabaseInstance( 7307): 	at aii.doInBackground(PG:1063)
E/AbstractDatabaseInstance( 7307): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 7307): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 7307): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  935): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=7407 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,E/SharedPreferencesImpl( 7085): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
E/AndroidRuntime( 7085): FATAL EXCEPTION: IntentService[UpdateCorporaService]
,E/AndroidRuntime( 7085): Process: com.google.android.googlequicksearchbox:search, PID: 7085
E/AndroidRuntime( 7085): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/AndroidRuntime( 7085): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/AndroidRuntime( 7085): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 7085): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/AndroidRuntime( 7085): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
,E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 7085): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 7085): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7085): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7085): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7085): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  935): App crashed! Process: com.google.android.googlequicksearchbox:search
I/Prism.ItemManager( 1628): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@3a846398 +
I/Prism.WidgetManager( 1628): onLoadItems() +
,I/DeviceManagement( 7382): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7382 dbg=false s=true
E/DropBoxManagerService(  935): Can't write: system_app_crash
E/DropBoxManagerService(  935): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  935): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  935): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  935): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  935): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  935): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  935): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  935): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  935): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  935): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  935): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  935): 	... 5 more
,I/DeviceManagement( 7382): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 7382): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
D/Process ( 7085): killProcess, pid=7085
D/Process ( 7085): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.y.uncaughtException:113 java.lang.ThreadGroup.uncaughtException:693 
,I/DeviceManagement( 7382): WorkflowService: Starting workflow service
,I/DeviceManagement( 7382): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@30940161] args=[Bundle[mParcelledData.dataSize=112]]
I/DeviceManagement( 7382): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 7382): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 7382): PackageUpdateWorkflow: ==================================================
,V/JNIHelp ( 7350): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/DeviceManagement( 7382): ModelRegistry: Loading model meta data from resources...
,I/ActivityManager(  935): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7434 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,W/ResourcesManager( 1628): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/DeviceManagement( 7382): BackgroundController: *** Processing package remove for appID=com.test.thalitest
,W/ActivityThread( 7350): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 7350): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@174fc64: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7350): Installed default security provider GmsCore_OpenSSL
,I/DeviceManagement( 7382): SessionStateController: Checking invariants...,
,W/NativeLibraryUtils( 7350): Failed to open lock file,
W/NativeLibraryUtils( 7350): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7350): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 7350): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 7350): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 7350): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 7350): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7350): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7350): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 7350): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 7350): 	... 3 more
,I/GAv4-SVC( 7350): Google Analytics 7.8.99 is starting up.,
,I/ActivityManager(  935): Recipient 7085,
,I/ActivityManager(  935): Process com.google.android.googlequicksearchbox:search (pid 7085) has died
W/ActivityManager(  935): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,I/ActivityManager(  935): Killing 6930:com.google.android.apps.magazines/u0a161 (adj 15): empty #17,
D/Process (  935): killProcessQuiet, pid=6930
E/SQLiteDatabase( 7434): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7434): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7434): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 7434): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 7434): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/SQLiteDatabase( 7434): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/SQLiteDatabase( 7434): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 7434): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/SQLiteDatabase( 7434): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 7434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/SQLiteDatabase( 7434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7434): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 7434): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 7434): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7434): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 7434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/AndroidRuntime( 7434): FATAL EXCEPTION: main
E/AndroidRuntime( 7434): Process: com.android.documentsui, PID: 7434
E/AndroidRuntime( 7434): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7434): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 7434): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 7434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 7434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7434): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 7434): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 7434): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7434): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 7434): 	at co,m.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 7434): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 7434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 7434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7434): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7434): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 7434): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 7434): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
E/AndroidRuntime( 7434): 	at android.content.ContentResolver.call(ContentResolver.java:1393)
E/AndroidRuntime( 7434): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 7434): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 7434): 	... 9 more
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7307): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7307): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 7307): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185),
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7307): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7307): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7307): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7307): 	at aen.run(PG:536)
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 7307): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 7307): Local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 7307): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 7307): Error opening database: android.database.sqlite.SQLiteException: Database open failed
,E/GAv4    ( 7307): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 7307): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 7307): java.lang.RuntimeException: An error occured while executing doInBackground()
E/CAKEMIX_CRASHED( 7307): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/CAKEMIX_CRASHED( 7307): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/CAKEMIX_CRASHED( 7307): 	at java.lang.Thread.run(Thread.java:818)
E/CAKEMIX_CRASHED( 7307): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/CAKEMIX_CRASHED( 7307): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/CAKEMIX_CRASHED( 7307): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 7307): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 7307): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 7307): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 7307): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 7307): 	at aej.c(PG:139)
E/CAKEMIX_CRASHED( 7307): 	at aej.a(PG:358)
E/CAKEMIX_CRASHED( 7307): 	at aej.a(PG:345)
E/CAKEMIX_CRASHED( 7307): 	at agf.c(PG:884)
E/CAKEMIX_CRASHED( 7307): 	at aii.doInBackground(PG:1063)
E/CAKEMIX_CRASHED( 7307): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/CAKEMIX_CRASHED( 7307): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/CAKEMIX_CRASHED( 7307): 	... 4 more
,E/SQLiteDatabase( 7382): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
E/SQLiteDatabase( 7382): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7382): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 7382): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 7382): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7382): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 7382): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 7382): ,	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 7382): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 7382): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 7382): ,	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 7382): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 7382): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 7382): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7382): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7382): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7382): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 1628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/ActivityManager(  935): Recipient 6930,
,W/asset   ( 1628): Copying FileAsset 0x55992883c0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,D/Process (  935): killProcessQuiet, pid=7021,
I/ActivityManager(  935): Killing 7021:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  935): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/Prism.WidgetManager( 1628): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1628): onLoadItems() -
I/Prism.ItemManager( 1628): loadItems() com.htc.launcher.pageview.WidgetManager@3a846398 -
,E/SQLiteLog( 1628): (3850) statement aborts at 10: [DELETE FROM appscustomize WHERE _id=75] disk I/O error,
E/SQLiteDBG( 1628): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0x5598bfdc50
,E/AndroidRuntime( 1628): FATAL EXCEPTION: TaskWorker,
E/AndroidRuntime( 1628): Process: com.htc.launcher, PID: 1628
E/AndroidRuntime( 1628): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1628): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1628): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1628): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1628): 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1628): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1628): 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:344)
E/AndroidRuntime( 1628): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 1628): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 1628): 	at com.htc.launcher.pageview.RearrangeDBHelper$3.run(RearrangeDBHelper.java:151)
E/AndroidRuntime( 1628): 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
E/AndroidRuntime( 1628): 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
E/AndroidRuntime( 1628): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1628): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1628): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  935): Recipient 7021
,I/ActivityManager(  935): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=7463 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a
I/ActivityManager(  935): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10101 pid 7307 on display 0
,E/SQLiteLog( 3738): (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10195)] disk I/O error,
E/SQLiteDBG( 3738): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.downloads/databases/downloads.db, handle: 0x5598ca9b70
,D/PhoneApp( 1561): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1561): -- N1 =0
,D/PhoneApp( 1561): -- N2 =0
E/AndroidRuntime( 3738): FATAL EXCEPTION: DownloadReceiver
E/AndroidRuntime( 3738): Process: android.process.media, PID: 3738
E/AndroidRuntime( 3738): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3738): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method),
E/AndroidRuntime( 3738): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 3738): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3738): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3738): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 3738): 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
E/AndroidRuntime( 3738): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
E/AndroidRuntime( 3738): 	at android.content.ContentResolver.delete(ContentResolver.java:1320)
E/AndroidRuntime( 3738): 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
E/AndroidRuntime( 3738): 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
E/AndroidRuntime( 3738): 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
E/AndroidRuntime( 3738): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3738): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3738): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 3738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PhoneApp( 1561): -- N3 =0

```
