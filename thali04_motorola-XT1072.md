#### Test 62560673a3c76e9_thali04_motorola-XT1072 Logs


```
--------- beginning of main
D/WearableService( 1727): callingUid 10016, callindPid: 1727
I/NetworkMonitor( 4778): type=WIFI subType= reason=null isConnected=true
I/MusicLeanback( 4778): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 4778): Stop autocaching.
,--------- beginning of system
I/ActivityManager(  888): Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=4827 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
I/MusicLeanback( 4778): Stop autocaching.
I/MusicLeanback( 4778): Stop autocaching.
I/GHttpClientFactory( 4778): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4778): Using platform SSLCertificateSocketFactory
I/MusicLeanback( 4778): Stop autocaching.
W/ResourcesManager( 4827): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/3CDM.DeviceAdminPushReceiver( 2564): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2564): Type: null
D/3CDM.DeviceAdminPushReceiver( 2564): Data: null
D/3CDM.Service( 2564): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.Service( 2564): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2564): DeviceAdmin - syncWithCCC
D/3CDM.Service( 2564): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2564): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
D/3CDM.Service( 2564): blur.service.cred.locationToken = null
D/3CDM.Service( 2564): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2564): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2564): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2564): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
D/3CDM.Service( 2564): Sync to CCE settings done, instantiate Locate now.
I/CE-UpdateModelService( 4827): ACTION_REGISTRATION_COMPLETE
I/ActivityManager(  888): Killing 4656:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
D/BSUtils ( 2564): set .setup.DeviceAdminSetupReceiver enabled
I/ActivityManager(  888): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4857 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  888): failed to open /acct/uid_10096/pid_4656/cgroup.procs: No such file or directory
D/AndroidRuntime( 4842): 
D/AndroidRuntime( 4842): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4842): CheckJNI is OFF
D/LocationInitializer( 1958): Restart initialization of location
D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1727): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/GmsUtils( 4778): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 4778): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ResourcesManager( 4857): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  888): Killing 4143:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
D/MMApiWSBase( 2564): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2564): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2564): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2564): BcsCore.status() called with error code=ERROR_OK
D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
W/libprocessgroup(  888): failed to open /acct/uid_10016/pid_4143/cgroup.procs: No such file or directory
I/CalendarProvider2( 4857): Created com.android.providers.calendar.CalendarAlarmManager@3d4c09d5(com.android.providers.calendar.CalendarProvider2@341d45ea)
V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1727): No location to return for getLastLocation()
V/AlarmManager(  888): done {1b1cb9ef, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [10511ms]
W/FusedLocationProvider( 1727): location=null
V/AlarmManager(  888): done {9bc2cfc, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10437ms]
E/SQLiteLog( 4857): (284) automatic index on view_events(_id)
V/AlarmManager(  888): done {1eb0375a, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [9706ms]
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=37.45 rxSuccessRate=36.45 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN with age=1457954174422 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN try full band scan age=1457954174422 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  888): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  888): [1,457,954,174,425 ms] noteScanstart no scan source
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
E/WifiStateMachine(  888): [1,457,954,174,457 ms] noteScanEnd no scan source
E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b6920ac sup_state=COMPLETED debouncing=false
I/ActivityManager(  888): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4892 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/AlarmManager(  888): done {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN} [9403ms]
D/AndroidRuntime( 4842): Calling main entry com.android.commands.am.Am
I/ActivityManager(  888): Killing 4687:com.google.android.deskclock/u0a55 (adj 15): empty #7
D/Checkin ( 2983): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
D/CheckinProvider(  888): 60 events delete 1 left
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/global frequency( 2564): BcsDSCheckin.events found events 0
D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/PermissionCache(  281): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4842): Shutting down VM
I/ActivityManager(  888): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4911 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  888): failed to open /acct/uid_10055/pid_4687/cgroup.procs: No such file or directory
E/ActivityThread( 2564): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2564): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2564): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2564): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2564): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2564): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2564): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2564): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2564): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2564): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2564): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2564): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2564): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
I/global frequency( 2564): BcsTimer.onReceive checkin completed (-1038517767:ERROR_OK)
D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
W/ResourcesManager( 4892): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  888): Activity reported stop, but no longer stopping: ActivityRecord{1bd5d893 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
W/DataUsage( 2564): invalid counter update blocked: 'err' by 0
D/Checkin ( 2564): publish the event [tag = MOT_CCE event name = LOG]
,I/WebViewFactory( 4911): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Babel_SMS( 4892): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4892): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4892): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 4892): MmsConfig.loadFromDatabase
,I/LibraryLoader( 4911): Time to load native libraries: 2 ms (timestamps 8097-8099)
,I/LibraryLoader( 4911): Expected native library version number "",actual native library version number ""
,E/Babel_SMS( 4892): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4892): MmsConfig.loadFromResources
,E/Babel_SMS( 4892): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4892): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/WebViewChromiumFactoryProvider( 4911): Binding Chromium to main looper Looper (main, tid 1) {22008778}
,I/LibraryLoader( 4911): Expected native library version number "",actual native library version number ""
I/chromium( 4911): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4911): Initializing chromium process, singleProcess=true
,W/art     ( 4911): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4911): ApplicationContext is null in ApplicationStatus
,W/chromium( 4911): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4911): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4911): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4911): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4911): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4911): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4911): Local Branch: 
I/Adreno-EGL( 4911): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4911): Local Patches: NONE
I/Adreno-EGL( 4911): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/Settings( 4892): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4892): startup - clean
,I/Babel   ( 4892): deleted: false for 0
,D/BluetoothManagerService(  888): Message: 20
D/BluetoothManagerService(  888): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ee98832:true
,W/art     ( 4911): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  888): Explicit concurrent mark sweep GC freed 16592(821KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 4.250ms total 171.511ms
,W/AwContents( 4911): onDetachedFromWindow called when already detached. Ignoring
,W/VideoCapabilities( 4892): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4892): Unsupported mime audio/amr-wb-plus
,D/SystemWebViewEngine( 4911): CordovaWebView is running on device made by: motorola
,I/ActivityManager(  888): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4968 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 4892): Unsupported mime video/mpeg2
,W/art     ( 4911): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4911): Attempt to remove local handle scope entry from IRT, ignoring
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (36:195 vsyncs) (38:941)
,I/VideoCapabilities( 4892): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4892): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4892): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4892): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4892): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4892): onServiceConnected
,W/Babel   ( 4892): Attempted to change video mute state without an active call.
,I/CalendarProvider2( 4857): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4857): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  888): Killing 4740:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,D/OpenGLRenderer( 4911): Render dirty regions requested: true
,D/Atlas   ( 4911): Validating map...
,W/libprocessgroup(  888): failed to open /acct/uid_10060/pid_4740/cgroup.procs: No such file or directory
,W/chromium( 4911): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  888): Killing 4778:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10080/pid_4778/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 4911): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4911): Enabling debug mode 0
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/ActivityManager(  888): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5001 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/LaunchCheckinHandler(  888): Displayed com.test.thalitest/.MainActivity,cp,ca,1205
,I/ActivityManager(  888): Displayed com.test.thalitest/.MainActivity: +1s205ms
,E/Adreno-ES20( 4911): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4911): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/ActivityManager(  888): Killing 4713:com.google.android.gm/u0a63 (adj 15): empty #7
,W/BindingManager( 4911): Cannot call determinedVisibility() - never saw a connection for the pid: 4911
,W/libprocessgroup(  888): failed to open /acct/uid_10063/pid_4713/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SFPerfTracer(  281):      triggers: (rate: 12:536) (compose: 0:1) (post: 0:1) (render: 0:2) (8:878 frames) (9:963)
D/SFPerfTracer(  281):        layers: (4:13) (FocusedStackFrame (0xb7a50f20): 0:15)* (DimLayer (0xb7a62ad0): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7a64ec0): 0:37)- (StatusBar (0xb79ffda8): 0:127) (NavigationBar (0xb7a01710): 0:36) (com.android.systemui.ImageWallpaper (0xb7a03b00): 0:6)* (Starting com.motorola.ccc.ota (0xb7a8d240): 0:33)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7aa3dd0): 0:58)- (Starting com.test.thalitest (0xb7a8d240): 9:38) (com.test.thalitest/com.test.thalitest.MainActivity (0xb7a658a0): 7:12) 
,D/JsMessageQueue( 4911): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  888): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5038 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 5038): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5038): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5038): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 5038): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  888): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=5067 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/Adreno-ES20( 4911): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4911): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/ActivityManager(  888): Killing 4827:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10008/pid_4827/cgroup.procs: No such file or directory
,I/ActivityManager(  888): Killing 3043:com.google.android.calendar/u0a49 (adj 15): empty #7
,D/jxcore_app_log( 4911): JniHelper::setJavaVM(0xb8879310), pthread_self() = -1195271416
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7268384 added. We now have 1 listener(s)
,W/libprocessgroup(  888): failed to open /acct/uid_10049/pid_3043/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  888): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911): setBluetoothMacAddress: 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4911): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4911): setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4911): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4911): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Bluetooth MAC address: 44:80:EB:7B:5A:05
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35481433 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4911): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  888): New client listening to asynchronous messages
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4911): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4911): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
E/io.jxcore.node.ConnectionHelper( 4911): Constructor: Bluetooth LE discovery mode is not supported
,I/chromium( 4911): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  888): Killing 4857:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10005/pid_4857/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 5067): Updating Gservices keys
,D/GmsModuleFndr( 1958): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1958): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/GmsModuleFndr( 1958): Module pkg com.google.android.projection.gearhead not installed, skipping
,I/SystemUpdateService( 1958): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/ChimeraCfgMgr( 1958): Beginning module configuration check
,D/SystemUpdateService( 1958): onCreate
,I/CheckinService( 1958): Checking schedule, now: 1457954177047 next: 1458555305542
I/CheckinService( 1958): active receiver: disabled
D/SystemUpdateService( 1958): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/ChimeraCfgMgr( 1958): Module APKs unchanged, check complete
,I/SystemUpdateService( 1958): cancelUpdate (empty URL)
I/SystemUpdateService( 1958): active receiver: disabled
,I/art     ( 3133): Explicit concurrent mark sweep GC freed 3922(166KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 720us total 31.410ms
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 11912(747KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 12MB/21MB, paused 1.103ms total 60.772ms
,W/SQLiteConnectionPool( 1958): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 3133): Explicit concurrent mark sweep GC freed 2635(101KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 586us total 23.242ms
,D/SystemUpdateService( 1958): onDestroy
,W/DynamiteLoaderImpl( 1958): Failed to load module version: module com.google.android.gms.flags not found
I/DynamiteModule( 1958): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1958): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 1958): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1958): Updating ocr activity enabled=false
,W/ActivityManager(  888): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1958): Updating downloaded model state (gservices changed)
,I/art     ( 3133): Explicit concurrent mark sweep GC freed 2689(105KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 544us total 41.670ms
,D/GCM     ( 1727): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1727): Explicit concurrent mark sweep GC freed 16357(871KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 13MB/22MB, paused 1.088ms total 67.831ms
,D/TaskPersister(  888): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/GCoreUlr( 1727): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1727): DispatchingService.onCreate()
,I/ActivityManager(  888): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5129 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 20.047ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 18.897ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.478ms
,I/GCoreUlr( 1727): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PhoneMonitor( 5129): Register our PhoneStateListener
,W/jxcore-log( 4911): Initializing JXcore engine
W/jxcore-log( 4911): JXcore engine is ready
,V/SetupWizard( 5129): Connected to Gservices successfully
,D/GCM     ( 1727): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  888): Explicit concurrent mark sweep GC freed 17821(872KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/31MB, paused 2.044ms total 159.903ms
,W/GeofencerStateMachine( 1727): Ignoring removeGeofence because network location is disabled.
,W/Thread-551( 5091): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[6495]" dev="sockfs" ino=6495 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-551( 5091): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-551( 5091): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7491]" dev="sockfs" ino=7491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-551( 5091): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[21276]" dev="sockfs" ino=21276 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,E/ctxmgr  ( 1727): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/jxcore-log( 4911): Starting JXcore engine
,I/ActivityManager(  888): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5151 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=326, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310130, SEQNUM=4334, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/ResourcesManager( 4892): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4892): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreUlr( 1727): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1727): Unbound from all location providers
I/GCoreUlr( 1727): Place inference reporting - stopped
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/JNIHelp ( 4892): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/GCoreUlr( 1727): DispatchingService.onDestroy()
I/GCoreUlr( 1727): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1727): Unbound from all location providers
I/GCoreUlr( 1727): Place inference reporting - stopped
I/art     ( 3133): Explicit concurrent mark sweep GC freed 2606(103KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 813us total 40.263ms
,W/jxcore-log( 4911): Platform android
W/jxcore-log( 4911): 
W/jxcore-log( 4911): Process ARCH arm
W/jxcore-log( 4911): 
,W/art     ( 4892): Suspending all threads took: 29.051ms
,I/ActivityManager(  888): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5171 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  888): Killing 5038:com.google.android.configupdater/u0a54 (adj 15): empty #7
,I/ContactLocale( 5151): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/System  ( 4892): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4892): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  888): failed to open /acct/uid_10054/pid_5038/cgroup.procs: No such file or directory
,W/asset   ( 5171): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5171): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5171): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5171): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ctxmgr  ( 1727): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1727): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/UpdateIcingCorporaServi( 5067): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/AlarmManager(  888): send {1bf9a7d9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,W/Launcher( 1577): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@285c9e8d new=com.google.android.velvet.VelvetApplication@285c9e8d
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 1958): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  888): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5198 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5198): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5067): UpdateCorporaTask done [took 208 ms] updated apps [took 208 ms] 
I/ActivityManager(  888): Killing 5001:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/jxcore-log( 4911): JXcore Cordova bridge is ready!
I/jxcore-log( 4911): 
W/jxcore-log( 4911): JXcore engine is started
,W/libprocessgroup(  888): failed to open /acct/uid_10019/pid_5001/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.ThaliPermissions( 4911): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 4911): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4911): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4911): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/PluginManager( 4911): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2564): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2564): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2564): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2564): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2564): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2564): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2564): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2564): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 4911): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/LaunchCheckinHandler(  888): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,7451
I/LaunchCheckinHandler(  888): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5242 (total)
,I/ActivityManager(  888): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5227 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 4968:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10088/pid_4968/cgroup.procs: No such file or directory
,D/Finsky  ( 5227): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5227): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5227): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5227): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 5227): Skipping gmscore version check
,D/Finsky  ( 5227): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5227): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  888): Killing 5129:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10035/pid_5129/cgroup.procs: No such file or directory
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/ActivityManager(  888): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.WidgetDataReceiver: pid=5281 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5171:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10027/pid_5171/cgroup.procs: No such file or directory
,D/Finsky  ( 5227): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Icing   ( 1958): Loaded CLD2 Version V2.0 - 20141016
,E/SQLiteLog( 5281): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/Finsky  ( 5227): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  888): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5308 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5308): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5308): Created com.android.providers.calendar.CalendarAlarmManager@3d4c09d5(com.android.providers.calendar.CalendarProvider2@341d45ea)
,I/AnalyticsLogBase( 5281): PlayLogger.onLoggerConnected
,I/ActivityManager(  888): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5328 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5151:android.process.acore/u0a7 (adj 15): empty #7
,I/ActivityManager(  888): Killing 5067:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  888): failed to open /acct/uid_10007/pid_5151/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10039/pid_5067/cgroup.procs: No such file or directory
,W/ResourcesManager( 5328): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  888): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5363 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5363): getAccountsCursor
,D/ActivityThread( 5363): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  888): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5385 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  888): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5363): Observing account changes for notifications
I/Exchange( 5385): EasService.onCreate
,W/GAV2    ( 5363): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Exchange( 5385): RestartPingTask
,I/Exchange( 5385): RestartPingsTask did not start any pings.
I/Exchange( 5385): PSS stopIfIdle
I/Exchange( 5385): PSS has no active accounts; stopping service.
,I/Exchange( 5385): onDestroy
,I/Gmail   ( 5363): getAccountsCursor
,I/ActivityManager(  888): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5421 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  888): Killing 5198:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10090/pid_5198/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  888): Explicit concurrent mark sweep GC freed 13548(680KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 4.636ms total 144.221ms
,E/SQLiteLog( 5363): (283) recovered 135 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 5363): notifyAccountChanged
,I/Gmail   ( 5363): getAccountsCursor
,I/Gmail   ( 5363): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ContactLocale( 5421): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Gmail   ( 5363): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  888): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5445 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  888): Killing 4911:com.test.thalitest/u0a109 (adj 15): empty #7
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.801ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.138ms
,D/WifiService(  888): Client connection lost with reason: 4
,I/Gmail   ( 5363): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5363): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.315ms
,W/libprocessgroup(  888): failed to open /acct/uid_10109/pid_4911/cgroup.procs: No such file or directory
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5308): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5308): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  888): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5473 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5227:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  888): Killing 5308:com.android.providers.calendar/u0a5 (adj 13): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10032/pid_5227/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10005/pid_5308/cgroup.procs: No such file or directory
,W/asset   ( 5473): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5473): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5473): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5473): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Gmail   ( 5363): getAccountsCursor
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SFPerfTracer(  281):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (35:297 vsyncs) (37:1063)
,I/SFPerfTracer(  281):      triggers: (rate: 12:539) (compose: 0:1) (post: 0:1) (render: 0:2) (0:965 frames) (1:1063)
D/SFPerfTracer(  281):        layers: (3:11) (FocusedStackFrame (0xb7a50f20): 0:17)* (DimLayer (0xb7a62ad0): 1:8)* (StatusBar (0xb79ffda8): 0:145) (NavigationBar (0xb7a01710): 0:46) (com.android.systemui.ImageWallpaper (0xb7a03b00): 0:6)* (Starting com.test.thalitest (0xb7a8d240): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7a658a0): 0:87)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7a8d240): 0:31) 
,I/ActivityManager(  888): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5494 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5328:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10008/pid_5328/cgroup.procs: No such file or directory
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/art     ( 1958): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,I/UpdateIcingCorporaServi( 5494): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AsyncTaskServiceImpl( 1958): Submit a task: k
,D/k       ( 1958): Processing package: com.test.thalitest
,D/GassUtils( 1958): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1958): Found info for package com.test.thalitest in db.
,I/ActivityManager(  888): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5527 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=5545 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  888): send {1fd3a53b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  888): send {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  888): done {1fd3a53b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [60ms]
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:37000 mC
,D/Finsky  ( 5545): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/PeopleDatabaseHelper( 1958): cleanUpNonGplusAccounts done.
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 37184(2MB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 14MB/18MB, paused 5.460ms total 213.998ms
,D/Finsky  ( 5545): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5545): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5545): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/UpdateIcingCorporaServi( 5494): UpdateCorporaTask done [took 449 ms] updated apps [took 449 ms] 
,D/Finsky  ( 5545): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Ads     ( 5545): Skipping gmscore version check
D/Finsky  ( 5545): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5545): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  888): Killing 5363:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10063/pid_5363/cgroup.procs: No such file or directory
,D/Finsky  ( 5545): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5545): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/GAv4    ( 5527): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5527):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5527):   adb logcat -s GAv4
,W/GAv4    ( 5527): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5527): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5527): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5527): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,D/TaskPersister(  888): removeObsoleteFile: deleting file=8_task.xml
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5527): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5527): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5527): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  888): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5613 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5385:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10060/pid_5385/cgroup.procs: No such file or directory
,I/ActivityManager(  888): Killing 4892:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ResourcesManager( 5613): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5527): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5527): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5527): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  888): failed to open /acct/uid_10070/pid_4892/cgroup.procs: No such file or directory
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/qtaguid ( 5545): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5545): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5545): untagSocket(37) failed with errno -22
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
I/Icing   ( 1958): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/Icing   ( 1958): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,I/ActivityManager(  888): Killing 5445:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,I/art     (  888): Explicit concurrent mark sweep GC freed 12431(638KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.672ms total 123.532ms
,W/libprocessgroup(  888): failed to open /acct/uid_10019/pid_5445/cgroup.procs: No such file or directory
,D/Finsky  ( 5545): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  888): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=5644 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 5545): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  888): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5662 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5644): getAccountsCursor
,D/ActivityThread( 5644): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ResourcesManager( 5662): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5662): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 5662): VM with version 2.1.0 has multidex support
I/MultiDex( 5662): install
I/MultiDex( 5662): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  888): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5685 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/JNIHelp ( 5662): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/GAV2    ( 5644): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  888): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 5685): EasService.onCreate
,I/Exchange( 5685): RestartPingTask
,I/Gmail   ( 5644): Observing account changes for notifications
,W/ActivityThread( 5662): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5662): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a98bf1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5662): Installed default security provider GmsCore_OpenSSL
,I/Exchange( 5685): RestartPingsTask did not start any pings.
I/Exchange( 5685): PSS stopIfIdle
,I/Exchange( 5685): PSS has no active accounts; stopping service.
V/AlarmManager(  888): send {d8a68f5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/ChimeraCfgMgr( 5662): Reading stored module config
,I/Gmail   ( 5644): getAccountsCursor
,I/Exchange( 5685): onDestroy
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminSetupReceiver( 2564): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
D/3CDM.DeviceAdminSetupReceiver( 2564): time to show notification
,I/ActivityManager(  888): Killing 5473:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10027/pid_5473/cgroup.procs: No such file or directory
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1297): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,D/NativeLibraryUtils( 5662): Install completed successfully. count=14 extracted=0
,E/SQLiteLog( 5644): (283) recovered 136 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/qtaguid ( 5545): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5545): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5545): untagSocket(37) failed with errno -22
,I/ActivityManager(  888): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5731 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 5731): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  888): Killing 5494:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/ActivatableNotificationView( 1297):  oops Width=0 ActualHeight=128
,W/libprocessgroup(  888): failed to open /acct/uid_10039/pid_5494/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 5662): Connecting to CarCallService...
,I/Gmail   ( 5644): notifyAccountChanged
,I/Gmail   ( 5644): getAccountsCursor
,I/Gmail   ( 5644): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5644): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5644): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5644): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  888): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5751 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     ( 5662): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5662): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 5751): Register our PhoneStateListener
,I/ActivityManager(  888): Killing 5527:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/CAR.SERVICE( 5662): com.google.android.projection.gearhead isn't installed.
,W/libprocessgroup(  888): failed to open /acct/uid_10057/pid_5527/cgroup.procs: No such file or directory
,I/ActivityManager(  888): Killing 5421:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10007/pid_5421/cgroup.procs: No such file or directory
,D/CAR.TEL.Service( 5662): Creating a new CarCallService.
D/GCM     ( 1727): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/CAR.TEL.PhoneAdapter( 5662): Creating a new PhoneAdapter instance
,W/ActivityManager(  888): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5662): setListener: com.google.android.gms.car.dn@2c66c38
W/ActivityManager(  888): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
I/CheckinService( 1958): Checking schedule, now: 1457954185839 next: 1457954198542
I/CheckinService( 1958): active receiver: disabled
,D/CAR.TEL.PhoneAdapter( 5662): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5662): Starting CarCallService with initial phone null
,I/art     ( 3133): Explicit concurrent mark sweep GC freed 3127(124KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 485us total 32.658ms
,I/ActivityManager(  888): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5774 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CAR.SERVICE( 5662): Package validated; name: com.android.vending
,I/art     (  319): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 23.531ms
,I/Gmail   ( 5644): getAccountsCursor
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.726ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.952ms
,V/Finsky  ( 5545): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/ContextImpl( 5281): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/art     ( 1727): Explicit concurrent mark sweep GC freed 22620(1374KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 13MB/23MB, paused 1.048ms total 94.723ms
,W/PackageSettings(  888): Skipping PackageSetting{20c6abf3 com.example.hello/10568} due to missing metadata
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5774): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/GAV2    ( 5281): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 5774): Created com.android.providers.calendar.CalendarAlarmManager@3d4c09d5(com.android.providers.calendar.CalendarProvider2@341d45ea)
,V/AlarmManager(  888): done {1bf9a7d9, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [6817ms]
,E/SQLiteLog( 5774): (284) automatic index on view_events(_id)
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=13.28 rxSuccessRate=11.59 targetRoamBSSID=any RSSI=-46
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN with age=1457954186254 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN try full band scan age=1457954186254 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  888): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  888): [1,457,954,186,256 ms] noteScanstart no scan source
V/AlarmManager(  888): done {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3089ms]
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 6
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 8
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
E/WifiStateMachine(  888): [1,457,954,186,328 ms] noteScanEnd no scan source
E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b6920ac sup_state=COMPLETED debouncing=false
,I/art     (  888): Explicit concurrent mark sweep GC freed 16603(1035KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 1.469ms total 119.022ms
,D/WearableService( 1727): callingUid 10016, callindPid: 1727
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1958): Restart initialization of location
,E/MDM     ( 1727): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  888): done {d8a68f5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1334ms]
,W/GCoreFlp( 1727): No location to return for getLastLocation()
W/FusedLocationProvider( 1727): location=null
,D/GCM     ( 1727): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/qtaguid ( 5545): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 5545): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 5545): untagSocket(37) failed with errno -22
,W/ActivityManager(  888): getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 5545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5545): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5774): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5774): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  888): Killing 5613:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10090/pid_5613/cgroup.procs: No such file or directory
,D/Finsky  ( 5545): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  888): send {376cb576, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,V/AlarmManager(  888): done {376cb576, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [18ms]
,D/DeviceConnectionService( 1727): client connected with version: 8296000
,D/Finsky  ( 5545): [654] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5545): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5545): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  888): Killing 5751:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  888): Killing 5685:com.google.android.gm.exchange/u0a60 (adj 15): empty #8
,W/libprocessgroup(  888): failed to open /acct/uid_10035/pid_5751/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10060/pid_5685/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  888): send {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  888): done {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/GAV2    ( 5644): Thread[GAThread,5,main]: No campaign data found.
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/CAR.SERVICE( 5662): mConnectedToCar = false, abort
,E/ActivityThread( 5662): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7529920 that was originally bound here
E/ActivityThread( 5662): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7529920 that was originally bound here
E/ActivityThread( 5662): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5662): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5662): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5662): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5662): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5662): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5662): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5662): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5662): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5662): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread( 5662): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread( 5662): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread( 5662): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread( 5662): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5662): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5662): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5662): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5662): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5662): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5662): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5662): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e8fc09b that was originally bound here
E/ActivityThread( 5662): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e8fc09b that was originally bound here
E/ActivityThread( 5662): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5662): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5662): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5662): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5662): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5662): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread( 5662): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread( 5662): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread( 5662): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread( 5662): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread( 5662): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread( 5662): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread( 5662): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5662): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5662): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5662): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5662): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5662): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5662): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5662): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5662): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  888): Unbind failed: could not find connection for android.os.BinderProxy@3e03a05a
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:36000 mC
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  888): Waited long enough for: ServiceRecord{13ad390a u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  888): send {2202e28b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  888): send {35489f81, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  888): send {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  888): done {35489f81, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [20ms]
,V/AlarmManager(  888): done {2202e28b, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [37ms]
,V/AlarmManager(  888): done {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN} [39ms]
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=2.13 rxSuccessRate=2.61 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN with age=1457954201216 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN try full band scan age=1457954201216 interval=20000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN bump interval =30000
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  888): [1,457,954,201,220 ms] noteScanstart no scan source
,I/CheckinService( 1958): Checking schedule, now: 1457954201237 next: 1457954198542
I/CheckinService( 1958): active receiver: enabled
,I/CheckinService( 1958): Preparing to send checkin request
I/EventLogService( 1958): Accumulating logs since 1457954157479
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5545): [645] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5545): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  888): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5847 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  888): Killing 5644:com.google.android.gm/u0a63 (adj 15): empty #7
,W/ResourcesManager( 5847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5847): VM with version 2.1.0 has multidex support
,I/MultiDex( 5847): install
I/MultiDex( 5847): VM has multidex support, MultiDex support library is disabled.
,D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 21 
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
D/TCMD    (  504): Listening for incoming client connection request
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 22 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 23 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 24 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
,D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 25 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 26 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 27 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 28 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 29 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 30 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 31 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 32 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 32 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 33 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 33 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 34 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 34 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine(  888): [1,457,954,201,678 ms] noteScanEnd no scan source
,E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b6920ac sup_state=COMPLETED debouncing=false
,W/libprocessgroup(  888): failed to open /acct/uid_10063/pid_5644/cgroup.procs: No such file or directory
,V/JNIHelp ( 5847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5847): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a98bf1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5847): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1727): callingUid 10016, callindPid: 1727
,E/MDM     ( 1727): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1727): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1958): Restart initialization of location
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1727): No location to return for getLastLocation()
W/FusedLocationProvider( 1727): location=null
,I/art     ( 5847): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5847): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5847): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  298): Instantiating CDM.
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     ( 5847): Background sticky concurrent mark sweep GC freed 20808(1240KB) AllocSpace objects, 2(32KB) LOS objects, 10% free, 10MB/11MB, paused 6.829ms total 53.859ms
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb142a960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb7f6af88, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e8bc18, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fc4fb0, idLength=0xb55ef730
,I/art     ( 5847): Background partial concurrent mark sweep GC freed 16531(992KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 10MB/16MB, paused 5.118ms total 43.064ms
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=2899328542
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7f69e18
D/DrmWidevineDash(  298): message_length=1591, signature=0xb7ef1cc8, signature_length=3042899732
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 5876): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5876): dex2oat took 73.073ms (threads: 4)
,I/Adreno-EGL( 5847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5847): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5847): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5847): Local Branch: 
I/Adreno-EGL( 5847): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5847): Local Patches: NONE
I/Adreno-EGL( 5847): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5847): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5847): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5847): Local Branch: 
I/Adreno-EGL( 5847): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5847): Local Patches: NONE
I/Adreno-EGL( 5847): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Adreno-EGL( 5847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5847): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5847): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5847): Local Branch: 
I/Adreno-EGL( 5847): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5847): Local Patches: NONE
I/Adreno-EGL( 5847): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 5847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5847): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5847): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5847): Local Branch: 
I/Adreno-EGL( 5847): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5847): Local Patches: NONE
I/Adreno-EGL( 5847): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  298): CdmEngine::OpenSession
I/WVCdm   (  298): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  298): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  298): Service_Initialize: starts!
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,E/QSEECOMAPI: (  298): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
E/QSEECOMAPI: (  298): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  298): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  298): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  298): App is not loaded in QSEE
,D/QSEECOMAPI: (  298): Loaded image: APP id = 3
,D/DrmWidevineDash(  298): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
E/DrmWidevineDash(  298): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5014000
,D/DrmWidevineDash(  298): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  298): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  298): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: starts! SID=0xb54ef960
D/DrmWidevineDash(  298): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  298): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: starts! randomData=0xb7f6b178, dataLength=8
D/DrmWidevineDash(  298): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7e8bc18, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  298): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  298): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  298): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  298): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  298): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: starts! deviceID=0xb7fc4fd0, idLength=0xb55ef730
,D/DrmWidevineDash(  298): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  298): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  298): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  298): hlos api version =  9
D/DrmWidevineDash(  298): tz api version =  8
,D/DrmWidevineDash(  298): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  298): PrepareKeyRequest: nonce=3714341856
D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e8ac68
D/DrmWidevineDash(  298): message_length=1622, signature=0xb7e947c0, signature_length=3042899732
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,D/DrmWidevineDash(  298): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  298): CdmEngine::CloseSession
,D/DrmWidevineDash(  298): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  298): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  298): L3 Terminate.
D/DrmWidevineDash(  298): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  298): Service_Uninitialize: starts!
D/QSEECOMAPI: (  298): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  298): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  298): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  298): OEMCrypto_Terminate: ends! returns 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/CheckinTask( 1958): Sending checkin request (9722 bytes)
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1457954204329 next: 1458555341323
I/CheckinService( 1958): active receiver: disabled
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1457954204350
,I/ActivityManager(  888): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5911 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5911): Register our PhoneStateListener
,V/SetupWizard( 5911): Connected to Gservices successfully
,I/ActivityManager(  888): Killing 5731:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10008/pid_5731/cgroup.procs: No such file or directory
,D/GCM     ( 1727): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  888): Killing 5662:com.google.android.gms:car/u0a16 (adj 13): empty #7
,I/ActivityManager(  888): Killing 5774:com.android.providers.calendar/u0a5 (adj 15): empty #8
,W/libprocessgroup(  888): failed to open /acct/uid_10016/pid_5662/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10005/pid_5774/cgroup.procs: No such file or directory
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=307, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309492, SEQNUM=4362, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-49, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  888): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5933 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  888): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  888): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  888): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  888): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@323f462a
,I/GCoreNlp( 1727): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1577): Deferring update until onResume
,I/art     (  888): Explicit concurrent mark sweep GC freed 35444(1749KB) AllocSpace objects, 4(158KB) LOS objects, 33% free, 21MB/32MB, paused 1.468ms total 129.318ms
,I/ActivityManager(  888): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5973 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  888): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5979 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  888): Killing 5281:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/ActivityManager(  888): Killing 5545:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10049/pid_5281/cgroup.procs: No such file or directory
,W/libprocessgroup(  888): failed to open /acct/uid_10032/pid_5545/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 5979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5979): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5979): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5979): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 5979): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5979): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5979): MmsConfig.loadFromResources
,E/Babel_SMS( 5979): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5979): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 5979): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5979): startup - clean
,I/Babel   ( 5979): deleted: false for 0
,I/ActivityManager(  888): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6022 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 5979): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5979): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 5979): Unsupported mime video/mpeg2
,I/VideoCapabilities( 5979): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5979): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5979): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5979): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5979): Unrecognized profile 2130706433 for video/avc
,I/ContactLocale( 6022): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  888): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6046 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  888): Killing 5911:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  888): failed to open /acct/uid_10035/pid_5911/cgroup.procs: No such file or directory
,W/asset   ( 6046): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6046): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 6046): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6046): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1577): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@285c9e8d new=com.google.android.velvet.VelvetApplication@285c9e8d
,D/PkgBroadcastIntentOp( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 1958): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  888): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6073 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/WearableController( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/vclib   ( 5979): onServiceConnected
,W/Babel   ( 5979): Attempted to change video mute state without an active call.
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6073): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5979): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5979): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 5933): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
,V/JNIHelp ( 5979): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5979): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5979): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  888): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6103 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:34000 mC
,I/ActivityManager(  888): Killing 5847:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10016/pid_5847/cgroup.procs: No such file or directory
,D/Finsky  ( 6103): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6103): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6103): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6103): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 6103): Skipping gmscore version check
D/Finsky  ( 6103): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6103): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6103): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6103): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  888): Killing 5973:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10019/pid_5973/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  888): send {2a025224, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  888): send {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  888): done {2a025224, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [12ms]
V/AlarmManager(  888): done {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN} [13ms]
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.00 rxSuccessRate=1.77 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN with age=16536 interval=30000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN full=false
E/WifiStateMachine(  888): WifiStateMachine starting scan for "NG700"WPA_PSK with 2422
,I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  888): [1,457,954,217,759 ms] noteScanstart no scan source
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 35 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 35 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
,D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
,E/WifiStateMachine(  888): [1,457,954,217,829 ms] noteScanEnd no scan source
,E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b6920ac sup_state=COMPLETED debouncing=false
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1727): Vacuum at: now=1457954217955 tag=VacuumService
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  888): Killing 6046:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10027/pid_6046/cgroup.procs: No such file or directory
,V/AlarmManager(  888): send {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  888): done {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ActivityManager(  888): Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=6167 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1958): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  888): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 196233, reason: UserStart
,I/GAv4    ( 6167): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6167):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6167):   adb logcat -s GAv4
,W/GAv4    ( 6167): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6167): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6167): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6167): Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,E/SQLiteLog( 6167): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,W/art     ( 6167): Suspending all threads took: 10.512ms
,I/ActivityManager(  888): Killing 5933:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10039/pid_5933/cgroup.procs: No such file or directory
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6167): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6167): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager(  888): send {b38f55f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): done {b38f55f, *alarm*:android.intent.action.TIME_TICK} [18ms]
,I/ActivityManager(  888): Killing 5979:com.google.android.talk/u0a70 (adj 15): empty #7
,V/JNIHelp ( 6167): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 6167): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  888): failed to open /acct/uid_10070/pid_5979/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=299, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309969, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-93, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/BackupManagerService(  888): Timeout restoring application @pm@
W/BackupManagerService(  888): Tried to clear data for @pm@ but not found
,W/GmsBackupTransport( 1727): Restore processing aborted, no more packages
,E/BackupManagerService(  888): Failure getting next package name
,E/BackupManagerService(  888): Duplicate finish
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  888): send {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  888): done {336a3850, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3ms]
,E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.36 rxSuccessRate=0.25 targetRoamBSSID=any RSSI=-46
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN with age=34383 interval=30000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN try full band scan age=34383 interval=30000 maxinterval=300000
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN full=true
E/WifiStateMachine(  888): WifiStateMachine CMD_START_SCAN bump interval =45000
I/wpa_supplicant( 1416): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  888): [1,457,954,235,605 ms] noteScanstart no scan source
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 36 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 36 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 37 
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-ADDED 37 
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  296): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  504): NL - Read 56 bytes from update socket.
D/TCMD    (  504): NL - message type is RTM_NEWLINK
D/TCMD    (  504): Listening for incoming client connection request
,E/WifiStateMachine(  888): [1,457,954,236,106 ms] noteScanEnd no scan source
,E/WifiStateMachine(  888): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2b6920ac sup_state=COMPLETED debouncing=false
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
,I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1727): onCreate
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1727): onDestroy
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1297): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,V/AlarmManager(  888): send {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  888): done {3dbdce6f, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=291, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309917, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-134, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/SBar.MotoNetworkCtrlr( 1297): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1297): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/PowerManagerService(  888): Nap time (uid 1000)...
,I/PowerManagerService(  888): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  888): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  888): Build Date: 10/28/14 Tue
I/Adreno-EGL(  888): Local Branch: 
I/Adreno-EGL(  888): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  888): Local Patches: NONE
I/Adreno-EGL(  888): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  888): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  888): BstSensorExt: id=1598182242, en=0
,D/        (  888): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 223
,D/        (  888): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  888): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  888): Display changed displayId=0
,D/SurfaceFlinger(  281): Set power mode=0, type=0 flinger=0xb7967550
,D/qdhwcomposer(  281): hwc_blank: Blanking display: 0
,I/art     (  888): Explicit concurrent mark sweep GC freed 37683(1849KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 6.050ms total 143.919ms
,I/rmt_storage(  292): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bcb820
I/rmt_storage(  292): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  292): wakelock acquired: 1, error no: 42
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212368760)
,I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  281): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  281): hwc_blank: Done blanking display: 0
D/SurfaceControl(  888): Excessive delay in setPowerMode(): 338ms
I/SFPerfTracer(  281):       trigger: frame rate (-28.646%)	(42.812 fps)	(23.358 ms) 	(4 drops)	(15 frames)
I/SFPerfTracer(  281):      triggers: (rate: 13:546) (compose: 0:1) (post: 0:1) (render: 0:2) (15:1017 frames) (16:1129)
D/SFPerfTracer(  281):        layers: (4:10) (FocusedStackFrame (0xb7a50f20): 0:17)* (DimLayer (0xb7a62ad0): 0:8)* (StatusBar (0xb79ffda8): 0:186) (NavigationBar (0xb7a01710): 0:46) (com.android.systemui.ImageWallpaper (0xb7a03b00): 0:6)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7a8d240): 0:31) (ColorFade (0xb7a64ec0): 16:18) 
,I/WindowManager(  888): AOD feature not enabled!
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PowerManagerService(  888): Sleeping (uid 1000)...
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  292): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212368760) wakelock released: 1, error no: 0
I/rmt_storage(  292): 
,I/rmt_storage(  292): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7bcb820
,D/WifiStateMachine(  888): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  888): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
E/msm8974_platform(  298): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,E/WifiStateMachine(  888): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  888): do suspend false
,I/Keyboard.Facilitator( 1417): onFinishInput()
,D/        (  888): activate, handle: 1598182229, enabled: 0, index 0
,E/        (  888): <BST> disable accel, orig state: 1
I/        (  888): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  298): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  298): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  298): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  298): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  298): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  888): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  888): handleScreenStateChanged Exit: false
E/WifiStateMachine(  888): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/WifiStateMachine(  888): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  888): do suspend true
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  888): send {2ce172f0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  888): done {2ce172f0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [10ms]
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309442, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1614, POWER_SUPPLY_CHARGE_COUNTER=-139, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  888): send {b38f55f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): send {22a34069, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  888): done {22a34069, *walarm*:com.google.android.intent.action.SEND_IDLE} [18ms]
,V/AlarmManager(  888): done {b38f55f, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/PhenotypeConfigurator( 1727): Scheduling Phenotype for one-off execution 618 seconds from now (1457954282802)
,I/PhenotypeFlagCommitter( 1727): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1727): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,E/global frequency( 2564): no tags to log
,D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1560): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1560): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 57563(3MB) AllocSpace objects, 35(1234KB) LOS objects, 40% free, 7MB/12MB, paused 795us total 53.796ms
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 2564): Explicit concurrent mark sweep GC freed 27531(1650KB) AllocSpace objects, 6(119KB) LOS objects, 40% free, 11MB/19MB, paused 1.250ms total 71.287ms
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1560): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2564): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1727): Background sticky concurrent mark sweep GC freed 110389(6MB) AllocSpace objects, 15(240KB) LOS objects, 27% free, 16MB/23MB, paused 2.209ms total 124.759ms
,E/DataBuffer( 1727): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7feed40)
,E/DataBuffer( 1727): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1354b479)
,E/DataBuffer( 1727): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18a3e5be)
E/DataBuffer( 1727): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cbce61f)
E/DataBuffer( 1727): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25859d6c)
,I/art     (  888): Explicit concurrent mark sweep GC freed 18035(847KB) AllocSpace objects, 2(222KB) LOS objects, 33% free, 21MB/32MB, paused 1.555ms total 135.853ms
,I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2564): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2564): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2564): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2564): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2564): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2564): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2564): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1727): disconnect managed GoogleApiClient
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  888): send {2d233695, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  888): done {2d233695, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310516, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1614, POWER_SUPPLY_CHARGE_COUNTER=-138, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1727): onCreate
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1727): onDestroy
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309816, SEQNUM=4400, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-227, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310097, SEQNUM=4401, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-340, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {b38f55f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): done {b38f55f, *alarm*:android.intent.action.TIME_TICK} [35ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {b38f55f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): send {d8a68f5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  888): send {1b4da711, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  888): done {d8a68f5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  888): done {1b4da711, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [35ms]
,V/AlarmManager(  888): done {b38f55f, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/EventLogService( 1958): Aggregate from 1457954201360 (log), 1457952858034 (data)
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {b38f55f, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): send {12d92e02, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  888): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6303 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 33.064ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 18.926ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.215ms
,V/AlarmManager(  888): done {b38f55f, *alarm*:android.intent.action.TIME_TICK} [217ms]
,I/GAv4    ( 6303): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6303):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6303):   adb logcat -s GAv4
,W/GAv4    ( 6303): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6303): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6303): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  888): done {12d92e02, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [284ms]
,I/ActivityManager(  888): Killing 6022:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10007/pid_6022/cgroup.procs: No such file or directory
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309708, SEQNUM=4409, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-38, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310283, SEQNUM=4410, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-50, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  888): User[0] Flushing usage stats to disk
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309674, SEQNUM=4411, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-163, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2443): Disconnected process message: 10, size: 0
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 6350): 
D/AndroidRuntime( 6350): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6350): CheckJNI is OFF
D/AndroidRuntime( 6350): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
W/PackageSettings(  888): Skipping PackageSetting{20c6abf3 com.example.hello/10568} due to missing metadata
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10109 user=0: pkg removed
I/art     ( 2983): Explicit concurrent mark sweep GC freed 10398(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 7MB/12MB, paused 657us total 39.615ms
I/art     ( 1577): Explicit concurrent mark sweep GC freed 2557(136KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 474us total 87.137ms
W/GeofencerStateMachine( 1727): Ignoring removeGeofence because network location is disabled.
I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
I/ActivityManager(  888): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6378 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
I/art     ( 1958): Explicit concurrent mark sweep GC freed 21293(1276KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 1.091ms total 146.626ms
I/Decoder ( 1417): createOrResetDecoder
I/art     (  888): Explicit concurrent mark sweep GC freed 20192(1609KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 21MB/32MB, paused 1.853ms total 164.540ms
I/ConfigService( 1727): onCreate
I/art     (  888): WaitForGcToComplete blocked for 63.746ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
D/VoicemailCleanupService( 6378): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  888): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6405 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  888): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  888): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/ContactLocale( 6378): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  888): Explicit concurrent mark sweep GC freed 4354(238KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/32MB, paused 1.479ms total 173.285ms
I/ActivityManager(  888): Killing 6073:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 6350): Shutting down VM
W/libprocessgroup(  888): failed to open /acct/uid_10090/pid_6073/cgroup.procs: No such file or directory
W/asset   ( 6405): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6405): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6405): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6405): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  888): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6423 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
I/ActivityManager(  888): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6443 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  888): Killing 6103:com.android.vending/u0a32 (adj 15): empty #7
W/libprocessgroup(  888): failed to open /acct/uid_10032/pid_6103/cgroup.procs: No such file or directory
I/ActivityManager(  888): Killing 6167:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
W/libprocessgroup(  888): failed to open /acct/uid_10105/pid_6167/cgroup.procs: No such file or directory

```
