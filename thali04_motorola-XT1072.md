#### Test 62885377aa56850_thali04_motorola-XT1072 Logs


```
--------- beginning of main
D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,I/SundryService( 2559): onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
D/WaitableIntentService( 2559): setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
D/SundryService( 2559): onHandleIntent(): isWaitEnabled=false
D/WaitableIntentService( 2559): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2559): unbindWebServices(): un-registering our AIDL callback...
--------- beginning of system
V/AlarmManager(  884): done {18d94570, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10898ms]
D/WearableService( 1716): callingUid 10016, callindPid: 1716
D/AuthorizationBluetoothService( 1716): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1958): Restart initialization of location
E/MDM     ( 1716): [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  884): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4657 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1716): No location to return for getLastLocation()
W/FusedLocationProvider( 1716): location=null
D/AndroidRuntime( 4643): 
D/AndroidRuntime( 4643): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4643): CheckJNI is OFF
D/ActivityThread( 4657): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/Gmail   ( 4657): getAccountsCursor
V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  884): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4689 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4643): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/GAV2    ( 4657): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (191 us)
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  884): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/AndroidRuntime( 4643): Shutting down VM
I/Exchange( 4689): EasService.onCreate
I/Gmail   ( 4657): Observing account changes for notifications
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4722 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/Exchange( 4689): RestartPingTask
I/Exchange( 4689): RestartPingsTask did not start any pings.
I/Exchange( 4689): PSS stopIfIdle
I/Exchange( 4689): PSS has no active accounts; stopping service.
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Gmail   ( 4657): getAccountsCursor
I/Exchange( 4689): onDestroy
I/ActivityManager(  884): Killing 4560:com.android.providers.calendar/u0a5 (adj 15): empty #7
V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_4560/cgroup.procs: No such file or directory
,I/CE-UpdateModelService( 4540): ACTION_REGISTRATION_COMPLETE
,I/ActivityManager(  884): Killing 4582:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,E/SQLiteLog( 4657): (283) recovered 68 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/WebViewFactory( 4722): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  884): failed to open /acct/uid_10096/pid_4582/cgroup.procs: No such file or directory
,I/Gmail   ( 4657): notifyAccountChanged
,I/Gmail   ( 4657): getAccountsCursor
,I/Gmail   ( 4657): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/3CDM.DeviceAdminPushReceiver( 2559): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,D/3CDM.DeviceAdminPushReceiver( 2559): Type: null
D/3CDM.DeviceAdminPushReceiver( 2559): Data: null
D/MMApiWSBase( 2559): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2559): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2559): AppWSProxy - sendAIDLWSResponse() sending reponse
,D/3CDM.Service( 2559): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,D/3CDM.Service( 2559): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2559): DeviceAdmin - syncWithCCC
,D/3CDM.Service( 2559): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2559): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2559): blur.service.cred.locationToken = null
D/3CDM.Service( 2559): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2559): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2559): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2559): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4657): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/3CDM.Service( 2559): Sync to CCE settings done, instantiate Locate now.
,I/LibraryLoader( 4722): Time to load native libraries: 5 ms (timestamps 8751-8756)
I/LibraryLoader( 4722): Expected native library version number "",actual native library version number ""
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.39 rxSuccessRate=19.59 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=13624 interval=30000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=false
,E/WifiStateMachine(  884): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
E/WifiStateMachine(  884): [1,458,040,371,261 ms] noteScanstart no scan source
I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/Gmail   ( 4657): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4657): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/global frequency( 2559): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/WebViewChromiumFactoryProvider( 4722): Binding Chromium to main looper Looper (main, tid 1) {1117137c}
,I/LibraryLoader( 4722): Expected native library version number "",actual native library version number ""
,I/chromium( 4722): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4759 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/AlarmManager(  884): done {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN} [7192ms]
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  884): [1,458,040,371,317 ms] noteScanEnd no scan source
,I/BrowserStartupController( 4722): Initializing chromium process, singleProcess=true
,W/art     ( 4722): Attempt to remove local handle scope entry from IRT, ignoring
,D/CheckinProvider(  884): 38 events delete 0 left
E/SysUtils( 4722): ApplicationContext is null in ApplicationStatus
E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@337aba70 sup_state=COMPLETED debouncing=false
,D/BSUtils ( 2559): set .setup.DeviceAdminSetupReceiver enabled
,W/chromium( 4722): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 4722): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4722): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4722): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4722): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4722): Local Branch: 
I/Adreno-EGL( 4722): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4722): Local Patches: NONE
I/Adreno-EGL( 4722): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 4759): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/global frequency( 2559): BcsDSCheckin.events found events 0
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2559): BcsTimer.onReceive checkin completed (-1046550831:ERROR_OK)
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/Gmail   ( 4657): getAccountsCursor
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fe37ab1:true
,I/Babel_SMS( 4759): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4759): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4759): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 4759): MmsConfig.loadFromDatabase
,W/art     ( 4722): Attempt to remove local handle scope entry from IRT, ignoring
,I/SFPerfTracer(  280):      triggers: (rate: 13:551) (compose: 0:1) (post: 0:1) (render: 0:2) (11:859 frames) (12:929)
D/SFPerfTracer(  280):        layers: (4:12) (FocusedStackFrame (0xb7f44650): 0:10)* (DimLayer (0xb7eed3c8): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7eeed30): 0:30)- (StatusBar (0xb7f2e030): 0:133) (NavigationBar (0xb7f2fd48): 0:40) (com.android.systemui.ImageWallpaper (0xb7f32138): 0:6)* (Starting com.motorola.ccc.ota (0xb7f22f68): 0:39)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f50f98): 1:53)* (Starting com.test.thalitest (0xb7f22f68): 12:22) 
,W/AwContents( 4722): onDetachedFromWindow called when already detached. Ignoring
,E/Babel_SMS( 4759): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4759): MmsConfig.loadFromResources
E/Babel_SMS( 4759): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4759): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
D/SystemWebViewEngine( 4722): CordovaWebView is running on device made by: motorola
,W/DataUsage( 2559): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  884): Explicit concurrent mark sweep GC freed 16104(773KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.368ms total 127.806ms
,W/art     ( 4722): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4722): Attempt to remove local handle scope entry from IRT, ignoring
,W/Settings( 4759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4759): startup - clean
,I/Babel   ( 4759): deleted: false for 0
,D/OpenGLRenderer( 4722): Render dirty regions requested: true
,D/Atlas   ( 4722): Validating map...
,W/chromium( 4722): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (20:214 vsyncs) (22:936)
,I/OpenGLRenderer( 4722): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4722): Enabling debug mode 0
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4810 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1142
,I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s142ms
,W/VideoCapabilities( 4759): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4759): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 4759): Unsupported mime video/mpeg2
,E/Adreno-ES20( 4722): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4722): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/VideoCapabilities( 4759): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4759): Unrecognized profile 2130706433 for video/avc
,W/BindingManager( 4722): Cannot call determinedVisibility() - never saw a connection for the pid: 4722
,W/VideoCapabilities( 4759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4759): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4759): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Killing 4044:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_4044/cgroup.procs: No such file or directory
,I/vclib   ( 4759): onServiceConnected
W/Babel   ( 4759): Attempted to change video mute state without an active call.
,D/JsMessageQueue( 4722): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4840 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4603:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10055/pid_4603/cgroup.procs: No such file or directory
,D/PhoneMonitor( 4840): Register our PhoneStateListener
,V/SetupWizard( 4840): Connected to Gservices successfully
,I/ActivityManager(  884): Killing 4689:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10060/pid_4689/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4863 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/GCM     ( 1716): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/Adreno-ES20( 4722): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 4722): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4886 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/jxcore_app_log( 4722): JniHelper::setJavaVM(0xb7287310), pthread_self() = -1218518392
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb53dc8 added. We now have 1 listener(s)
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4722): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4722): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4722): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4722): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62fb647 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4722): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  884): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4722): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4722): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4722): Constructor: Bluetooth LE discovery mode is not supported
,W/ResourcesManager( 4886): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4722): bind: Binding a new listener
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4722): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - active network type is Wi-Fi: true
D/io.jxcore.node.JXcoreExtension( 4722): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 4722): start: OK
,I/CalendarProvider2( 4886): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,I/ActivityManager(  884): Killing 4657:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10063/pid_4657/cgroup.procs: No such file or directory
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: No relevant state changes
,I/chromium( 4722): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 4722): Background partial concurrent mark sweep GC freed 6107(546KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 12.850ms total 70.564ms
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4912 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4931 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 4759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4759): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4759): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4954 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4540:com.motorola.context/u0a8 (adj 15): empty #7
,I/ContactLocale( 4931): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 22.914ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.441ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.216ms
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_4540/cgroup.procs: No such file or directory
,W/asset   ( 4954): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4954): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4954): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4954): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4863): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32a11b81 new=com.google.android.velvet.VelvetApplication@32a11b81
,I/CalendarProvider2( 4886): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4886): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4981 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  884): Killing 4810:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/PkgBroadcastIntentOp( 1958): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 4863): UpdateCorporaTask done [took 211 ms] updated apps [took 211 ms] 
W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_4810/cgroup.procs: No such file or directory
I/ActivityManager(  884): Killing 4840:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 4981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_4840/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5015 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 4722): Initializing JXcore engine
W/jxcore-log( 4722): JXcore engine is ready
,I/ActivityManager(  884): Killing 4886:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/Thread-535( 4905): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9457]" dev="sockfs" ino=9457 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-535( 4905): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-535( 4905): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9591]" dev="sockfs" ino=9591 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-535( 4905): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22275]" dev="sockfs" ino=22275 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4722): Starting JXcore engine
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_4886/cgroup.procs: No such file or directory
,D/Finsky  ( 5015): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Finsky  ( 5015): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5015): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5015): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5057 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5057): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Finsky  ( 5015): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5015): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5015): Skipping gmscore version check
,I/CalendarProvider2( 5057): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,I/ActivityManager(  884): Killing 4912:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_4912/cgroup.procs: No such file or directory
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5083 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/Checkin ( 2966): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Finsky  ( 5015): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5015): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/UpdateIcingCorporaServi( 4863): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/art     (  884): Explicit concurrent mark sweep GC freed 13776(691KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.632ms total 145.953ms
,I/art     ( 1958): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/Icing   ( 1958): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/AsyncTaskServiceImpl( 1958): Submit a task: k
,D/k       ( 1958): Processing package: com.test.thalitest
,D/GassUtils( 1958): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1958): Found info for package com.test.thalitest in db.
W/BaseAppContext( 1958): Using Auth Proxy for data requests.
W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 4863): UpdateCorporaTask done [took 391 ms] updated apps [took 391 ms] 
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,I/ActivityManager(  884): Killing 4981:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5119 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4981/cgroup.procs: No such file or directory
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 43048(2MB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 13MB/22MB, paused 1.191ms total 119.260ms
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1958): cleanUpNonGplusAccounts done.
,I/CalendarProvider2( 5057): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5057): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Killing 5057:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_5057/cgroup.procs: No such file or directory
,I/art     ( 3816): Explicit concurrent mark sweep GC freed 3248(127KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 375us total 26.178ms
,I/art     ( 3816): WaitForGcToComplete blocked for 10.551ms for cause HomogeneousSpaceCompact
,I/Icing   ( 1958): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/Icing   ( 1958): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/GAv4    ( 5119): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5119):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5119):   adb logcat -s GAv4
,W/GAv4    ( 5119): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5119): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5119): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/AnalyticsTrackerProxyImpl( 5119): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5119): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5119): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5119): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5163 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 4931:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_4931/cgroup.procs: No such file or directory
,W/ResourcesManager( 5163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5119): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AlarmManager(  884): send {f808116, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,W/System  ( 5119): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5119): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5188 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/Finsky  ( 5015): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  884): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5211 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ContactLocale( 5188): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  884): Killing 5083:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/ResourcesManager( 5211): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_5083/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 4954:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10027/pid_4954/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5235 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5251 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4863:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Gmail   ( 5235): getAccountsCursor
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_4863/cgroup.procs: No such file or directory
,D/ActivityThread( 5235): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Killing 4759:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 5251): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:38000 mC
,I/ActivityManager(  884): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5284 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_4759/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5251): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 22.316ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.556ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.686ms
,W/GAV2    ( 5235): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  884): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5284): EasService.onCreate
I/Gmail   ( 5235): Observing account changes for notifications
,I/Exchange( 5284): RestartPingTask
,I/Exchange( 5284): RestartPingsTask did not start any pings.
I/Exchange( 5284): PSS stopIfIdle
I/Exchange( 5284): PSS has no active accounts; stopping service.
,I/Gmail   ( 5235): getAccountsCursor
,I/Exchange( 5284): onDestroy
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  884): Killing 5119:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10057/pid_5119/cgroup.procs: No such file or directory
,D/3CDM.DeviceAdminSetupReceiver( 2559): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2559): time to show notification
,I/ActivityManager(  884): Killing 5163:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_5163/cgroup.procs: No such file or directory
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1294): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,E/SQLiteLog( 5235): (283) recovered 69 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/AlarmManager(  884): done {f808116, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [1685ms]
,E/SQLiteLog( 5251): (284) automatic index on view_events(_id)
,E/ActivatableNotificationView( 1294):  oops Width=0 ActualHeight=128
,I/Gmail   ( 5235): notifyAccountChanged
,I/Gmail   ( 5235): getAccountsCursor
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5235): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5235): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5235): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5235): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  884): Explicit concurrent mark sweep GC freed 14930(722KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.832ms total 149.319ms
,I/Gmail   ( 5235): getAccountsCursor
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  884): send {379af8cc, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {379af8cc, *alarm*:android.intent.action.TIME_TICK} [27ms]
,I/CalendarProvider2( 5251): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5251): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Killing 5188:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_5188/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/SQLiteConnectionPool( 1958): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/AlarmManager(  884): send {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  884): send {3e295774, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  884): done {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1ms]
,V/AlarmManager(  884): done {3e295774, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [2ms]
,E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.77 rxSuccessRate=2.72 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=22990 interval=30000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  884): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  884): [1,458,040,380,627 ms] noteScanstart no scan source
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 3
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/TCMD    (  475): Listening for incoming client connection request
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  884): [1,458,040,380,698 ms] noteScanEnd no scan source
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@337aba70 sup_state=COMPLETED debouncing=false
,D/Finsky  ( 5015): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  884): send {30d4bd12, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  884): done {30d4bd12, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [6ms]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (37:309 vsyncs) (39:1046)
,I/SFPerfTracer(  280):      triggers: (rate: 13:553) (compose: 0:1) (post: 0:1) (render: 0:2) (38:961 frames) (39:1046)
D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb7f44650): 0:13)* (DimLayer (0xb7eed3c8): 0:6)* (StatusBar (0xb7f2e030): 39:172) (NavigationBar (0xb7f2fd48): 0:40) (com.android.systemui.ImageWallpaper (0xb7f32138): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f50f98): 0:54)- (Starting com.test.thalitest (0xb7f22f68): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7eef710): 0:61) 
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5015): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5015): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 5015): untagSocket(37) failed with errno -22
,D/Finsky  ( 5015): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5354 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 5354): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5354): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5354): VM with version 2.1.0 has multidex support
I/MultiDex( 5354): install
I/MultiDex( 5354): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5354): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ActivityThread( 5354): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5354): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f3fde0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5354): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1716): callingUid 10016, callindPid: 1716
,E/MDM     ( 1716): [167] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1958): Restart initialization of location
,D/AuthorizationBluetoothService( 1716): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5354): Reading stored module config
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1716): No location to return for getLastLocation()
W/FusedLocationProvider( 1716): location=null
,D/CAR.SERVICE( 5354): Connecting to CarCallService...
,D/NativeLibraryUtils( 5354): Install completed successfully. count=14 extracted=0
,I/art     ( 5354): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5354): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5354): com.google.android.projection.gearhead isn't installed.
,I/qtaguid ( 5015): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5015): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5015): untagSocket(37) failed with errno -22
,D/CAR.TEL.Service( 5354): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5354): Creating a new PhoneAdapter instance
,W/ActivityManager(  884): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5354): setListener: com.google.android.gms.car.dn@94a9c3c
,W/ActivityManager(  884): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5354): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5354): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5354): Package validated; name: com.android.vending
,V/Finsky  ( 5015): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/GAV2    ( 5235): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5015): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5015): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5015): untagSocket(37) failed with errno -22
,W/ActivityManager(  884): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,I/ActivityManager(  884): Waited long enough for: ServiceRecord{4d43667 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,W/ResourcesManager( 5015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5015): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  884): send {9106f07, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  884): done {9106f07, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [39ms]
D/DeviceConnectionService( 1716): client connected with version: 8296000
,D/Finsky  ( 5015): [590] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5015): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5015): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  884): Killing 5284:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10060/pid_5284/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/jxcore-log( 4722): Platform android
W/jxcore-log( 4722): 
,W/jxcore-log( 4722): Process ARCH arm
W/jxcore-log( 4722): 
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 4722): JXcore Cordova bridge is ready!
I/jxcore-log( 4722): 
,W/jxcore-log( 4722): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4722): execute: REQUEST_ACCESS_COARSE_LOCATION
,V/AlarmManager(  884): send {3187b9cc, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  884): done {3187b9cc, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,D/CAR.SERVICE( 5354): mConnectedToCar = false, abort
,E/ActivityThread( 5354): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c9a5ca4 that was originally bound here
E/ActivityThread( 5354): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c9a5ca4 that was originally bound here
E/ActivityThread( 5354): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5354): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5354): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5354): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5354): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5354): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5354): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5354): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5354): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5354): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5354): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5354): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5354): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5354): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5354): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5354): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5354): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5354): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5354): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5354): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@13ae5e2f that was originally bound here
E/ActivityThread( 5354): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@13ae5e2f that was originally bound here
E/ActivityThread( 5354): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5354): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5354): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5354): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5354): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5354): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5354): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5354): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5354): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5354): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5354): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5354): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5354): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5354): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5354): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5354): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5354): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5354): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  884): Unbind failed: could not find connection for android.os.BinderProxy@312e7415
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=331, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310925, SEQNUM=4351, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-16927, POWER_SUPPLY_CHARGE_COUNTER=-293, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,V/io.jxcore.node.JXcoreExtension( 4722): isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,I/jxcore-log( 4722): WARN testUtils BLE multiple advertisement issue: null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO testUtils Toggling radios to: true
I/jxcore-log( 4722): 
,D/BluetoothAdapter( 4722): enable(): BT is already enabled..!
,I/jxcore-log( 4722): Unit Test app is loaded
I/jxcore-log( 4722): 
,D/WifiService(  884): setWifiEnabled: true pid=4722, uid=10109
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 4722): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  293):  STA Disconnected !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
,I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  475): NL - Read 1004 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  884): InitialState.processMessage what=4
,E/WifiStateMachine(  884): WifiStateMachine: Leaving Connected state
,W/Settings(  884): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  884): ApnList is empty for checkDunConfigured()
D/Tethering(  884):  upstream interface types: 
D/Tethering(  884):  1
D/Tethering(  884):  5
,D/Tethering(  884):  7
D/Tethering(  884):  0
,E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  884): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  884): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  884): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1429): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 21
D/TCMD    (  475): Listening for incoming client connection request
,V/NativeCrypto( 1716): Read error: ssl=0xb7696e40: I/O error during system call, Connection timed out
V/NativeCrypto( 1716): SSL shutdown failed: ssl=0xb7696e40: I/O error during system call, Broken pipe
,E/GCM     ( 1716): Wifi connection closed with errorCode 20
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info<unknown ssid>
,D/ConnectivityService(  884): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Checking http://clients3.google.com/generate_204 on "NG700"
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  884): connected time updated 40787
,D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/wpa_supplicant( 1429): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  884): Start Disconnecting Watchdog 1
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  884): ConnectModeState: Network connection lost 
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService(  884): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1429): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/LaunchCheckinHandler(  884): cleanup(): cleared. Last call was 11827 ms ago
I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5438 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CommandListener(  290): Clearing all IP addresses on wlan0
,D/ConnectivityService(  884): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  884): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  884): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  884): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  884): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  884): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 5438): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1544): Explicit concurrent mark sweep GC freed 26248(1704KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 938us total 80.282ms
,I/Babel_SMS( 5438): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5438): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5438): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5438): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5438): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5438): MmsConfig.loadFromResources
,E/Babel_SMS( 5438): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5438): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5438): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5438): startup - clean
,I/Babel   ( 5438): deleted: false for 0
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  884): [1,458,040,395,456 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1429): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  884): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1429): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3664390f sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 5438): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5438): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5438): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5438): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5438): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5438): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5438): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5438): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Killing 5235:com.google.android.gm/u0a63 (adj 15): empty #7
,D/TCMD    (  475): NL - Read 312 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 180 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/TCMD    (  475): NL - Read 1004 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1429): wlan0: Associated with f4:f2:6d:22:99:3e
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
D/MDMCTBK (  293): Event received = Associated with f4:f2:6d
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 80 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
D/TCMD    (  475): NL - Read 68 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  884): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  884): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  884): ApnList is empty for checkDunConfigured()
D/Tethering(  884):  upstream interface types: 
,D/Tethering(  884):  0
,D/Tethering(  884):  1
,D/Tethering(  884):  5
,D/Tethering(  884):  7
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1429): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
D/TCMD    (  475): NL - Read 1004 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2457, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2457
I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2457
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
,I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  293): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
,I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
,I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
,I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1193230936
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
,I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
,D/Tethering(  884): sendTetherStateChangedBroadcast 1, 0, 0
,W/libprocessgroup(  884): failed to open /acct/uid_10063/pid_5235/cgroup.procs: No such file or directory
,I/vclib   ( 5438): onServiceConnected
,W/Babel   ( 5438): Attempted to change video mute state without an active call.
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  884): Network connection established
E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  884): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  884): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  884): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  884): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  884): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  884): Start Dhcp Watchdog 2
,E/WifiStateMachine(  884): calculateWifiScore() report new score 60
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  884): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  884): do suspend false
,E/wpa_supplicant( 1429): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  884): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1429): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  884): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@236fdfd2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@236fdfd2 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5484): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5484): version 5.5.6 starting
E/DHCPCD  ( 5484): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 5484): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 5484): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5484): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 5484): wlan0: rebinding lease of 192.168.1.112
D/DHCPCD  ( 5484): wlan0: sending REQUEST (xid 0x5e02ea4e), next in 3.02 seconds
,I/DHCPCD  ( 5484): wlan0: acknowledged 192.168.1.112 from 192.168.1.1
,I/DHCPCD  ( 5484): wlan0: leased 192.168.1.112 for 172800 seconds
D/DHCPCD  ( 5484): wlan0: adding IP address 192.168.1.112/24
,D/DHCPCD  ( 5484): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5484): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5484): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  475): NL - Read 60 bytes from update socket.
D/TCMD    (  475): NL - ignore NL message, type = 20
D/TCMD    (  475): Listening for incoming client connection request
,D/DHCPCD  ( 5484): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  884): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  884): WifiStateMachine DHCP successful
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  884): Calling ARP set with IP = 192.168.1.112
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/WifiStateMachine(  884): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  884): Adding iface wlan0 to network 101
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  884): ConnectedState Enter  mScreenOn=true scanperiod=20000
,E/ConnectivityService(  884): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  884): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  884): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  884): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  884): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  884): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  884): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884):    accepting network in place of null
,D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  884): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  884): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Mar 2016 11:13:17 GMT], X-Android-Received-Millis=[1458040396782], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458040396727]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Validated
D/ConnectivityService(  884): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1537): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1537): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  884): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524295
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524295
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  884): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: No relevant state changes
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5547 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2559): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: No relevant state changes
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2559): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/Central_PollingManager( 1471): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,V/AlarmManager(  884): send {18d94570, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2559): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2559): [debug] > CusSM.onRadioDown
,E/ActivityThread( 1958): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  884): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 181600, reason: UserStart
,I/MusicStore( 5547): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5547): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5547): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5547): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 5547): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5547): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5547): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5547): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5547): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2489c03b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5547): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5547): GMSCore installation verified
,I/ConfigStore( 5547): Config Database version: 1
,I/art     (  884): Explicit concurrent mark sweep GC freed 64477(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.591ms total 136.712ms
,I/MediaRouter( 5547): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,V/MusicLeanback( 5547): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5597 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5547): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5547): Using platform SSLCertificateSocketFactory
,V/Mms     ( 5597): mnc/mcc: 
V/Mms     ( 5597): tag: int value: recipientLimit - 20
V/Mms     ( 5597): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5597): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5597): tag: int value: maxSubjectLength - 80
V/Mms     ( 5597): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5597): tag: bool value: enableGroupMms - false
V/Mms     ( 5597):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  884): Killing 5251:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_5251/cgroup.procs: No such file or directory
,W/ResourcesManager( 5597): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5623 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5354:com.google.android.gms:car/u0a16 (adj 15): empty #7
,D/PhoneMonitor( 5623): Register our PhoneStateListener
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_5354/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 5623): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5623): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  884): Killing 5015:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_5015/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5642 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1958): Checking schedule, now: 1458040399317 next: 1458040396262
I/CheckinService( 1958): active receiver: enabled
,I/CheckinService( 1958): Preparing to send checkin request
,I/EventLogService( 1958): Accumulating logs since 1458040359166
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  884): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=5660 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  884): send {3a6047ee, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
V/AlarmManager(  884): send {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN}
V/AlarmManager(  884): done {3a6047ee, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [41ms]
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 117012 ,futureTime: 9223372036854775807
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 117012 ,futureTime: 9223372036854775807
D/PollingManager( 2559): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2559): now: 117012 ,futureTime: 9223372036854775807
D/OtaApp  ( 2559): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2559): [debug] > PollingManagerService, now: 117014 ,futureTime: 79949220
D/OtaApp  ( 2559): [debug] > Polling alarm set to expire at: 79949220 Current Time: 117015
,D/OtaApp  ( 2559): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2559): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: No relevant state changes
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/Central_PollingManager( 1471): now: 117025 ,futureTime: 86480417
D/Central_PollingManager( 1471): Polling alarm set to expire at: 86480417 Current Time: 117025
,I/OtaApp  ( 2559): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2559): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2559): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/NetworkMonitor( 5547): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2559): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2559): set mOutstandingReq to true.
I/ Nonce  ( 2559):  Nonce getNonce 
I/ Nonce  ( 2559):  Nonce Request 
I/ Nonce  ( 2559):  Nonce execute Request 
,D/MMApiWebService( 2559): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2559): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2559): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2559): createDeviceIdOrLogin update_device
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2559): Not proxy app, so login/provision not allowed
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5660): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/MMApiWebService( 2559): generating token using payload instead of using session token
,D/ Nonce  ( 2559):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2559): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5700 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 4722): My device name is: motorola-XT1072
I/jxcore-log( 4722): 
I/ActivityManager(  884): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5723 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/Finsky  ( 5660): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5660): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5660): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Babel   ( 5438): connection state changed from UNKNOWN to CONNECTED
,I/art     (  884): Explicit concurrent mark sweep GC freed 11990(591KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.793ms total 149.088ms
,D/Ads     ( 5660): Skipping gmscore version check
D/Finsky  ( 5660): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5660): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  884): Killing 5211:com.motorola.context/u0a8 (adj 15): empty #7
,W/ResourcesManager( 5723): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5723): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5723): VM with version 2.1.0 has multidex support
I/MultiDex( 5723): install
,I/MultiDex( 5723): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_5211/cgroup.procs: No such file or directory
,D/Finsky  ( 5660): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5660): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 5723): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5723): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5723): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f3fde0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5723): Installed default security provider GmsCore_OpenSSL
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/art     ( 5723): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5723): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAv4    ( 5700): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5700):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5700):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5700): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/GAv4    ( 5700): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5700): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 5723): Install completed successfully. count=14 extracted=0
,D/Finsky  ( 5660): [660] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5660): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/WVCdm   (  295): Instantiating CDM.
I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
I/art     ( 3816): Explicit concurrent mark sweep GC freed 3310(129KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 384us total 24.878ms
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbe9264e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8b166e8, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a14270, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8b4aa68, idLength=0xb54e7730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=931655297
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8aff170
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8af0c50, signature_length=3041818388
,I/WebViewFactory( 5700): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5700): Time to load native libraries: 1 ms (timestamps 8365-8366)
I/LibraryLoader( 5700): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5700): Binding Chromium to main looper Looper (main, tid 1) {34729f10}
I/LibraryLoader( 5700): Expected native library version number "",actual native library version number ""
I/chromium( 5700): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5700): Initializing chromium process, singleProcess=true
W/art     ( 5700): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5700): ApplicationContext is null in ApplicationStatus
,I/ Nonce  ( 2559):  Nonce Reponse 
D/        ( 2559): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"f155ba8e-8418-4239-9c0a-ab75da8d97fe"}
D/MMApiWSBase( 2559): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2559):  Nonce Handle Reponse 
D/MMApiProvisionService( 2559): mOutstandingReq set to false
,W/chromium( 5700): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5781 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,E/libEGL  ( 5700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5700): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5700): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5700): Local Branch: 
I/Adreno-EGL( 5700): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5700): Local Patches: NONE
I/Adreno-EGL( 5700): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/ResourcesManager( 5781): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5781): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,W/AudioManagerAndroid( 5700): Requires BLUETOOTH permission
,I/NSApplication( 5700): Starting up...
,D/MMApiProvisionService( 2559):  pTime 1457886726448 sExp 172742 cTime 1458040401180 tTime 1458059468448
D/MMApiProvisionService( 2559):  No login Required 
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5814 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5597:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 23.775ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 422us total 23.061ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.822ms
,I/dex2oat ( 5823): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  884): Killing 5547:com.google.android.music:main/u0a80 (adj 15): empty #8
,I/dex2oat ( 5823): dex2oat took 83.758ms (threads: 4)
,W/DataUsage( 2559): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2559): publish the event [tag = MOT_CCE event name = LOG]
,I/Adreno-EGL( 5723): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5723): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5723): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5723): Local Branch: 
I/Adreno-EGL( 5723): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5723): Local Patches: NONE
I/Adreno-EGL( 5723): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_5597/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_5547/cgroup.procs: No such file or directory
,I/Adreno-EGL( 5723): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5723): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5723): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5723): Local Branch: 
I/Adreno-EGL( 5723): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5723): Local Patches: NONE
I/Adreno-EGL( 5723): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  884): Killing 3053:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55e7960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8af0b68, dataLength=8
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a00718, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8b4aa88, idLength=0xb1422730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3841889996
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89ff068
D/DrmWidevineDash(  295): message_length=1622, signature=0xb89ff6c8, signature_length=2973902612
,W/libprocessgroup(  884): failed to open /acct/uid_10049/pid_3053/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5849 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 5623:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 5723): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5723): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5723): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5723): Local Branch: 
I/Adreno-EGL( 5723): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5723): Local Patches: NONE
I/Adreno-EGL( 5723): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5723): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5723): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5723): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5723): Local Branch: 
I/Adreno-EGL( 5723): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5723): Local Patches: NONE
I/Adreno-EGL( 5723): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_5623/cgroup.procs: No such file or directory
,W/ResourcesManager( 5849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5781): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5781): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Killing 5642:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_5642/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5870 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/ActivityManager(  884): Killing 5700:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/ContactLocale( 5870): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  884): failed to kill 1 processes for processgroup 5700
,I/ActivityManager(  884): Killing 5438:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_5438/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5910 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 5910): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5910): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5910): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5910): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 5910): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5910): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5910): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinTask( 1958): Sending checkin request (9875 bytes)
,W/ActivityThread( 5910): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5910): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2489c03b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5910): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5910): GMSCore installation verified
,I/ConfigStore( 5910): Config Database version: 1
,I/MediaRouter( 5910): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5910): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5910): type=WIFI subType= reason=null isConnected=true
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/NetworkMonitor( 5910): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=5946 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 5910): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5910): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  884): Killing 5660:com.android.vending/u0a32 (adj 15): empty #7
,V/Mms     ( 5946): mnc/mcc: 
V/Mms     ( 5946): tag: int value: recipientLimit - 20
V/Mms     ( 5946): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 5946): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 5946): tag: int value: maxSubjectLength - 80
V/Mms     ( 5946): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 5946): tag: bool value: enableGroupMms - false
V/Mms     ( 5946):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_5660/cgroup.procs: No such file or directory
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 5946): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5976 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  884): Explicit concurrent mark sweep GC freed 12167(567KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.569ms total 120.044ms
,I/ActivityManager(  884): Killing 5781:com.android.providers.calendar/u0a5 (adj 15): empty #7
,D/PhoneMonitor( 5976): Register our PhoneStateListener
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_5781/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 5976): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5976): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=5994 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5814:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_5814/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1458040404570 next: 1458641541565
I/CheckinService( 1958): active receiver: disabled
,I/CheckinService( 1958): Checking schedule, now: 1458040404587 next: 1458641541565
I/CheckinService( 1958): active receiver: disabled
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1458040404591
,I/ActivityManager(  884): Killing 5870:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  884): Killing 5849:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_5870/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_5849/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6027 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5910:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_5910/cgroup.procs: No such file or directory
,W/ResourcesManager( 6027): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6027): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6027): MmsConfig.loadMmsSettings
I/Babel_SMS( 6027): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6027): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6027): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6027): MmsConfig.loadFromResources
,E/Babel_SMS( 6027): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6027): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6027): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6027): startup - clean
,I/Babel   ( 6027): deleted: false for 0
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6062 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6027): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6027): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6027): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6027): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6027): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6027): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6027): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6027): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6027): onServiceConnected
W/Babel   ( 6027): Attempted to change video mute state without an active call.
,I/GAv4    ( 6062): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6062):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6062):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6062): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6062): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6062): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6062): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6027): connection state changed from UNKNOWN to CONNECTED
,I/WebViewFactory( 6062): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6062): Time to load native libraries: 2 ms (timestamps 3722-3724)
I/LibraryLoader( 6062): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6062): Binding Chromium to main looper Looper (main, tid 1) {34729f10}
,I/LibraryLoader( 6062): Expected native library version number "",actual native library version number ""
I/chromium( 6062): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6062): Initializing chromium process, singleProcess=true
W/art     ( 6062): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6062): ApplicationContext is null in ApplicationStatus
,W/chromium( 6062): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6062): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6062): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6062): Local Branch: 
I/Adreno-EGL( 6062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6062): Local Patches: NONE
I/Adreno-EGL( 6062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 6062): Requires BLUETOOTH permission
,I/NSApplication( 6062): Starting up...
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6126 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5976:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Killing 5946:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_5976/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_5946/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6149 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5994:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_5994/cgroup.procs: No such file or directory
,W/ResourcesManager( 6149): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6173 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.500ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 18.979ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.605ms
,I/ActivityManager(  884): Killing 6062:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 6173): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  884): failed to kill 1 processes for processgroup 6062
I/ActivityManager(  884): Killing 6027:com.google.android.talk/u0a70 (adj 15): empty #8
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_6027/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2559): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2559): onServiceConnected()
,D/GetNotificationsWS( 2559): onServiceConnected(): Registered for remote service callbacks...
,V/AlarmManager(  884): done {18d94570, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9467ms]
D/GetNotificationsWS( 2559): unbindWebServices(): un-registering our AIDL callback...
,E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=29.56 rxSuccessRate=26.50 targetRoamBSSID=any RSSI=-41
,E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=50083 interval=20000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN try full band scan age=50083 interval=20000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  884): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  884): [1,458,040,407,725 ms] noteScanstart no scan source
,I/PushService( 2559): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6216 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  884): done {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN} [8302ms]
,D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
,E/WifiStateMachine(  884): [1,458,040,407,788 ms] noteScanEnd no scan source
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@337aba70 sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MusicStore( 6216): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6216): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6216): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6216): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6216): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6216): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6216): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6216): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6216): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2489c03b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6216): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6216): GMSCore installation verified
,I/ConfigStore( 6216): Config Database version: 1
,I/MediaRouter( 6216): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6216): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6216): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6216): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6255 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6216): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6216): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  884): Killing 5723:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  884): Explicit concurrent mark sweep GC freed 16544(834KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.698ms total 136.068ms
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_5723/cgroup.procs: No such file or directory
,V/Mms     ( 6255): mnc/mcc: 
,V/Mms     ( 6255): tag: int value: recipientLimit - 20
V/Mms     ( 6255): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6255): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6255): tag: int value: maxSubjectLength - 80
V/Mms     ( 6255): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6255): tag: bool value: enableGroupMms - false
V/Mms     ( 6255):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6285 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6126:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_6126/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6285): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6285): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6285): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1958): Checking schedule, now: 1458040408899 next: 1458040434565
I/CheckinService( 1958): active receiver: disabled
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6308 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1958): Checking schedule, now: 1458040408949 next: 1458040434565
I/CheckinService( 1958): active receiver: disabled
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,I/ActivityManager(  884): Killing 6149:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_6149/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6328 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6173:android.process.acore/u0a7 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_6173/cgroup.procs: No such file or directory
,W/ResourcesManager( 1544): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 6328): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6328): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6328): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6328): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6328): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6328): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6328): MmsConfig.loadFromResources
,E/Babel_SMS( 6328): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6328): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  884): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  884): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@33b1535b
,I/GCoreNlp( 1716): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,W/Settings( 6328): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6328): startup - clean
,I/Babel   ( 6328): deleted: false for 0
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6367 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6328): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6328): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6328): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6328): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6328): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6328): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 6367): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6367):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6367):   adb logcat -s GAv4
W/VideoCapabilities( 6328): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6367): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6367): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 6328): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 6367): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 6328): onServiceConnected
W/Babel   ( 6328): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6367): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6367): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6367): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6367): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6328): connection state changed from UNKNOWN to CONNECTED
,I/WebViewFactory( 6367): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/LibraryLoader( 6367): Time to load native libraries: 1 ms (timestamps 7975-7976)
,I/LibraryLoader( 6367): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6367): Binding Chromium to main looper Looper (main, tid 1) {34729f10}
,I/LibraryLoader( 6367): Expected native library version number "",actual native library version number ""
,I/chromium( 6367): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6367): Initializing chromium process, singleProcess=true
,W/art     ( 6367): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6367): ApplicationContext is null in ApplicationStatus
,W/chromium( 6367): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6367): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6367): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6367): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6367): Local Branch: 
I/Adreno-EGL( 6367): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6367): Local Patches: NONE
I/Adreno-EGL( 6367): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 6367): Starting up...
,W/AudioManagerAndroid( 6367): Requires BLUETOOTH permission
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6430 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6255:com.android.mms/u0a23 (adj 15): empty #7
,I/ActivityManager(  884): Killing 6216:com.google.android.music:main/u0a80 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_6255/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_6216/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6452 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6285:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_6285/cgroup.procs: No such file or directory
,W/ResourcesManager( 6452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6476 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Killing 6328:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 6476): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  884): Killing 6308:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_6328/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_6308/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2559): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2559): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2559): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2559): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2559): onServiceConnected()
D/GetNotificationsWS( 2559): onServiceConnected(): Registered for remote service callbacks...
,D/OtaApp  ( 2559): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2559): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2559): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2559): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  884): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2559): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=6519 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2559): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2559): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2559): [info] > Exceed max defer attempts for optional update, suppresing later btn,
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2559): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2559): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2559): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2559): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2559): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2559): publish the event [tag = MOT_OTA event name = LOG]
,W/InputMethodManagerService(  884): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2ed30a93 (uid=10109 pid=4722)
W/IInputConnectionWrapper( 4722): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,192
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WearableService( 1716): callingUid 10016, callindPid: 1716
,D/LocationInitializer( 1958): Restart initialization of location
,E/MDM     ( 1716): [177] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1716): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6546 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.584ms
,W/GCoreFlp( 1716): No location to return for getLastLocation()
W/FusedLocationProvider( 1716): location=null
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 22.210ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 22.687ms
,I/art     (  884): Explicit concurrent mark sweep GC freed 20293(1002KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.783ms total 132.671ms
,W/ResourcesManager( 6546): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=6566 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6367:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10081/pid_6367/cgroup.procs: No such file or directory
,E/SQLiteLog( 6566): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6592 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6592): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6592): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,I/AnalyticsLogBase( 6566): PlayLogger.onLoggerConnected
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6623 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6623): Register our PhoneStateListener
,V/SetupWizard( 6623): Connected to Gservices successfully
,I/ActivityManager(  884): Killing 6430:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_6430/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6649 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/GCM     ( 1716): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ResourcesManager( 6649): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6649): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6649): MmsConfig.loadMmsSettings
I/Babel_SMS( 6649): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6649): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6649): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6649): MmsConfig.loadFromResources
,E/Babel_SMS( 6649): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6649): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6649): startup - clean
,I/Babel   ( 6649): deleted: false for 0
,D/GCM     ( 1716): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CalendarProvider2( 6592): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6592): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/VideoCapabilities( 6649): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6649): Unsupported mime audio/amr-wb-plus
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6682 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6452:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/VideoCapabilities( 6649): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6649): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6649): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6649): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6649): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6649): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_6452/cgroup.procs: No such file or directory
I/ActivityManager(  884): Killing 6476:android.process.acore/u0a7 (adj 15): empty #7
,I/vclib   ( 6649): onServiceConnected
W/Babel   ( 6649): Attempted to change video mute state without an active call.
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_6476/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6708 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6546:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_6546/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6730 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 6649): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6649): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6762 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 6649): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6649): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  884): Killing 6592:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/ContactLocale( 6730): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_6592/cgroup.procs: No such file or directory
,W/asset   ( 6762): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6762): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 6762): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6762): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32a11b81 new=com.google.android.velvet.VelvetApplication@32a11b81
I/UpdateIcingCorporaServi( 6682): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1958): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6790 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6790): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 6682): UpdateCorporaTask done [took 203 ms] updated apps [took 202 ms] 
,I/ActivityManager(  884): Killing 6623:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_6623/cgroup.procs: No such file or directory
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6826 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6519:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_6519/cgroup.procs: No such file or directory
,D/Finsky  ( 6826): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6826): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 6826): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6826): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6826): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6826): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6826): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6826): Skipping gmscore version check
,D/Finsky  ( 6826): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  884): Killing 6708:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_6708/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6873 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 239us total 22.440ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.355ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 19.697ms
,I/ActivityManager(  884): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6894 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/ResourcesManager( 6873): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6894): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6873): Created com.android.providers.calendar.CalendarAlarmManager@39452c49(com.android.providers.calendar.CalendarProvider2@3f68494e)
,V/AlarmManager(  884): send {3187b9cc, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  884): done {3187b9cc, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,I/ActivityManager(  884): Killing 6762:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,I/art     (  884): Explicit concurrent mark sweep GC freed 15624(787KB) AllocSpace objects, 3(137KB) LOS objects, 33% free, 21MB/32MB, paused 1.595ms total 126.354ms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/libprocessgroup(  884): failed to open /acct/uid_10027/pid_6762/cgroup.procs: No such file or directory
,W/ContextImpl( 6566): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 6566): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 6873): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 6873): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Killing 6682:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_6682/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  884): send {2b3b9b08, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): send {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  884): done {2b3b9b08, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4ms]
,V/AlarmManager(  884): done {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN} [6ms]
,E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.14 rxSuccessRate=1.83 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=63072 interval=20000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN try full band scan age=63072 interval=20000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN bump interval =30000
I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  884): [1,458,040,420,712 ms] noteScanstart no scan source
,I/ActivityManager(  884): Killing 6649:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_6649/cgroup.procs: No such file or directory
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1716): Vacuum at: now=1458040420991 tag=VacuumService
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,E/WifiStateMachine(  884): [1,458,040,421,138 ms] noteScanEnd no scan source
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@337aba70 sup_state=COMPLETED debouncing=false
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log( 4722): 
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 4722): 
,V/io.jxcore.node.ConnectivityMonitor( 4722): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 4722):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 4722):     - active network type is Wi-Fi: true
,D/io.jxcore.node.JXcoreExtension( 4722): notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 4722): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 4722): 
I/jxcore-log( 4722): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 4722): 
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  884): Waited long enough for: ServiceRecord{256d7cc4 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ActivityManager(  884): Killing 6790:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  884): Killing 6730:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_6790/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_6730/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:37000 mC
,E/BackupManagerService(  884): Timeout restoring application @pm@
,W/BackupManagerService(  884): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1716): Restore processing aborted, no more packages
,E/BackupManagerService(  884): Failure getting next package name
E/BackupManagerService(  884): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  884): send {3d4704d9, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  884): send {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  884): done {3d4704d9, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [9ms]
V/AlarmManager(  884): done {23351a40, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10ms]
,E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.32 rxSuccessRate=0.31 targetRoamBSSID=any RSSI=-41
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=15961 interval=30000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  884): WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
I/wpa_supplicant( 1429): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  884): [1,458,040,436,673 ms] noteScanstart no scan source
,I/CheckinService( 1958): Checking schedule, now: 1458040436684 next: 1458040434565
I/CheckinService( 1958): active receiver: enabled
,I/CheckinService( 1958): Preparing to send checkin request
I/EventLogService( 1958): Accumulating logs since 1458040399359
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  475): NL - Read 56 bytes from update socket.
D/TCMD    (  475): NL - message type is RTM_NEWLINK
D/TCMD    (  475): Listening for incoming client connection request
,I/CheckinRequestBuilder( 1958): Checkin reason type: 12 attempt count: 1
,E/WifiStateMachine(  884): [1,458,040,436,738 ms] noteScanEnd no scan source
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@337aba70 sup_state=COMPLETED debouncing=false
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6950 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6950): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6950): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6950): VM with version 2.1.0 has multidex support
I/MultiDex( 6950): install
I/MultiDex( 6950): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6950): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6950): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6950): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f3fde0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6950): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 1958): Restart initialization of location
,D/WearableService( 1716): callingUid 10016, callindPid: 1716
,D/AuthorizationBluetoothService( 1716): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1716): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1716): No location to return for getLastLocation()
W/FusedLocationProvider( 1716): location=null
,I/art     ( 6950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6950): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6950): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55e7960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8b03340, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a00718, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8b4aa48, idLength=0xbe9262b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3737698971
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89ff068
D/DrmWidevineDash(  295): message_length=1591, signature=0xb89ff6a8, signature_length=3197264532
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 6986): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6986): dex2oat took 64.768ms (threads: 4)
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb500c000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb55e7960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8a7cff0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a5ce08, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8b4aa88, idLength=0xb54e7730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3789355651
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89fc460
D/DrmWidevineDash(  295): message_length=1622, signature=0xb89fcac0, signature_length=3041818388
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:36000 mC
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6950): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6950): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6950): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6950): Local Branch: 
I/Adreno-EGL( 6950): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6950): Local Patches: NONE
I/Adreno-EGL( 6950): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,V/AlarmManager(  884): send {379af8cc, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): done {379af8cc, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/CheckinTask( 1958): Sending checkin request (9864 bytes)
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinRequestBuilder( 1958): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1458040440874 next: 1458641577860
I/CheckinService( 1958): active receiver: disabled
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1458040440893
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7010 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/PhoneMonitor( 7010): Register our PhoneStateListener
,V/SetupWizard( 7010): Connected to Gservices successfully
,D/GCM     ( 1716): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  884): Killing 6873:com.android.providers.calendar/u0a5 (adj 13): empty #7
,I/ActivityManager(  884): Killing 6826:com.android.vending/u0a32 (adj 15): empty #8
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_6873/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_6826/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7029 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  884): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  884): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@af07179
,I/GCoreNlp( 1716): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1571): Deferring update until onResume
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  884): Nap time (uid 1000)...
I/PowerManagerService(  884): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  884): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  884): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  884): Build Date: 10/28/14 Tue
I/Adreno-EGL(  884): Local Branch: 
I/Adreno-EGL(  884): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  884): Local Patches: NONE
I/Adreno-EGL(  884): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  884): Explicit concurrent mark sweep GC freed 33157(1627KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.621ms total 132.372ms
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7063 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7069 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6894:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_6894/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 6566:com.google.android.calendar/u0a49 (adj 15): empty #7
,D/        (  884): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  884): BstSensorExt: id=1598182242, en=0
,D/        (  884): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,D/        (  884): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  884): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb7e14550
,V/ActivityManager(  884): Display changed displayId=0
,D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,W/libprocessgroup(  884): failed to open /acct/uid_10049/pid_6566/cgroup.procs: No such file or directory
,W/ResourcesManager( 7069): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/rmt_storage(  289): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8be0820
,I/rmt_storage(  289): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  289): wakelock acquired: 1, error no: 42
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1195506376)
,I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  289): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1195506376) wakelock released: 1, error no: 0
I/rmt_storage(  289): 
,I/rmt_storage(  289): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8be0820
,I/Babel_SMS( 7069): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7069): MmsConfig.loadMmsSettings
I/Babel_SMS( 7069): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7069): MmsConfig.loadFromDatabase
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
D/SurfaceControl(  884): Excessive delay in setPowerMode(): 326ms
,I/PowerManagerService(  884): Sleeping (uid 1000)...
E/Babel_SMS( 7069): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7069): MmsConfig.loadFromResources
I/WindowManager(  884): AOD feature not enabled!
E/Babel_SMS( 7069): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7069): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/WifiStateMachine(  884): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  884): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  884): do suspend false
,W/Settings( 7069): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7069): startup - clean
,D/        (  884): activate, handle: 1598182229, enabled: 0, index 0
E/        (  884): <BST> disable accel, orig state: 1
I/        (  884): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
D/WifiStateMachine(  884): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  884): handleScreenStateChanged Exit: false
E/WifiStateMachine(  884): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  884): do suspend true
I/Babel   ( 7069): deleted: false for 0
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1419): onFinishInput()
,I/art     ( 1716): Explicit concurrent mark sweep GC freed 46632(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.042ms total 75.322ms
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7117 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7069): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7069): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7069): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7138 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7010:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 7117): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/VideoCapabilities( 7069): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 4722): 
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_7010/cgroup.procs: No such file or directory
,W/asset   ( 7138): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7138): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7138): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7138): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7029): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32a11b81 new=com.google.android.velvet.VelvetApplication@32a11b81
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1958): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7166 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/vclib   ( 7069): onServiceConnected
W/Babel   ( 7069): Attempted to change video mute state without an active call.
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7069): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 4722): 
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/art     ( 7069): Suspending all threads took: 6.055ms
,I/UpdateIcingCorporaServi( 7029): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
V/JNIHelp ( 7069): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7069): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7069): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7197 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:36000 mC
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 4722): 
,I/ActivityManager(  884): Killing 6950:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log( 4722): 
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_6950/cgroup.procs: No such file or directory
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 4722): 
,D/Finsky  ( 7197): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 4722): 
,D/Finsky  ( 7197): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7197): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7197): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7197): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7197): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7197): Skipping gmscore version check
,D/Finsky  ( 7197): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7197): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  884): Killing 7063:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log( 4722): 
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_7063/cgroup.procs: No such file or directory
,I/jxcore-log( 4722): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 4722): 
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 56278(3MB) AllocSpace objects, 36(1230KB) LOS objects, 39% free, 7MB/12MB, paused 783us total 49.340ms
,V/AlarmManager(  884): send {1587b948, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  884): done {1587b948, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [17ms]
,I/ActivityManager(  884): Killing 7138:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10027/pid_7138/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 7029:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_7029/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:35000 mC
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=317, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311108, SEQNUM=4450, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-611, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:34000 mC
,V/AlarmManager(  884): send {1aee03e1, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {1aee03e1, *walarm*:com.google.android.intent.action.SEND_IDLE} [9ms]
,I/PhenotypeConfigurator( 1716): Scheduling Phenotype for one-off execution 11982 seconds from now (1458040478505)
,I/PhenotypeFlagCommitter( 1716): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1716): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1716): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/global frequency( 2559): no tags to log
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  884): Explicit concurrent mark sweep GC freed 28348(1370KB) AllocSpace objects, 2(212KB) LOS objects, 33% free, 21MB/32MB, paused 1.527ms total 125.518ms
,I/art     ( 2559): Explicit concurrent mark sweep GC freed 39091(2MB) AllocSpace objects, 7(135KB) LOS objects, 40% free, 11MB/19MB, paused 1.120ms total 93.278ms
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1471): Explicit concurrent mark sweep GC freed 6765(302KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 594us total 32.135ms
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1544): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2559): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2559): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2559): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2559): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2559): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2559): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2559): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2559): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=305, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311247, SEQNUM=4458, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-675, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1716): disconnect managed GoogleApiClient
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {36a5678d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  884): done {36a5678d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [9ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  884): send {379af8cc, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  884): send {e083d42, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  884): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7314 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  884): done {379af8cc, *alarm*:android.intent.action.TIME_TICK} [97ms]
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 51.117ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 27.950ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 29.737ms
,I/GAv4    ( 7314): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7314):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7314):   adb logcat -s GAv4
,W/GAv4    ( 7314): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7314): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7314): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  884): done {e083d42, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [397ms]
,I/ActivityManager(  884): Killing 7069:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_7069/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1419): run()
,I/Keyboard.Facilitator( 1419): flushDynamicLanguageModels()
,I/ConfigService( 1716): onCreate
,I/art     ( 1716): Background sticky concurrent mark sweep GC freed 101542(5MB) AllocSpace objects, 25(423KB) LOS objects, 26% free, 16MB/22MB, paused 2.007ms total 104.406ms
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/ConfigService( 1716): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4722): Reconnected to the test server
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): TAP version 13
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 1. calling createNativeListener directly rejects
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 1 Should throw
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 2. emits incomingConnectionState
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 2 initial connection state should be CONNECTED
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 3 final connection state should be DISCONNECTED
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 3. emits routerPortConnectionFailed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 4 routerPortConnectionFailed is emitted
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 4. native server connections all up
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 5 Send/recvd #1 should be equal length
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 6 Send/recvd #1 should be same
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 7 Send/recvd #2 should be equal length
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 8 Send/recvd #2 should be same
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 9 Should be exactly 2 client sockets
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 5. native server - closing incoming stream cleans outgoing socket
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311711, SEQNUM=4470, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-762, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,I/jxcore-log( 4722): ok 10 socket shouldn't close until after stream
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 11 incoming remains open
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 6. native server - closing incoming connection cleans outgoing socket
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 12 we should not have gotten an error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 13 socket shouldn't close until after incoming
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 14 incoming is cleaned up
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 7. native server - closing outgoing socket cleans associated mux stream
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 15 stream was closed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 16 incoming should survive
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 17 mux should have no streams
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 8. native server - closing the whole server cleans everything up
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 18 we should not have gotten an error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 19 Buffers are identical
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 20 native server is nulled out
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 21 native server should be closed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 22 incoming has been removed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 23 Incoming should be done
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 24 The mux object should be closed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 25 The mux stream should be closed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 9. native server - we can get a ton of connections and data through and still clean up the server completely
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 26 native server is nulled out
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 27 native server should be closed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 28 incoming has been removed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 10. native server - simulate mux failure, make sure everything is cleaned up
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 29 we should not have gotten an error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 30 Buffers are identical
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 31 server should be fine
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 32 server should be open
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 33 incoming has been removed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 34 The mux object should be closed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 35 The mux stream should be closed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 11. native server - timing out the incoming connection cleans everything up
I/jxcore-log( 4722): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 36 we should not have gotten an error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 37 Buffers are identical
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 38 server should be fine
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 39 server should be open
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 40 incoming has been removed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 41 The mux object should be closed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 42 The mux stream should be closed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 12. closeAll can close even when connections open
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 43 not possible to connect to the server anymore
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 13. closeAll with promise
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 44 not possible to connect to the server anymore
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 14. multiplex can send data
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 45 String should be length:200
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4722): # 15. enqueue and run in order
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 46 firstPromise setTimeout
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 47 firstPromise result
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 48 firstPromise testValue
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 49 secondPromise setTimeout
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 50 secondPromise result
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 51 secondPromise testValue
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 52 thirdPromise in promise
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 53 thirdPromise result
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 54 thirdPromise testValue
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 16. enqueueAtTop and run backwards
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 55 thirdPromise - first to run
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 56 thirdPromise - in resolve
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 57 secondPromise - second to run
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 58 secondPromise - in catch
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 59 firstPromise - third to run
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 60 firstPromise - in then
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 61 testing promises
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 17. mix enqueue and enqueueAtTop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 62 fourth
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 63 fourth
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 64 second
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 65 secondPromise - in then
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 66 first
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 67 firstPromise - in catch
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 68 third
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 69 thirdPromise - in then
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 70 testingPromises
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 18. queues handled independently
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 71 all short operations completed before the long resolves
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 19. basic
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 72 sane
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 20. another
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 73 sane
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 21. #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 74 specific error should be returned
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 75 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 76 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 22. #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 77 specific error should be returned
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 78 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 79 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 23. should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 80 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 81 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 82 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 83 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 84 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 85 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 24. should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 86 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 87 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 88 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 89 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 90 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 91 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 25. should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 92 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 93 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 94 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 95 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 96 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 97 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 26. should be able to call #stopAdvertisingAndListening many times
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 98 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 99 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 100 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 101 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 102 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 103 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 27. #start should fail if called twice in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 104 first call should succeed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 105 first call should succeed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 106 specific error should be returned
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 107 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 108 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 28. does not emit duplicate discoveryAdvertisingStateUpdate
I/jxcore-log( 4722): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 109 called only once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 110 discovery state matches
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 111 advertising state matches
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 112 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 113 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 29. does not send duplicate availability changes
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 114 should be called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 115 should not have been called more than once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 116 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 117 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 30. can get the network status
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 118 network status should have certain non-empty properties
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 119 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 120 error should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 31. wifi peer is marked unavailable if announcements stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 121 host address should match
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 122 port should match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 123 host address should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 124 port should should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 125 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 126 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # 32. can get the network status before starting
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 127 network status should have certain non-empty properties
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 33. #generatePreambleAndBeacons bad args
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 128 publicKeysToNotify cannot be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 129 ecdh for local device cannot be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 130 milliseconds cannot be less than 0
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 131 milliseconds cannot be 0
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 132 milliseconds cannot be greater than one_day
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 34. #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 133 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 35. #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 134 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 135 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 136 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 137 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 36. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 138 should throw
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 37. #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 139 Preamble expiration must be a 64 bit integer
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 38. #parseBeacons expiration out of range lower
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 140 Expiration out of range
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 4722): # 39. #parseBeacons expiration out of range lower
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 141 Expiration out of range
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 40. #parseBeacons no beacons returns null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 142 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 41. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 143 Malformed encrypted beacon key ID
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 42. #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 144 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 43. #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 145 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 146 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 44. #parseBeacons addressBookCallback returns spurious match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 147 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 148 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 45. #parseBeacons addressBookCallback returns public key
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 149 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 150 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 46. #parseBeacons with beacons both for and not for the user
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 151 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 152 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 47. Start and stop ThaliNotificationServer
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 153 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 154 ThaliMobile.StopAdvertisingAndListening should be called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 48. Pass an empty array to ThaliNotificationServer.start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 155 StartUpdateAdvertisingAndListening should not be called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 156 ThaliMobile.StopAdvertisingAndListening should be called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 157 no error
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 158 should be 204
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 49. Pass a string to ThaliNotificationServer.start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 159 StartUpdateAdvertisingAndListening should not be called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 50. Pass an empty parameter to ThaliNotificationServer.start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 160 StartUpdateAdvertisingAndListening should not be called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 4722): # 51. Make an HTTP request to /NotificationBeacons
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 161 no error
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 162 should be 200
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 163 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 164 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 165 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 166 no error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 167 should be 204
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 52. Make an HTTP request to /NotificationBeacons (no keys)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 168 error should be null
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 169 should be 204
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 53. Make an HTTP request to /NotificationBeacons before calling start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 170 should be 404
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 54. #testThaliPeerAction - test getters
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 171 getPeerIdentifier
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 172 getConnectionType
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 173 getActionType
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 174 getActionState
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 55. #testThaliPeerAction - start and kill
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 175 initial state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 176 after start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 177 after kill
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 56. #testThaliPeerAction - double start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 178 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 57. #testThaliPeerAction - start after kill
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 179 clean kill
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 180 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 58. #testThaliPeerAction - make sure ids are unique
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 181 should not be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 59. Test PeerConnectionInformation basics
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 182 getHostAddress works
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 183 getPortNumber works
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 184 getSuggestedTCPTimeout works
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 60. Test PeerDictionary basic functionality
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 185 Entry counter must be 1
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 186 Size must be 1
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 187 Entry counter must be 2
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 188 Size must be 2
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 189 Entry2 should not be found
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 190 Size must be 1
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 191 Size must be 0
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 192 entry not found must be thrown
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 61. Test PeerDictionary with multiple entries.
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 4722): ok 193 Size must be100
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 194 Entries between 20 and MAXSIZE + 20 should exist
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 195 WAITING state entry should not be removed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 62. RESOLVED entries are removed before WAITING state entry.
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 196 Entries between 6 and MAXSIZE + 4 should exist
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 197 Size should be MAXSIZE
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 198 Size should be MAXSIZE+6
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 63. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 199 WAITING state entry should not be removed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 200 Waiting entries between 6 and MAXSIZE + 4 should exist
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 201 Size should be MAXSIZE
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 202 entryCounter should be MAXSIZE+6
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 64. When CONTROLLED_BY_POOL entry is removed and kill is called.
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 203 Kill should be called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 204 Size should be 100
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 65. #ThaliPeerPoolInterface - bad enqueues
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 205 null arg
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 206 wrong arg type
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 207 wrong state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 66. #ThaliPeerPoolInterface - do not allow same object type
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 208 good enqueue
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 209 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 67. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 210 good enqueue
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 211 2nd good enqueue
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 212 we are in the pool
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 213 We are out of the pool
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 214 Action was killed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 215 The original kill was called too
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 216 second item is still in queue
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 68. compareBufferArrays
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 217 should throw
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 218 should throw
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 219 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 220 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 221 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 222 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 223 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 69. Call start twice and get error
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 224 should throw
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 70. Start and make sure it runs
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 71. Make sure getTimeWhenRun is right after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 225 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 72. Make sure getTimeWhenRun is -1 after function is called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 226 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 73. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 227 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 228 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 229 should throw
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 74. Test TransientState
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 230 should throw
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 231 should throw
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 232 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 233 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 234 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 235 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 236 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 237 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 4722): # 75. No peers and empty database
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 238 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 239 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 240 constructor called with right args
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 241 match start arg
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 242 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 243 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 244 stop after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 76. One peer and empty DB
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 245 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 246 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 247 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 248 match start arg
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 249 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 250 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 251 stop after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 77. One peer with _Local set behind current seq
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 252 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 253 constructor called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 254 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 255 match start arg
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 256 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 257 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 258 stop after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 78. One peer with _Local set equal to current seq
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 259 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 260 constructor called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 261 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 262 match start arg
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 263 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 264 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 265 stop after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 79. One peer with _Local set ahead of current seq (and no this should not happen)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 266 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 267 constructor called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 268 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 269 match start arg
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 270 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 271 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 272 stop after start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 80. Three peers, one not in DB, one behind and one ahead
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 273 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 274 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 275 constructor called with right args
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 276 match start arg
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 277 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 278 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 279 stop after start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 81. More than maximum peers, make sure we only send maximum allowed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=298, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310659, SEQNUM=4505, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-15825, POWER_SUPPLY_CHARGE_COUNTER=-888, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2425): Disconnected process message: 10, size: 0
,I/jxcore-log( 4722): ok 280 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 281 constructor called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 282 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 283 match start arg
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 284 start called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 285 stop called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 286 stop after start
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 82. two peers with empty DB, update the doc
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 287 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 288 constructor called once
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 289 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 290 last start before stop
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 291 empty first start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 292 full second start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 293 only 2 timers
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 83. add doc and make sure tokens refresh when they expire
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 294 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 295 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 296 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 297 start before stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 298 We got at least 3 calls to start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 299 at least 3
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 300 default 1
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 301 1 run
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 302 default 2
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 303 2 run
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 304 default 3
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 84. start and stop and start and stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 305 start out null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 306 back to null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 307 still null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 308 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 309 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 310 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 311 first start before first stop
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 312 first stop before second start
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 313 second start before second stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 85. two identical starts in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 314 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 315 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 316 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 317 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 86. two different starts in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 318 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 319 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 320 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 321 (unnamed assert)
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 322 (unnamed assert)
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 87. two stops and a start and two stops
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 4722): ok 323 verify failed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 324 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 325 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 326 start before stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 88. we properly enqueue requests so no then needed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 327 verify failed
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 328 constructor called once
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 329 constructor called with right args
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 330 start before stop
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 89. test calculateSeqPointKeyId
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 331 should be equal
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 332 should be equal
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 90. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 333 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 334 peer identifier should match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 335 host address should match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 336 port should match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 337 host address should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 338 port should should be null
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 339 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 91. #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 340 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 341 USN should have changed from the first one
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 342 when receiving the second byebye, the first USN should be already set
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 343 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 92. messages with invalid location or USN should be ignored
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 344 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 345 should not have emitted with invalid port
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): WARN thaliWifiInfrastructure Received an invalid USN value: 
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 346 should not have emitted with invalid USN
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 347 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 93. verify that Thali-specific messages are filtered correctly
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 348 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 349 irrelevant messages should be ignored
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 350 relevant messages should not be ignored
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 351 messages from this device should be ignored
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 352 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 94. #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 353 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 354 specific error should be returned
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 355 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 95. #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 356 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 357 specific error should be returned
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 358 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 96. #start should fail if called twice in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 359 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 360 specific error should be received
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 361 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 97. should not be started after stop is called
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 362 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 363 should not be started
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 364 should not be listening
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 365 should not target listening
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 366 should not be advertising
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 367 should not target advertising
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 368 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 98. #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 369 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,E/jxcore-log( 4722): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 370 specific error should be received
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 371 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 99. #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 372 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,E/jxcore-log( 4722): ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
E/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 373 specific error expected
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 374 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 100. #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 375 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 376 server should respond with code 200
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 377 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 101. #stop can be called multiple times in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 378 should be in started state
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 379 should be in stopped state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 380 should still be in stopped state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 381 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 102. #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 382 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 383 should be in listening state
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 384 should still be in listening state
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 385 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 103. #stopListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 386 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 387 should not be in listening state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 388 should still not be in listening state
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 389 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 104. #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 390 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 391 should not be in advertising state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 392 should still not be in advertising state
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 393 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 105. functions are run from a queue in the right order
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 394 should be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 395 call order must match
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 396 should not be in started state
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 106. #ThaliPeerPoolDefault - single action
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 397 is an agent
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 398 enqueue is fine
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 399 Everything should be off the queue
I/jxcore-log( 4722): 
I/jxcore-log( 4722): # setup
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # 107. #ThaliPeerPoolDefault - multiple actions
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): # teardown
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 400 is an agent
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ok 401 first enqueue is fine
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 402 is an agent
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 403 second enqueue is fine
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 404 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ok 405 Queue is empty
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): Tests Complete
I/jxcore-log( 4722): 
,I/chromium( 4722): [INFO:CONSOLE(78)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (78)
,I/jxcore-log( 4722): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 4722): 
,I/jxcore-log( 4722): ****TEST TOOK:  ms ****
I/jxcore-log( 4722): 
I/jxcore-log( 4722): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4722): 
,I/chromium( 4722): [INFO:CONSOLE(78)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (78)
,I/jxcore-log( 4722): Disconnected from the test server
I/jxcore-log( 4722): 
,D/AndroidRuntime( 7531): 
D/AndroidRuntime( 7531): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7531): CheckJNI is OFF
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 7531): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  884): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 4722:com.test.thalitest/u0a109 (adj 7): stop com.test.thalitest
,W/PackageSettings(  884): Skipping PackageSetting{2b288207 com.example.hello/10568} due to missing metadata
,I/WindowState(  884): WIN DEATH: Window{20cbe82a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  884): Client connection lost with reason: 4
,I/ActivityManager(  884):   Force finishing activity ActivityRecord{ced41f3 u0 com.test.thalitest/.MainActivity t9}
,I/ActivityManager(  884): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/art     ( 2966): Explicit concurrent mark sweep GC freed 9251(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 7MB/12MB, paused 4.010ms total 39.162ms
,W/ActivityManager(  884): Spurious death for ProcessRecord{26e0eb8e 4722:com.test.thalitest/u0a109}, curProc for 4722: null
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1716): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
,I/art     ( 1571): Explicit concurrent mark sweep GC freed 2855(150KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 509us total 86.471ms
,I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
,D/VoicemailCleanupService( 7117): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1419): createOrResetDecoder
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7561 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  884): Explicit concurrent mark sweep GC freed 18108(1437KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 1.486ms total 187.967ms
,I/art     (  884): WaitForGcToComplete blocked for 86.221ms for cause Explicit
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 17401(1020KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 940us total 199.001ms
,I/ConfigService( 1716): onCreate
,W/asset   ( 7561): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7561): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7561): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7561): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
,I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7586 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/art     (  884): Explicit concurrent mark sweep GC freed 5287(275KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.485ms total 201.799ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
,I/ActivityManager(  884): Killing 7166:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/AndroidRuntime( 7531): Shutting down VM
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7166/cgroup.procs: No such file or directory
,W/ContextImpl( 7586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  884): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7609 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/Launcher( 1571): Deferring update until onResume
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7628 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7197:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_7197/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 1958:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  884): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2a02797b)
D/WifiService(  884): Client connection lost with reason: 4
,D/ConnectivityService(  884): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_1958/cgroup.procs: No such file or directory
E/ConnectivityService(  884): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32a11b81 new=com.google.android.velvet.VelvetApplication@32a11b81
,I/ActivityManager(  884): Start proc com.google.android.gms for service com.google.android.gms/.chimera.GmsIntentOperationService: pid=7649 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7649): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7649): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/MultiDex( 7649): VM with version 2.1.0 has multidex support
I/MultiDex( 7649): install
I/MultiDex( 7649): VM has multidex support, MultiDex support library is disabled.

```
