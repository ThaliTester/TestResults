#### Test 62509094058a2d4_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,I/ActivityManager(  891): Killing 3106:com.google.android.calendar/u0a49 (adj 15): empty #7
W/libprocessgroup(  891): failed to open /acct/uid_10049/pid_3106/cgroup.procs: No such file or directory
--------- beginning of main
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/art     ( 1820): Explicit concurrent mark sweep GC freed 21082(1100KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 13MB/23MB, paused 1.442ms total 87.578ms
I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/GCoreUlr( 1820): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=4859 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 3549:com.android.defcontainer/u0a10 (adj 15): empty #7
D/AndroidRuntime( 4855): 
D/AndroidRuntime( 4855): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4855): CheckJNI is OFF
W/libprocessgroup(  891): failed to open /acct/uid_10010/pid_3549/cgroup.procs: No such file or directory
I/GCoreUlr( 1820): DispatchingService.onCreate()
D/AndroidRuntime( 4855): Calling main entry com.android.commands.am.Am
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/GCoreUlr( 1820): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4855): Shutting down VM
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4896 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ctxmgr  ( 1820): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  891): done {38e5438f, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [9830ms]
,E/SQLiteLog( 4716): (284) automatic index on view_events(_id)
,I/GCoreUlr( 1820): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4923 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/WebViewFactory( 4896): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/GCoreUlr( 1820): Unbound from all location providers
I/GCoreUlr( 1820): Place inference reporting - stopped
,W/ctxmgr  ( 1820): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,I/LibraryLoader( 4896): Time to load native libraries: 5 ms (timestamps 7827-7832)
,I/LibraryLoader( 4896): Expected native library version number "",actual native library version number ""
E/ctxmgr  ( 1820): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/ActivityManager(  891): Killing 4756:com.google.android.configupdater/u0a54 (adj 15): empty #7
,W/ResourcesManager( 4923): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/WebViewChromiumFactoryProvider( 4896): Binding Chromium to main looper Looper (main, tid 1) {3a94bec0}
,I/LibraryLoader( 4896): Expected native library version number "",actual native library version number ""
I/chromium( 4896): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4896): Initializing chromium process, singleProcess=true
,W/art     ( 4896): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4896): ApplicationContext is null in ApplicationStatus
,W/chromium( 4896): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4896): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4896): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4896): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4896): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4896): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4896): Local Branch: 
I/Adreno-EGL( 4896): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4896): Local Patches: NONE
I/Adreno-EGL( 4896): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  891): failed to open /acct/uid_10054/pid_4756/cgroup.procs: No such file or directory
,I/GCoreUlr( 1820): DispatchingService.onDestroy()
I/GCoreUlr( 1820): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1820): Unbound from all location providers
I/GCoreUlr( 1820): Place inference reporting - stopped
,D/BluetoothManagerService(  891): Message: 20
,D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@201c2ca5:true
,I/Babel_SMS( 4923): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4923): MmsConfig.loadMmsSettings
I/Babel_SMS( 4923): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 4923): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4923): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4923): MmsConfig.loadFromResources
,E/Babel_SMS( 4923): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4923): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/art     ( 4896): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4896): onDetachedFromWindow called when already detached. Ignoring
,W/Settings( 4923): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SystemWebViewEngine( 4896): CordovaWebView is running on device made by: motorola
,W/art     ( 4896): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4896): Attempt to remove local handle scope entry from IRT, ignoring
,I/Babel_Crash( 4923): startup - clean
,I/SFPerfTracer(  278):      triggers: (rate: 11:344) (compose: 0:1) (post: 0:1) (render: 0:2) (11:1010 frames) (12:1092)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb8c6e6e8): 0:11)* (DimLayer (0xb8ca66e8): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8ca8ad8): 0:37)- (StatusBar (0xb8c0cd28): 0:134) (NavigationBar (0xb8c0f9f8): 0:35) (com.android.systemui.ImageWallpaper (0xb8c5ba58): 0:35)* (Starting com.motorola.ccc.ota (0xb8c5dda0): 0:28)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8c60190): 1:51)* (Starting com.test.thalitest (0xb8c62580): 12:24) 
,I/Babel   ( 4923): deleted: false for 0
,D/OpenGLRenderer( 4896): Render dirty regions requested: true
,D/Atlas   ( 4896): Validating map...
,W/chromium( 4896): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/OpenGLRenderer( 4896): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4896): Enabling debug mode 0
,I/Keyboard.Facilitator( 1425): onFinishInput()
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4979 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/LaunchCheckinHandler(  891): Displayed com.test.thalitest/.MainActivity,cp,ca,1026
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +1s27ms
,W/VideoCapabilities( 4923): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4923): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 4923): Unsupported mime video/mpeg2
,D/PhoneMonitor( 4979): Register our PhoneStateListener
,E/Adreno-ES20( 4896): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4896): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/VideoCapabilities( 4923): Unsupported profile 4 for video/mp4v-es
,W/BindingManager( 4896): Cannot call determinedVisibility() - never saw a connection for the pid: 4896
,V/SetupWizard( 4979): Connected to Gservices successfully
,W/VideoCapabilities( 4923): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4923): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4923): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  891): Killing 4710:com.google.android.partnersetup/u0a19 (adj 15): empty #7
W/VideoCapabilities( 4923): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_4710/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 4785:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/JsMessageQueue( 4896): Set native->JS mode to OnlineEventsBridgeMode
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (15:237 vsyncs) (17:1120)
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_4785/cgroup.procs: No such file or directory
,I/vclib   ( 4923): onServiceConnected
,E/WifiStateMachine(  891): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.66 rxSuccessRate=20.69 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  891): WifiStateMachine CMD_START_SCAN with age=15003 interval=30000 maxinterval=300000
E/WifiStateMachine(  891): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
,E/WifiStateMachine(  891): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  891): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,E/WifiStateMachine(  891): [1,458,044,199,765 ms] noteScanstart no scan source
,I/wpa_supplicant( 1421): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-STARTED 
,W/Babel   ( 4923): Attempted to change video mute state without an active call.
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5004 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,V/AlarmManager(  891): done {19f7b612, *alarm*:com.android.server.WifiManager.action.START_SCAN} [9840ms]
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  303): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  484): NL - Read 56 bytes from update socket.
D/TCMD    (  484): NL - message type is RTM_NEWLINK
D/TCMD    (  484): Listening for incoming client connection request
,E/WifiStateMachine(  891): [1,458,044,199,827 ms] noteScanEnd no scan source
,D/GCM     ( 1820): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/WifiStateMachine(  891): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b9adf74 sup_state=COMPLETED debouncing=false
,W/ResourcesManager( 5004): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5025 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 4716:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_4716/cgroup.procs: No such file or directory
,E/Adreno-ES20( 4896): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4896): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,E/SQLiteLog( 5025): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,D/jxcore_app_log( 4896): JniHelper::setJavaVM(0xb7a1f310), pthread_self() = -1210457824
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4086b4c added. We now have 1 listener(s)
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4896): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4896): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4896): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4896): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dfd49b added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4896): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4896): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4896): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4896): Constructor: Bluetooth LE discovery mode is not supported
,I/art     (  891): Explicit concurrent mark sweep GC freed 21456(1065KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.610ms total 125.794ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4896): bind: Binding a new listener
D/WifiService(  891): New client listening to asynchronous messages
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4896): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,V/io.jxcore.node.ConnectivityMonitor( 4896): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 4896):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 4896):     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 4896):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4896):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4896):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 4896):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 4896):     - active network type is Wi-Fi: true
,D/io.jxcore.node.JXcoreExtension( 4896): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 4896): start: OK
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5049 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/io.jxcore.node.ConnectivityMonitor( 4896): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 4896): updateConnectivityInfo: No relevant state changes
,I/chromium( 4896): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 5049): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5025): PlayLogger.onLoggerConnected
,I/CalendarProvider2( 5049): Created com.android.providers.calendar.CalendarAlarmManager@3edfb8fd(com.android.providers.calendar.CalendarProvider2@4d09f2)
,I/ActivityManager(  891): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5072 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5072): getAccountsCursor
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityThread( 5072): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  891): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5097 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ActivityManager(  891): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5097): EasService.onCreate
,I/Gmail   ( 5072): Observing account changes for notifications
,I/Exchange( 5097): RestartPingTask
W/GAV2    ( 5072): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 5097): RestartPingsTask did not start any pings.
I/Exchange( 5097): PSS stopIfIdle
I/Exchange( 5097): PSS has no active accounts; stopping service.
,I/Exchange( 5097): onDestroy
I/ActivityManager(  891): Killing 4923:com.google.android.talk/u0a70 (adj 15): empty #7
,I/Gmail   ( 5072): getAccountsCursor
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_4923/cgroup.procs: No such file or directory
V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2602): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2602): time to show notification
,I/ActivityManager(  891): Killing 4979:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_4979/cgroup.procs: No such file or directory
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 5072): (283) recovered 85 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5072): notifyAccountChanged
,I/Gmail   ( 5072): getAccountsCursor
,I/art     ( 2602): Explicit concurrent mark sweep GC freed 39213(2MB) AllocSpace objects, 7(135KB) LOS objects, 39% free, 11MB/19MB, paused 1.304ms total 91.675ms
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5072): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ResourcesManager( 1300): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,I/Gmail   ( 5072): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 3196): Explicit concurrent mark sweep GC freed 2702(106KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 793us total 40.793ms
,I/Gmail   ( 5072): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5072): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5136 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/ActivatableNotificationView( 1300):  oops Width=0 ActualHeight=128
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5072): getAccountsCursor
,V/GLSActivity( 1820): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5049): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5049): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  891): Killing 1963:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  891): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8d0f084)
,D/WifiService(  891): Client connection lost with reason: 4
,D/ConnectivityService(  891): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  891): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_1963/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  891): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5158 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 21.118ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 451us total 20.249ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.504ms
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5175 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 4859:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  891): Killing 5004:com.motorola.context/u0a8 (adj 15): empty #7
,W/jxcore-log( 4896): Initializing JXcore engine
W/jxcore-log( 4896): JXcore engine is ready
,D/TaskPersister(  891): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_4859/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_5004/cgroup.procs: No such file or directory
,W/ResourcesManager( 5175): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Thread-530( 5045): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9314]" dev="sockfs" ino=9314 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-530( 5045): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-530( 5045): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6517]" dev="sockfs" ino=6517 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-530( 5045): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22906]" dev="sockfs" ino=22906 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4896): Starting JXcore engine
,W/jxcore-log( 4896): Platform android
W/jxcore-log( 4896): 
W/jxcore-log( 4896): Process ARCH arm
W/jxcore-log( 4896): 
,I/Babel_SMS( 5175): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5175): MmsConfig.loadMmsSettings,
I/Babel_SMS( 5175): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5175): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5175): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5175): MmsConfig.loadFromResources
,E/Babel_SMS( 5175): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5175): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5175): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5175): startup - clean
,I/Babel   ( 5175): deleted: false for 0
,W/art     ( 5175): Suspending all threads took: 5.860ms
,I/ActivityManager(  891): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5211 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/AlarmManager(  891): send {21c01620, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 5175): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5175): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5175): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5175): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5175): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5175): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5175): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5175): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5230 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 5049:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/ContactLocale( 5211): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  891): failed to open /acct/uid_10005/pid_5049/cgroup.procs: No such file or directory
,W/asset   ( 5230): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5230): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5230): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5230): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/vclib   ( 5175): onServiceConnected
,W/Babel   ( 5175): Attempted to change video mute state without an active call.
,I/jxcore-log( 4896): JXcore Cordova bridge is ready!
I/jxcore-log( 4896): 
,W/jxcore-log( 4896): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4896): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4896): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 4896): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4896): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,W/ResourcesManager( 5175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,I/chromium( 4896): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,W/ResourcesManager( 5175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/chromium( 4896): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 4896): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2602): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/SFPerfTracer(  278):      triggers: (rate: 11:349) (compose: 0:1) (post: 0:1) (render: 0:2) (36:1096 frames) (37:1192)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb8c6e6e8): 0:14)* (DimLayer (0xb8ca66e8): 0:6)* (StatusBar (0xb8c0cd28): 37:171) (NavigationBar (0xb8c0f9f8): 0:35) (com.android.systemui.ImageWallpaper (0xb8c5ba58): 0:35)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8c60190): 0:52)- (Starting com.test.thalitest (0xb8c62580): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8ca8ad8): 0:51) 
,V/JNIHelp ( 5175): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5175): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5175): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 5136): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@f820ab5 new=com.google.android.velvet.VelvetApplication@f820ab5
,I/ActivityManager(  891): Start proc com.google.android.gms for service com.google.android.gms/.chimera.GmsIntentOperationService: pid=5262 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  891): Explicit concurrent mark sweep GC freed 13430(713KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 2.113ms total 193.571ms
,D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5282 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5262): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5262): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/IInputConnectionWrapper( 4896): showStatusIcon on inactive InputConnection
,D/AndroidRuntime( 5252): 
D/AndroidRuntime( 5252): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/Keyboard.Facilitator( 1425): onFinishInput()
,D/AndroidRuntime( 5252): CheckJNI is OFF
,I/LaunchCheckinHandler(  891): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,9763
I/LaunchCheckinHandler(  891): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5239 (total)
,W/ResourcesManager( 5282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MultiDex( 5262): VM with version 2.1.0 has multidex support
I/MultiDex( 5262): install
I/MultiDex( 5262): VM has multidex support, MultiDex support library is disabled.
,I/UpdateIcingCorporaServi( 5136): UpdateCorporaTask done [took 356 ms] updated apps [took 356 ms] 
,I/ActivityManager(  891): Killing 5097:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  891): failed to open /acct/uid_10060/pid_5097/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5252): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 4896:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,D/WifiService(  891): Client connection lost with reason: 4
,W/InputDispatcher(  891): channel '233f60ce com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  891): channel '233f60ce com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowState(  891): WIN DEATH: Window{233f60ce u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
W/InputDispatcher(  891): Attempted to unregister already unregistered input channel '233f60ce com.test.thalitest/com.test.thalitest.MainActivity (server)'
,W/PackageSettings(  891): Skipping PackageSetting{2d49145b com.example.hello/10568} due to missing metadata
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (26:322 vsyncs) (28:1221)
,I/SBar.MotoNetworkCtrlr( 1300): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  891): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,W/ActivityManager(  891): Spurious death for ProcessRecord{2346b78b 4896:com.test.thalitest/u0a109}, curProc for 4896: null
,I/Keyboard.Facilitator( 1425): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1425): run()
,I/Decoder ( 1425): createOrResetDecoder
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 3031): Explicit concurrent mark sweep GC freed 9383(1604KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 5.058ms total 88.893ms
,V/JNIHelp ( 5262): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SFPerfTracer(  278):      triggers: (rate: 11:349) (compose: 0:1) (post: 0:1) (render: 0:3) (16:1136 frames) (17:1239)
D/SFPerfTracer(  278):        layers: (4:10) (FocusedStackFrame (0xb8c6e6e8): 0:16)* (DimLayer (0xb8ca66e8): 0:7) (StatusBar (0xb8c0cd28): 0:190) (NavigationBar (0xb8c0f9f8): 0:48) (com.android.systemui.ImageWallpaper (0xb8c5ba58): 0:35)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8ca8ad8): 2:78)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8c5d3c0): 17:28) 
,I/ConfigService( 1820): onCreate
,W/ActivityThread( 5262): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5262): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e0ec0a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5262): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 5262): Reading stored module config
,I/art     ( 1582): Explicit concurrent mark sweep GC freed 2210(118KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 486us total 231.564ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1425): run()
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
,D/PkgBroadcastIntentOp( 5262): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 5262): Null package name or gms related package.  Ignoreing.
,D/WearableController( 5262): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1425): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = history
,D/TaskPersister(  891): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  891): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  891): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = user
,I/Launcher( 1582): Deferring update until onResume
D/NativeLibraryUtils( 5262): Install completed successfully. count=14 extracted=0
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1425): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1425): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1425): run()
I/StatsUtilsManager( 1425): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1425): shouldRecordStats() = Too Soon
,I/Icing   ( 5262): Storage manager: low false usage 1.70MB avail 3.10GB capacity 4.85GB
,I/art     (  891): Explicit concurrent mark sweep GC freed 20184(1516KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.932ms total 408.808ms
,I/art     ( 5262): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5262): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5352 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AndroidRuntime( 5252): Shutting down VM
,I/ActivityManager(  891): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5373 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 5072:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10063/pid_5072/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 5158:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_5158/cgroup.procs: No such file or directory
,D/Finsky  ( 5352): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ContextImpl( 5025): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,F/PackageManager(  891): Unable to write package manager settings, current changes will be lost at reboot
F/PackageManager(  891): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  891): 	at libcore.io.IoBridge.write(IoBridge.java:502)
F/PackageManager(  891): 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
F/PackageManager(  891): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  891): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  891): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  891): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  891): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:119)
F/PackageManager(  891): 	at com.android.internal.util.FastXmlSerializer.startTag(FastXmlSerializer.java:366)
F/PackageManager(  891): 	at com.android.server.pm.Settings.writeDisabledSysPackageLPr(Settings.java:1879)
F/PackageManager(  891): 	at com.android.server.pm.Settings.writeLPr(Settings.java:1682)
F/PackageManager(  891): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1174)
F/PackageManager(  891): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:798)
F/PackageManager(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/PackageManager(  891): 	at android.os.Looper.loop(Looper.java:135)
F/PackageManager(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/PackageManager(  891): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
F/PackageManager(  891): Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  891): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  891): 	at libcore.io.Posix.write(Posix.java:223)
F/PackageManager(  891): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
F/PackageManager(  891): 	at libcore.io.IoBridge.write(IoBridge.java:497)
F/PackageManager(  891): 	... 15 more
,I/GAV2    ( 5025): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  891): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5417 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/RollingFileStream( 5352): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,I/GAv4-SVC( 5262): Google Analytics 8.7.03 is starting up.
,E/native  ( 1425): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1425): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1425): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1425): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1425): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1425): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,W/ResourcesManager( 5417): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Finsky  ( 5352): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/SBar.MotoNetworkCtrlr( 1300): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
