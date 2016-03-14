#### Test 62509094c3227b2_thali04_motorola-XT1072 Logs


```
--------- beginning of system
I/ActivityManager(  896): Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=5354 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
--------- beginning of main
V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  896): Killing 5162:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/ResourcesManager( 5354): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
E/SQLiteLog( 5282): (283) recovered 105 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup(  896): failed to open /acct/uid_10090/pid_5162/cgroup.procs: No such file or directory
D/3CDM.DeviceAdminPushReceiver( 2899): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2899): Type: null
D/3CDM.DeviceAdminPushReceiver( 2899): Data: null
D/3CDM.Service( 2899): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,D/3CDM.Service( 2899): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
I/CE-UpdateModelService( 5354): ACTION_REGISTRATION_COMPLETE
D/3CDM.Service( 2899): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2899): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2899): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2899): blur.service.cred.locationToken = null
D/3CDM.Service( 2899): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2899): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2899): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2899): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
D/3CDM.Service( 2899): Sync to CCE settings done, instantiate Locate now.
I/ActivityManager(  896): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5377 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  896): Killing 4053:com.android.defcontainer/u0a10 (adj 15): empty #7
D/BSUtils ( 2899): set .setup.DeviceAdminSetupReceiver enabled
I/Gmail   ( 5282): notifyAccountChanged
I/Gmail   ( 5282): getAccountsCursor
I/Gmail   ( 5282): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5282): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5282): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5282): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  896): failed to open /acct/uid_10010/pid_4053/cgroup.procs: No such file or directory
V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5282): getAccountsCursor
V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 5377): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
I/ActivityManager(  896): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5400 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 5400): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/AndroidRuntime( 5394): 
D/AndroidRuntime( 5394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  896): Killing 5190:com.android.vending/u0a32 (adj 15): empty #7
D/AndroidRuntime( 5394): CheckJNI is OFF
I/AnalyticsLogBase( 5377): PlayLogger.onLoggerConnected
W/libprocessgroup(  896): failed to open /acct/uid_10032/pid_5190/cgroup.procs: No such file or directory
I/CalendarProvider2( 5400): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
V/AlarmManager(  896): done {1b53cdcd, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [16842ms]
E/SQLiteLog( 5400): (284) automatic index on view_events(_id)
E/MDM     ( 1803): [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1970): Restart initialization of location
D/AuthorizationBluetoothService( 1803): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1803): No location to return for getLastLocation()
W/FusedLocationProvider( 1803): location=null
D/Checkin ( 3305): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/AndroidRuntime( 5394): Calling main entry com.android.commands.am.Am
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  279): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (208 us)
D/AndroidRuntime( 5394): Shutting down VM
W/ContextImpl( 1491): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5448 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/WifiStateMachine(  896): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=21.31 rxSuccessRate=16.41 targetRoamBSSID=any RSSI=-43
E/WifiStateMachine(  896): WifiStateMachine CMD_START_SCAN with age=1457934260480 interval=20000 maxinterval=300000
E/WifiStateMachine(  896): WifiStateMachine CMD_START_SCAN try full band scan age=1457934260480 interval=20000 maxinterval=300000
E/WifiStateMachine(  896): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  896): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  896): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1450): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
V/AlarmManager(  896): done {11ca965c, *alarm*:com.android.server.WifiManager.action.START_SCAN} [15996ms]
E/WifiStateMachine(  896): [1,457,934,260,486 ms] noteScanstart no scan source
I/art     (  313): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 407us total 24.261ms
V/AlarmManager(  896): done {268ca98f, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [11883ms]
V/AlarmManager(  896): done {1b419d73, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [11528ms]
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.451ms
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.654ms
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
E/WifiStateMachine(  896): [1,457,934,260,551 ms] noteScanEnd no scan source
E/WifiStateMachine(  896): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@6528592 sup_state=COMPLETED debouncing=false
I/ActivityManager(  896): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=5465 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1491): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5448): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5448): Time to load native libraries: 6 ms (timestamps 2489-2495)
I/LibraryLoader( 5448): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5448): Binding Chromium to main looper Looper (main, tid 1) {2b819bbe}
I/LibraryLoader( 5448): Expected native library version number "",actual native library version number ""
I/chromium( 5448): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5448): Initializing chromium process, singleProcess=true
W/art     ( 5448): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5448): ApplicationContext is null in ApplicationStatus
,W/chromium( 5448): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5448): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5448): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5448): Local Branch: 
I/Adreno-EGL( 5448): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5448): Local Patches: NONE
I/Adreno-EGL( 5448): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  896): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5493 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  896): send {189240e9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,D/BluetoothManagerService(  896): Message: 20
D/BluetoothManagerService(  896): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ea82421:true
,I/CalendarProvider2( 5400): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5400): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  896): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5534 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,W/art     ( 5448): Attempt to remove local handle scope entry from IRT, ignoring
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/AwContents( 5448): onDetachedFromWindow called when already detached. Ignoring
,I/art     (  896): Explicit concurrent mark sweep GC freed 19671(979KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.621ms total 198.496ms
,D/SystemWebViewEngine( 5448): CordovaWebView is running on device made by: motorola
,W/art     ( 5448): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5448): Attempt to remove local handle scope entry from IRT, ignoring
,E/UpdateRequestReceiver( 5534): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/OpenGLRenderer( 5448): Render dirty regions requested: true
,E/UpdateRequestReceiver( 5534): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5534): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5534): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/Atlas   ( 5448): Validating map...
,I/ActivityManager(  896): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=5568 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 5239:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10080/pid_5239/cgroup.procs: No such file or directory
W/chromium( 5448): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5448): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5448): Enabling debug mode 0
,I/Keyboard.Facilitator( 1433): onFinishInput()
,I/LaunchCheckinHandler(  896): Displayed com.test.thalitest/.MainActivity,cp,ca,1198
I/ActivityManager(  896): Displayed com.test.thalitest/.MainActivity: +1s198ms
,E/Adreno-ES20( 5448): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5448): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5448): Cannot call determinedVisibility() - never saw a connection for the pid: 5448
,I/ActivityManager(  896): Killing 5317:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10060/pid_5317/cgroup.procs: No such file or directory
,I/ActivityManager(  896): Killing 5282:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10063/pid_5282/cgroup.procs: No such file or directory
,D/GmsModuleFndr( 1970): Beginning GMS chimera module scan
,I/GservicesUpdateTask( 5568): Updating Gservices keys
,D/GmsModuleFndr( 1970): Module pkg com.google.android.apps.kids.familylink not installed, skipping
D/GmsModuleFndr( 1970): Module pkg com.google.android.projection.gearhead not installed, skipping
,D/ChimeraCfgMgr( 1970): Beginning module configuration check
,I/SystemUpdateService( 1970): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 1970): Checking schedule, now: 1457934262123 next: 1458535391002
,I/CheckinService( 1970): active receiver: disabled
,D/SystemUpdateService( 1970): onCreate
,D/SystemUpdateService( 1970): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 4173(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 971us total 54.655ms
,D/ChimeraCfgMgr( 1970): Module APKs unchanged, check complete
,I/SystemUpdateService( 1970): cancelUpdate (empty URL)
I/SystemUpdateService( 1970): active receiver: disabled
,E/Adreno-ES20( 5448): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5448): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  896): Killing 5027:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10070/pid_5027/cgroup.procs: No such file or directory
,I/art     ( 1970): Explicit concurrent mark sweep GC freed 36498(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/21MB, paused 1.386ms total 74.367ms
,D/JsMessageQueue( 5448): Set native->JS mode to OnlineEventsBridgeMode
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (36:198 vsyncs) (38:940)
,I/SFPerfTracer(  279):      triggers: (rate: 11:534) (compose: 0:1) (post: 0:1) (render: 0:2) (24:854 frames) (25:940)
D/SFPerfTracer(  279):        layers: (3:13) (FocusedStackFrame (0xb8d0d338): 0:14)* (DimLayer (0xb8da06c0): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb8da3698): 0:38)- (StatusBar (0xb8dbc2a0): 0:113) (NavigationBar (0xb8dbd968): 0:36) (com.android.systemui.ImageWallpaper (0xb8dc5e40): 0:5)* (Starting com.motorola.ccc.ota (0xb8dc7ab0): 0:31)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8dca1a8): 0:51)- (Starting com.test.thalitest (0xb8da3698): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8dc8490): 25:36) 
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 2812(110KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 722us total 24.288ms
,D/jxcore_app_log( 5448): JniHelper::setJavaVM(0xb78c3310), pthread_self() = -1211710824
,I/ActivityManager(  896): Killing 5465:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33de12a added. We now have 1 listener(s)
,D/BluetoothManagerService(  896): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/libprocessgroup(  896): failed to open /acct/uid_10088/pid_5465/cgroup.procs: No such file or directory
D/SystemUpdateService( 1970): onDestroy
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5448): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5448): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5448): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5448): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a13291 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5448): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  896): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5448): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5448): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 5448): Constructor: Bluetooth LE discovery mode is not supported
,W/DynamiteLoaderImpl( 1970): Failed to load module version: module com.google.android.gms.flags not found
,I/DynamiteModule( 1970): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1970): Selected local version of com.google.android.gms.flags
,I/chromium( 5448): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SystemEventReceiver( 1970): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1970): Updating ocr activity enabled=false
,I/ActivityManager(  896): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5633 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  896): send {1ccdf271, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
V/AlarmManager(  896): send {11ca965c, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  896): done {1ccdf271, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [37ms]
,W/ActivityManager(  896): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1970): Updating downloaded model state (gservices changed)
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 2877(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 517us total 29.008ms
,D/Finsky  ( 5633): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 1970): Explicit concurrent mark sweep GC freed 10756(629KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 13MB/21MB, paused 2.166ms total 148.236ms
,D/Finsky  ( 5633): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/SQLiteConnectionPool( 1970): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/Settings( 5633): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5633): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 1803): Explicit concurrent mark sweep GC freed 17368(945KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 13MB/22MB, paused 1.238ms total 101.133ms
,D/GCM     ( 1803): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/Finsky  ( 5633): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Ads     ( 5633): Skipping gmscore version check
D/Finsky  ( 5633): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5633): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5633): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5633): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1803): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  896): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=5684 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1803): DispatchingService.onCreate()
,W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1803): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1770): Explicit concurrent mark sweep GC freed 2588(103KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 713us total 34.277ms
,D/TaskPersister(  896): removeObsoleteFile: deleting file=8_task_thumbnail.png
,E/ctxmgr  ( 1803): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  896): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  896): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  896): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  896): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32a8f67c
I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     ( 5448): Background sticky concurrent mark sweep GC freed 6018(684KB) AllocSpace objects, 0(0B) LOS objects, 5% free, 18MB/19MB, paused 6.868ms total 39.484ms
,I/GCoreNlp( 1803): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  896): Explicit concurrent mark sweep GC freed 23373(1187KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/31MB, paused 4.352ms total 169.622ms
,I/Launcher( 1583): Deferring update until onResume
,W/ctxmgr  ( 1803): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1803): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/GCoreUlr( 1803): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1803): Unbound from all location providers
I/GCoreUlr( 1803): Place inference reporting - stopped
,I/ActivityManager(  896): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5715 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1803): DispatchingService.onDestroy()
I/GCoreUlr( 1803): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1803): Unbound from all location providers
I/GCoreUlr( 1803): Place inference reporting - stopped
,I/ActivityManager(  896): Killing 5354:com.motorola.context/u0a8 (adj 15): empty #7
,W/jxcore-log( 5448): Initializing JXcore engine
W/jxcore-log( 5448): JXcore engine is ready
,W/libprocessgroup(  896): failed to open /acct/uid_10008/pid_5354/cgroup.procs: No such file or directory
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:36000 mC
,W/Thread-576( 5621): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[6387]" dev="sockfs" ino=6387 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-576( 5621): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-576( 5621): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7448]" dev="sockfs" ino=7448 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-576( 5621): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[24636]" dev="sockfs" ino=24636 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5448): Starting JXcore engine
,D/PhoneMonitor( 5715): Register our PhoneStateListener
,V/SetupWizard( 5715): Connected to Gservices successfully
,I/ActivityManager(  896): Killing 5400:com.android.providers.calendar/u0a5 (adj 15): empty #7
,I/qtaguid ( 5633): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5633): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5633): untagSocket(37) failed with errno -22
,D/Finsky  ( 5633): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ContextImpl( 5377): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,W/jxcore-log( 5448): Platform android
W/jxcore-log( 5448): 
W/jxcore-log( 5448): Process ARCH arm
W/jxcore-log( 5448): 
,W/libprocessgroup(  896): failed to open /acct/uid_10005/pid_5400/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/GAV2    ( 5377): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  896): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5738 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/GCM     ( 1803): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  896): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5755 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 5738): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/ResourcesManager( 5755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5755): VM with version 2.1.0 has multidex support
I/MultiDex( 5755): install
I/MultiDex( 5755): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  896): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5774 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/JNIHelp ( 5755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  896): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5792 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  313): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 20.580ms
,W/ActivityThread( 5755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@367d6b82: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5755): Installed default security provider GmsCore_OpenSSL
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 18.831ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.441ms
,D/ChimeraCfgMgr( 5755): Reading stored module config
,I/ActivityManager(  896): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5814 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ContactLocale( 5774): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  896): Killing 5534:com.google.android.configupdater/u0a54 (adj 15): empty #7
,I/qtaguid ( 5633): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5633): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5633): untagSocket(37) failed with errno -22
W/ResourcesManager( 5792): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/NativeLibraryUtils( 5755): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  896): failed to open /acct/uid_10054/pid_5534/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5792): Created com.android.providers.calendar.CalendarAlarmManager@37a39ec3(com.android.providers.calendar.CalendarProvider2@18dc3340)
,W/asset   ( 5814): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5814): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5814): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5814): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/jxcore-log( 5448): JXcore Cordova bridge is ready!
I/jxcore-log( 5448): 
W/jxcore-log( 5448): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 5448): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 5448): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 5448): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5448): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5448): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 5448): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,W/PluginManager( 5448): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1491): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1491): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2899): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2899): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2899): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2899): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2899): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2899): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2899): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2899): publish the event [tag = MOT_OTA event name = LOG]
,D/CAR.SERVICE( 5755): Connecting to CarCallService...
,I/UpdateIcingCorporaServi( 5568): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator( 1433): onFinishInput()
,W/IInputConnectionWrapper( 5448): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  896): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,11717
I/LaunchCheckinHandler(  896): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5557 (total)
,I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1970): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/PkgBroadcastIntentOp( 1970): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1970): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/CAR.SERVICE( 5755): com.google.android.projection.gearhead isn't installed.
,D/AndroidRuntime( 5840): 
D/AndroidRuntime( 5840): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5840): CheckJNI is OFF
,W/art     ( 5633): Suspending all threads took: 6.642ms
,D/CAR.TEL.Service( 5755): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5755): Creating a new PhoneAdapter instance
,W/ActivityManager(  896): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5755): setListener: com.google.android.gms.car.dn@198367e
,W/ActivityManager(  896): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5755): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5755): Starting CarCallService with initial phone null
,I/ActivityManager(  896): Killing 5684:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10088/pid_5684/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5755): Package validated; name: com.android.vending
,V/AlarmManager(  896): send {2c0b7b21, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/AndroidRuntime( 5840): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  896): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 5448:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,V/Finsky  ( 5633): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/WifiService(  896): Client connection lost with reason: 4
,I/WindowState(  896): WIN DEATH: Window{295b8f93 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/PackageSettings(  896): Skipping PackageSetting{21945851 com.example.hello/10568} due to missing metadata
,E/Icing   ( 1970): Package com.test.thalitest not found
,D/AsyncTaskServiceImpl( 1970): Submit a task: k
,E/libprocessgroup(  896): failed to kill 1 processes for processgroup 5448
,W/ActivityManager(  896): Spurious death for ProcessRecord{1cedab46 5448:com.test.thalitest/u0a109}, curProc for 5448: null
,I/ActivityManager(  896): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1433): resetDictionaries() : en_US
I/CalendarProvider2( 5792): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5792): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Keyboard.Facilitator.DecoderInitializer( 1433): run()
,I/art     ( 3305): Explicit concurrent mark sweep GC freed 9137(1570KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 744us total 47.309ms
,D/k       ( 1970): Processing package: com.test.thalitest
,W/k       ( 1970): Failed to find package com.test.thalitest
,I/Decoder ( 1433): createOrResetDecoder
E/Vision  ( 1970): Failed to find package com.test.thalitest
,I/ActivityManager(  896): Killing 5715:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     ( 1583): Explicit concurrent mark sweep GC freed 2402(127KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 656us total 119.918ms
,D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
,W/libprocessgroup(  896): failed to open /acct/uid_10035/pid_5715/cgroup.procs: No such file or directory
,I/ActivityManager(  896): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5873 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     (  896): Explicit concurrent mark sweep GC freed 25804(1498KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 2.075ms total 195.790ms
,I/ConfigService( 1803): onCreate
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,I/Launcher( 1583): Deferring update until onResume
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
,D/TaskPersister(  896): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  896): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  896): removeObsoleteFile: deleting file=9_task_thumbnail.png
,I/UpdateIcingCorporaServi( 5568): UpdateCorporaTask done [took 1223 ms] updated apps [took 1222 ms] 
,W/BaseAppContext( 1970): Using Auth Proxy for data requests.
I/ActivityManager(  896): Killing 5738:com.motorola.context/u0a8 (adj 15): empty #7
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1433): run()
,D/AndroidRuntime( 5840): Shutting down VM
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1433): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Loading LM = contacts
,W/libprocessgroup(  896): failed to open /acct/uid_10008/pid_5738/cgroup.procs: No such file or directory
,I/ActivityManager(  896): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5895 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Loading LM = user
,I/SBar.MotoNetworkCtrlr( 1305): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1433): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1433): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1433): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1433): run()
I/StatsUtilsManager( 1433): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1433): shouldRecordStats() = Too Soon
,V/GLSActivity( 1803): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleDatabaseHelper( 1970): cleanUpNonGplusAccounts done.
,I/ActivityManager(  896): Killing 5774:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10007/pid_5774/cgroup.procs: No such file or directory
,I/GAv4    ( 5873): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5873):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5873):   adb logcat -s GAv4
,I/qtaguid ( 5633): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5633): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5633): untagSocket(37) failed with errno -22
,W/GAv4    ( 5873): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5873): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 1970): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteDatabase( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:368)
E/SQLiteDatabase( 1970): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:500)
E/SQLiteDatabase( 1970): 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:143)
E/SQLiteDatabase( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:380)
E/SQLiteDatabase( 1970): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 1970): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 1970): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3734)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/SQLiteDatabase( 1970): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/SQLiteDatabase( 1970): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1970): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1970): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 5873): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5873): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteOpenHelper( 1970): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 1970): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1970): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1970): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1970): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
E/SQLiteOpenHelper( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:368)
E/SQLiteOpenHelper( 1970): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteOpenHelper( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:500)
E/SQLiteOpenHelper( 1970): 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:143)
E/SQLiteOpenHelper( 1970): 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:380)
E/SQLiteOpenHelper( 1970): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteOpenHelper( 1970): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 1970): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3734)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/SQLiteOpenHelper( 1970): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/SQLiteOpenHelper( 1970): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1970): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1970): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 5873): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5873): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 5873): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/SBar.MotoNetworkCtrlr( 1305): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Icing   ( 1970): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
I/Icing   ( 1970): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
