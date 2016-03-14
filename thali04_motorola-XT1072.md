#### Test 6250909442642cd_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
--------- beginning of system
W/ActivityThread( 4776): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4776): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4776): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4776): GMSCore installation verified
I/ConfigStore( 4776): Config Database version: 1
,I/MediaRouter( 4776): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/NetworkMonitor( 4776): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 4776): type=WIFI subType= reason=null isConnected=true
D/3CDM.DeviceAdminPushReceiver( 2545): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2545): Type: null
D/3CDM.DeviceAdminPushReceiver( 2545): Data: null
I/MusicLeanback( 4776): Stop autocaching.
D/3CDM.Service( 2545): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2545): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2545): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2545): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2545): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2545): blur.service.cred.locationToken = null
D/3CDM.Service( 2545): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2545): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2545): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2545): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
I/MusicLeanback( 4776): Stop autocaching.
V/AlarmManager(  879): done {22de9dc9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [8055ms]
V/AlarmManager(  879): done {7bfec7b, *alarm*:com.android.server.WifiManager.action.START_SCAN} [7381ms]
V/AlarmManager(  879): done {284a5aa, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [7382ms]
D/3CDM.Service( 2545): Sync to CCE settings done, instantiate Locate now.
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=29.89 rxSuccessRate=25.41 targetRoamBSSID=any RSSI=-43
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN with age=1457937484366 interval=20000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN try full band scan age=1457937484366 interval=20000 maxinterval=300000
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  879): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  879): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1438): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  879): [1,457,937,484,371 ms] noteScanstart no scan source
I/GHttpClientFactory( 4776): Using our fixed implementation of GMSCore's GoogleHttpClient
E/SQLiteLog( 4728): (284) automatic index on view_events(_id)
I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4831 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
I/GoogleURLConnFactory( 4776): Using platform SSLCertificateSocketFactory
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  486): NL - Read 56 bytes from update socket.
D/TCMD    (  486): NL - message type is RTM_NEWLINK
D/TCMD    (  486): Listening for incoming client connection request
E/WifiStateMachine(  879): [1,457,937,484,438 ms] noteScanEnd no scan source
E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
D/BSUtils ( 2545): set .setup.DeviceAdminSetupReceiver enabled
D/Checkin ( 2997): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
I/MusicLeanback( 4776): Stop autocaching.
I/MusicLeanback( 4776): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4776): Stop autocaching.
D/AndroidRuntime( 4813): 
D/AndroidRuntime( 4813): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4813): CheckJNI is OFF
D/PhoneMonitor( 4831): Register our PhoneStateListener
I/CalendarProvider2( 4728): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4728): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  879): Killing 4610:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
W/libprocessgroup(  879): failed to open /acct/uid_10096/pid_4610/cgroup.procs: No such file or directory
V/SetupWizard( 4831): Connected to Gservices successfully
I/ActivityManager(  879): Killing 4630:com.google.android.deskclock/u0a55 (adj 15): empty #7
E/GmsUtils( 4776): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 4776): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/libprocessgroup(  879): failed to open /acct/uid_10055/pid_4630/cgroup.procs: No such file or directory
I/ActivityManager(  879): Killing 4685:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
I/ThermalEngine(  302): Sensor:xo_therm_pu2:36000 mC
D/AndroidRuntime( 4813): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_4685/cgroup.procs: No such file or directory
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (139 us)
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4813): Shutting down VM
I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4872 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/GCM     ( 1803): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4889 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ResourcesManager( 4872): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WebViewFactory( 4889): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4889): Time to load native libraries: 3 ms (timestamps 7004-7007)
,I/LibraryLoader( 4889): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4889): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 4889): Expected native library version number "",actual native library version number ""
I/chromium( 4889): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Babel_SMS( 4872): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4872): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4872): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 4872): MmsConfig.loadFromDatabase
I/BrowserStartupController( 4889): Initializing chromium process, singleProcess=true
W/art     ( 4889): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4889): ApplicationContext is null in ApplicationStatus
,E/Babel_SMS( 4872): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4872): MmsConfig.loadFromResources
,W/chromium( 4889): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/Babel_SMS( 4872): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4872): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/libEGL  ( 4889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4889): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4889): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4889): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4889): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4889): Local Branch: 
I/Adreno-EGL( 4889): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4889): Local Patches: NONE
I/Adreno-EGL( 4889): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/Settings( 4872): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38b44315:true
,I/Babel_Crash( 4872): startup - clean
,I/Babel   ( 4872): deleted: false for 0
,I/art     (  879): Explicit concurrent mark sweep GC freed 15973(775KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.231ms total 144.919ms
,I/SFPerfTracer(  278):      triggers: (rate: 14:483) (compose: 0:1) (post: 0:1) (render: 0:2) (11:910 frames) (12:988)
D/SFPerfTracer(  278):        layers: (4:12) (FocusedStackFrame (0xb77eb220): 0:12)* (DimLayer (0xb7871670): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb78632e8): 0:32)- (StatusBar (0xb78656d8): 0:149) (NavigationBar (0xb7868858): 0:48) (com.android.systemui.ImageWallpaper (0xb781dc98): 0:8)* (Starting com.motorola.ccc.ota (0xb7876528): 0:37)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7842f68): 1:45)* (Starting com.test.thalitest (0xb7876528): 12:23) 
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4950 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 4889): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4889): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4889): CordovaWebView is running on device made by: motorola
,W/art     ( 4889): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4889): Attempt to remove local handle scope entry from IRT, ignoring
,W/VideoCapabilities( 4872): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4872): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 4872): Unsupported mime video/mpeg2
,D/OpenGLRenderer( 4889): Render dirty regions requested: true
,I/VideoCapabilities( 4872): Unsupported profile 4 for video/mp4v-es
,D/Atlas   ( 4889): Validating map...
,W/VideoCapabilities( 4872): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4872): Unrecognized profile 2130706433 for video/avc
,W/chromium( 4889): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/VideoCapabilities( 4872): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4872): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Killing 4658:com.google.android.gm/u0a63 (adj 15): empty #7
,I/OpenGLRenderer( 4889): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4889): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_4658/cgroup.procs: No such file or directory
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1063
,I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +1s64ms
,I/vclib   ( 4872): onServiceConnected
,W/Babel   ( 4872): Attempted to change video mute state without an active call.
,E/Adreno-ES20( 4889): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4889): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4889): Cannot call determinedVisibility() - never saw a connection for the pid: 4889
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4984 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 4776:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/JsMessageQueue( 4889): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_4776/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5017 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:258 vsyncs) (45:1042)
,D/jxcore_app_log( 4889): JniHelper::setJavaVM(0xb83ca310), pthread_self() = -1200253752
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
,E/Adreno-ES20( 4889): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4889): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5037 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
D/BluetoothManagerService(  879): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/ActivityManager(  879): Killing 4831:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4889): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4889): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4889): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4889): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4889): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  879): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4889): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4889): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4889): Constructor: Bluetooth LE discovery mode is not supported
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_4831/cgroup.procs: No such file or directory
,W/ResourcesManager( 4872): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4872): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4872): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/chromium( 4889): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 4889): Background partial concurrent mark sweep GC freed 8785(745KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/19MB, paused 5.323ms total 63.513ms
,W/System  ( 4872): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4872): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5063 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 4950:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 5037): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_4950/cgroup.procs: No such file or directory
,W/asset   ( 5063): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5063): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5063): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4984): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,D/PkgBroadcastIntentOp( 1951): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 1951): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5088 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1951): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1951): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5088): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4984): UpdateCorporaTask done [took 305 ms] updated apps [took 305 ms] 
,I/ActivityManager(  879): Killing 4753:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_4753/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5116 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 21.308ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.172ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.859ms
,I/ActivityManager(  879): Killing 4728:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10005/pid_4728/cgroup.procs: No such file or directory
,D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/Finsky  ( 5116): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/jxcore-log( 4889): Initializing JXcore engine
W/jxcore-log( 4889): JXcore engine is ready
,W/Thread-539( 5056): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[8479]" dev="sockfs" ino=8479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,D/Finsky  ( 5116): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Thread-539( 5056): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-539( 5056): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[10008]" dev="sockfs" ino=10008 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-539( 5056): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[19277]" dev="sockfs" ino=19277 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4889): Starting JXcore engine
,W/Settings( 5116): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5116): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 5116): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5116): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5116): Skipping gmscore version check
,I/ActivityManager(  879): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5166 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5017:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/Icing   ( 1951): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/jxcore-log( 4889): Platform android
W/jxcore-log( 4889): 
W/jxcore-log( 4889): Process ARCH arm
W/jxcore-log( 4889): 
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_5017/cgroup.procs: No such file or directory
,D/Finsky  ( 5116): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5116): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Icing   ( 1951): Loaded CLD2 Version V2.0 - 20141016
,I/Gmail   ( 5166): getAccountsCursor
,D/ActivityThread( 5166): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1951): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5190 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  879): Explicit concurrent mark sweep GC freed 12523(643KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.661ms total 130.878ms
,W/ActivityManager(  879): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5190): EasService.onCreate
,I/Exchange( 5190): RestartPingTask
,I/Gmail   ( 5166): Observing account changes for notifications
,I/Exchange( 5190): RestartPingsTask did not start any pings.
I/Exchange( 5190): PSS stopIfIdle
I/Exchange( 5190): PSS has no active accounts; stopping service.
,W/GAV2    ( 5166): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 5166): getAccountsCursor
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 5190): onDestroy
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5224 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 5063:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/jxcore-log( 4889): JXcore Cordova bridge is ready!
I/jxcore-log( 4889): 
,W/jxcore-log( 4889): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4889): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_5063/cgroup.procs: No such file or directory
I/chromium( 4889): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/ActivityManager(  879): Killing 4984:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/jxcore  ( 4889): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4889): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4889): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
I/chromium( 4889): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_4984/cgroup.procs: No such file or directory
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 4889): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2545): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2545): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2545): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,E/SQLiteLog( 5166): (283) recovered 113 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5248 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2545): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2545): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,I/ActivityManager(  879): Killing 5088:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/Checkin ( 2545): publish the event [tag = MOT_OTA event name = LOG]
,I/Gmail   ( 5166): notifyAccountChanged
,I/Gmail   ( 5166): getAccountsCursor
,I/Gmail   ( 5166): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5166): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5166): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5166): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_5088/cgroup.procs: No such file or directory
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/asset   ( 5248): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5248): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5248): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator( 1414): onFinishInput()
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/IInputConnectionWrapper( 4889): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,8863
I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5252 (total)
,D/AndroidRuntime( 5246): 
D/AndroidRuntime( 5246): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5246): CheckJNI is OFF
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5271 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 5116:com.android.vending/u0a32 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_5116/cgroup.procs: No such file or directory
,D/AndroidRuntime( 5246): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,I/ActivityManager(  879): Killing 4889:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,W/PackageSettings(  879): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
,D/WifiService(  879): Client connection lost with reason: 4
,I/WindowState(  879): WIN DEATH: Window{d4f48e8 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/ActivityManager(  879): Spurious death for ProcessRecord{28aadd87 4889:com.test.thalitest/u0a109}, curProc for 4889: null
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/SFPerfTracer(  278):      triggers: (rate: 14:488) (compose: 0:1) (post: 0:1) (render: 0:2) (9:996 frames) (10:1092)
D/SFPerfTracer(  278):        layers: (5:12) (FocusedStackFrame (0xb77eb220): 0:17)* (DimLayer (0xb7871670): 0:7) (StatusBar (0xb78656d8): 5:168) (NavigationBar (0xb7868858): 0:61) (com.android.systemui.ImageWallpaper (0xb781dc98): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7842f68): 0:46)- (Starting com.test.thalitest (0xb7876528): 0:42)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb78632e8): 10:83) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7876528): 7:12) 
,I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
,I/art     ( 2997): Explicit concurrent mark sweep GC freed 11177(1708KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 7MB/12MB, paused 1.117ms total 51.420ms
,I/Decoder ( 1414): createOrResetDecoder
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 2192(117KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 580us total 84.296ms
,D/PkgBroadcastIntentOp( 1951): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/ConfigService( 1803): onCreate
,I/Gmail   ( 5166): getAccountsCursor
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableController( 1951): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     ( 1951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
,I/Launcher( 1572): Deferring update until onResume
,D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  879): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/art     (  879): Explicit concurrent mark sweep GC freed 22554(1624KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.622ms total 363.874ms
,D/AndroidRuntime( 5246): Shutting down VM
,E/Icing   ( 1951): Package com.test.thalitest not found
,D/AsyncTaskServiceImpl( 1951): Submit a task: k
,I/ActivityManager(  879): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5319 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  879): send {ccd8b7d, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/UpdateIcingCorporaServi( 5271): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/k       ( 1951): Processing package: com.test.thalitest
,E/Vision  ( 1951): Failed to find package com.test.thalitest
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,W/k       ( 1951): Failed to find package com.test.thalitest
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,W/ResourcesManager( 5319): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5340 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 5319): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,I/ActivityManager(  879): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5358 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 3064:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10049/pid_3064/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 5166:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10063/pid_5166/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  879): Skipping unknown process pid 5163
,W/ProcessCpuTracker(  879): Skipping unknown process pid 5164
W/ProcessCpuTracker(  879): Skipping unknown process pid 5172
,W/ProcessCpuTracker(  879): Skipping unknown process pid 5378
W/ProcessCpuTracker(  879): Skipping unknown process pid 5379
,I/PeopleDatabaseHelper( 1951): cleanUpNonGplusAccounts done.
,E/SQLiteLog( 5271): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AppDataSearchHelper( 5271): Exception thrown from onTableChanged
E/AppDataSearchHelper( 5271): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 5271): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 5271): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 5271): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 5271): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 5271): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 5271): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 5271): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 5271): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 5271): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227),
E/AppDataSearchHelper( 5271): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 5271): 	... 16 more
W/AppDataSearchHelper( 5271): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 5271): UpdateCorporaTask done [took 751 ms] updated apps [took 750 ms] 
E/native  ( 1414): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1414): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1414): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1414): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  879): Killing 5190:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,E/SQLiteDatabase( 1951): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteDatabase( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:368)
E/SQLiteDatabase( 1951): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:500)
E/SQLiteDatabase( 1951): 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:143)
E/SQLiteDatabase( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:380)
E/SQLiteDatabase( 1951): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 1951): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 1951): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3734)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/SQLiteDatabase( 1951): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/SQLiteDatabase( 1951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1951): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1951): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1951): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1951): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteOpenHelper( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:368)
E/SQLiteOpenHelper( 1951): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteOpenHelper( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:500)
E/SQLiteOpenHelper( 1951): 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:143)
E/SQLiteOpenHelper( 1951): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:380)
E/SQLiteOpenHelper( 1951): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteOpenHelper( 1951): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 1951): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3734)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/SQLiteOpenHelper( 1951): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/SQLiteOpenHelper( 1951): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1951): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1951): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1951): Opened games_3a3529a.db in read-only mode
,W/libprocessgroup(  879): failed to open /acct/uid_10060/pid_5190/cgroup.procs: No such file or directory
E/native  ( 1414): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1414): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1414): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1414): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/GCore-Chimera-Crash( 1951): Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
I/GCore-Chimera-Crash( 1951): 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM2KRjU36UR
I/GCore-Chimera-Crash( 1951): IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
I/GCore-Chimera-Crash( 1951): ==
I/GCore-Chimera-Crash( 1951): GCore-Chimera-Crash
--------- beginning of crash
E/AndroidRuntime( 1951): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 1951): Process: com.google.android.gms, PID: 1951
E/AndroidRuntime( 1951): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:780)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/AndroidRuntime( 1951): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1951): 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
E/AndroidRuntime( 1951): 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
E/AndroidRuntime( 1951): 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
E/AndroidRuntime( 1951): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1668)
E/AndroidRuntime( 1951): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1589)
E/AndroidRuntime( 1951): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1951): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1951): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  879): Killing 4872:com.google.android.talk/u0a70 (adj 15): empty #7
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
