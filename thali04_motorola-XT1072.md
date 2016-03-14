#### Test 62754403b276699_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_4280/cgroup.procs: No such file or directory
D/ActivityThread( 4902): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
--------- beginning of main
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  882): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4940 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
I/ActivityManager(  882): Killing 3561:com.android.defcontainer/u0a10 (adj 15): empty #7
W/ActivityManager(  882): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/libprocessgroup(  882): failed to open /acct/uid_10010/pid_3561/cgroup.procs: No such file or directory
V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [264ms]
I/Gmail   ( 4902): Observing account changes for notifications
I/Exchange( 4940): EasService.onCreate
W/GAV2    ( 4902): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Exchange( 4940): RestartPingTask
I/Exchange( 4940): RestartPingsTask did not start any pings.
I/Exchange( 4940): PSS stopIfIdle
I/Exchange( 4940): PSS has no active accounts; stopping service.
I/ActivityManager(  882): Killing 4774:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
W/libprocessgroup(  882): failed to open /acct/uid_10096/pid_4774/cgroup.procs: No such file or directory
I/Gmail   ( 4902): getAccountsCursor
I/Exchange( 4940): onDestroy
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  882): Killing 4813:com.google.android.deskclock/u0a55 (adj 15): empty #7
D/AndroidRuntime( 4946): 
D/AndroidRuntime( 4946): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4946): CheckJNI is OFF
W/libprocessgroup(  882): failed to open /acct/uid_10055/pid_4813/cgroup.procs: No such file or directory
I/CE-UpdateModelService( 4745): ACTION_REGISTRATION_COMPLETE
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  882): Killing 4839:com.android.providers.calendar/u0a5 (adj 15): empty #7
W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_4839/cgroup.procs: No such file or directory
D/3CDM.DeviceAdminPushReceiver( 2738): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2738): Type: null
D/3CDM.DeviceAdminPushReceiver( 2738): Data: null
D/3CDM.Service( 2738): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2738): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2738): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2738): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2738): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2738): blur.service.cred.locationToken = null
D/3CDM.Service( 2738): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2738): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2738): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2738): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
D/3CDM.Service( 2738): Sync to CCE settings done, instantiate Locate now.
D/LocationInitializer( 1951): Restart initialization of location
E/MDM     ( 1761): [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/SQLiteLog( 4902): (283) recovered 42 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  882): done {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [7351ms]
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=22.82 rxSuccessRate=20.58 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN with age=1457975820645 interval=20000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN try full band scan age=1457975820645 interval=20000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  882): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1451): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  882): [1,457,975,820,648 ms] noteScanstart no scan source
D/BSUtils ( 2738): set .setup.DeviceAdminSetupReceiver enabled
I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5007 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  882): [1,457,975,820,714 ms] noteScanEnd no scan source
E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
D/AndroidRuntime( 4946): Calling main entry com.android.commands.am.Am
W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
D/Checkin ( 3261): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
I/Gmail   ( 4902): notifyAccountChanged
I/Gmail   ( 4902): getAccountsCursor
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4902): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4902): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4902): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4902): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4946): Shutting down VM
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5027 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2738): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2738): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2738): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2738): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2738): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2738): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2738): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2738): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2738): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ResourcesManager( 5007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  882): Activity reported stop, but no longer stopping: ActivityRecord{3a33e1f9 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
I/Gmail   ( 4902): getAccountsCursor
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 5007): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5007): MmsConfig.loadMmsSettings
I/Babel_SMS( 5007): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5007): MmsConfig.loadFromDatabase
,I/WebViewFactory( 5027): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/Babel_SMS( 5007): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5007): MmsConfig.loadFromResources
,E/Babel_SMS( 5007): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5007): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/LibraryLoader( 5027): Time to load native libraries: 4 ms (timestamps 9275-9279)
I/LibraryLoader( 5027): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5027): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
I/LibraryLoader( 5027): Expected native library version number "",actual native library version number ""
,I/chromium( 5027): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5027): Initializing chromium process, singleProcess=true
W/art     ( 5027): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5027): ApplicationContext is null in ApplicationStatus
,W/Settings( 5007): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/chromium( 5027): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/Babel_Crash( 5007): startup - clean
,E/libEGL  ( 5027): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5027): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5027): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5027): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5027): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5027): Local Branch: 
I/Adreno-EGL( 5027): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5027): Local Patches: NONE
I/Adreno-EGL( 5027): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Babel   ( 5007): deleted: false for 0
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e7d0b53:true
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 5007): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5007): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5007): Unsupported mime video/mpeg2
,I/art     (  882): Explicit concurrent mark sweep GC freed 16492(819KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.545ms total 133.230ms
,I/VideoCapabilities( 5007): Unsupported profile 4 for video/mp4v-es
,I/SFPerfTracer(  279):      triggers: (rate: 12:550) (compose: 0:1) (post: 0:1) (render: 0:2) (10:823 frames) (11:901)
D/SFPerfTracer(  279):        layers: (4:12) (FocusedStackFrame (0xb71c3280): 0:10)* (DimLayer (0xb71a5d38): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb71aa470): 0:32)- (StatusBar (0xb7219a70): 0:138) (NavigationBar (0xb721b788): 0:34) (com.android.systemui.ImageWallpaper (0xb7220988): 0:6)* (Starting com.motorola.ccc.ota (0xb722e288): 0:33)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7249558): 1:52)* (Starting com.test.thalitest (0xb71aa410): 11:22) 
,W/VideoCapabilities( 5007): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5007): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5007): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5007): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5075 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 5007): onServiceConnected
W/Babel   ( 5007): Attempted to change video mute state without an active call.
,W/art     ( 5027): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5027): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5027): CordovaWebView is running on device made by: motorola
,W/art     ( 5027): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5027): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5027): Render dirty regions requested: true
,D/Atlas   ( 5027): Validating map...
,W/chromium( 5027): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  882): Killing 4865:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_4865/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 5027): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5027): Enabling debug mode 0
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5111 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5129 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1249
,I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s249ms
,I/ActivityManager(  882): Killing 4464:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,E/Adreno-ES20( 5027): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5027): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/ResourcesManager( 5111): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/BindingManager( 5027): Cannot call determinedVisibility() - never saw a connection for the pid: 5027
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_4464/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5111): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,D/PhoneMonitor( 5129): Register our PhoneStateListener
,V/SetupWizard( 5129): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 4940:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,D/JsMessageQueue( 5027): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  882): failed to open /acct/uid_10060/pid_4940/cgroup.procs: No such file or directory
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (13:207 vsyncs) (15:928)
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5161 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/GCM     ( 1761): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/jxcore_app_log( 5027): JniHelper::setJavaVM(0xb848b310), pthread_self() = -1199377672
,E/Adreno-ES20( 5027): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5027): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5027): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5027): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5027): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5027): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  882): New client listening to asynchronous messages
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5027): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5027): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5027): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
,W/System.err( 5027): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5027): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5027): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5027): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5027): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5027): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 5027): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9da6bb added. We now have 2 listener(s)
D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5027): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5027): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8f27d8 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5027): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5027): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5027): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5027): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5027): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5027): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5027): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5027): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5027): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5193 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 404us total 20.676ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 364us total 19.981ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.363ms
,I/ActivityManager(  882): Killing 4902:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10063/pid_4902/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5213 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ResourcesManager( 5007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5007): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CalendarProvider2( 5111): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5111): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5235 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 4745:com.motorola.context/u0a8 (adj 15): empty #7
I/ContactLocale( 5213): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/System  ( 5007): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5007): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_4745/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 5075:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/asset   ( 5235): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5235): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5235): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5235): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_5075/cgroup.procs: No such file or directory
,W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 5161): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1951): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1951): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5262 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1951): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1951): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/UpdateIcingCorporaServi( 5161): UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,I/ActivityManager(  882): Killing 5129:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_5129/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 3353:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_3353/cgroup.procs: No such file or directory
,I/art     ( 1761): Explicit concurrent mark sweep GC freed 45126(2MB) AllocSpace objects, 34(544KB) LOS objects, 39% free, 13MB/22MB, paused 1.276ms total 106.467ms
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5291 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5111:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_5111/cgroup.procs: No such file or directory
,D/Finsky  ( 5291): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Finsky  ( 5291): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5291): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5291): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5291): Skipping gmscore version check
,D/Finsky  ( 5291): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5291): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  882): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=5333 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5193:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_5193/cgroup.procs: No such file or directory
,D/Finsky  ( 5291): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/SQLiteLog( 5333): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,D/Finsky  ( 5291): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5357 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AnalyticsLogBase( 5333): PlayLogger.onLoggerConnected
,I/art     (  882): Explicit concurrent mark sweep GC freed 13086(653KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.507ms total 120.050ms
,W/ResourcesManager( 5357): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Killing 5235:com.motorola.MotGallery2/u0a27 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_5235/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5357): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5377 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5161:com.google.android.googlequicksearchbox:search/u0a39 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5161/cgroup.procs: No such file or directory
,I/Icing   ( 1951): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5400 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 5400): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5400): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5400): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5400): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Icing   ( 1951): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5421 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5262:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_5262/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 1951): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/PkgBroadcastIntentOp( 1951): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1951): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/AsyncTaskServiceImpl( 1951): Submit a task: k
,D/k       ( 1951): Processing package: com.test.thalitest
,D/GassUtils( 1951): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1951): Found info for package com.test.thalitest in db.
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5465 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 5421): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,W/BaseAppContext( 1951): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1951): cleanUpNonGplusAccounts done.
,I/CalendarProvider2( 5357): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5357): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  882): Killing 5291:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_5291/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 5421): UpdateCorporaTask done [took 496 ms] updated apps [took 496 ms] 
,I/ActivityManager(  882): Killing 5333:com.google.android.calendar/u0a49 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_5333/cgroup.procs: No such file or directory
,I/GAv4    ( 5465): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5465):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5465):   adb logcat -s GAv4
,W/GAv4    ( 5465): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5465): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5465): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5465): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5465): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 1951): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5506 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5213:android.process.acore/u0a7 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 20.966ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 396us total 19.167ms
I/Icing   ( 1951): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.366ms
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5213/cgroup.procs: No such file or directory
,W/ResourcesManager( 5506): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5465): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5465): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5465): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=5531 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Icing   ( 1951): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5553 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): send {18d98cc2, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/ContactLocale( 5531): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 5357:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/chromium( 5027): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 5027): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_5357/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 5377:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_5377/cgroup.procs: No such file or directory
,I/Icing   ( 1951): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,D/Finsky  ( 5553): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5553): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5553): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5553): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5553): Skipping gmscore version check
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5601 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Finsky  ( 5553): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5553): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5553): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 5601): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Finsky  ( 5553): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5553): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 5400:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_5400/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5623 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5421:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5421/cgroup.procs: No such file or directory
,E/SQLiteLog( 5623): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5643 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5643): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AnalyticsLogBase( 5623): PlayLogger.onLoggerConnected
,I/ActivityManager(  882): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5664 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 5643): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,I/art     (  882): Explicit concurrent mark sweep GC freed 13513(670KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.676ms total 125.344ms
,I/Gmail   ( 5664): getAccountsCursor
,D/ActivityThread( 5664): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  882): Killing 5007:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:38000 mC
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_5007/cgroup.procs: No such file or directory
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5692 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  882): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5664): Observing account changes for notifications
,I/Exchange( 5692): EasService.onCreate
,W/GAV2    ( 5664): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 5692): RestartPingTask
,I/Exchange( 5692): RestartPingsTask did not start any pings.
I/Exchange( 5692): PSS stopIfIdle
I/Exchange( 5692): PSS has no active accounts; stopping service.
,I/Gmail   ( 5664): getAccountsCursor
I/Exchange( 5692): onDestroy
,I/ActivityManager(  882): Killing 5465:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_5465/cgroup.procs: No such file or directory
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2738): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2738): time to show notification
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Killing 5506:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_5506/cgroup.procs: No such file or directory
,W/ResourcesManager( 1280): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,E/SQLiteLog( 5664): (283) recovered 43 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/AlarmManager(  882): done {18d98cc2, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [1346ms]
,E/SQLiteLog( 5643): (284) automatic index on view_events(_id)
,E/ActivatableNotificationView( 1280):  oops Width=0 ActualHeight=128
,I/Gmail   ( 5664): notifyAccountChanged
,I/Gmail   ( 5664): getAccountsCursor
,I/Gmail   ( 5664): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5664): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5664): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5664): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5664): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5643): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5643): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  882): Killing 5531:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5531/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  882): send {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  882): send {12f3967e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [5ms]
,V/AlarmManager(  882): done {12f3967e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.35 rxSuccessRate=2.82 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN with age=1457975829871 interval=20000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN try full band scan age=1457975829871 interval=20000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN bump interval =30000
I/wpa_supplicant( 1451): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): [1,457,975,829,875 ms] noteScanstart no scan source
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 16 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 17 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 18 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 19 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  882): [1,457,975,830,638 ms] noteScanEnd no scan source
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,W/SQLiteConnectionPool( 1951): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/AlarmManager(  882): send {1a089c2c, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,D/Finsky  ( 5553): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  882): done {1a089c2c, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [14ms]
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SFPerfTracer(  279):      triggers: (rate: 12:553) (compose: 0:1) (post: 0:1) (render: 0:2) (38:917 frames) (39:1010)
D/SFPerfTracer(  279):        layers: (3:11) (FocusedStackFrame (0xb71c3280): 0:13)* (DimLayer (0xb71a5d38): 0:6)* (StatusBar (0xb7219a70): 39:177) (NavigationBar (0xb721b788): 0:34) (com.android.systemui.ImageWallpaper (0xb7220988): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7249558): 0:53)- (Starting com.test.thalitest (0xb71aa410): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb722e710): 0:59) 
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5553): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5553): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5553): untagSocket(37) failed with errno -22
,D/Finsky  ( 5553): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  882): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5779 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5779): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5779): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MultiDex( 5779): VM with version 2.1.0 has multidex support
,I/MultiDex( 5779): install
I/MultiDex( 5779): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5779): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5779): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5779): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5779): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1761): callingUid 10016, callindPid: 1761
,D/LocationInitializer( 1951): Restart initialization of location
,D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 5779): Reading stored module config
,E/MDM     ( 1761): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
,I/qtaguid ( 5553): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5553): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5553): untagSocket(37) failed with errno -22
,D/CAR.SERVICE( 5779): Connecting to CarCallService...
,D/NativeLibraryUtils( 5779): Install completed successfully. count=14 extracted=0
I/art     ( 5779): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5779): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5779): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5779): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5779): Creating a new PhoneAdapter instance
,W/ActivityManager(  882): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5779): setListener: com.google.android.gms.car.dn@1dd60e23
,W/ActivityManager(  882): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5779): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 5779): Starting CarCallService with initial phone null
,W/ContextImpl( 5623): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 5623): Thread[GAThread,5,main]: No campaign data found.
,D/CAR.SERVICE( 5779): Package validated; name: com.android.vending
,V/Finsky  ( 5553): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/GAV2    ( 5664): Thread[GAThread,5,main]: No campaign data found.
,I/art     (  882): Explicit concurrent mark sweep GC freed 18341(904KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.539ms total 123.800ms
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5553): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5553): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5553): untagSocket(37) failed with errno -22
,W/ActivityManager(  882): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5553): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5553): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5553): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5553): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  882): send {34c54ec, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  882): done {34c54ec, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [18ms]
,D/DeviceConnectionService( 1761): client connected with version: 8296000
,D/Finsky  ( 5553): [644] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5553): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5553): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Killing 5692:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10060/pid_5692/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  882): send {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CAR.SERVICE( 5779): mConnectedToCar = false, abort
,E/ActivityThread( 5779): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2781b4ab that was originally bound here
E/ActivityThread( 5779): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2781b4ab that was originally bound here
E/ActivityThread( 5779): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5779): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5779): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5779): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5779): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5779): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5779): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5779): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5779): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5779): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5779): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5779): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5779): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5779): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5779): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5779): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5779): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5779): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5779): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5779): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5779): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5779): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2305b52 that was originally bound here
E/ActivityThread( 5779): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5779): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5779): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5779): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5779): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5779): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5779): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5779): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5779): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5779): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5779): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5779): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5779): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5779): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5779): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5779): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5779): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5779): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5779): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5779): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5779): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5779): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  882): Unbind failed: could not find connection for android.os.BinderProxy@9b291a2
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:37000 mC
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{3bf06dd4 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:35000 mC
,I/ActivityManager(  882): Killing 5601:com.motorola.context/u0a8 (adj 15): empty #7
,I/ActivityManager(  882): Killing 5664:com.google.android.gm/u0a63 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5601/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10063/pid_5664/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {263945f0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  882): send {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  882): done {263945f0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [9ms]
,E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.13 rxSuccessRate=2.76 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN with age=18709 interval=30000 maxinterval=300000
,E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  882): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1451): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): [1,457,975,848,588 ms] noteScanstart no scan source
,V/AlarmManager(  882): done {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [25ms]
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  882): [1,457,975,848,655 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,D/Finsky  ( 5553): [635] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5553): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=316, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311116, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13521, POWER_SUPPLY_CHARGE_COUNTER=-244, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
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
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  882): send {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,E/ActivityThread( 1951): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  882): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 196154, reason: UserStart
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:34000 mC
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  882): send {10d8b2fa, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  882): send {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  882): done {10d8b2fa, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [13ms]
,V/AlarmManager(  882): done {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [17ms]
,E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.02 rxSuccessRate=0.02 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN with age=40543 interval=30000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN try full band scan age=40543 interval=30000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN bump interval =45000
I/wpa_supplicant( 1451): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): [1,457,975,870,421 ms] noteScanstart no scan source
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1761): Vacuum at: now=1457975870588 tag=VacuumService
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 20 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/TCMD    (  482): NL - Read 56 bytes from update socket.,
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  882): [1,457,975,870,910 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=305, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311534, SEQNUM=4385, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-317, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,E/BackupManagerService(  882): Timeout restoring application @pm@
W/BackupManagerService(  882): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1761): Restore processing aborted, no more packages
,E/BackupManagerService(  882): Failure getting next package name
,E/BackupManagerService(  882): Duplicate finish
,V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1761): onCreate
,V/AlarmManager(  882): send {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  882): done {1b5e47e4, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3ms]
,E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN with age=12847 interval=45000 maxinterval=300000
E/WifiStateMachine(  882): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  882): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1451): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): [1,457,975,883,267 ms] noteScanstart no scan source
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,E/WifiStateMachine(  882): [1,457,975,883,336 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ConfigService( 1761): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1280): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1280): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,I/SBar.MotoNetworkCtrlr( 1280): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1280): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  882): Nap time (uid 1000)...
,I/PowerManagerService(  882): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  882): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  882): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  882): Build Date: 10/28/14 Tue
I/Adreno-EGL(  882): Local Branch: 
I/Adreno-EGL(  882): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  882): Local Patches: NONE
I/Adreno-EGL(  882): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/AlarmManager(  882): send {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  882): done {15acd16d, *walarm*:android.content.syncmanager.SYNC_ALARM} [13ms]
,D/        (  882): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  882): BstSensorExt: id=1598182242, en=0
D/        (  882): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,D/        (  882): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  882): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb710d550
,V/ActivityManager(  882): Display changed displayId=0
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7401820
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220536184)
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220536184) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7401820
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  279): enable_dcabc: Done setting OFF mode
,D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl(  882): Excessive delay in setPowerMode(): 325ms
,I/PowerManagerService(  882): Sleeping (uid 1000)...
,I/WindowManager(  882): AOD feature not enabled!
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/JX-Cordova( 5027): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d27f731 added. We now have 3 listener(s)
,I/LaunchCheckinHandler(  882): cleanup(): cleared. Last call was 64633 ms ago
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5027): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5027): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@283b5e16 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5027): addListener: New listener added - the number of listeners is now 1
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5027): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5027): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5027): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5027): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5027): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5027): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5027): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
,W/System.err( 5027): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5027): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5027): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5027): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/WifiStateMachine(  882): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  882): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  882): do suspend false
,I/Keyboard.Facilitator( 1413): onFinishInput()
,D/        (  882): activate, handle: 1598182229, enabled: 0, index 0
E/        (  882): <BST> disable accel, orig state: 1
I/        (  882): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  882): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  882): handleScreenStateChanged Exit: false
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  882): do suspend true
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  882): send {1b921e38, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  882): done {1b921e38, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [8ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
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
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311370, SEQNUM=4393, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-406, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
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
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
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
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=292, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311036, SEQNUM=4395, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-420, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,V/AlarmManager(  882): send {19bc1e11, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  882): done {19bc1e11, *walarm*:com.google.android.intent.action.SEND_IDLE} [7ms]
,I/PhenotypeConfigurator( 1761): Scheduling Phenotype for one-off execution 11389 seconds from now (1457975927610)
,I/PhenotypeFlagCommitter( 1761): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1761): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/art     ( 1761): Background sticky concurrent mark sweep GC freed 109309(5MB) AllocSpace objects, 13(231KB) LOS objects, 27% free, 16MB/22MB, paused 7.269ms total 86.895ms
,E/DataBuffer( 1761): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3bf4b1c7)
,E/DataBuffer( 1761): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c4483f4)
E/DataBuffer( 1761): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c18b71d)
,E/DataBuffer( 1761): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bbefd92)
E/DataBuffer( 1761): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2280a363)
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/global frequency( 2738): no tags to log
,D/Checkin ( 2738): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2738): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  882): Explicit concurrent mark sweep GC freed 57331(2MB) AllocSpace objects, 3(328KB) LOS objects, 33% free, 20MB/31MB, paused 1.596ms total 132.936ms
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 56592(3MB) AllocSpace objects, 35(1231KB) LOS objects, 40% free, 7MB/12MB, paused 1.010ms total 49.808ms
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2738): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 2738): Explicit concurrent mark sweep GC freed 13101(707KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 1.191ms total 63.728ms
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2738): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2738): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2738): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2738): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2738): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2738): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2738): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2738): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2738): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2738): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1761): disconnect managed GoogleApiClient
,V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {3d48a0bd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  882): done {3d48a0bd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [14ms]
,V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1761): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1761): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310954, SEQNUM=4404, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-492, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 8
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 2
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311150, SEQNUM=4407, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-749, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [35ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {12f3967e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {12f3967e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  882): send {1148fba3, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {2a638bb9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=5971 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  882): done {1148fba3, *alarm*:android.intent.action.TIME_TICK} [98ms]
,I/GAv4    ( 5971): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5971):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5971):   adb logcat -s GAv4
,W/GAv4    ( 5971): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5971): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5971): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  882): done {2a638bb9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [281ms]
,I/ActivityManager(  882): Killing 5643:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_5643/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310440, SEQNUM=4410, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-2202, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2637): Disconnected process message: 10, size: 0
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 6004): 
D/AndroidRuntime( 6004): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6004): CheckJNI is OFF
D/AndroidRuntime( 6004): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  882): Killing 5027:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
D/WifiService(  882): Client connection lost with reason: 4
I/WindowState(  882): WIN DEATH: Window{37a506f9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (23:301 vsyncs) (25:1044)
W/PackageSettings(  882): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
I/ActivityManager(  882):   Force finishing activity ActivityRecord{3a45e3fb u0 com.test.thalitest/.MainActivity t9}
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  882): Spurious death for ProcessRecord{2b0b0bfe 5027:com.test.thalitest/u0a109}, curProc for 5027: null
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
I/ActivityManager(  882):   Force finishing activity ActivityRecord{3a45e3fb u0 com.test.thalitest/.MainActivity t9 f}
W/ActivityManager(  882): Duplicate finish request for ActivityRecord{3a45e3fb u0 com.test.thalitest/.MainActivity t9 f}
I/art     ( 3261): Explicit concurrent mark sweep GC freed 9862(2MB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 721us total 34.872ms
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
W/GeofencerStateMachine( 1761): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1558): Explicit concurrent mark sweep GC freed 2313(126KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 506us total 63.043ms
I/Decoder ( 1413): createOrResetDecoder
I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6033 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1951): Explicit concurrent mark sweep GC freed 2979(174KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/19MB, paused 940us total 121.152ms
I/ConfigService( 1761): onCreate
D/OtaApp  ( 2738): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2738): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2738): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2738): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2738): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  882): Explicit concurrent mark sweep GC freed 21470(1640KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 20MB/31MB, paused 9.731ms total 168.355ms
I/art     (  882): WaitForGcToComplete blocked for 96.582ms for cause Explicit
W/InputMethodManagerService(  882): Got RemoteException sending setActive(false) notification to pid 5027 uid 10109
I/Keyboard.Facilitator( 1413): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Time to Run
I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Time to Run
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task.xml
D/VoicemailCleanupService( 6033): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 6033): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6059 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 360us total 20.552ms
I/art     (  882): Explicit concurrent mark sweep GC freed 3896(212KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.852ms total 187.800ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 19.292ms
I/ActivityManager(  882): Killing 5623:com.google.android.calendar/u0a49 (adj 15): empty #7
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.325ms
D/AndroidRuntime( 6004): Shutting down VM
W/asset   ( 6059): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6059): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6059): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6059): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  882): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6079 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_5623/cgroup.procs: No such file or directory
I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6099 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  882): Killing 5779:com.google.android.gms:car/u0a16 (adj 15): empty #7
W/ContextImpl( 6099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_5779/cgroup.procs: No such file or directory
I/ActivityManager(  882): Killing 5553:com.android.vending/u0a32 (adj 15): empty #7
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6121 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_5553/cgroup.procs: No such file or directory
I/ActivityManager(  882): Killing 1951:com.google.android.gms/u0a16 (adj 15): empty #7
D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3edcc640)
D/WifiService(  882): Client connection lost with reason: 4
D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_1951/cgroup.procs: No such file or directory
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
