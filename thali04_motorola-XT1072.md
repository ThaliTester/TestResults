#### Test 62947189e430ee9_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-15 19:12:24.273  5038  5038 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
03-15 19:12:24.292  5038  5038 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-15 19:12:24.318  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:24.389  5038  5038 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-15 19:12:24.394  5038  5071 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-15 19:12:24.394  5038  5071 I MusicLeanback: Stop autocaching.
03-15 19:12:24.403  1784  1784 D WearableService: callingUid 10016, callindPid: 1784
03-15 19:12:24.410  2863  2863 I ActivationLocation: Provisioning status received: ERROR_FAIL
--------- beginning of system
03-15 19:12:24.443   885   900 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5077 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:12:24.444  5038  5038 I MusicLeanback: Stop autocaching.
03-15 19:12:24.446  5038  5057 I MusicLeanback: Stop autocaching.
03-15 19:12:24.481  5038  5038 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
03-15 19:12:24.486  5038  5038 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-15 19:12:24.494  5038  5057 I MusicLeanback: Stop autocaching.
03-15 19:12:24.606  5038  5038 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-15 19:12:24.607  5038  5099 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
03-15 19:12:24.610   885  1597 I ActivityManager: Killing 4937:android.process.acore/u0a7 (adj 15): empty #7
03-15 19:12:24.668   885   901 W libprocessgroup: failed to open /acct/uid_10007/pid_4937/cgroup.procs: No such file or directory
03-15 19:12:24.732  5077  5102 I Gmail   : getAccountsCursor
03-15 19:12:24.733  5077  5103 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-15 19:12:24.748  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:12:24.810  5074  5074 D AndroidRuntime: 
03-15 19:12:24.810  5074  5074 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 19:12:24.814  5074  5074 D AndroidRuntime: CheckJNI is OFF
03-15 19:12:24.848   885  1538 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5105 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:12:24.927   885  1814 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-15 19:12:24.937  5105  5105 I Exchange: EasService.onCreate
03-15 19:12:24.947  5077  5135 I Gmail   : Observing account changes for notifications
03-15 19:12:24.953  5105  5141 I Exchange: RestartPingTask
03-15 19:12:24.961  5077  5077 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-15 19:12:24.965  5105  5105 I Exchange: RestartPingsTask did not start any pings.
03-15 19:12:24.966  5105  5105 I Exchange: PSS stopIfIdle
03-15 19:12:24.966  5105  5105 I Exchange: PSS has no active accounts; stopping service.
03-15 19:12:25.020  5077  5102 I Gmail   : getAccountsCursor
03-15 19:12:25.024  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:12:25.031  5105  5105 I Exchange: onDestroy
03-15 19:12:25.032   885  1814 I ActivityManager: Killing 4475:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
03-15 19:12:25.060  5074  5074 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 19:12:25.071   885  1538 W libprocessgroup: failed to open /acct/uid_10016/pid_4475/cgroup.procs: No such file or directory
03-15 19:12:25.074   885  1488 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-15 19:12:25.102   281  1149 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (147 us)
03-15 19:12:25.124  1482  4186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-15 19:12:25.138  5074  5074 D AndroidRuntime: Shutting down VM
03-15 19:12:25.142  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:12:25.189   885  1814 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5159 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 19:12:25.202   885  4415 I ActivityManager: Killing 4958:com.motorola.context/u0a8 (adj 15): empty #7
03-15 19:12:25.319  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-15 19:12:25.345   885  1814 W libprocessgroup: failed to open /acct/uid_10008/pid_4958/cgroup.procs: No such file or directory
03-15 19:12:25.354  1482  4186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 19:12:25.417   885  1538 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5176 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:25.485  1784  5189 E MDM     : [217] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:12:25.486  5077  5186 E SQLiteLog: (283) recovered 21 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 19:12:25.497  1957  5196 D LocationInitializer: Restart initialization of location
,03-15 19:12:25.498  5176  5176 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 19:12:25.507  1784  1784 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:12:25.530  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:25.600   885  4415 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=5200 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-15 19:12:25.605  5176  5176 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1172e6bf(com.android.providers.calendar.CalendarProvider2@26f4a18c)
,03-15 19:12:25.614  1784  2010 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:12:25.615  1784  5197 W FusedLocationProvider: location=null
,03-15 19:12:25.646   885  4415 I ActivityManager: Killing 4983:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-15 19:12:25.664  5077  5190 I Gmail   : notifyAccountChanged
,03-15 19:12:25.670  5077  5147 I Gmail   : getAccountsCursor
03-15 19:12:25.673  5077  5190 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:12:25.679  5077  5190 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:12:25.680  5159  5159 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-15 19:12:25.689  5077  5190 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 19:12:25.690  5077  5190 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 19:12:25.702   281   281 I SFPerfTracer:      triggers: (rate: 16:564) (compose: 0:1) (post: 0:1) (render: 0:2) (18:809 frames) (19:889)
03-15 19:12:25.702   281   281 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb7bb0340): 1:12)* (DimLayer (0xb7c3a670): 1:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7c3cd30): 0:34)- (StatusBar (0xb7bff178): 18:106) (NavigationBar (0xb7c00e90): 13:32) (com.android.systemui.ImageWallpaper (0xb7c065a0): 0:7)* (Starting com.motorola.ccc.ota (0xb7c2ba68): 0:33)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c635b8): 18:46) (Starting com.test.thalitest (0xb7c2ba68): 1:4)* 
,03-15 19:12:25.775   885   900 I art     : Explicit concurrent mark sweep GC freed 14577(722KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.714ms total 149.435ms
,03-15 19:12:25.791   885  1249 W libprocessgroup: failed to open /acct/uid_10096/pid_4983/cgroup.procs: No such file or directory
,03-15 19:12:25.810  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:25.820   885   901 I ActivityManager: Killing 3357:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-15 19:12:25.829  5200  5200 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-15 19:12:25.831  5159  5159 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8858-8860)
,03-15 19:12:25.831  5159  5159 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:12:25.863  5159  5159 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9f890ea}
03-15 19:12:25.863  5159  5159 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-15 19:12:25.863  5159  5159 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 19:12:25.880  5159  5159 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 19:12:25.880  5159  5159 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:12:25.882  5159  5159 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 19:12:25.901  5159  5159 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 19:12:25.907  5159  5159 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 19:12:25.907  5159  5159 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 19:12:25.908  5159  5159 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:12:25.908  5159  5159 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:12:25.908  5159  5159 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:12:25.908  5159  5159 I Adreno-EGL: Local Branch: 
03-15 19:12:25.908  5159  5159 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:12:25.908  5159  5159 I Adreno-EGL: Local Patches: NONE
03-15 19:12:25.908  5159  5159 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:12:25.922   885  1814 W libprocessgroup: failed to open /acct/uid_10049/pid_3357/cgroup.procs: No such file or directory
,03-15 19:12:25.977   885  1141 D BluetoothManagerService: Message: 20
03-15 19:12:25.977   885  1141 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bd1f0b3:true
,03-15 19:12:26.016  2863  2863 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-15 19:12:26.016  2863  2863 D 3CDM.DeviceAdminPushReceiver: Type: null
,03-15 19:12:26.016  2863  2863 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-15 19:12:26.026  5200  5238 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-15 19:12:26.028  2863  2919 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-15 19:12:26.028  2863  2919 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-15 19:12:26.028  2863  2919 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-15 19:12:26.028  2863  2919 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-15 19:12:26.029  2863  2919 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
,03-15 19:12:26.029  2863  2919 D 3CDM.Service: blur.service.cred.locationToken = null
03-15 19:12:26.029  2863  2919 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-15 19:12:26.029  2863  2919 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-15 19:12:26.029  2863  2919 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-15 19:12:26.029  2863  2919 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-15 19:12:26.034  2863  2919 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-15 19:12:26.039   885   885 V AlarmManager: done {36ddcf1b, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [11721ms]
,03-15 19:12:26.047  5176  5239 E SQLiteLog: (284) automatic index on view_events(_id)
,03-15 19:12:26.084   885   900 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=5240 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:26.095  2863  2919 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-15 19:12:26.128  5077  5103 I Gmail   : getAccountsCursor
,03-15 19:12:26.132  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:26.193  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:12:26.194  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:26.195  5240  5240 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-15 19:12:26.200  5159  5159 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:12:26.215  5159  5159 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 19:12:26.233  5159  5159 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-15 19:12:26.252  5159  5159 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 19:12:26.252  5159  5159 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:12:26.301   885   885 V AlarmManager: done {3dc32a26, *alarm*:android.content.jobscheduler.JOB_DELAY_EXPIRED} [10741ms]
,03-15 19:12:26.320  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:26.323  5159  5268 D OpenGLRenderer: Render dirty regions requested: true
03-15 19:12:26.333  5240  5240 I AnalyticsLogBase: PlayLogger.onLoggerConnected
03-15 19:12:26.338  5159  5159 D Atlas   : Validating map...
03-15 19:12:26.343  5159  5232 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-15 19:12:26.370   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=29.96 rxSuccessRate=26.64 targetRoamBSSID=any RSSI=-48
03-15 19:12:26.370   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458065546370 interval=20000 maxinterval=300000
03-15 19:12:26.370   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458065546370 interval=20000 maxinterval=300000
03-15 19:12:26.370   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-15 19:12:26.370   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-15 19:12:26.371   885  1240 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-15 19:12:26.371  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-15 19:12:26.372   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 19:12:26.372   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
03-15 19:12:26.372   885  1240 E WifiStateMachine: [1,458,065,546,372 ms] noteScanstart no scan source
03-15 19:12:26.373   885   885 V AlarmManager: done {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN} [10567ms]
,03-15 19:12:26.375  2863  2922 I SundryService: onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
03-15 19:12:26.375  2863  2922 I SundryService: Received shoulder tap
,03-15 19:12:26.378   885   885 V AlarmManager: done {3d7e3248, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10424ms]
,03-15 19:12:26.390  5159  5268 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 19:12:26.396  5159  5268 D OpenGLRenderer: Enabling debug mode 0
,03-15 19:12:26.431   470   505 D TCMD    : NL - Read 56 bytes from update socket.
03-15 19:12:26.431   470   505 D TCMD    : NL - message type is RTM_NEWLINK
03-15 19:12:26.431   470   505 D TCMD    : Listening for incoming client connection request
,03-15 19:12:26.432   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 19:12:26.432   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-15 19:12:26.437   885  1651 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=5277 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:26.438   885  1240 E WifiStateMachine: [1,458,065,546,438 ms] noteScanEnd no scan source
,03-15 19:12:26.441   885  1240 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@235f81fe sup_state=COMPLETED debouncing=false
,03-15 19:12:26.460  3296  3317 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-15 19:12:26.472  1421  1421 I Keyboard.Facilitator: onFinishInput()
,03-15 19:12:26.484   885  1142 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1341
,03-15 19:12:26.484   885  1142 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s342ms
,03-15 19:12:26.605   885  1597 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=5306 uid=10054 gids={50054, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:26.629  5159  5305 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-15 19:12:26.629  5159  5305 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-15 19:12:26.647  2863  2922 D WaitableIntentService: setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,03-15 19:12:26.658  2863  2922 D GetNotificationsWS: GetNotificationsWS.Request: message={"request":{"wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","requestFormat":"json","httpMethod":"post","baseUrl":"v1\/gns\/list\/messages","isSecure":true,"useOAuth":true,"retries":"-1","appendDeviceId":true,"queryParams":{"appid":"6R1TANEX3ZMQ6EU1UH43P34C8B868KTE"},"payload":{"type":"json","data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}"}}}
,03-15 19:12:26.659  2863  2922 D GetNotificationsWS: sendAidlRequest(): was sent by CCE successfully!
,03-15 19:12:26.662  2863  2922 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=2
03-15 19:12:26.662  2863  2922 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
,03-15 19:12:26.662  2863  2922 D WaitableIntentService: setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
03-15 19:12:26.662  2863  2922 D SundryService: onHandleIntent(): isWaitEnabled=true
03-15 19:12:26.662  2863  2922 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=1
,03-15 19:12:26.665  2863  3555 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,03-15 19:12:26.676  5159  5159 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5159
,03-15 19:12:26.751  2863  3555 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-15 19:12:26.753  2863  3555 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:12:26.818  5306  5306 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,03-15 19:12:26.829  5306  5306 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,03-15 19:12:26.834  5306  5306 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,03-15 19:12:26.839  5306  5306 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,03-15 19:12:26.891   885  1597 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=5339 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-15 19:12:26.924  5176  5176 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 19:12:26.924  5176  5176 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 19:12:26.927   885  1488 I ActivityManager: Killing 5003:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-15 19:12:26.992   885  1597 W libprocessgroup: failed to open /acct/uid_10055/pid_5003/cgroup.procs: No such file or directory
,03-15 19:12:27.128  4154  4169 I art     : Explicit concurrent mark sweep GC freed 3962(166KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 563us total 31.427ms
,03-15 19:12:27.149   281   744 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (27:201 vsyncs) (29:957)
,03-15 19:12:27.158  5159  5268 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-15 19:12:27.158  5159  5268 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-15 19:12:27.180   885  1249 I ActivityManager: Killing 5038:com.google.android.music:main/u0a80 (adj 15): empty #7
,03-15 19:12:27.233   885  1303 W libprocessgroup: failed to open /acct/uid_10080/pid_5038/cgroup.procs: No such file or directory
,03-15 19:12:27.312   885  1620 I ActivityManager: Killing 5105:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-15 19:12:27.321  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:27.391   885  1556 W libprocessgroup: failed to open /acct/uid_10060/pid_5105/cgroup.procs: No such file or directory
,03-15 19:12:27.446  5159  5159 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 19:12:27.562   885  1620 I ActivityManager: Killing 5077:com.google.android.gm/u0a63 (adj 15): empty #7
,03-15 19:12:27.574  5159  5295 D jxcore_app_log: JniHelper::setJavaVM(0xb8174310), pthread_self() = -1202874640
,03-15 19:12:27.584  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 19:12:27.584  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 19:12:27.584  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 19:12:27.584  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 19:12:27.584  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 19:12:27.585  5159  5295 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11f16316 added. We now have 1 listener(s)
,03-15 19:12:27.624   885  1488 W libprocessgroup: failed to open /acct/uid_10063/pid_5077/cgroup.procs: No such file or directory
,03-15 19:12:27.768   885  1303 I art     : Explicit concurrent mark sweep GC freed 11964(588KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.134ms total 136.910ms
03-15 19:12:27.768   885  1597 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 19:12:27.773  5159  5295 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-15 19:12:27.777  5159  5295 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-15 19:12:27.778  5159  5295 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-15 19:12:27.778  5159  5295 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-15 19:12:27.780  5159  5295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 19:12:27.790  5159  5295 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d315e6d added. We now have 1 listener(s)
,03-15 19:12:27.790  5159  5295 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 19:12:27.794  1957  5382 D GmsModuleFndr: Beginning GMS chimera module scan
,03-15 19:12:27.796  1957  5382 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-15 19:12:27.797  1957  5382 D GmsModuleFndr: Module pkg com.google.android.projection.gearhead not installed, skipping
,03-15 19:12:27.798   885  1243 D WifiService: New client listening to asynchronous messages
,03-15 19:12:27.803  5339  5381 I GservicesUpdateTask: Updating Gservices keys
,03-15 19:12:27.805  5159  5295 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-15 19:12:27.816  5159  5295 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-15 19:12:27.816  5159  5295 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-15 19:12:27.821  5159  5295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-15 19:12:27.821   885  1537 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 19:12:27.821  1957  5382 D ChimeraCfgMgr: Beginning module configuration check
,03-15 19:12:27.824  5159  5295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-15 19:12:27.829  1957  5384 I CheckinService: Checking schedule, now: 1458065547829 next: 1458666676472
03-15 19:12:27.829  1957  5384 I CheckinService: active receiver: disabled
03-15 19:12:27.829  1957  1957 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 19:12:27.836  5159  5295 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 19:12:27.836  5159  5295 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 19:12:27.836  5159  5295 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 19:12:27.841  5159  5159 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 19:12:27.843  5159  5159 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 19:12:27.844  1957  1957 D SystemUpdateService: onCreate
,03-15 19:12:27.848  1957  1957 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-15 19:12:27.853  1957  5382 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-15 19:12:27.861  2863  3555 D MMApiWSBase: doRequest(): v1/gns/list/messages resp length: 1363
,03-15 19:12:27.863  2863  3555 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
03-15 19:12:27.865  2863  3555 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
,03-15 19:12:27.878  5159  5159 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 19:12:27.887  2863  3555 D Checkin : publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
03-15 19:12:27.888  1957  5387 I SystemUpdateService: cancelUpdate (empty URL)
,03-15 19:12:27.888  1957  5387 I SystemUpdateService: active receiver: disabled
,03-15 19:12:27.888  2863  3555 D SundryService: handleGetNotificationsResponse(): got 0; more=false
,03-15 19:12:28.066  4154  4170 I art     : Explicit concurrent mark sweep GC freed 2946(115KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 493us total 24.578ms
,03-15 19:12:28.172  1957  1957 I art     : Explicit concurrent mark sweep GC freed 5697(345KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.082ms total 60.487ms
,03-15 19:12:28.184  1957  1970 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-15 19:12:28.252  1957  1957 D SystemUpdateService: onDestroy
,03-15 19:12:28.304  1957  1957 W DynamiteLoaderImpl: Failed to load module version: module com.google.android.gms.flags not found
03-15 19:12:28.304  1957  1957 I DynamiteModule: Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
03-15 19:12:28.307  1957  1957 I DynamiteModule: Selected local version of com.google.android.gms.flags
,03-15 19:12:28.366  1957  1957 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,03-15 19:12:28.377  1957  1957 I OcrUtils: Updating ocr activity enabled=false
,03-15 19:12:28.442  2863  2893 W DataUsage: invalid counter update blocked: 'err' by 0
,03-15 19:12:28.442  2863  2893 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:12:28.520   885  1488 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,03-15 19:12:28.532  1957  1957 D OcrModelManager: Updating downloaded model state (gservices changed)
,03-15 19:12:28.591  4154  4242 I art     : Explicit concurrent mark sweep GC freed 2557(99KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 499us total 27.489ms
,03-15 19:12:28.730   885  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-15 19:12:28.817  1784  1784 I art     : Explicit concurrent mark sweep GC freed 14159(889KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.074ms total 81.685ms
,03-15 19:12:28.834  1784  2563 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,03-15 19:12:29.106  1784  1784 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,03-15 19:12:29.109  1784  1784 I GCoreUlr: DispatchingService.onCreate()
,03-15 19:12:29.140   885  1538 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver: pid=5413 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:29.159   325   325 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.167ms
,03-15 19:12:29.179   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 19.596ms
,03-15 19:12:29.204   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 24.497ms
,03-15 19:12:29.210  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:12:29.211  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:29.241  4154  4170 I art     : Explicit concurrent mark sweep GC freed 2763(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 508us total 26.954ms
,03-15 19:12:29.271  1784  5430 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,03-15 19:12:29.280  1784  2032 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-15 19:12:29.293  1784  5410 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,03-15 19:12:29.323  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:29.398  1784  5410 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,03-15 19:12:29.400  1784  1784 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,03-15 19:12:29.412  1784  5430 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-15 19:12:29.416  1784  5430 I GCoreUlr: Unbound from all location providers
03-15 19:12:29.416  1784  5430 I GCoreUlr: Place inference reporting - stopped
,03-15 19:12:29.436  1784  1784 I GCoreUlr: DispatchingService.onDestroy()
03-15 19:12:29.436  1784  1784 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-15 19:12:29.441  1784  1784 I GCoreUlr: Unbound from all location providers
,03-15 19:12:29.441  1784  1784 I GCoreUlr: Place inference reporting - stopped
,03-15 19:12:29.688  5159  5386 W jxcore-log: Initializing JXcore engine
03-15 19:12:29.688  5159  5386 W jxcore-log: JXcore engine is ready
,03-15 19:12:29.762   885  1537 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5437 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-15 19:12:29.763   885  1537 I ActivityManager: Killing 5176:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-15 19:12:29.769  5386  5386 W Thread-540: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9661]" dev="sockfs" ino=9661 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-15 19:12:29.769  5386  5386 W Thread-540: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-15 19:12:29.769  5386  5386 W Thread-540: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[8483]" dev="sockfs" ino=8483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-15 19:12:29.769  5386  5386 W Thread-540: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22949]" dev="sockfs" ino=22949 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-15 19:12:29.800  5159  5386 W jxcore-log: Starting JXcore engine
,03-15 19:12:29.871   885  1488 W libprocessgroup: failed to open /acct/uid_10005/pid_5176/cgroup.procs: No such file or directory
,03-15 19:12:29.891  5437  5437 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:12:29.940  5159  5386 W jxcore-log: Platform android
03-15 19:12:29.940  5159  5386 W jxcore-log: 
,03-15 19:12:29.941  5159  5386 W jxcore-log: Process ARCH arm
03-15 19:12:29.941  5159  5386 W jxcore-log: 
,03-15 19:12:30.154  5437  5459 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-15 19:12:30.154  5437  5459 I Babel_SMS: MmsConfig.loadMmsSettings
03-15 19:12:30.155  5437  5459 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-15 19:12:30.155  5437  5459 I Babel_SMS: MmsConfig.loadFromDatabase
,03-15 19:12:30.168  5437  5459 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-15 19:12:30.168  5437  5459 I Babel_SMS: MmsConfig.loadFromResources
,03-15 19:12:30.171  5437  5459 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-15 19:12:30.172  5437  5459 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-15 19:12:30.285  5437  5437 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-15 19:12:30.289  5437  5437 I Babel_Crash: startup - clean
,03-15 19:12:30.318  5437  5466 I Babel   : deleted: false for 0
,03-15 19:12:30.443   885  1303 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5468 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:30.500  5437  5437 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:12:30.508  5437  5437 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-15 19:12:30.512  5437  5437 W VideoCapabilities: Unsupported mime video/mpeg2
,03-15 19:12:30.569   885  1303 I ActivityManager: Killing 5200:com.motorola.context/u0a8 (adj 15): empty #7
,03-15 19:12:30.578  5468  5468 D PhoneMonitor: Register our PhoneStateListener
,03-15 19:12:30.583  5437  5437 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-15 19:12:30.592  5437  5437 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:12:30.599  5437  5437 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 19:12:30.603  5437  5437 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:12:30.608  5437  5437 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:12:30.637  5159  5386 I jxcore-log: JXcore Cordova bridge is ready!
03-15 19:12:30.637  5159  5386 I jxcore-log: 
,03-15 19:12:30.637  5159  5386 W jxcore-log: JXcore engine is started
,03-15 19:12:30.642  5159  5295 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 19:12:30.652  5159  5386 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 19:12:30.652  5159  5386 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 19:12:30.658  5159  5159 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 19:12:30.751   885  4415 W libprocessgroup: failed to open /acct/uid_10008/pid_5200/cgroup.procs: No such file or directory
,03-15 19:12:30.754   885  1814 I ActivityManager: Killing 5306:com.google.android.configupdater/u0a54 (adj 15): empty #7
,03-15 19:12:30.841   885  1229 V AlarmManager: send {3fa57dd8, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-15 19:12:30.844  5437  5437 I vclib   : onServiceConnected
,03-15 19:12:30.844  5437  5437 W Babel   : Attempted to change video mute state without an active call.
,03-15 19:12:30.862  5159  5295 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 203ms. Plugin should use CordovaInterface.getThreadPool().
03-15 19:12:30.862  1482  4186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 19:12:30.871   885  1538 W libprocessgroup: failed to open /acct/uid_10054/pid_5306/cgroup.procs: No such file or directory
,03-15 19:12:30.877  1482  4186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 19:12:30.887  2863  2863 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-15 19:12:30.891  2863  2863 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-15 19:12:30.893  2863  2863 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 19:12:30.896  2863  2863 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-15 19:12:30.899  2863  2863 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 19:12:30.905  2863  2863 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-15 19:12:30.906  2863  2863 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-15 19:12:30.907  5468  5468 V SetupWizard: Connected to Gservices successfully
03-15 19:12:30.907  2863  2863 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-15 19:12:30.930   885  1556 I ActivityManager: Killing 5277:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 19:12:30.939  5159  5159 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-15 19:12:30.939  1421  1421 I Keyboard.Facilitator: onFinishInput()
,03-15 19:12:30.983   885  1466 W libprocessgroup: failed to open /acct/uid_10019/pid_5277/cgroup.procs: No such file or directory
,03-15 19:12:30.986   885  1142 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,7174
03-15 19:12:30.986   885  1142 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5844 (total)
,03-15 19:12:30.997  2863  2922 I SundryService: onHandleIntent(): action=com.motorola.notification.RETREIVE_NOTIFICATIONS
03-15 19:12:30.997  2863  2922 I SundryService: Received shoulder tap
,03-15 19:12:31.059  2863  2922 D WaitableIntentService: setWaitEnabled(): mWaitCount=2 isWaitEnabled=true
,03-15 19:12:31.065  2863  2922 D GetNotificationsWS: GetNotificationsWS.Request: message={"request":{"wsReqId":"com.motorola.ccc.notification.GetNotificationsWS.Request","requestFormat":"json","httpMethod":"post","baseUrl":"v1\/gns\/list\/messages","isSecure":true,"useOAuth":true,"retries":"-1","appendDeviceId":true,"queryParams":{"appid":"6R1TANEX3ZMQ6EU1UH43P34C8B868KTE"},"payload":{"type":"json","data":"{\"appidNotifStoreMessageidPageSizeList\":[{\"appid\":\"OCVKVSQ5Q1EYVBX76813UOPTCKGAH4VS\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"LX6TJJI6F2MILF1NPZW6A3HBAKK8W44Z\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"L71KGK4CCWOW658MGESIRYO2428ODW11\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SZZTNOGZA6O6PRFZH2V3FF14N1J8W3HC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"SULIGJDMXLSL7T1DOVYSTVG2KCBHZ5GH\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"RCEAZODHQBX3UTIE62BUQ6T6TXXI6JSR\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"TESULHNZGDWZ5T3EMNZRTVE51RR7EUXC\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"5LWTCLJBZO4OUDU5BY7ANJI4Y2MHY8OY\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"68OUD4VKG23F7BUH6M2QBRXPLIC7IMCO\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"6U5KK17SNFB416J4SYG7LC6HYFNOPYM8\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"QZYSBKU4MGE71O1PLTE8HAT11SWL5M6E\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"B642GFV24HEMEDQNCF3ZED8BIUMPCBOM\",\"pageSize\":100,\"notifStoreMessageid\":0},{\"appid\":\"XX274VEJBOVSSPHDKHSPURVRQ1YT5VEM\",\"pageSize\":100,\"notifStoreMessageid\":0}]}"}}}
,03-15 19:12:31.068   885  1651 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5494 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
03-15 19:12:31.076  2863  2922 D GetNotificationsWS: sendAidlRequest(): was sent by CCE successfully!
03-15 19:12:31.076  2863  2922 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=2
03-15 19:12:31.086  2863  2985 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
03-15 19:12:31.089  1784  2704 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 19:12:31.123  5437  5437 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 19:12:31.123  5437  5437 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:12:31.212  2863  2985 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/gns/list/messages.json/2072049230914535424?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
03-15 19:12:31.213  2863  2985 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:12:31.224  5437  5437 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:12:31.244  5240  5262 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-15 19:12:31.285   281   281 I SFPerfTracer:      triggers: (rate: 16:567) (compose: 0:1) (post: 0:1) (render: 0:2) (14:899 frames) (15:998)
03-15 19:12:31.285   281   281 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb7bb0340): 0:17)* (DimLayer (0xb7c3a670): 1:6) (StatusBar (0xb7bff178): 15:123) (NavigationBar (0xb7c00e90): 12:45) (com.android.systemui.ImageWallpaper (0xb7c065a0): 0:7)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c635b8): 0:55)- (Starting com.test.thalitest (0xb7c2ba68): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7c3d710): 15:69) (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c2ba68): 1:4)* 
,03-15 19:12:31.287   885  1249 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5518 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:31.296  5494  5515 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-15 19:12:31.297  5240  5262 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 19:12:31.328  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:31.337  5437  5437 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-15 19:12:31.338  5437  5437 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:12:31.495   885  1620 I art     : Explicit concurrent mark sweep GC freed 17608(873KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 21MB/32MB, paused 1.824ms total 139.935ms
,03-15 19:12:31.525  5518  5518 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 19:12:31.526  5518  5518 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-15 19:12:31.526  5518  5518 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:12:31.529  5518  5518 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 19:12:31.532   885   901 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5537 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:31.577  5537  5537 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 19:12:31.613  5537  5537 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1172e6bf(com.android.providers.calendar.CalendarProvider2@26f4a18c)
,03-15 19:12:31.697  5339  5560 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-15 19:12:31.703  1574  1574 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@7d0eeb7 new=com.google.android.velvet.VelvetApplication@7d0eeb7
,03-15 19:12:31.728  1957  5563 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 19:12:31.730  1957  5563 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-15 19:12:31.735   281   281 I SFPerfTracer:      triggers: (rate: 16:568) (compose: 0:1) (post: 0:1) (render: 0:3) (18:923 frames) (19:1024)
03-15 19:12:31.735   281   281 D SFPerfTracer:        layers: (4:10) (FocusedStackFrame (0xb7bb0340): 0:17)* (DimLayer (0xb7c3a670): 0:6) (StatusBar (0xb7bff178): 0:125) (NavigationBar (0xb7c00e90): 0:45) (com.android.systemui.ImageWallpaper (0xb7c065a0): 0:7)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb7c3d710): 2:78)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c2ba68): 19:27) 
,03-15 19:12:31.758   885  1814 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5565 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:31.781  1957  2033 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-15 19:12:31.798   885  1556 I ActivityManager: Killing 5240:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-15 19:12:31.807  1957  5563 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 19:12:31.812  5565  5565 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:12:31.877  5339  5560 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
,03-15 19:12:31.900   885  1651 W libprocessgroup: failed to open /acct/uid_10049/pid_5240/cgroup.procs: No such file or directory
,03-15 19:12:31.909   885  1556 I ActivityManager: Killing 5468:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 19:12:31.929  5159  5159 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@e189aa2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:12:31.929  5159  5159 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@e189aa2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 19:12:31.929  5159  5159 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 19:12:32.062   885  1651 W libprocessgroup: failed to open /acct/uid_10035/pid_5468/cgroup.procs: No such file or directory
,03-15 19:12:32.065  5159  5159 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3ae36333 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:12:32.065  5159  5159 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3ae36333 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 19:12:32.065  5159  5159 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 19:12:32.125   885  1556 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5591 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:32.217  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:32.217  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:32.237   885  1651 I ActivityManager: Killing 4154:com.google.process.gapps/u0a16 (adj 15): empty #7
,03-15 19:12:32.267  2863  2985 D MMApiWSBase: doRequest(): v1/gns/list/messages resp length: 1363
,03-15 19:12:32.268  2863  2985 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=com.motorola.ccc.notification.GetNotificationsWS.Request
,03-15 19:12:32.269  2863  2985 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
,03-15 19:12:32.281  2863  2985 D Checkin : publish the event [tag = MOT_CCE_STATS event name = RetrieveNotifications]
,03-15 19:12:32.282  2863  2985 D SundryService: handleGetNotificationsResponse(): got 0; more=false
,03-15 19:12:32.291   885  1303 W libprocessgroup: failed to open /acct/uid_10016/pid_4154/cgroup.procs: No such file or directory
,03-15 19:12:32.329  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:32.364   885  1620 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5614 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 19:12:32.410  5614  5614 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,03-15 19:12:32.499  5614  5614 I GoogleHttpClient: GMS http client unavailable, use old client
,03-15 19:12:32.516  5614  5614 I GoogleHttpClient: GMS http client unavailable, use old client
,03-15 19:12:32.626  5537  5537 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 19:12:32.626  5537  5537 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 19:12:32.630   885   900 I ActivityManager: Killing 5413:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-15 19:12:32.642  5591  5591 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 19:12:32.681   885  1538 W libprocessgroup: failed to open /acct/uid_10088/pid_5413/cgroup.procs: No such file or directory
,03-15 19:12:32.785  5591  5591 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 19:12:32.805  5591  5591 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:12:32.808  5591  5591 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:12:32.841  2863  2893 W DataUsage: invalid counter update blocked: 'err' by 0
,03-15 19:12:32.842  2863  2893 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:12:32.879  5591  5659 D Ads     : Skipping gmscore version check
,03-15 19:12:32.882  5591  5591 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-15 19:12:32.882  5591  5591 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
03-15 19:12:32.884   885  1620 I ActivityManager: Killing 5537:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-15 19:12:32.911   885  1651 W libprocessgroup: failed to open /acct/uid_10005/pid_5537/cgroup.procs: No such file or directory
,03-15 19:12:32.964   885  1303 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5661 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
03-15 19:12:32.965   885  1303 I ActivityManager: Killing 5518:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 19:12:33.002   885  1597 W libprocessgroup: failed to open /acct/uid_10027/pid_5518/cgroup.procs: No such file or directory
,03-15 19:12:33.015  5591  5591 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 19:12:33.021  5661  5661 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-15 19:12:33.042  5591  5591 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 19:12:33.102   885  1556 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5680 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:33.111   885  1538 I ActivityManager: Killing 5339:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 19:12:33.144   885  1466 W libprocessgroup: failed to open /acct/uid_10039/pid_5339/cgroup.procs: No such file or directory
,03-15 19:12:33.169  1957  2033 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
03-15 19:12:33.174  5680  5680 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-15 19:12:33.237  1957  2033 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-15 19:12:33.245   885  1597 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5700 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:33.266   325   325 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 21.493ms
,03-15 19:12:33.291   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 23.873ms
,03-15 19:12:33.301  1957  2033 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 19:12:33.309  5700  5700 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 19:12:33.317   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 23.981ms
,03-15 19:12:33.330  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:33.344  5700  5700 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1172e6bf(com.android.providers.calendar.CalendarProvider2@26f4a18c)
,03-15 19:12:33.357  5680  5680 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-15 19:12:33.413   885  4415 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5733 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:33.492   314   414 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-15 19:12:33.519   885  1537 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5755 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:33.533   885  1537 I ActivityManager: Killing 5159:com.test.thalitest/u0a109 (adj 15): empty #7
,03-15 19:12:33.573   885  1243 D WifiService: Client connection lost with reason: 4
,03-15 19:12:33.646   885  1597 W libprocessgroup: failed to open /acct/uid_10109/pid_5159/cgroup.procs: No such file or directory
,03-15 19:12:33.659  5755  5755 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 19:12:33.659  5755  5755 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-15 19:12:33.660  5755  5755 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:12:33.660  5755  5755 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 19:12:33.742   885   900 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5782 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-15 19:12:33.751   885  1537 I ActivityManager: Killing 5565:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-15 19:12:33.791   885  4415 W libprocessgroup: failed to open /acct/uid_10090/pid_5565/cgroup.procs: No such file or directory
,03-15 19:12:33.878  1957  5563 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-15 19:12:33.904  1957  5563 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-15 19:12:33.920  5591  5591 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-15 19:12:33.923   885  1229 V AlarmManager: send {2108f26b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,03-15 19:12:33.924   885  1229 V AlarmManager: send {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 19:12:33.924   885   885 V AlarmManager: done {2108f26b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [7ms]
,03-15 19:12:33.943  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:33.950  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:33.952  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:34.064  1957  1957 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-15 19:12:34.223  5782  5799 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-15 19:12:34.308  1957  5818 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-15 19:12:34.337   885  1537 I art     : Explicit concurrent mark sweep GC freed 11995(571KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.627ms total 139.562ms
,03-15 19:12:34.358  5700  5700 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 19:12:34.358  5700  5700 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 19:12:34.369  1957  1957 D AsyncTaskServiceImpl: Submit a task: k
,03-15 19:12:34.384  1957  5827 D k       : Processing package: com.test.thalitest
,03-15 19:12:34.400  1957  5827 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-15 19:12:34.400  1957  5827 D k       : Found info for package com.test.thalitest in db.
,03-15 19:12:34.455   885  1651 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5830 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-15 19:12:34.517  1957  5824 W BaseAppContext: Using Auth Proxy for data requests.
03-15 19:12:34.517  1957  5824 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:12:34.523  1957  5824 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:12:34.531  1957  5824 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:12:34.545  1957  5824 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:12:34.685  5782  5799 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 461 ms] updated apps [took 461 ms] 
,03-15 19:12:34.687   885  1651 I ActivityManager: Killing 5661:com.motorola.context/u0a8 (adj 15): empty #7
,03-15 19:12:34.781   885  1556 W libprocessgroup: failed to open /acct/uid_10008/pid_5661/cgroup.procs: No such file or directory
,03-15 19:12:34.925  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:35.000   885  1259 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-15 19:12:35.075  5591  5645 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-15 19:12:35.075  5591  5645 I qtaguid : Untagging socket 37 failed errno=-22
03-15 19:12:35.075  5591  5645 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 19:12:35.079  5591  5591 D Finsky  : [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,03-15 19:12:35.163  5830  5830 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-15 19:12:35.163  5830  5830 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 19:12:35.163  5830  5830 I GAv4    :   adb logcat -s GAv4
,03-15 19:12:35.176   885  1620 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5870 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 19:12:35.241  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:35.245  5830  5830 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-15 19:12:35.245  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:12:35.245  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:35.267  5870  5870 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 19:12:35.269  5870  5870 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:12:35.276  5830  5830 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:12:35.282  5830  5892 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:12:35.302  5830  5830 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-15 19:12:35.324  5870  5870 I MultiDex: VM with version 2.1.0 has multidex support
03-15 19:12:35.325  5870  5870 I MultiDex: install
03-15 19:12:35.325  5870  5870 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 19:12:35.333  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:35.344  5830  5894 E SQLiteLog: (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,03-15 19:12:35.353  5870  5870 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:12:35.365   885  1229 V AlarmManager: send {2b76c996, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-15 19:12:35.376  1957  1978 I art     : Explicit concurrent mark sweep GC freed 57964(4MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 14MB/19MB, paused 1.197ms total 96.938ms
,03-15 19:12:35.420  5870  5870 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-15 19:12:35.420  5870  5870 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3689beee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 19:12:35.420  5870  5870 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:12:35.433  5870  5870 D ChimeraCfgMgr: Reading stored module config
,03-15 19:12:35.485   280   390 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-15 19:12:35.485   280   390 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:12:35.486  5830  5900 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-15 19:12:35.498  1957  2033 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-15 19:12:35.542  5830  5902 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:12:35.542  5830  5902 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:12:35.556   885  1620 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5904 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:35.588  5870  5897 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-15 19:12:35.637  5904  5904 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:12:35.682  5830  5902 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-15 19:12:35.688  5870  5870 D CAR.SERVICE: Connecting to CarCallService...
,03-15 19:12:35.705  1957  2033 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 19:12:35.707  1957  2033 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-15 19:12:35.715  5870  5870 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 19:12:35.715  5870  5870 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 19:12:35.766  5830  5902 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 19:12:35.766  5830  5902 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:12:35.770  5870  5870 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-15 19:12:35.774   885  1537 I ActivityManager: Killing 5700:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-15 19:12:35.795  5870  5870 D CAR.TEL.Service: Creating a new CarCallService.
,03-15 19:12:35.797  5870  5870 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-15 19:12:35.934   885  1814 W libprocessgroup: failed to open /acct/uid_10005/pid_5700/cgroup.procs: No such file or directory
,03-15 19:12:35.939  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:35.942   885  1556 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-15 19:12:35.946  5870  5870 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@39cfaf9b
,03-15 19:12:35.951   885   901 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-15 19:12:35.952  5870  5870 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-15 19:12:35.952  5870  5870 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-15 19:12:35.955  1957  2033 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-15 19:12:36.021  5591  5591 D Finsky  : [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,03-15 19:12:36.049  5591  5644 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-15 19:12:36.049  5591  5644 I qtaguid : Untagging socket 37 failed errno=-22
03-15 19:12:36.049  5591  5644 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 19:12:36.053   885  1249 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5936 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:36.068  5870  5887 D CAR.SERVICE: Package validated; name: com.android.vending
,03-15 19:12:36.118  5591  5591 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,03-15 19:12:36.131   885  1651 I ActivityManager: Killing 5733:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 19:12:36.214  5936  5957 I Gmail   : getAccountsCursor
,03-15 19:12:36.281   885   901 W libprocessgroup: failed to open /acct/uid_10019/pid_5733/cgroup.procs: No such file or directory
,03-15 19:12:36.282  5936  5958 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-15 19:12:36.288  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:36.327   885  4415 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5960 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:36.402   885  1814 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-15 19:12:36.406  5936  5981 I Gmail   : Observing account changes for notifications
,03-15 19:12:36.412  5936  5936 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-15 19:12:36.427  5960  5960 I Exchange: EasService.onCreate
,03-15 19:12:36.432  5960  5983 I Exchange: RestartPingTask
,03-15 19:12:36.452  5960  5960 I Exchange: RestartPingsTask did not start any pings.
03-15 19:12:36.452  5960  5960 I Exchange: PSS stopIfIdle
,03-15 19:12:36.453  5960  5960 I Exchange: PSS has no active accounts; stopping service.
,03-15 19:12:36.454   885   900 I ActivityManager: Killing 5437:com.google.android.talk/u0a70 (adj 15): empty #7
,03-15 19:12:36.581   885  1151 W PackageSettings: Skipping PackageSetting{1421c02d com.example.hello/10568} due to missing metadata
,03-15 19:12:36.591   885  1249 W libprocessgroup: failed to open /acct/uid_10070/pid_5437/cgroup.procs: No such file or directory
,03-15 19:12:36.604  5936  5990 I Gmail   : getAccountsCursor
03-15 19:12:36.604  5960  5960 I Exchange: onDestroy
,03-15 19:12:36.614   885  1814 I ActivityManager: Killing 5755:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 19:12:36.615  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:36.661   885   901 W libprocessgroup: failed to open /acct/uid_10027/pid_5755/cgroup.procs: No such file or directory
,03-15 19:12:36.679  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:12:36.679  2863  2863 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
03-15 19:12:36.680  2863  2863 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-15 19:12:36.700  1296  1816 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-15 19:12:36.729  5936  6000 E SQLiteLog: (283) recovered 22 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 19:12:36.738   885  1556 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6002 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:12:36.793   885  4415 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6023 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-15 19:12:36.814   885  4415 I ActivityManager: Killing 5782:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 19:12:36.834  6002  6002 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 19:12:36.911   885  1620 W libprocessgroup: failed to open /acct/uid_10039/pid_5782/cgroup.procs: No such file or directory
,03-15 19:12:36.920  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:36.928  6002  6002 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@1172e6bf(com.android.providers.calendar.CalendarProvider2@26f4a18c)
,03-15 19:12:36.936  6023  6023 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-15 19:12:36.958   885  1303 I art     : Explicit concurrent mark sweep GC freed 16610(1054KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 21MB/32MB, paused 2.140ms total 138.566ms
,03-15 19:12:36.961  5936  6001 I Gmail   : notifyAccountChanged
,03-15 19:12:36.964  5936  5988 I Gmail   : getAccountsCursor
,03-15 19:12:36.969  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:36.977  5936  6001 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:12:36.979  1296  1296 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
,03-15 19:12:36.994  5936  6001 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:12:37.005  5936  6001 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 19:12:37.006  5936  6001 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 19:12:37.038   885  4415 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6046 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:37.039   885  4415 I ActivityManager: Killing 5830:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-15 19:12:37.062   325   325 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 365us total 23.840ms
,03-15 19:12:37.083   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.377ms
,03-15 19:12:37.104   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.033ms
,03-15 19:12:37.111   885  1597 W libprocessgroup: failed to open /acct/uid_10057/pid_5830/cgroup.procs: No such file or directory
,03-15 19:12:37.137  6046  6046 D PhoneMonitor: Register our PhoneStateListener
,03-15 19:12:37.142  5936  5958 I Gmail   : getAccountsCursor
,03-15 19:12:37.145  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:37.151   885  1651 I ActivityManager: Killing 5494:android.process.acore/u0a7 (adj 15): empty #7
,03-15 19:12:37.252   885  1556 W libprocessgroup: failed to open /acct/uid_10007/pid_5494/cgroup.procs: No such file or directory
,03-15 19:12:37.273  1784  3605 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 19:12:37.275  2863  2922 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-15 19:12:37.276  2863  2922 D WaitableIntentService: setWaitEnabled(): mWaitCount=1 isWaitEnabled=false
03-15 19:12:37.276  2863  2922 D SundryService: onHandleIntent(): isWaitEnabled=true
03-15 19:12:37.276  2863  2922 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=1
,03-15 19:12:37.277  1957  6064 I CheckinService: Checking schedule, now: 1458065557277 next: 1458065569472
03-15 19:12:37.277  1957  6064 I CheckinService: active receiver: disabled
,03-15 19:12:37.369  1784  1784 I art     : Explicit concurrent mark sweep GC freed 23228(1424KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/23MB, paused 1.030ms total 77.002ms
,03-15 19:12:37.456   885   885 V AlarmManager: done {3fa57dd8, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [6813ms]
,03-15 19:12:37.463  2863  2922 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-15 19:12:37.463  2863  2922 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
03-15 19:12:37.463  6002  6068 E SQLiteLog: (284) automatic index on view_events(_id)
03-15 19:12:37.463  2863  2922 D SundryService: onHandleIntent(): isWaitEnabled=false
03-15 19:12:37.463  2863  2922 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
,03-15 19:12:37.467  2863  2863 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
,03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=18.37 rxSuccessRate=17.58 targetRoamBSSID=any RSSI=-48
03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458065557492 interval=20000 maxinterval=300000
03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458065557492 interval=20000 maxinterval=300000
03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-15 19:12:37.492   885  1240 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-15 19:12:37.493  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-15 19:12:37.493   885   885 V AlarmManager: done {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN} [3576ms]
,03-15 19:12:37.493   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 19:12:37.493   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 19:12:37.496   885  1240 E WifiStateMachine: [1,458,065,557,496 ms] noteScanstart no scan source
,03-15 19:12:37.511   885   885 V AlarmManager: done {2b76c996, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [2146ms]
,03-15 19:12:37.528  1784  1784 D WearableService: callingUid 10016, callindPid: 1784
,03-15 19:12:37.537  1784  4238 E MDM     : [194] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:12:37.538  1957  6072 D LocationInitializer: Restart initialization of location
03-15 19:12:37.539  1784  1784 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 18 
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 18 
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   470   505 D TCMD    : NL - Read 56 bytes from update socket.
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   470   505 D TCMD    : NL - message type is RTM_NEWLINK
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   470   505 D TCMD    : Listening for incoming client connection request
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 5
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 4
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 6
03-15 19:12:37.552   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.552   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:12:37.553   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 19:12:37.553   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-15 19:12:37.554   885  1240 E WifiStateMachine: [1,458,065,557,554 ms] noteScanEnd no scan source
,03-15 19:12:37.555   885  1240 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@235f81fe sup_state=COMPLETED debouncing=false
,03-15 19:12:37.557  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:37.563  5591  5645 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
,03-15 19:12:37.563  5591  5645 I qtaguid : Untagging socket 37 failed errno=-22
03-15 19:12:37.563  5591  5645 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-15 19:12:37.578  1784  2010 W GCoreFlp: No location to return for getLastLocation()
03-15 19:12:37.578  1784  6073 W FusedLocationProvider: location=null
,03-15 19:12:37.612  1784  5189 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 19:12:37.657   885   900 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-15 19:12:37.707  5591  5591 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:12:37.707  5591  5591 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:12:37.885  5591  5591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:12:37.904  5591  5591 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,03-15 19:12:37.911   885  1229 V AlarmManager: send {2e5677fd, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-15 19:12:37.929   885   885 V AlarmManager: done {2e5677fd, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [18ms]
,03-15 19:12:37.933  1784  1803 D DeviceConnectionService: client connected with version: 8296000
,03-15 19:12:37.935  5591  6087 D Finsky  : [614] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 19:12:37.942  5591  5591 D Finsky  : [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-15 19:12:37.942  5591  5591 D Finsky  : [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,03-15 19:12:37.945  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:37.952  6002  6002 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 19:12:37.952  6002  6002 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-15 19:12:37.969   885  1466 I ActivityManager: Killing 5904:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-15 19:12:38.044   885  1814 W libprocessgroup: failed to open /acct/uid_10090/pid_5904/cgroup.procs: No such file or directory
,03-15 19:12:38.203  5680  5699 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-15 19:12:38.213  5680  5699 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 19:12:38.227  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:12:38.228  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:38.649   885  1303 I ActivityManager: Killing 6046:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 19:12:38.664   885  1303 I ActivityManager: Killing 5960:com.google.android.gm.exchange/u0a60 (adj 15): empty #8
,03-15 19:12:38.681   885  1249 W libprocessgroup: failed to open /acct/uid_10035/pid_6046/cgroup.procs: No such file or directory
,03-15 19:12:38.683   885  1538 W libprocessgroup: failed to open /acct/uid_10060/pid_5960/cgroup.procs: No such file or directory
,03-15 19:12:39.168   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=340, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311659, SEQNUM=4436, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9815, POWER_SUPPLY_CHARGE_COUNTER=-134, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:12:39.266  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:12:39.299   281   744 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (37:295 vsyncs) (39:1068)
,03-15 19:12:39.325  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:12:39.371   885  1229 V AlarmManager: send {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 19:12:39.373   885   885 V AlarmManager: done {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM} [2ms]
,03-15 19:12:40.342  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:41.165  5870  5870 D CAR.SERVICE: mConnectedToCar = false, abort
,03-15 19:12:41.178  5870  5870 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2740f052 that was originally bound here
03-15 19:12:41.178  5870  5870 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2740f052 that was originally bound here
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 19:12:41.178  5870  5870 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-15 19:12:41.184  5870  5870 E ActivityThread: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37d6aa95 that was originally bound here
03-15 19:12:41.184  5870  5870 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37d6aa95 that was originally bound here
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-15 19:12:41.184  5870  5870 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,03-15 19:12:41.190   885  1556 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@12a5b097
,03-15 19:12:41.243  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:41.243  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:41.417  5936  5980 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 19:12:43.496   314   414 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-15 19:12:44.259  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:44.259  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:47.273  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:47.274  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:48.338   885  1127 I ActivityManager: Waited long enough for: ServiceRecord{357d6c75 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-15 19:12:48.349  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:49.351  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:50.289  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:50.289  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:51.643   885  1229 V AlarmManager: send {3d93e6a2, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,03-15 19:12:51.657   885  1229 V AlarmManager: send {4c722f0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,03-15 19:12:51.659   885  1229 V AlarmManager: send {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 19:12:51.662   885   885 V AlarmManager: done {4c722f0, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [19ms]
,03-15 19:12:51.678   885   885 V AlarmManager: done {3d93e6a2, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [36ms]
03-15 19:12:51.678   885   885 V AlarmManager: done {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN} [36ms]
,03-15 19:12:51.681   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=3.01 rxSuccessRate=3.83 targetRoamBSSID=any RSSI=-48
03-15 19:12:51.681   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=1458065571681 interval=20000 maxinterval=300000
03-15 19:12:51.681   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=1458065571681 interval=20000 maxinterval=300000
03-15 19:12:51.682   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-15 19:12:51.682   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =30000
03-15 19:12:51.682  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-15 19:12:51.683   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 19:12:51.683   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 19:12:51.685   885  1240 E WifiStateMachine: [1,458,065,571,685 ms] noteScanstart no scan source
,03-15 19:12:51.698  1957  6125 I CheckinService: Checking schedule, now: 1458065571698 next: 1458065569472
03-15 19:12:51.698  1957  6125 I CheckinService: active receiver: enabled
,03-15 19:12:51.713  1957  6125 I CheckinService: Preparing to send checkin request
03-15 19:12:51.713  1957  6125 I EventLogService: Accumulating logs since 1458065528641
,03-15 19:12:51.792  1957  6125 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-15 19:12:51.795  1957  6125 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-15 19:12:51.870  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:51.872  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:51.915  5591  5657 D Finsky  : [605] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,03-15 19:12:51.916  5591  5591 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,03-15 19:12:51.964   885   901 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6131 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-15 19:12:51.996  6131  6131 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:12:51.997  6131  6131 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:12:52.034  6131  6131 I MultiDex: VM with version 2.1.0 has multidex support
,03-15 19:12:52.034  6131  6131 I MultiDex: install
03-15 19:12:52.034  6131  6131 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 19:12:52.054  6131  6131 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:12:52.107  6131  6131 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 19:12:52.108  6131  6131 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3689beee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-15 19:12:52.108  6131  6131 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:12:52.128  1784  1784 D WearableService: callingUid 10016, callindPid: 1784
,03-15 19:12:52.133  1784  2563 E MDM     : [156] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:12:52.143  1784  1784 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:12:52.145  1957  6152 D LocationInitializer: Restart initialization of location
,03-15 19:12:52.163   470   505 D TCMD    : NL - Read 56 bytes from update socket.
03-15 19:12:52.163   470   505 D TCMD    : NL - message type is RTM_NEWLINK
03-15 19:12:52.163   470   505 D TCMD    : Listening for incoming client connection request
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 19 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 19 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 20 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 20 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 21 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 21 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 22 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 22 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 23 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 23 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 24 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 24 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 25 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 25 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 26 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 26 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 27 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 27 
03-15 19:12:52.163   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 19:12:52.163   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-15 19:12:52.166   885  1240 E WifiStateMachine: [1,458,065,572,165 ms] noteScanEnd no scan source
03-15 19:12:52.167  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:12:52.175   885  1240 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@235f81fe sup_state=COMPLETED debouncing=false
,03-15 19:12:52.193  1784  2010 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:12:52.194  1784  6153 W FusedLocationProvider: location=null
,03-15 19:12:52.207  6131  6131 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-15 19:12:52.208  6131  6131 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-15 19:12:52.290  6131  6151 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-15 19:12:52.386   306   306 D WVCdm   : Instantiating CDM.
,03-15 19:12:52.387   306   983 I WVCdm   : CdmEngine::OpenSession
03-15 19:12:52.387   306   983 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-15 19:12:52.394   306   983 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-15 19:12:52.413   306   983 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-15 19:12:52.413   306   983 D DrmWidevineDash: Service_Initialize: starts!
03-15 19:12:52.413   306   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,03-15 19:12:52.413   306   983 D QSEECOMAPI: : App is not loaded in QSEE
03-15 19:12:52.413   306   983 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-15 19:12:52.413   306   983 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 19:12:52.413   306   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 19:12:52.414   306   983 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 19:12:52.414   306   983 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-15 19:12:52.414   306   983 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 19:12:52.414   306   983 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 19:12:52.414   306   983 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 19:12:52.443   306   983 D QSEECOMAPI: : Loaded image: APP id = 3
03-15 19:12:52.444   306   983 D DrmWidevineDash: Service_Initialize: ends! returns 0
,03-15 19:12:52.444   306   983 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee4000
03-15 19:12:52.444   306   983 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee4000
,03-15 19:12:52.451   306   983 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
03-15 19:12:52.451   306   983 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,03-15 19:12:52.452   306   983 D DrmWidevineDash: hlos api version =  9
03-15 19:12:52.452   306   983 D DrmWidevineDash: tz api version =  8
03-15 19:12:52.452   306   983 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 19:12:52.452   306   983 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-15 19:12:52.459   306   983 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
03-15 19:12:52.459   306   983 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,03-15 19:12:52.459   306   983 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb561c960
03-15 19:12:52.460   306   983 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-15 19:12:52.460   306   983 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-15 19:12:52.460   306   983 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7318168, dataLength=8
03-15 19:12:52.460   306   983 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-15 19:12:52.462   306   983 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7250e60, wrapped_rsa_key_length=1280
,03-15 19:12:52.465   306   983 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-15 19:12:52.465   306   983 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-15 19:12:52.466   306  1637 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
03-15 19:12:52.466   306  1637 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-15 19:12:52.466   306  1637 I WVCdm   : CdmEngine::GenerateKeyRequest
03-15 19:12:52.466   306  1637 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7349d70, idLength=0xb12ee730
,03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
03-15 19:12:52.473   306  1637 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 19:12:52.474   306  1637 D DrmWidevineDash: hlos api version =  9
03-15 19:12:52.474   306  1637 D DrmWidevineDash: tz api version =  8
03-15 19:12:52.474   306  1637 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 19:12:52.474   306  1637 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-15 19:12:52.474   306  1637 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-15 19:12:52.474   306  1637 D WVCdm   : PrepareKeyRequest: nonce=1843712210
,03-15 19:12:52.474   306  1637 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7307d20
,03-15 19:12:52.474   306  1637 D DrmWidevineDash: message_length=1591, signature=0xb7283d50, signature_length=2972641044
,03-15 19:12:52.663   306  1637 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-15 19:12:52.664   306   984 I WVCdm   : CdmEngine::CloseSession
03-15 19:12:52.664   306   984 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,03-15 19:12:52.665   306   984 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-15 19:12:52.665   306   984 I WVCdm   : L3 Terminate.
03-15 19:12:52.665   306   984 D DrmWidevineDash: OEMCrypto_Terminate: starts!
03-15 19:12:52.665   306   984 D DrmWidevineDash: Service_Uninitialize: starts!
03-15 19:12:52.665   306   984 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 19:12:52.665   306   984 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-15 19:12:52.665   306   984 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
03-15 19:12:52.666   306   984 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-15 19:12:52.757   306   306 I WVCdm   : CdmEngine::OpenSession
03-15 19:12:52.757   306   306 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,03-15 19:12:52.760   306   306 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,03-15 19:12:52.781   306   306 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
03-15 19:12:52.781   306   306 D DrmWidevineDash: Service_Initialize: starts!
,03-15 19:12:52.781   306   306 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 19:12:52.781   306   306 D QSEECOMAPI: : App is not loaded in QSEE
03-15 19:12:52.781   306   306 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
03-15 19:12:52.781   306   306 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 19:12:52.782   306   306 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 19:12:52.782   306   306 D QSEECOMAPI: : App is not loaded in QSEE
03-15 19:12:52.782   306   306 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
03-15 19:12:52.782   306   306 E QSEECOMAPI: : Error::Loading image failed with ret = -1
03-15 19:12:52.782   306   306 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
03-15 19:12:52.782   306   306 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 19:12:52.809   306   306 D QSEECOMAPI: : Loaded image: APP id = 3
,03-15 19:12:52.810   306   306 D DrmWidevineDash: Service_Initialize: ends! returns 0
03-15 19:12:52.810   306   306 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee4000
,03-15 19:12:52.810   306   306 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ee4000
,03-15 19:12:52.813   306   306 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,03-15 19:12:52.813   306   306 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 19:12:52.813   306   306 D DrmWidevineDash: hlos api version =  9
03-15 19:12:52.814   306   306 D DrmWidevineDash: tz api version =  8
03-15 19:12:52.814   306   306 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
03-15 19:12:52.814   306   306 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,03-15 19:12:52.820   306   306 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,03-15 19:12:52.820   306   306 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
03-15 19:12:52.820   306   306 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbed4c4e0
03-15 19:12:52.820   306   306 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
03-15 19:12:52.820   306   306 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
03-15 19:12:52.820   306   306 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7318358, dataLength=8
,03-15 19:12:52.821   306   306 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,03-15 19:12:52.821   306   306 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7250e60, wrapped_rsa_key_length=1280
03-15 19:12:52.824   306   306 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
03-15 19:12:52.824   306   306 I WVCdm   : CdmEngine::QueryKeyControlInfo
,03-15 19:12:52.826   306  1637 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,03-15 19:12:52.826   306  1637 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
03-15 19:12:52.826   306  1637 I WVCdm   : CdmEngine::GenerateKeyRequest
03-15 19:12:52.826   306  1637 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7349d90, idLength=0xb12ee730
,03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
03-15 19:12:52.834   306  1637 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
,03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
03-15 19:12:52.835   306  1637 D DrmWidevineDash: hlos api version =  9
03-15 19:12:52.835   306  1637 D DrmWidevineDash: tz api version =  8
03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
03-15 19:12:52.835   306  1637 D WVCdm   : PrepareKeyRequest: nonce=3773164202
03-15 19:12:52.835   306  1637 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb724fa80
03-15 19:12:52.835   306  1637 D DrmWidevineDash: message_length=1622, signature=0xb7283d50, signature_length=2972641044
,03-15 19:12:53.025   306  1637 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,03-15 19:12:53.026   306   984 I WVCdm   : CdmEngine::CloseSession
,03-15 19:12:53.026   306   984 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
03-15 19:12:53.026   306   984 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
03-15 19:12:53.026   306   984 I WVCdm   : L3 Terminate.
03-15 19:12:53.026   306   984 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,03-15 19:12:53.026   306   984 D DrmWidevineDash: Service_Uninitialize: starts!
03-15 19:12:53.026   306   984 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 19:12:53.026   306   984 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
03-15 19:12:53.027   306   984 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,03-15 19:12:53.027   306   984 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,03-15 19:12:53.213  6179  6179 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-15 19:12:53.301  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:53.301  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:53.313  6179  6179 I dex2oat : dex2oat took 99.570ms (threads: 4)
,03-15 19:12:53.329  6131  6147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:12:53.329  6131  6147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:12:53.329  6131  6147 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:12:53.329  6131  6147 I Adreno-EGL: Local Branch: 
03-15 19:12:53.329  6131  6147 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:12:53.329  6131  6147 I Adreno-EGL: Local Patches: NONE
03-15 19:12:53.329  6131  6147 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:12:53.430  6131  6147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:12:53.430  6131  6147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:12:53.430  6131  6147 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:12:53.430  6131  6147 I Adreno-EGL: Local Branch: 
03-15 19:12:53.430  6131  6147 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:12:53.430  6131  6147 I Adreno-EGL: Local Patches: NONE
03-15 19:12:53.430  6131  6147 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:12:53.487  6131  6147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:12:53.487  6131  6147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:12:53.487  6131  6147 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:12:53.487  6131  6147 I Adreno-EGL: Local Branch: 
03-15 19:12:53.487  6131  6147 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:12:53.487  6131  6147 I Adreno-EGL: Local Patches: NONE
03-15 19:12:53.487  6131  6147 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:12:53.501   314   414 I ThermalEngine: Sensor:xo_therm_pu2:36000 mC
,03-15 19:12:53.545  6131  6147 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:12:53.545  6131  6147 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:12:53.545  6131  6147 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:12:53.545  6131  6147 I Adreno-EGL: Local Branch: 
03-15 19:12:53.545  6131  6147 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:12:53.545  6131  6147 I Adreno-EGL: Local Patches: NONE
03-15 19:12:53.545  6131  6147 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:12:53.964  1957  6125 I CheckinRequestBuilder: Classify the device as Phone.
,03-15 19:12:54.101   885   901 I art     : Explicit concurrent mark sweep GC freed 28737(1384KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 1.469ms total 120.370ms
,03-15 19:12:54.242  1957  6125 I CheckinTask: Sending checkin request (9874 bytes)
,03-15 19:12:54.364  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:54.796  1957  6125 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,03-15 19:12:54.799  1957  6125 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,03-15 19:12:54.875  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 19:12:55.050  1957  6125 I CheckinRequestBuilder: Classify the device as Phone.
,03-15 19:12:55.066  1957  6125 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,03-15 19:12:55.071  1957  6125 I CheckinService: Checking schedule, now: 1458065575071 next: 1458666712066
03-15 19:12:55.071  1957  6125 I CheckinService: active receiver: disabled
,03-15 19:12:55.084  1957  1957 D CheckinService: Recording last checkin time for package unspecified as 1458065575084
,03-15 19:12:55.131   885  4415 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6207 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-15 19:12:55.199  6207  6207 D PhoneMonitor: Register our PhoneStateListener
,03-15 19:12:55.214  6207  6207 V SetupWizard: Connected to Gservices successfully
,03-15 19:12:55.216   885  1651 I ActivityManager: Killing 5936:com.google.android.gm/u0a63 (adj 15): empty #7
,03-15 19:12:55.361   885  1466 W libprocessgroup: failed to open /acct/uid_10063/pid_5936/cgroup.procs: No such file or directory
,03-15 19:12:55.396  1784  2704 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-15 19:12:56.317  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:56.318  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:56.368  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:12:58.597   885  1556 I ActivityManager: Killing 6002:com.android.providers.calendar/u0a5 (adj 13): empty #7
,03-15 19:12:58.621   885  1556 I ActivityManager: Killing 6023:com.motorola.context/u0a8 (adj 15): empty #8
,03-15 19:12:58.650   885  1556 I ActivityManager: Killing 5870:com.google.android.gms:car/u0a16 (adj 15): empty #9
,03-15 19:12:58.671   885  1488 W libprocessgroup: failed to open /acct/uid_10005/pid_6002/cgroup.procs: No such file or directory
,03-15 19:12:58.675   885   901 W libprocessgroup: failed to open /acct/uid_10008/pid_6023/cgroup.procs: No such file or directory
,03-15 19:12:58.677   885  1537 W libprocessgroup: failed to open /acct/uid_10016/pid_5870/cgroup.procs: No such file or directory
,03-15 19:12:59.231   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=320, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311288, SEQNUM=4453, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8213, POWER_SUPPLY_CHARGE_COUNTER=-180, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:12:59.265  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:12:59.320  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:12:59.338  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:12:59.338  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:00.001   885  1229 V AlarmManager: send {1d219c60, *alarm*:android.intent.action.TIME_TICK}
,03-15 19:13:00.041   885   885 V AlarmManager: done {1d219c60, *alarm*:android.intent.action.TIME_TICK} [41ms]
,03-15 19:13:01.783   885  1231 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 19:13:01.856   885  1127 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6232 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-15 19:13:01.944   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 19:13:01.944   885   885 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:13:01.947   885   885 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:13:01.954   885   885 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 19:13:01.955   885   885 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@263bb509
,03-15 19:13:01.994  1784  1784 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-15 19:13:02.019  1574  1574 I Launcher: Deferring update until onResume
,03-15 19:13:02.254   885  1538 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6270 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-15 19:13:02.298   885  1651 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6284 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-15 19:13:02.299   885  1651 I ActivityManager: Killing 5680:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-15 19:13:02.406   885  1597 I ActivityManager: Killing 5591:com.android.vending/u0a32 (adj 15): empty #7
,03-15 19:13:02.501   885   900 W libprocessgroup: failed to open /acct/uid_10049/pid_5680/cgroup.procs: No such file or directory
,03-15 19:13:02.516   885  1814 W libprocessgroup: failed to open /acct/uid_10032/pid_5591/cgroup.procs: No such file or directory
,03-15 19:13:02.523  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:13:02.523  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:02.533  6284  6284 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:13:02.699  6284  6317 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-15 19:13:02.699  6284  6317 I Babel_SMS: MmsConfig.loadMmsSettings
,03-15 19:13:02.699  6284  6317 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-15 19:13:02.699  6284  6317 I Babel_SMS: MmsConfig.loadFromDatabase
,03-15 19:13:02.714  6284  6317 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-15 19:13:02.714  6284  6317 I Babel_SMS: MmsConfig.loadFromResources
,03-15 19:13:02.718  6284  6317 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-15 19:13:02.720  6284  6317 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-15 19:13:02.756  6284  6284 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-15 19:13:02.759  6284  6284 I Babel_Crash: startup - clean
,03-15 19:13:02.785  6284  6320 I Babel   : deleted: false for 0
,03-15 19:13:02.885   885  1620 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6322 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-15 19:13:02.953  6284  6284 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:13:02.959  6284  6284 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-15 19:13:02.963  6284  6284 W VideoCapabilities: Unsupported mime video/mpeg2
,03-15 19:13:02.985  6284  6284 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-15 19:13:02.991  6284  6284 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 19:13:02.992  6284  6284 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-15 19:13:02.995  6284  6284 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:13:02.999  6284  6284 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:13:03.062   885  1249 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6343 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:13:03.064   885  1249 I ActivityManager: Killing 6207:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-15 19:13:03.119  6322  6340 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-15 19:13:03.181   885  1303 W libprocessgroup: failed to open /acct/uid_10035/pid_6207/cgroup.procs: No such file or directory
,03-15 19:13:03.187  6284  6284 I vclib   : onServiceConnected
,03-15 19:13:03.188  6284  6284 W Babel   : Attempted to change video mute state without an active call.
,03-15 19:13:03.197  6343  6343 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 19:13:03.197  6343  6343 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-15 19:13:03.197  6343  6343 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:13:03.198  6343  6343 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-15 19:13:03.204  6284  6284 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:13:03.204  6284  6284 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:13:03.234  6284  6284 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:13:03.247  1574  1574 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@7d0eeb7 new=com.google.android.velvet.VelvetApplication@7d0eeb7
,03-15 19:13:03.248  6232  6368 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-15 19:13:03.261  1957  6372 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-15 19:13:03.261  1957  6372 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-15 19:13:03.301   885  4415 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6374 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-15 19:13:03.302  6284  6284 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 19:13:03.302  6284  6284 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:13:03.417  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:03.422  1957  6372 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-15 19:13:03.451  1957  2033 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-15 19:13:03.470  6374  6374 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:13:03.478  6232  6368 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 228 ms] updated apps [took 228 ms] 
,03-15 19:13:03.505   314   414 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-15 19:13:03.724   885  1466 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6403 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:13:03.881   885   900 I art     : Explicit concurrent mark sweep GC freed 22878(1228KB) AllocSpace objects, 2(126KB) LOS objects, 33% free, 21MB/32MB, paused 1.495ms total 118.973ms
,03-15 19:13:03.889   885  1303 I ActivityManager: Killing 6131:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-15 19:13:03.971   885  1620 W libprocessgroup: failed to open /acct/uid_10016/pid_6131/cgroup.procs: No such file or directory
,03-15 19:13:04.043  6403  6403 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 19:13:04.145  6403  6403 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 19:13:04.157  6403  6403 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:13:04.161  6403  6403 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:13:04.214  6403  6403 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 19:13:04.214  6403  6403 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-15 19:13:04.221  6403  6448 D Ads     : Skipping gmscore version check
,03-15 19:13:04.224   885  4415 I ActivityManager: Killing 6270:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-15 19:13:04.244   885  1556 W libprocessgroup: failed to open /acct/uid_10019/pid_6270/cgroup.procs: No such file or directory
,03-15 19:13:04.248  6403  6403 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 19:13:04.262  6403  6403 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 19:13:04.373  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:04.552  1957  2033 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-15 19:13:04.602  1957  2033 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-15 19:13:05.360  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:13:05.362  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:08.376  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:08.377  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:08.462   885  1651 I ActivityManager: Killing 6284:com.google.android.talk/u0a70 (adj 15): empty #7
,03-15 19:13:08.520   885  1488 W libprocessgroup: failed to open /acct/uid_10070/pid_6284/cgroup.procs: No such file or directory
,03-15 19:13:09.376   885  1229 V AlarmManager: send {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 19:13:09.382   885   885 V AlarmManager: done {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM} [5ms]
,03-15 19:13:09.443   885  1124 I ActivityManager: Start proc com.google.android.apps.docs.editors.sheets for service com.google.android.apps.docs.editors.sheets/com.google.android.apps.docs.sync.syncadapter.DocsSyncAdapterService: pid=6454 uid=10105 gids={50105, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:13:09.490  1957  6463 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,03-15 19:13:09.517   885  1124 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 193113, reason: UserStart
,03-15 19:13:10.039  6454  6454 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-15 19:13:10.039  6454  6454 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 19:13:10.039  6454  6454 I GAv4    :   adb logcat -s GAv4
,03-15 19:13:10.060  6454  6454 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:13:10.084  6454  6454 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:13:10.092  6454  6486 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:13:10.111  6454  6454 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-5, app name Sheets, version 1.4.312.11.30
,03-15 19:13:10.198  6454  6487 E SQLiteLog: (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs.editors.sheets/databases/DocList.db-wal
,03-15 19:13:10.382  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:10.398   885  1303 I ActivityManager: Killing 6343:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-15 19:13:10.440   885   901 W libprocessgroup: failed to open /acct/uid_10027/pid_6343/cgroup.procs: No such file or directory
,03-15 19:13:10.447  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:13:10.454   885   901 I ActivityManager: Killing 6232:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-15 19:13:10.504   885  1597 W libprocessgroup: failed to open /acct/uid_10039/pid_6232/cgroup.procs: No such file or directory
,03-15 19:13:10.525  6454  6491 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:13:10.525  6454  6491 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:13:10.551  6454  6491 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:13:10.602  6454  6491 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 19:13:10.776   885  1229 V AlarmManager: send {1fff56cf, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,03-15 19:13:10.778   885  1229 V AlarmManager: send {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 19:13:10.780   885   885 V AlarmManager: done {1fff56cf, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4ms]
,03-15 19:13:10.782   885   885 V AlarmManager: done {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN} [6ms]
,03-15 19:13:10.785   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.52 rxSuccessRate=0.90 targetRoamBSSID=any RSSI=-48
03-15 19:13:10.785   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=19104 interval=30000 maxinterval=300000
03-15 19:13:10.785   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-15 19:13:10.785   885  1240 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-15 19:13:10.789  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-15 19:13:10.789   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
,03-15 19:13:10.789   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
03-15 19:13:10.789   885  1240 E WifiStateMachine: [1,458,065,590,789 ms] noteScanstart no scan source
,03-15 19:13:10.842   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 19:13:10.842   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-15 19:13:10.842   470   505 D TCMD    : NL - Read 56 bytes from update socket.
03-15 19:13:10.842   470   505 D TCMD    : NL - message type is RTM_NEWLINK
03-15 19:13:10.842   470   505 D TCMD    : Listening for incoming client connection request
,03-15 19:13:10.846   885  1240 E WifiStateMachine: [1,458,065,590,845 ms] noteScanEnd no scan source
,03-15 19:13:10.849   885  1240 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@235f81fe sup_state=COMPLETED debouncing=false
,03-15 19:13:10.962  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:13:10.970  1784  6506 I VacuumService: Vacuum at: now=1458065590970 tag=VacuumService
,03-15 19:13:11.384  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:11.388  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:13:11.389  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:13.386  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:13.510   314   414 I ThermalEngine: Sensor:xo_therm_pu2:35000 mC
,03-15 19:13:14.412  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:14.413  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:17.417  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:17.418  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:19.181   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=311, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310843, SEQNUM=4464, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11418, POWER_SUPPLY_CHARGE_COUNTER=-232, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:13:19.271  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:13:19.327  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:13:20.432  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:20.433  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:23.347   885  1250 E BackupManagerService: Timeout restoring application @pm@
,03-15 19:13:23.352   885  1250 W BackupManagerService: Tried to clear data for @pm@ but not found
,03-15 19:13:23.357  1784  2030 W GmsBackupTransport: Restore processing aborted, no more packages
,03-15 19:13:23.358   885  1250 E BackupManagerService: Failure getting next package name
,03-15 19:13:23.360   885  1250 E BackupManagerService: Duplicate finish
,03-15 19:13:23.448  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:23.449  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:23.515   314   414 I ThermalEngine: Sensor:xo_therm_pu2:34000 mC
,03-15 19:13:26.291   885  1229 V AlarmManager: send {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-15 19:13:26.296   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.48 rxSuccessRate=0.34 targetRoamBSSID=any RSSI=-48
03-15 19:13:26.296   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=34615 interval=30000 maxinterval=300000
03-15 19:13:26.296   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN try full band scan age=34615 interval=30000 maxinterval=300000
03-15 19:13:26.296   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=true
03-15 19:13:26.296   885  1240 E WifiStateMachine: WifiStateMachine CMD_START_SCAN bump interval =45000
03-15 19:13:26.297  1445  1445 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-15 19:13:26.298   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-15 19:13:26.298   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-15 19:13:26.303   885   885 V AlarmManager: done {ec63762, *alarm*:com.android.server.WifiManager.action.START_SCAN} [12ms]
,03-15 19:13:26.306   885  1240 E WifiStateMachine: [1,458,065,606,306 ms] noteScanstart no scan source
,03-15 19:13:26.728   470   505 D TCMD    : NL - Read 56 bytes from update socket.
03-15 19:13:26.728   470   505 D TCMD    : NL - message type is RTM_NEWLINK
03-15 19:13:26.728   470   505 D TCMD    : Listening for incoming client connection request
,03-15 19:13:26.734   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 28 
,03-15 19:13:26.734   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 28 
,03-15 19:13:26.736   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 29 
,03-15 19:13:26.736   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 29 
,03-15 19:13:26.736   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 30 
03-15 19:13:26.736   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 30 
,03-15 19:13:26.737   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 31 
03-15 19:13:26.737   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-ADDED 31 
03-15 19:13:26.737   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:13:26.737   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:13:26.737   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:13:26.737   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:13:26.738   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-15 19:13:26.738   304  1644 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-15 19:13:26.744  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:26.745  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:26.752   885  1240 E WifiStateMachine: [1,458,065,606,752 ms] noteScanEnd no scan source
,03-15 19:13:26.756   885  1240 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@235f81fe sup_state=COMPLETED debouncing=false
,03-15 19:13:29.749  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:29.749  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:30.942  1421  1611 I Keyboard.Facilitator.LanguageModelFlusher: run()
,03-15 19:13:30.945  1421  1611 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-15 19:13:30.984  1784  1784 I ConfigService: onCreate
,03-15 19:13:32.765  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:32.765  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:33.519   314   414 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 19:13:33.572   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-15 19:13:33.572   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:13:33.572   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:13:33.572   304   520 I MDMCTBK : checkDefaultInst, pid match
,03-15 19:13:33.572   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:13:33.573   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:13:33.573   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:13:33.573   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:13:33.573   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:13:33.573   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:13:33.573   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:13:33.573   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:13:33.573   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:13:33.573   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:13:34.573   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:13:34.573   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:13:34.573   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:13:34.574   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:13:34.574   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:13:34.574   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:13:34.574   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:13:35.779  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:35.780  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:36.049  1784  1784 I ConfigService: onDestroy
,03-15 19:13:38.794  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-15 19:13:38.795  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-15 19:13:38.795  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
03-15 19:13:38.795  1296  1296 I SBar.MotoNetworkCtrlr: refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,03-15 19:13:39.181   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=303, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311619, SEQNUM=4466, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-284, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:13:39.295  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:13:39.450   885  1229 V AlarmManager: send {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-15 19:13:39.454   885   885 V AlarmManager: done {300fef16, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,03-15 19:13:41.810  1296  1296 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-15 19:13:41.814  1296  1296 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-15 19:13:41.849   885  1146 I PowerManagerService: Nap time (uid 1000)...
,03-15 19:13:41.853   885  1146 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,03-15 19:13:41.870   885  1146 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-15 19:13:41.870   885  1146 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-15 19:13:41.870   885  1146 I Adreno-EGL: Build Date: 10/28/14 Tue
03-15 19:13:41.870   885  1146 I Adreno-EGL: Local Branch: 
03-15 19:13:41.870   885  1146 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-15 19:13:41.870   885  1146 I Adreno-EGL: Local Patches: NONE
03-15 19:13:41.870   885  1146 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-15 19:13:42.384   885  1146 D         : activate, handle: 1598182242, enabled: 0, index 2
03-15 19:13:42.384   885  1146 D         : BstSensorExt: id=1598182242, en=0
,03-15 19:13:42.386   885  1146 D         : enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 224
,03-15 19:13:42.391   885  1146 D         : activate, handle: 2, enabled: 0, index 5
,03-15 19:13:42.398   885  1142 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-15 19:13:42.402   885   885 V ActivityManager: Display changed displayId=0
,03-15 19:13:42.421   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb7b27550
,03-15 19:13:42.424   281   281 D qdhwcomposer: hwc_blank: Blanking display: 0
,03-15 19:13:42.490  1557  1557 I art     : Explicit concurrent mark sweep GC freed 28967(1844KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.145ms total 67.228ms
,03-15 19:13:42.625   300   300 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8210820
03-15 19:13:42.626   300   300 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
03-15 19:13:42.626   300   300 I rmt_storage: wakelock acquired: 1, error no: 42
,03-15 19:13:42.627   300   824 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205794680)
,03-15 19:13:42.734   281   724 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-15 19:13:42.737   281   281 I qdhwcomposer: enable_dcabc: Done setting OFF mode
,03-15 19:13:42.738   281   281 D qdhwcomposer: hwc_blank: Done blanking display: 0
03-15 19:13:42.738   281   281 I SFPerfTracer:       trigger: frame rate (-31.216%)	(41.270 fps)	(24.231 ms) 	(3 drops)	(16 frames)
,03-15 19:13:42.738   281   281 I SFPerfTracer:      triggers: (rate: 17:573) (compose: 0:2) (post: 0:1) (render: 0:4) (16:980 frames) (17:1098)
03-15 19:13:42.739   281   281 D SFPerfTracer:        layers: (4:10) (FocusedStackFrame (0xb7bb0340): 0:17)* (DimLayer (0xb7c3a670): 0:7)* (StatusBar (0xb7bff178): 0:172) (NavigationBar (0xb7c00e90): 0:45) (com.android.systemui.ImageWallpaper (0xb7c065a0): 0:7)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7c2ba68): 0:29) (ColorFade (0xb7c3d710): 17:19) 
,03-15 19:13:42.742   300   824 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
03-15 19:13:42.742   300   824 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,03-15 19:13:42.744   300   824 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205794680) wakelock released: 1, error no: 0
03-15 19:13:42.744   300   824 I rmt_storage: 
,03-15 19:13:42.745   885  1258 D SurfaceControl: Excessive delay in setPowerMode(): 348ms
,03-15 19:13:42.747   300   300 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8210820
,03-15 19:13:42.753   885   885 I WindowManager: AOD feature not enabled!
,03-15 19:13:42.760  1482  4186 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-15 19:13:42.785   885  1146 I PowerManagerService: Sleeping (uid 1000)...
,03-15 19:13:42.822   885  1240 D WifiStateMachine: backgroundScan enabled=false startBackgroundScanIfNeeded:false
,03-15 19:13:42.822   885  1240 E WifiStateMachine: handleScreenStateChanged Exit: true
,03-15 19:13:42.826   306   983 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,03-15 19:13:42.827   306   983 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-15 19:13:42.827   306   983 V msm8974_platform: platform_set_parameters: exit with code(0)
03-15 19:13:42.827   306   983 E msm8974_platform: platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
03-15 19:13:42.827   306   983 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
,03-15 19:13:42.829   306   983 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,03-15 19:13:42.842   885  1240 E WifiStateMachine: setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-15 19:13:42.842   885  1240 E native  : do suspend false
,03-15 19:13:42.931  1421  1421 I Keyboard.Facilitator: onFinishInput()
,03-15 19:13:42.935   885   885 D         : activate, handle: 1598182229, enabled: 0, index 0
03-15 19:13:42.935   885   885 E         : <BST> disable accel, orig state: 1
03-15 19:13:42.935   885   885 I         : <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,03-15 19:13:42.937   306  1637 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-15 19:13:42.937   306  1637 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-15 19:13:42.937   306  1637 V msm8974_platform: platform_set_parameters: exit with code(0)
03-15 19:13:42.937   306  1637 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
03-15 19:13:42.937   306  1637 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
03-15 19:13:42.939   885  1240 D WifiStateMachine: backgroundScan enabled=true startBackgroundScanIfNeeded:false
03-15 19:13:42.939   885  1240 E WifiStateMachine: handleScreenStateChanged Exit: false
,03-15 19:13:42.944   885  1240 E WifiStateMachine: setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,03-15 19:13:42.945   885  1240 E WifiStateMachine: setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
03-15 19:13:42.945   885  1240 E native  : do suspend true
,03-15 19:13:43.524   314   414 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 19:13:44.978  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 19:13:45.119  1482  1482 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,03-15 19:13:47.772   885  1229 V AlarmManager: send {3e13c3d5, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,03-15 19:13:47.778   885   885 V AlarmManager: done {3e13c3d5, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [6ms]
,03-15 19:13:53.529   314   414 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-15 19:13:59.171   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311187, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-314, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:13:59.262  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:13:59.316  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:14:03.533   314   414 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 19:14:12.975   885  1229 V AlarmManager: send {1d219c60, *alarm*:android.intent.action.TIME_TICK}
,03-15 19:14:12.979   885  1229 V AlarmManager: send {3fd377ea, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-15 19:14:12.990   885   885 V AlarmManager: done {3fd377ea, *walarm*:com.google.android.intent.action.SEND_IDLE} [15ms]
,03-15 19:14:13.026   885   885 V AlarmManager: done {1d219c60, *alarm*:android.intent.action.TIME_TICK} [50ms]
,03-15 19:14:13.238  1784  6555 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 10409 seconds from now (1458065653238)
,03-15 19:14:13.349  1784  6548 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-15 19:14:13.356  1784  6548 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-15 19:14:13.538   314   414 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 19:14:15.126  1784  1798 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@176cd040)
,03-15 19:14:15.127  1784  1798 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32485b79)
03-15 19:14:15.127  1784  1798 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d4400be)
,03-15 19:14:15.129  1784  1798 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f22651f)
,03-15 19:14:15.129  1784  1798 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16eb06c)
,03-15 19:14:15.367  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:14:15.369  1784  1784 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:14:15.752  2863  4276 E global frequency: no tags to log
,03-15 19:14:15.755  2863  4276 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:15.801  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:15.805  1557  2535 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 19:14:15.926  1482  2920 I art     : Explicit concurrent mark sweep GC freed 57889(3MB) AllocSpace objects, 37(1269KB) LOS objects, 39% free, 7MB/12MB, paused 725us total 54.303ms
,03-15 19:14:15.929  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:15.940  2863  2863 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:15.948  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:15.950  1557  3218 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 19:14:16.086   885  1597 I art     : Explicit concurrent mark sweep GC freed 45603(2MB) AllocSpace objects, 3(238KB) LOS objects, 33% free, 21MB/32MB, paused 1.805ms total 123.806ms
,03-15 19:14:16.171  2863  2863 I art     : Explicit concurrent mark sweep GC freed 41816(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.024ms total 64.356ms
,03-15 19:14:16.204  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:16.214  2863  2863 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:16.236  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:16.240  1557  1573 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-15 19:14:16.332  1482  4297 I art     : Explicit concurrent mark sweep GC freed 3859(163KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 567us total 29.868ms
,03-15 19:14:16.344  2863  2863 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-15 19:14:16.355  2863  2863 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:16.360  2863  4276 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:16.364  2863  4276 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-15 19:14:16.365  2863  4276 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:16.366  2863  4276 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-15 19:14:16.366  2863  4276 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:16.368  2863  4276 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-15 19:14:16.391  2863  4276 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-15 19:14:16.516  2863  4276 I global frequency: BcsDSCheckin.events found events 82
,03-15 19:14:16.517  2863  4276 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:16.585  2863  4276 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:16.605  2863  6578 D MMApiWebService: doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,03-15 19:14:16.641  2863  6578 I MMApiWSBase: doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,03-15 19:14:16.643  2863  6578 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:14:17.954  2863  6578 D MMApiWSBase: doRequest(): v1/cs/checkin resp length: 4
,03-15 19:14:17.961  2863  6578 D CCE     : AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
03-15 19:14:17.961  2863  6578 D CCE     : AppWSProxy - sendAIDLWSResponse() sending reponse
,03-15 19:14:17.992  2863  6578 I global frequency: BcsCore.status() called with error code=ERROR_OK
,03-15 19:14:17.999  2863  6578 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:18.039   885  1620 D CheckinProvider: 82 events delete 0 left
,03-15 19:14:18.079  2863  6578 I global frequency: BcsDSCheckin.events found events 0
,03-15 19:14:18.081  2863  6578 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:18.085  2863  6578 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:18.088  2863  6578 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-15 19:14:18.098  2863  2863 I global frequency: BcsTimer.onReceive checkin completed (0:ERROR_OK)
,03-15 19:14:18.100  2863  2863 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-15 19:14:18.472  2863  2893 W DataUsage: invalid counter update blocked: 'err' by 0
,03-15 19:14:18.475  2863  2893 D Checkin : publish the event [tag = MOT_CCE event name = LOG]
,03-15 19:14:19.587   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:14:19.587   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:14:19.587   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:14:19.587   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:14:19.587   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:14:19.587   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:14:19.587   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:14:19.587   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:14:19.587   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:14:19.587   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:14:19.587   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:14:19.587   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:14:19.587   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:14:19.587   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:14:23.543   314   414 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 19:14:25.825   885  1229 V AlarmManager: send {39eb2b66, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-15 19:14:25.829   885   885 V AlarmManager: done {39eb2b66, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,03-15 19:14:33.547   314   414 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 19:14:34.937  1784  2709 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-15 19:14:42.931  1421  1611 I Keyboard.Facilitator.LanguageModelFlusher: run()
03-15 19:14:42.931  1421  1611 I Keyboard.Facilitator: flushDynamicLanguageModels()
,03-15 19:14:42.949  1784  1784 I ConfigService: onCreate
,03-15 19:14:43.552   314   414 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-15 19:14:48.006  1784  1784 I ConfigService: onDestroy
,03-15 19:14:53.556   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:14:56.597   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:14:56.597   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:14:56.597   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:14:56.597   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:14:56.597   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:14:56.598   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:14:56.598   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:14:56.598   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:14:56.598   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:14:56.598   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:14:56.598   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:14:56.598   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:14:56.598   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:14:56.598   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:14:59.201   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311638, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-372, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-15 19:14:59.265  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:14:59.320  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:15:00.999   885  1229 V AlarmManager: send {1d219c60, *alarm*:android.intent.action.TIME_TICK}
,03-15 19:15:01.003   885  1229 V AlarmManager: send {31ee97f2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-15 19:15:01.045   885  1127 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6593 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,03-15 19:15:01.088   325   325 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 40.906ms
,03-15 19:15:01.124   885   885 V AlarmManager: done {1d219c60, *alarm*:android.intent.action.TIME_TICK} [125ms]
,03-15 19:15:01.128   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 36.236ms
,03-15 19:15:01.150   325   325 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.997ms
,03-15 19:15:01.150  6593  6593 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-15 19:15:01.150  6593  6593 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 19:15:01.150  6593  6593 I GAv4    :   adb logcat -s GAv4
,03-15 19:15:01.166  6593  6593 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:15:01.186  6593  6593 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:15:01.194  6593  6625 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 19:15:01.199   885  1620 I ActivityManager: Killing 6322:android.process.acore/u0a7 (adj 15): empty #7
,03-15 19:15:01.199   885   885 V AlarmManager: done {31ee97f2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [200ms]
,03-15 19:15:01.215   885  1538 W libprocessgroup: failed to open /acct/uid_10007/pid_6322/cgroup.procs: No such file or directory
,03-15 19:15:03.561   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:15:10.602   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:10.602   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:10.602   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:10.602   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:10.602   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:10.602   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:10.602   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:10.602   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:10.602   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:10.602   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:10.602   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:10.602   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:10.603   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:10.603   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:15:13.566   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:15:20.605   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:20.605   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:20.605   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:20.605   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:20.605   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:20.605   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:20.605   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:20.606   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:20.606   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:20.606   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:20.606   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:20.606   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:20.607   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:15:23.570   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:15:28.609   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:28.609   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:28.609   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:28.609   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:28.609   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:28.609   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:28.609   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:28.609   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:28.609   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:28.609   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:28.609   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:28.609   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:28.609   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:28.609   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:15:33.575   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:15:36.611   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-15 19:15:36.612   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:36.612   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:36.612   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:36.612   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:36.612   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:36.612   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-15 19:15:36.612   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:15:36.612   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:15:36.612   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:15:36.612   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:15:36.612   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:15:36.612   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:15:36.612   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:15:43.579   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:15:53.584   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:03.589   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:13.593   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:16.089   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:16:16.089   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
,03-15 19:16:23.598   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:33.602   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 3
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 3
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-15 19:16:36.091   304  1644 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
,03-15 19:16:40.128   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311543, SEQNUM=4494, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-502, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 19:16:40.130   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:16:40.130   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:16:40.130   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:16:40.130   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:16:40.130   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:16:40.130   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:16:40.130   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:16:40.177  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:16:40.217   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:16:40.217   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:16:40.217   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:16:40.217   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:16:40.217   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:16:40.218   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:16:40.218   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:16:40.274  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:16:43.607   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:16:53.612   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:17:03.616   314   414 I ThermalEngine: Sensor:xo_therm_pu2:31000 mC
,03-15 19:17:13.621   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:17:23.625   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:17:33.630   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:17:43.635   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:17:53.639   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:03.644   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:13.648   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:23.653   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:33.657   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:43.662   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:18:53.667   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:03.671   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:13.676   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:23.680   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:33.685   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:43.689   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:19:53.694   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:03.699   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:13.703   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:23.708   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:33.712   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:43.717   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:20:53.722   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:03.726   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:13.731   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:23.735   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:33.740   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:43.744   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:21:53.749   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:03.754   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:13.758   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:23.763   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:33.767   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:43.772   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:22:53.777   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:03.781   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:13.786   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:23.790   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:33.795   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:43.799   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:23:53.804   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:03.809   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:13.813   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:23.818   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:33.822   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:37.522   885  1229 V AlarmManager: send {1d219c60, *alarm*:android.intent.action.TIME_TICK}
03-15 19:24:37.525   885  1229 V AlarmManager: send {2b76c996, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-15 19:24:37.528   885   885 V AlarmManager: done {2b76c996, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,03-15 19:24:37.569   885   885 V AlarmManager: done {1d219c60, *alarm*:android.intent.action.TIME_TICK} [47ms]
,03-15 19:24:43.827   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:24:53.832   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:03.836   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:13.841   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:23.845   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:33.850   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:43.855   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:25:53.859   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:03.864   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:13.868   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:23.873   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:33.878   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:43.882   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:26:53.887   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:27:03.891   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:27:13.896   314   414 I ThermalEngine: Sensor:xo_therm_pu2:30000 mC
,03-15 19:27:23.900   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:27:33.905   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:27:40.128   885  1225 D BatteryService: uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311102, SEQNUM=4498, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-1686, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
03-15 19:27:40.130   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:27:40.130   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:27:40.130   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:27:40.130   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:27:40.130   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:27:40.131   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:27:40.131   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:27:40.175  2737  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 19:27:40.217   304   520 I MDMCTBK : NetlinkHandler, power_supply subsys
03-15 19:27:40.217   304   520 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-15 19:27:40.217   304   520 I MDMCTBK : checkDefaultInst, current pid is = 304
03-15 19:27:40.217   304   520 I MDMCTBK : checkDefaultInst, pid match
03-15 19:27:40.217   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-15 19:27:40.217   304   520 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-15 19:27:40.217   304   520 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-15 19:27:43.910   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:27:53.914   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:03.919   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:13.923   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:23.928   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:33.933   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:43.937   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:28:53.942   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:03.946   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:13.951   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:23.956   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:33.960   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:43.965   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:29:53.969   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:01.000   885  1229 V AlarmManager: send {1d219c60, *alarm*:android.intent.action.TIME_TICK}
03-15 19:30:01.003   885  1229 V AlarmManager: send {2c0e9e43, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,03-15 19:30:01.022   885   885 V AlarmManager: done {2c0e9e43, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [22ms]
,03-15 19:30:01.039   885   885 V AlarmManager: done {1d219c60, *alarm*:android.intent.action.TIME_TICK} [39ms]
,03-15 19:30:03.974   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:13.979   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:23.983   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:33.988   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:43.992   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:30:53.997   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:04.002   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:14.006   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:24.011   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:33.757   885  1124 I UsageStatsService: User[0] Flushing usage stats to disk
,03-15 19:31:34.015   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:44.020   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:31:54.025   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:04.029   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:14.034   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:24.039   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:34.043   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:44.048   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:32:54.052   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:04.057   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:14.061   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:24.066   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:34.071   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:44.076   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:33:54.081   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:04.086   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:14.090   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:24.095   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:34.099   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:44.104   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:34:54.109   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:04.113   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:14.118   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:24.122   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:34.127   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:44.131   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,03-15 19:35:54.136   314   414 I ThermalEngine: Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),03-15 19:35:55.776  6658  6658 D AndroidRuntime: 
03-15 19:35:55.776  6658  6658 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 19:35:55.780  6658  6658 D AndroidRuntime: CheckJNI is OFF
03-15 19:35:55.956  6658  6658 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-15 19:35:55.966   885  1127 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-15 19:35:56.022   885  1151 W PackageSettings: Skipping PackageSetting{1421c02d com.example.hello/10568} due to missing metadata
03-15 19:35:56.043   885  1151 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
03-15 19:35:56.078  3296  3296 I art     : Explicit concurrent mark sweep GC freed 10342(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 7MB/12MB, paused 1.396ms total 32.875ms
03-15 19:35:56.117  1574  1574 I art     : Explicit concurrent mark sweep GC freed 2567(136KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 455us total 52.638ms
03-15 19:35:56.139   885  1231 I InputReader: Reconfiguring input devices.  changes=0x00000010
03-15 19:35:56.142  1784  2032 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
03-15 19:35:56.148  1557  1557 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:35:56.164   885  1127 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6685 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
03-15 19:35:56.167  1421  1421 I Keyboard.Facilitator: resetDictionaries() : en_US
03-15 19:35:56.171  1421  6692 I Keyboard.Facilitator.DecoderInitializer: run()
03-15 19:35:56.202  1421  6692 I Decoder : createOrResetDecoder
03-15 19:35:56.222  1957  1957 I art     : Explicit concurrent mark sweep GC freed 20825(1226KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 14MB/19MB, paused 1.052ms total 153.843ms
03-15 19:35:56.248  1784  1784 I ConfigService: onCreate
03-15 19:35:56.275   885   885 I art     : Explicit concurrent mark sweep GC freed 24606(1775KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 21MB/32MB, paused 6.524ms total 184.031ms
03-15 19:35:56.276   885  1151 I art     : WaitForGcToComplete blocked for 107.284ms for cause Explicit
03-15 19:35:56.308  1421  6692 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-15 19:35:56.347  6685  6707 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
03-15 19:35:56.352  1421  6692 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-15 19:35:56.355  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-15 19:35:56.355  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-15 19:35:56.359  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-15 19:35:56.359  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-15 19:35:56.362  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-15 19:35:56.362  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
03-15 19:35:56.366  1421  6692 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-15 19:35:56.368  1421  6692 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-15 19:35:56.368  1421  6692 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-15 19:35:56.368  1421  6692 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-15 19:35:56.368  1421  6692 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-15 19:35:56.368  1421  6692 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-15 19:35:56.374   885   900 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6709 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:35:56.393  6685  6706 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
03-15 19:35:56.424   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-15 19:35:56.424   885   885 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-15 19:35:56.427   885  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-15 19:35:56.427   885  1259 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
03-15 19:35:56.438   885  1537 I ActivityManager: Killing 6374:com.google.android.apps.plus/u0a90 (adj 15): empty #7
03-15 19:35:56.444  6709  6709 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-15 19:35:56.444  6709  6709 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-15 19:35:56.444  6709  6709 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:35:56.444  6709  6709 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
03-15 19:35:56.509   885  1151 I art     : Explicit concurrent mark sweep GC freed 5991(314KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 2.021ms total 232.117ms
03-15 19:35:56.521   885  1651 W libprocessgroup: failed to open /acct/uid_10090/pid_6374/cgroup.procs: No such file or directory
03-15 19:35:56.532  1574  1574 I Launcher: Deferring update until onResume
03-15 19:35:56.573   885  1814 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6731 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
03-15 19:35:56.582   885  1249 I ActivityManager: Killing 6403:com.android.vending/u0a32 (adj 15): empty #7
03-15 19:35:56.715  6658  6658 D AndroidRuntime: Shutting down VM
03-15 19:35:56.718   885  1620 W libprocessgroup: failed to open /acct/uid_10032/pid_6403/cgroup.procs: No such file or directory
03-15 19:35:56.780  6731  6731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
03-15 19:35:56.792   885  1151 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6751 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-15 19:35:56.844   885  1249 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6769 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-15 19:35:56.854   885   900 I ActivityManager: Killing 6454:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
03-15 19:35:56.928   885  1249 W libprocessgroup: failed to open /acct/uid_10105/pid_6454/cgroup.procs: No such file or directory
03-15 19:35:56.938   885   900 I ActivityManager: Killing 1957:com.google.android.gms/u0a16 (adj 15): empty #7
03-15 19:35:56.963   885  1249 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@a8739ba)
03-15 19:35:56.963   885  1243 D WifiService: Client connection lost with reason: 4
03-15 19:35:56.964   885  1244 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-15 19:35:56.965   885  1244 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-15 19:35:57.011   885  1466 W libprocessgroup: failed to open /acct/uid_10016/pid_1957/cgroup.procs: No such file or directory
03-15 19:35:57.023  1574  1574 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@7d0eeb7 new=com.google.android.velvet.VelvetApplication@7d0eeb7
03-15 19:35:57.058   885  1538 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.chimera.GmsIntentOperationService: pid=6790 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
03-15 19:35:57.115  6790  6790 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 19:35:57.116  6790  6790 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-15 19:35:57.127   281   724 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
