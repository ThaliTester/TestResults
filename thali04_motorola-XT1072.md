#### Test 62509094cfda267_thali04_motorola-XT1072 Logs


```
--------- beginning of system
W/ActivityManager(  884): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
--------- beginning of main
W/GAV2    ( 4730): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Gmail   ( 4730): Observing account changes for notifications
I/Exchange( 4752): EasService.onCreate
I/Exchange( 4752): RestartPingTask
I/MMApiWSBase( 2571): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2571): publish the event [tag = MOT_CCE event name = LOG]
I/Exchange( 4752): RestartPingsTask did not start any pings.
I/Exchange( 4752): PSS stopIfIdle
I/Exchange( 4752): PSS has no active accounts; stopping service.
I/Exchange( 4752): onDestroy
I/Gmail   ( 4730): getAccountsCursor
I/ActivityManager(  884): Killing 4607:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_4607/cgroup.procs: No such file or directory
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/AlarmManager(  884): done {3019375d, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9353ms]
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ActivityManager(  884): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4798 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  884): Killing 4575:com.google.android.apps.plus/u0a90 (adj 15): empty #7
E/SQLiteLog( 4730): (283) recovered 127 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_4575/cgroup.procs: No such file or directory
W/ResourcesManager( 4798): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Gmail   ( 4730): getAccountsCursor
I/Gmail   ( 4730): notifyAccountChanged
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4730): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4730): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4730): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/CalendarProvider2( 4798): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
V/AlarmManager(  884): done {39875593, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [9112ms]
D/3CDM.DeviceAdminPushReceiver( 2571): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2571): Type: null
D/3CDM.DeviceAdminPushReceiver( 2571): Data: null
D/3CDM.Service( 2571): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2571): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2571): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2571): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2571): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2571): blur.service.cred.locationToken = null
D/3CDM.Service( 2571): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2571): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2571): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2571): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
I/CE-UpdateModelService( 4639): ACTION_REGISTRATION_COMPLETE
D/3CDM.Service( 2571): Sync to CCE settings done, instantiate Locate now.
E/SQLiteLog( 4798): (284) automatic index on view_events(_id)
I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4828 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
D/BSUtils ( 2571): set .setup.DeviceAdminSetupReceiver enabled
I/Gmail   ( 4730): getAccountsCursor
V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 4796): 
D/AndroidRuntime( 4796): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/PhoneMonitor( 4828): Register our PhoneStateListener
D/AndroidRuntime( 4796): CheckJNI is OFF
V/SetupWizard( 4828): Connected to Gservices successfully
I/ActivityManager(  884): Killing 4661:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
I/art     (  884): Explicit concurrent mark sweep GC freed 9381(443KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.786ms total 119.335ms
W/libprocessgroup(  884): failed to open /acct/uid_10096/pid_4661/cgroup.procs: No such file or directory
V/AlarmManager(  884): done {58904e4, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [7783ms]
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=37.20 rxSuccessRate=31.73 targetRoamBSSID=any RSSI=-43
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN with age=15511 interval=30000 maxinterval=300000
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  884): WifiStateMachine CMD_START_SCAN full=false
V/AlarmManager(  884): done {1f31854e, *alarm*:com.android.server.WifiManager.action.START_SCAN} [7569ms]
E/WifiStateMachine(  884): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1443): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  884): [1,457,945,539,897 ms] noteScanstart no scan source
D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1714): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  884): [1,457,945,539,926 ms] noteScanEnd no scan source
E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@22d37767 sup_state=COMPLETED debouncing=false
I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4859 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4796): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/Checkin ( 3021): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (190 us)
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4796): Shutting down VM
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4878 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2571): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2571): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2571): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2571): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2571): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2571): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2571): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2571): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2571): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2571): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
W/ResourcesManager( 4859): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  884): Activity reported stop, but no longer stopping: ActivityRecord{342fa6c9 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
,I/WebViewFactory( 4878): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Babel_SMS( 4859): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4859): MmsConfig.loadMmsSettings
I/Babel_SMS( 4859): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 4859): MmsConfig.loadFromDatabase
,I/LibraryLoader( 4878): Time to load native libraries: 3 ms (timestamps 8482-8485)
I/LibraryLoader( 4878): Expected native library version number "",actual native library version number ""
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/Babel_SMS( 4859): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4859): MmsConfig.loadFromResources
,E/Babel_SMS( 4859): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4859): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/WebViewChromiumFactoryProvider( 4878): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 4878): Expected native library version number "",actual native library version number ""
I/chromium( 4878): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4878): Initializing chromium process, singleProcess=true
W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4878): ApplicationContext is null in ApplicationStatus
,W/chromium( 4878): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4878): Local Branch: 
I/Adreno-EGL( 4878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4878): Local Patches: NONE
I/Adreno-EGL( 4878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/Settings( 4859): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4859): startup - clean
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3de671e0:true
,I/Babel   ( 4859): deleted: false for 0
,I/CalendarProvider2( 4798): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4798): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/MMApiWSBase( 2571): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2571): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2571): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2571): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2571): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4935 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
,D/CheckinProvider(  884): 56 events delete 0 left
,W/AwContents( 4878): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4878): CordovaWebView is running on device made by: motorola
,W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
,W/VideoCapabilities( 4859): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4859): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 4859): Unsupported mime video/mpeg2
,I/global frequency( 2571): BcsDSCheckin.events found events 0
,D/Checkin ( 2571): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 2571): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2571): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2571): BcsTimer.onReceive checkin completed (1520966159:ERROR_OK)
,D/Checkin ( 2571): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/VideoCapabilities( 4859): Unsupported profile 4 for video/mp4v-es
,D/OpenGLRenderer( 4878): Render dirty regions requested: true
,W/VideoCapabilities( 4859): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4859): Unrecognized profile 2130706433 for video/avc
D/Atlas   ( 4878): Validating map...
,W/VideoCapabilities( 4859): Unrecognized profile 2130706433 for video/avc
,W/chromium( 4878): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  884): Killing 4683:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/VideoCapabilities( 4859): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Killing 4752:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10055/pid_4683/cgroup.procs: No such file or directory
,I/vclib   ( 4859): onServiceConnected
W/Babel   ( 4859): Attempted to change video mute state without an active call.
,I/OpenGLRenderer( 4878): Initialized EGL, version 1.4
W/libprocessgroup(  884): failed to open /acct/uid_10060/pid_4752/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 4878): Enabling debug mode 0
,W/DataUsage( 2571): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2571): publish the event [tag = MOT_CCE event name = LOG]
,I/Keyboard.Facilitator( 1422): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1183
I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s183ms
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4963 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/Adreno-ES20( 4878): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4878): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  884): Killing 4730:com.google.android.gm/u0a63 (adj 15): empty #7
,W/BindingManager( 4878): Cannot call determinedVisibility() - never saw a connection for the pid: 4878
,W/libprocessgroup(  884): failed to open /acct/uid_10063/pid_4730/cgroup.procs: No such file or directory
,I/SFPerfTracer(  278):      triggers: (rate: 14:470) (compose: 0:1) (post: 0:1) (render: 0:2) (0:933 frames) (1:1011)
D/SFPerfTracer(  278):        layers: (3:13) (FocusedStackFrame (0xb7ea7770): 0:15)* (DimLayer (0xb7ec02a0): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7ec2fc0): 0:37)- (StatusBar (0xb7f13028): 0:113) (NavigationBar (0xb7f15418): 0:32) (com.android.systemui.ImageWallpaper (0xb7ef9958): 0:7)* (Starting com.motorola.ccc.ota (0xb7ecf5d0): 0:38)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7efe8a8): 0:48)- (Starting com.test.thalitest (0xb7ec2fc0): 1:39)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7ecf5d0): 1:8) 
,D/JsMessageQueue( 4878): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4994 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (11:239 vsyncs) (13:1031)
,I/ActivityManager(  884): Killing 4798:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_4798/cgroup.procs: No such file or directory
,E/Adreno-ES20( 4878): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4878): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5019 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/jxcore_app_log( 4878): JniHelper::setJavaVM(0xb7ea3310), pthread_self() = -1205407496
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878): setBluetoothMacAddress: 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4878): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4878): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4878): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4878): setHandshakeRequired: true -> false
,W/ResourcesManager( 4859): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4859): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4878): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  884): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4878): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4878): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4878): Constructor: Bluetooth LE discovery mode is not supported
,V/JNIHelp ( 4859): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5046 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4639:com.motorola.context/u0a8 (adj 15): empty #7
,W/System  ( 4859): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4859): Installed default security provider GmsCore_OpenSSL
,I/ContactLocale( 5019): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/chromium( 4878): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_4639/cgroup.procs: No such file or directory
,W/asset   ( 5046): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5046): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5046): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5046): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/UpdateIcingCorporaServi( 4963): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5071 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/PkgBroadcastIntentOp( 1952): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 1952): Null package name or gms related package.  Ignoreing.
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.307ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.842ms
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 347us total 23.232ms
,D/WearableController( 1952): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1952): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5071): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4963): UpdateCorporaTask done [took 337 ms] updated apps [took 337 ms] 
I/ActivityManager(  884): Killing 4828:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 46238(2MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 13MB/22MB, paused 1.191ms total 120.069ms
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_4828/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5100 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 4935:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_4935/cgroup.procs: No such file or directory
,D/Finsky  ( 5100): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/Finsky  ( 5100): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5100): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5100): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  884): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5145 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/jxcore-log( 4878): Initializing JXcore engine
W/jxcore-log( 4878): JXcore engine is ready
,I/art     (  884): Explicit concurrent mark sweep GC freed 14659(732KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 2.117ms total 152.725ms
,W/ResourcesManager( 5145): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Ads     ( 5100): Skipping gmscore version check
D/Finsky  ( 5100): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5100): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  884): Killing 4994:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/Thread-544( 5043): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[6622]" dev="sockfs" ino=6622 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-544( 5043): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-544( 5043): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9728]" dev="sockfs" ino=9728 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-544( 5043): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22687]" dev="sockfs" ino=22687 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4878): Starting JXcore engine
,I/Icing   ( 1952): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_4994/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5145): Created com.android.providers.calendar.CalendarAlarmManager@21c9faf4(com.android.providers.calendar.CalendarProvider2@3a2e621d)
,D/Finsky  ( 5100): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5167 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,W/jxcore-log( 4878): Platform android
W/jxcore-log( 4878): 
W/jxcore-log( 4878): Process ARCH arm
W/jxcore-log( 4878): 
,D/Finsky  ( 5100): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Icing   ( 1952): Loaded CLD2 Version V2.0 - 20141016
,I/UpdateIcingCorporaServi( 4963): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/PkgBroadcastIntentOp( 1952): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/Icing   ( 1952): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/WearableController( 1952): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/art     ( 1952): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/AsyncTaskServiceImpl( 1952): Submit a task: k
,D/k       ( 1952): Processing package: com.test.thalitest
,D/GassUtils( 1952): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1952): Found info for package com.test.thalitest in db.
,I/UpdateIcingCorporaServi( 4963): UpdateCorporaTask done [took 382 ms] updated apps [took 382 ms] 
,I/art     ( 2813): Explicit concurrent mark sweep GC freed 3142(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 401us total 31.973ms
,I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5204 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5071:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_5071/cgroup.procs: No such file or directory
,W/BaseAppContext( 1952): Using Auth Proxy for data requests.
,W/BaseAppContext( 1952): Using Auth Proxy for data requests.
,W/BaseAppContext( 1952): Using Auth Proxy for data requests.
,W/BaseAppContext( 1952): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 1952): cleanUpNonGplusAccounts done.
,I/jxcore-log( 4878): JXcore Cordova bridge is ready!
I/jxcore-log( 4878): 
W/jxcore-log( 4878): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4878): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4878): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 4878): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4878): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,W/BaseAppContext( 1952): Using Auth Proxy for data requests.
,I/chromium( 4878): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
I/chromium( 4878): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,W/PluginManager( 4878): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().,
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2571): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2571): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2571): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2571): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2571): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2571): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2571): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2571): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1422): onFinishInput()
W/IInputConnectionWrapper( 4878): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  884): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,6403
I/LaunchCheckinHandler(  884): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5052 (total)
,I/CalendarProvider2( 5145): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5145): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  884): Killing 5019:android.process.acore/u0a7 (adj 15): empty #7
,D/AndroidRuntime( 5223): 
D/AndroidRuntime( 5223): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5223): CheckJNI is OFF
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_5019/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AndroidRuntime( 5223): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  884): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 4878:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,D/WifiService(  884): Client connection lost with reason: 4
,I/Icing   ( 1952): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,W/PackageSettings(  884): Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
,I/WindowState(  884): WIN DEATH: Window{1853622f u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,W/ActivityManager(  884): Spurious death for ProcessRecord{19bd392c 4878:com.test.thalitest/u0a109}, curProc for 4878: null
,I/ActivityManager(  884): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,I/Keyboard.Facilitator( 1422): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1714): Ignoring removeGeofence because network location is disabled.
,V/AlarmManager(  884): send {3cb5018a, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,I/art     ( 3021): Explicit concurrent mark sweep GC freed 11043(1666KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 7MB/12MB, paused 983us total 51.455ms
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1422): run()
,I/Decoder ( 1422): createOrResetDecoder
,I/ConfigService( 1714): onCreate
,I/art     ( 1575): Explicit concurrent mark sweep GC freed 2220(119KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 4.113ms total 139.743ms
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1422): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/GAv4    ( 5204): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5204):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5204):   adb logcat -s GAv4
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = history
,I/Icing   ( 1952): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Loading LM = user
,D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister(  884): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Icing   ( 1952): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,W/GAv4    ( 5204): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1422): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1422): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1422): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1422): run()
I/StatsUtilsManager( 1422): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1422): shouldRecordStats() = Too Soon
,I/Launcher( 1575): Deferring update until onResume
,I/Icing   ( 1952): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,W/GAv4    ( 5204): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5204): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5204): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/art     (  884): Explicit concurrent mark sweep GC freed 25829(1769KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 2.447ms total 369.784ms
,E/GameAgent( 1952): Caller attempted to insert game data for non-existent package.
E/GameAgent( 1952): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
E/GameAgent( 1952): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
E/GameAgent( 1952): 	at com.google.android.gms.games.broker.GameAgent.registerGame(GameAgent.java:1573)
E/GameAgent( 1952): 	at com.google.android.gms.games.broker.DataBroker.registerGame(DataBroker.java:3309)
E/GameAgent( 1952): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
E/GameAgent( 1952): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/GameAgent( 1952): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
E/GameAgent( 1952): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/GameAgent( 1952): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/GameAgent( 1952): 	at java.lang.Thread.run(Thread.java:818)
D/AndroidRuntime( 5223): Shutting down VM
,I/ActivityManager(  884): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5255 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 5100:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_5100/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5204): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5277 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 5145:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10005/pid_5145/cgroup.procs: No such file or directory
,W/ResourcesManager( 5277): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5204): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5204): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5204): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SharedPreferencesImpl( 5204): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
