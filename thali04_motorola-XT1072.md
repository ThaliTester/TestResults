#### Test 62548124bd1cdb6_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,03-21 07:33:22.967   890  1525 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=4661 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
--------- beginning of main
03-21 07:33:23.074  4661  4661 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-21 07:33:23.074  4661  4661 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 07:33:23.074  4661  4661 I GAv4    :   adb logcat -s GAv4
03-21 07:33:23.096  4661  4661 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
03-21 07:33:23.119  4661  4661 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
03-21 07:33:23.127  4661  4682 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
03-21 07:33:23.170   890  1603 I ActivityManager: Killing 3434:com.android.defcontainer/u0a10 (adj 15): empty #7
03-21 07:33:23.220   890   905 W libprocessgroup: failed to open /acct/uid_10010/pid_3434/cgroup.procs: No such file or directory
03-21 07:33:23.230  2634  2634 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
03-21 07:33:23.232  2634  2634 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-21 07:33:23.232  2634  2634 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
03-21 07:33:23.237   890  1509 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
03-21 07:33:23.248  2634  2634 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-21 07:33:23.252  2634  2634 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-21 07:33:23.252  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-21 07:33:23.255  2634  2634 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-21 07:33:23.256  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-21 07:33:23.259  2634  2634 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-21 07:33:23.260  2634  2634 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-21 07:33:23.261  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-21 07:33:23.302  2634  2713 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-21 07:33:23.302  2634  2713 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
03-21 07:33:23.302  2634  2713 D SundryService: onHandleIntent(): isWaitEnabled=false
03-21 07:33:23.302  2634  2713 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
03-21 07:33:23.304   890  1252 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4685 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:33:23.327  2634  2634 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
03-21 07:33:23.394  4678  4678 D AndroidRuntime: 
03-21 07:33:23.394  4678  4678 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 07:33:23.398  4678  4678 D AndroidRuntime: CheckJNI is OFF
03-21 07:33:23.451  4685  4713 I Gmail   : getAccountsCursor
03-21 07:33:23.452  4685  4714 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-21 07:33:23.460  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:33:23.526   890  1521 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4727 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 07:33:23.615   890  1130 I ActivityManager: Waited long enough for: ServiceRecord{2ef8a453 u0 com.motorola.ccc.checkin/.CheckinService}
03-21 07:33:23.619  4678  4678 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 07:33:23.626   890  1603 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 07:33:23.631  4685  4685 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-21 07:33:23.648   279  1154 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (538 us)
03-21 07:33:23.664  1483  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-21 07:33:23.671  4678  4678 D AndroidRuntime: Shutting down VM
03-21 07:33:23.672   890  1525 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-21 07:33:23.678  4727  4727 I Exchange: EasService.onCreate
03-21 07:33:23.683  4685  4751 I Gmail   : Observing account changes for notifications
03-21 07:33:23.714   890   905 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4754 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:33:23.755  4727  4761 I Exchange: RestartPingTask
03-21 07:33:23.766  4727  4727 I Exchange: RestartPingsTask did not start any pings.
03-21 07:33:23.766  4727  4727 I Exchange: PSS stopIfIdle
03-21 07:33:23.766  4727  4727 I Exchange: PSS has no active accounts; stopping service.
03-21 07:33:23.773  1483  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-21 07:33:23.780  4685  4777 I Gmail   : getAccountsCursor
03-21 07:33:23.799  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:33:23.834  4727  4727 I Exchange: onDestroy
03-21 07:33:23.840   890  1307 I ActivityManager: Killing 4555:com.android.chrome/u0a52 (adj 15): empty #7
03-21 07:33:23.841  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:23.908   890  1525 W libprocessgroup: failed to open /acct/uid_10052/pid_4555/cgroup.procs: No such file or directory
,03-21 07:33:23.910  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:23.927  4618  4782 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-21 07:33:23.933  2634  2634 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-21 07:33:23.933  2634  2634 D 3CDM.DeviceAdminPushReceiver: Type: null
03-21 07:33:23.933  2634  2634 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-21 07:33:23.934   890  1307 I ActivityManager: Killing 4575:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-21 07:33:23.939  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:23.939  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:23.953  4685  4783 E SQLiteLog: (283) recovered 67 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-21 07:33:24.002  4754  4754 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 07:33:24.038  4685  4784 I Gmail   : notifyAccountChanged
,03-21 07:33:24.039   890  1252 W libprocessgroup: failed to open /acct/uid_10090/pid_4575/cgroup.procs: No such file or directory
,03-21 07:33:24.041  4685  4713 I Gmail   : getAccountsCursor
,03-21 07:33:24.043  4685  4784 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:24.048  4685  4784 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:24.054  2634  2709 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,03-21 07:33:24.056  2634  2709 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-21 07:33:24.056  2634  2709 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-21 07:33:24.056  2634  2709 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-21 07:33:24.056  2634  2709 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-21 07:33:24.056  2634  2709 D 3CDM.Service: blur.service.cred.locationToken = null
03-21 07:33:24.056  2634  2709 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-21 07:33:24.056  2634  2709 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-21 07:33:24.056  2634  2709 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-21 07:33:24.056  2634  2709 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-21 07:33:24.059  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-21 07:33:24.060  2634  2709 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-21 07:33:24.085  4754  4754 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 4222-4230)
03-21 07:33:24.086  4754  4754 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:33:24.095  4685  4784 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:24.100  4685  4784 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:24.108  2034  2034 D WearableService: callingUid 10016, callindPid: 2034
,03-21 07:33:24.116  2034  2034 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 07:33:24.122  1953  4791 D LocationInitializer: Restart initialization of location
,03-21 07:33:24.123  2034  4789 E MDM     : [234] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-21 07:33:24.128  2634  2709 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-21 07:33:24.130  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:24.134  4754  4754 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2741de35}
,03-21 07:33:24.136  4754  4754 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 07:33:24.137  4754  4754 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 07:33:24.159  2034  2075 W GCoreFlp: No location to return for getLastLocation()
03-21 07:33:24.160  2034  4793 W FusedLocationProvider: location=null
03-21 07:33:24.162  4754  4754 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 07:33:24.163  4754  4754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:33:24.164  4754  4754 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 07:33:24.167   890   890 V AlarmManager: done {98a7d0d, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6822ms]
,03-21 07:33:24.191  4754  4754 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 07:33:24.198  4754  4754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 07:33:24.198  4754  4754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-21 07:33:24.199  4754  4754 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-21 07:33:24.199  4754  4754 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-21 07:33:24.199  4754  4754 I Adreno-EGL: Build Date: 10/28/14 Tue
03-21 07:33:24.199  4754  4754 I Adreno-EGL: Local Branch: 
03-21 07:33:24.199  4754  4754 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-21 07:33:24.199  4754  4754 I Adreno-EGL: Local Patches: NONE
03-21 07:33:24.199  4754  4754 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-21 07:33:24.213   890  1525 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4799 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:24.275  4799  4799 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 07:33:24.283   890  1144 D BluetoothManagerService: Message: 20
03-21 07:33:24.283   890  1144 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@299248a9:true
,03-21 07:33:24.310  4685  4714 I Gmail   : getAccountsCursor
,03-21 07:33:24.314  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:24.328  3072  3092 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
03-21 07:33:24.328   890  1130 I ActivityManager: Waited long enough for: ServiceRecord{1f11ea4b u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,03-21 07:33:24.340  4799  4799 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2aae08be(com.android.providers.calendar.CalendarProvider2@33b7cd1f)
,03-21 07:33:24.359   890   890 V AlarmManager: done {3267eb0f, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [6437ms]
,03-21 07:33:24.367  4799  4830 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 07:33:24.405   890  1495 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4832 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-21 07:33:24.451   279   279 I SFPerfTracer:      triggers: (rate: 15:352) (compose: 0:1) (post: 0:1) (render: 0:2) (10:1014 frames) (11:1090)
03-21 07:33:24.451   279   279 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb751b5c0): 0:11)* (DimLayer (0xb7566ed8): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb74d5298): 0:32)- (StatusBar (0xb7524258): 0:127) (NavigationBar (0xb75254e8): 0:34) (com.android.systemui.ImageWallpaper (0xb75278d8): 0:36)* (Starting com.motorola.ccc.ota (0xb752ab30): 0:35)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7586730): 1:53)* (Starting com.test.thalitest (0xb752ab30): 11:22) 
,03-21 07:33:24.466  4754  4754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:33:24.482  4754  4754 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 07:33:24.502  4754  4754 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-21 07:33:24.509  4754  4754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:33:24.509  4754  4754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:33:24.603   890  4371 I art     : Explicit concurrent mark sweep GC freed 17399(874KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.493ms total 150.224ms
,03-21 07:33:24.620  4832  4832 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:33:24.621  4754  4858 D OpenGLRenderer: Render dirty regions requested: true
,03-21 07:33:24.641  4754  4754 D Atlas   : Validating map...
,03-21 07:33:24.649  4754  4821 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-21 07:33:24.651   890  1578 I ActivityManager: Killing 4637:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-21 07:33:24.695   890  1525 W libprocessgroup: failed to open /acct/uid_10096/pid_4637/cgroup.procs: No such file or directory
,03-21 07:33:24.722  4754  4858 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 07:33:24.728  4754  4858 D OpenGLRenderer: Enabling debug mode 0
,03-21 07:33:24.784   890  1145 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1112
03-21 07:33:24.784   890  1145 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s112ms
,03-21 07:33:24.787  1425  1425 I Keyboard.Facilitator: onFinishInput()
,03-21 07:33:24.840  4754  4863 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-21 07:33:24.840  4754  4863 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-21 07:33:24.873  4754  4754 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4754
,03-21 07:33:24.890  4832  4873 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-21 07:33:24.891  4832  4873 I Babel_SMS: MmsConfig.loadMmsSettings
,03-21 07:33:24.891  4832  4873 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-21 07:33:24.891  4832  4873 I Babel_SMS: MmsConfig.loadFromDatabase
,03-21 07:33:24.905  4832  4873 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-21 07:33:24.905  4832  4873 I Babel_SMS: MmsConfig.loadFromResources
,03-21 07:33:24.912  4832  4873 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-21 07:33:24.913  4832  4873 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-21 07:33:25.025  4832  4832 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-21 07:33:25.043  4832  4832 I Babel_Crash: startup - clean
,03-21 07:33:25.064  4754  4754 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 07:33:25.070  4832  4879 I Babel   : deleted: false for 0
,03-21 07:33:25.163   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=27.47 rxSuccessRate=26.28 targetRoamBSSID=any RSSI=-42
03-21 07:33:25.163   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=10411 interval=30000 maxinterval=300000
03-21 07:33:25.163   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-21 07:33:25.163   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-21 07:33:25.164   890  1242 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-21 07:33:25.165  1416  1416 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,03-21 07:33:25.165   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-21 07:33:25.165   293  1656 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-21 07:33:25.170   890  1242 E WifiStateMachine: [1,458,542,005,170 ms] noteScanstart no scan source
,03-21 07:33:25.206  4832  4832 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:25.207   890   890 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4881 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:33:25.208   890   890 V AlarmManager: done {26ad15cf, *alarm*:com.android.server.WifiManager.action.START_SCAN} [5948ms]
,03-21 07:33:25.226   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-21 07:33:25.226   293  1656 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
,03-21 07:33:25.226   484   505 D TCMD    : NL - Read 56 bytes from update socket.
03-21 07:33:25.226   484   505 D TCMD    : NL - message type is RTM_NEWLINK
03-21 07:33:25.226   484   505 D TCMD    : Listening for incoming client connection request
,03-21 07:33:25.229   890  1242 E WifiStateMachine: [1,458,542,005,229 ms] noteScanEnd no scan source
,03-21 07:33:25.233   890  1242 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2418e5d5 sup_state=COMPLETED debouncing=false
,03-21 07:33:25.243  4832  4832 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-21 07:33:25.254  4832  4832 W VideoCapabilities: Unsupported mime video/mpeg2
,03-21 07:33:25.294  4832  4832 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-21 07:33:25.301  4832  4832 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-21 07:33:25.303  4832  4832 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:25.307  4832  4832 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:25.314  4832  4832 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:25.325   890   906 I ActivityManager: Killing 4661:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-21 07:33:25.358  4799  4799 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-21 07:33:25.359  4799  4799 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 07:33:25.482  4754  4858 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-21 07:33:25.482  4754  4858 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-21 07:33:25.569   890   905 W libprocessgroup: failed to open /acct/uid_10055/pid_4661/cgroup.procs: No such file or directory
,03-21 07:33:25.576   890  1509 I ActivityManager: Killing 4727:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-21 07:33:25.578  4832  4832 I vclib   : onServiceConnected
,03-21 07:33:25.581  4832  4832 W Babel   : Attempted to change video mute state without an active call.
,03-21 07:33:25.607  4754  4861 D jxcore_app_log: JniHelper::setJavaVM(0xb7598310), pthread_self() = -1215070160
,03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 07:33:25.614  4754  4861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fad391 added. We now have 1 listener(s)
,03-21 07:33:25.742   890  1511 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-21 07:33:25.743   890  1521 W libprocessgroup: failed to open /acct/uid_10060/pid_4727/cgroup.procs: No such file or directory
,03-21 07:33:25.748  4754  4861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-21 07:33:25.752  4754  4861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:80:EB:7B:5A:05"
,03-21 07:33:25.753  4754  4861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 07:33:25.754  4754  4861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 07:33:25.761  4754  4861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c873964 added. We now have 1 listener(s)
,03-21 07:33:25.762  4754  4861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 07:33:25.768   890  1245 D WifiService: New client listening to asynchronous messages
,03-21 07:33:25.770  4754  4861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-21 07:33:25.774  4754  4861 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-21 07:33:25.774  4754  4861 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-21 07:33:25.777  4754  4861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 07:33:25.777   890  1521 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-21 07:33:25.778  4754  4861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:33:25.783  4754  4861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:33:25.784  4754  4861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 07:33:25.784  4754  4861 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 07:33:25.785  4754  4754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:33:25.787  4754  4754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 07:33:25.788  4754  4861 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 07:33:25.820  4754  4754 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 07:33:25.875   890   905 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4907 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-21 07:33:25.887   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.042ms
,03-21 07:33:25.907   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.062ms
,03-21 07:33:25.929   890  4371 I ActivityManager: Killing 4685:com.google.android.gm/u0a63 (adj 15): empty #7
,03-21 07:33:25.937   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 29.759ms
,03-21 07:33:26.015   890  1603 W libprocessgroup: failed to open /acct/uid_10063/pid_4685/cgroup.procs: No such file or directory
,03-21 07:33:26.403   890  4371 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4933 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-21 07:33:26.420   303   394 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-21 07:33:26.463   890   905 I ActivityManager: Killing 4618:com.motorola.context/u0a8 (adj 15): empty #7
,03-21 07:33:26.585   890  1603 W libprocessgroup: failed to open /acct/uid_10008/pid_4618/cgroup.procs: No such file or directory
,03-21 07:33:26.629   890  1579 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4957 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:26.652  4754  4902 W jxcore-log: Initializing JXcore engine
,03-21 07:33:26.652  4754  4902 W jxcore-log: JXcore engine is ready
,03-21 07:33:26.679  4832  4832 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:33:26.679  4832  4832 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:33:26.743  4832  4832 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:33:26.754  4957  4957 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-21 07:33:26.754  4957  4957 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,03-21 07:33:26.755  4957  4957 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:33:26.755  4957  4957 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-21 07:33:26.756  4902  4902 W Thread-500: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[8397]" dev="sockfs" ino=8397 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 07:33:26.756  4902  4902 W Thread-500: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 07:33:26.756  4902  4902 W Thread-500: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7450]" dev="sockfs" ino=7450 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 07:33:26.756  4902  4902 W Thread-500: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[23600]" dev="sockfs" ino=23600 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 07:33:26.801  4754  4902 W jxcore-log: Starting JXcore engine
,03-21 07:33:26.811  4832  4832 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 07:33:26.811  4832  4832 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:33:26.958   890  1521 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4980 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:26.976  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:26.976  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:26.981   890   905 I ActivityManager: Killing 4799:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-21 07:33:26.987  4754  4902 W jxcore-log: Platform android
03-21 07:33:26.987  4754  4902 W jxcore-log: 
,03-21 07:33:26.987  4754  4902 W jxcore-log: Process ARCH arm
03-21 07:33:26.987  4754  4902 W jxcore-log: 
,03-21 07:33:27.085   890  1578 W libprocessgroup: failed to open /acct/uid_10005/pid_4799/cgroup.procs: No such file or directory
,03-21 07:33:27.323   890  1263 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-21 07:33:27.338  4754  4902 I jxcore-log: JXcore Cordova bridge is ready!
03-21 07:33:27.338  4754  4902 I jxcore-log: 
03-21 07:33:27.338  4754  4902 W jxcore-log: JXcore engine is started
,03-21 07:33:27.346  4754  4861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 07:33:27.351  4754  4754 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 07:33:27.458  4980  4980 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 07:33:27.650  4980  4980 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-21 07:33:27.668  4980  4980 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:27.669  4980  4980 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:27.721   890  4371 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5024 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:27.787  4980  4980 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-21 07:33:27.790  5024  5024 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-21 07:33:27.790  4980  4980 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-21 07:33:27.791  4980  4980 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-21 07:33:27.793  4980  5042 D Ads     : Skipping gmscore version check
,03-21 07:33:27.801  4980  4980 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-21 07:33:27.854  4907  5048 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-21 07:33:27.854  5024  5024 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2aae08be(com.android.providers.calendar.CalendarProvider2@33b7cd1f)
,03-21 07:33:27.855  1580  1580 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15307196 new=com.google.android.velvet.VelvetApplication@15307196
03-21 07:33:27.856  4980  4980 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-21 07:33:27.898  1953  5052 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-21 07:33:27.899  1953  5052 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-21 07:33:27.917   890  1252 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5055 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:27.945   890   905 I ActivityManager: Killing 3143:com.google.android.calendar/u0a49 (adj 15): empty #7
03-21 07:33:27.947  1953  5052 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-21 07:33:27.971  1953  2062 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-21 07:33:28.026  4907  5048 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 172 ms] updated apps [took 171 ms] 
,03-21 07:33:28.092   890  1495 W libprocessgroup: failed to open /acct/uid_10049/pid_3143/cgroup.procs: No such file or directory
,03-21 07:33:28.108   890   905 I ActivityManager: Killing 4237:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-21 07:33:28.127  5055  5055 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 07:33:28.215   279   729 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (14:287 vsyncs) (16:1158)
,03-21 07:33:28.300   890  1511 W libprocessgroup: failed to open /acct/uid_10016/pid_4237/cgroup.procs: No such file or directory
,03-21 07:33:28.496   890  4371 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5085 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-21 07:33:28.558  5085  5085 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-21 07:33:28.581  3226  4370 I art     : Explicit concurrent mark sweep GC freed 3295(134KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 445us total 27.517ms
,03-21 07:33:28.665   890  1511 I ActivityManager: Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=5108 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:28.737   890  1578 I ActivityManager: Killing 4881:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-21 07:33:28.830  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:28.905   890   906 W libprocessgroup: failed to open /acct/uid_10088/pid_4881/cgroup.procs: No such file or directory
,03-21 07:33:28.912   890  1578 I ActivityManager: Killing 4933:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-21 07:33:28.921  5024  5024 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-21 07:33:28.922  5024  5024 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 07:33:28.983  5108  5108 E SQLiteLog: (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-21 07:33:29.046   890  1525 W libprocessgroup: failed to open /acct/uid_10019/pid_4933/cgroup.procs: No such file or directory
,03-21 07:33:29.049   890  1559 I ActivityManager: Killing 4957:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-21 07:33:29.245   890   906 W libprocessgroup: failed to open /acct/uid_10027/pid_4957/cgroup.procs: No such file or directory
,03-21 07:33:29.254   890  1231 V AlarmManager: send {107acd03, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,03-21 07:33:29.254   890   890 V AlarmManager: done {107acd03, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [4ms]
,03-21 07:33:29.256  4980  4980 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.onStartCommand(150): Beginning daily hygiene
,03-21 07:33:29.323  5108  5108 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-21 07:33:29.351   890  1509 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5137 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-21 07:33:29.369  1953  2062 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-21 07:33:29.409   890  4371 I art     : Explicit concurrent mark sweep GC freed 14613(741KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.585ms total 129.427ms
,03-21 07:33:29.416  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:29.423  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:29.426  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:29.473  5137  5137 D PhoneMonitor: Register our PhoneStateListener
,03-21 07:33:29.528  1953  2062 D Icing   : Loaded CLD2 Version V2.0 - 20141016
03-21 07:33:29.528  5137  5137 V SetupWizard: Connected to Gservices successfully
,03-21 07:33:29.587   890  1509 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5162 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-21 07:33:29.605  1953  2062 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-21 07:33:29.671  2034  2460 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-21 07:33:29.757   890   905 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5182 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:29.832   890  1578 I ActivityManager: Killing 4907:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-21 07:33:29.925   890  1579 W libprocessgroup: failed to open /acct/uid_10039/pid_4907/cgroup.procs: No such file or directory
,03-21 07:33:29.935  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:29.935  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:29.942  5182  5182 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-21 07:33:29.942  5182  5182 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-21 07:33:29.942  5182  5182 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:33:29.942  5182  5182 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-21 07:33:29.989  4980  4980 I Finsky  : [1] com.google.android.finsky.utils.ExternalReferrer.a(4312): Package state data is missing for com.test.thalitest
,03-21 07:33:30.027   890  1578 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5206 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-21 07:33:30.050   307   307 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 271us total 22.856ms
,03-21 07:33:30.069   307   307 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 19.101ms
,03-21 07:33:30.072   890  4371 I ActivityManager: Killing 5055:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-21 07:33:30.090   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.525ms
,03-21 07:33:30.209   890  1559 W libprocessgroup: failed to open /acct/uid_10090/pid_5055/cgroup.procs: No such file or directory
,03-21 07:33:30.214  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:30.308  1953  5052 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-21 07:33:30.324  4980  5009 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
,03-21 07:33:30.324  4980  5009 I qtaguid : Untagging socket 38 failed errno=-22
03-21 07:33:30.324  4980  5009 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
03-21 07:33:30.328  4980  4980 I Finsky  : [1] com.google.android.finsky.utils.hn.a(147): Skipping DFE self-update. Local Version [80621400] >= Server Version [-1]
,03-21 07:33:30.346  1953  5052 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-21 07:33:30.470   890  1525 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5233 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-21 07:33:30.476  1953  1953 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-21 07:33:30.518  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:30.559  5233  5233 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:33:30.559  5233  5233 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:33:30.608  5233  5233 I MultiDex: VM with version 2.1.0 has multidex support
03-21 07:33:30.608  5233  5233 I MultiDex: install
03-21 07:33:30.608  5233  5233 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-21 07:33:30.643  5233  5233 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:33:30.700  5206  5223 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
03-21 07:33:30.710  5233  5233 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-21 07:33:30.710  5233  5233 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25eb63c9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 07:33:30.710  5233  5233 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:33:30.733  5233  5233 D ChimeraCfgMgr: Reading stored module config
,03-21 07:33:30.772  1953  1953 D AsyncTaskServiceImpl: Submit a task: k
,03-21 07:33:30.808  1953  5264 D k       : Processing package: com.test.thalitest
,03-21 07:33:30.834  1953  5264 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
03-21 07:33:30.835  1953  5264 D k       : Found info for package com.test.thalitest in db.
,03-21 07:33:30.861  1953  5263 W BaseAppContext: Using Auth Proxy for data requests.
03-21 07:33:30.861  1953  5263 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 07:33:30.874  1953  5263 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 07:33:30.883  1953  5263 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 07:33:30.957   890  1579 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5270 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-21 07:33:30.961  1953  5263 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 07:33:31.014  5233  5262 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-21 07:33:31.043  4980  5010 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-21 07:33:31.043  4980  5010 I qtaguid : Untagging socket 38 failed errno=-22
03-21 07:33:31.043  4980  5010 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-21 07:33:31.126  5233  5233 D CAR.SERVICE: Connecting to CarCallService...
,03-21 07:33:31.154  5233  5233 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
03-21 07:33:31.155  5233  5233 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-21 07:33:31.215   890  1234 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:33:31.223  5233  5233 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,03-21 07:33:31.253  5233  5233 D CAR.TEL.Service: Creating a new CarCallService.
,03-21 07:33:31.259  5233  5233 D CAR.TEL.PhoneAdapter: Creating a new PhoneAdapter instance
,03-21 07:33:31.282   890  1521 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,03-21 07:33:31.320  5233  5233 D CAR.TEL.PhoneAdapter: setListener: com.google.android.gms.car.dn@329b47f5
,03-21 07:33:31.326   890  1252 W ActivityManager: Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
03-21 07:33:31.326  5233  5233 D CAR.TEL.PhoneAdapter: Returning an existing PhoneAdapter instance.
03-21 07:33:31.327  5233  5233 D CAR.TEL.Service: Starting CarCallService with initial phone null
,03-21 07:33:31.384  5233  5250 W art     : Suspending all threads took: 21.649ms
,03-21 07:33:31.415   890   890 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,03-21 07:33:31.416   890   890 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-21 07:33:31.420   890   890 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-21 07:33:31.432   890   890 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-21 07:33:31.433   890   890 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c590d18
,03-21 07:33:31.519  5233  5252 D CAR.SERVICE: Package validated; name: com.android.vending
,03-21 07:33:31.581  1580  1580 I Launcher: Deferring update until onResume
,03-21 07:33:31.605  2034  2034 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-21 07:33:31.715  1953  5259 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-21 07:33:31.816  5206  5223 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 1114 ms] updated apps [took 1114 ms] 
03-21 07:33:31.817   890  1307 I ActivityManager: Killing 5085:com.motorola.context/u0a8 (adj 15): empty #7
,03-21 07:33:31.976  2034  4526 I art     : Explicit concurrent mark sweep GC freed 45984(2MB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 13MB/22MB, paused 1.149ms total 264.962ms
,03-21 07:33:32.023  1953  2062 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-21 07:33:32.025   890  1521 W libprocessgroup: failed to open /acct/uid_10008/pid_5085/cgroup.procs: No such file or directory
,03-21 07:33:32.037   890  1511 I ActivityManager: Killing 4832:com.google.android.talk/u0a70 (adj 15): empty #7
,03-21 07:33:32.107  1953  2062 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, current pid is = 293
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, pid match
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-21 07:33:32.204   293   510 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, power_supply subsys
03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, current pid is = 293
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, pid match
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-21 07:33:32.204   293   510 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, power_supply subsys
03-21 07:33:32.204   293   510 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, current pid is = 293
03-21 07:33:32.204   293   510 I MDMCTBK : checkDefaultInst, pid match
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-21 07:33:32.204   293   510 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-21 07:33:32.204   293   510 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-21 07:33:32.272   890  1495 W libprocessgroup: failed to open /acct/uid_10070/pid_4832/cgroup.procs: No such file or directory
,03-21 07:33:32.367  5270  5270 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-21 07:33:32.367  5270  5270 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 07:33:32.367  5270  5270 I GAv4    :   adb logcat -s GAv4
,03-21 07:33:32.384  5270  5270 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 07:33:32.407  5270  5270 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 07:33:32.417  5270  5309 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 07:33:32.433  5270  5270 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-21 07:33:32.499  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:32.635   278   396 E Vold    : Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
03-21 07:33:32.635   278   396 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 07:33:32.636  5270  5314 W ContextImpl: Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,03-21 07:33:32.666  5270  5315 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:33:32.667  5270  5315 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:33:32.692   890  1509 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5316 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:32.694   890  1509 I ActivityManager: Killing 5024:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-21 07:33:32.805   890  1578 W libprocessgroup: failed to open /acct/uid_10005/pid_5024/cgroup.procs: No such file or directory
,03-21 07:33:32.822  1953  2062 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-21 07:33:32.841  4980  5009 I qtaguid : Failed write_ctrl(u 38) res=-1 errno=22
03-21 07:33:32.841  4980  5009 I qtaguid : Untagging socket 38 failed errno=-22
03-21 07:33:32.841  4980  5009 W NetworkManagementSocketTagger: untagSocket(38) failed with errno -22
,03-21 07:33:32.870   890  1231 V AlarmManager: send {3895ed9a, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-21 07:33:32.895   890   906 W ActivityManager: getRecentTasks: caller 10032 is using old GET_TASKS but privileged; allowing
,03-21 07:33:32.912  5270  5315 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:33:32.940  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-21 07:33:32.940  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:32.941   890  1307 I art     : Explicit concurrent mark sweep GC freed 21336(1016KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 2.659ms total 129.351ms
,03-21 07:33:32.957  5316  5316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 07:33:32.996  4980  4980 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:33:32.997  4980  4980 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:33:33.050  5270  5315 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 07:33:33.051  5270  5315 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:33:33.063  1953  2062 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-21 07:33:33.083  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:33.219  4980  4980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 07:33:33.241  4980  4980 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.b(10426): Logging device features
,03-21 07:33:33.250   890  1231 V AlarmManager: send {165c95f2, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,03-21 07:33:33.281  2034  4526 D DeviceConnectionService: client connected with version: 8298000
,03-21 07:33:33.286  2034  2034 D WearableService: callingUid 10016, callindPid: 2034
,03-21 07:33:33.334  4980  4980 E Finsky  : [1] com.google.android.finsky.wear.ba.a(689): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-21 07:33:33.336  4980  4980 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6302): Dropping command=hygiene due to Gms not connected
,03-21 07:33:33.347   890  1495 I ActivityManager: Killing 5162:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-21 07:33:33.505   890  1495 I ActivityManager: Killing 5137:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,03-21 07:33:33.690   890  1252 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5353 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:33.691   890   905 W libprocessgroup: failed to open /acct/uid_10019/pid_5162/cgroup.procs: No such file or directory
,03-21 07:33:33.701   890  1579 W libprocessgroup: failed to open /acct/uid_10035/pid_5137/cgroup.procs: No such file or directory
,03-21 07:33:33.748   890  1495 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5370 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:33.856   890  1495 I ActivityManager: Killing 5182:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-21 07:33:33.867  5353  5353 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 07:33:33.954  5370  5398 I Gmail   : getAccountsCursor
,03-21 07:33:34.025   890  1603 W libprocessgroup: failed to open /acct/uid_10027/pid_5182/cgroup.procs: No such file or directory
,03-21 07:33:34.029  5353  5353 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2aae08be(com.android.providers.calendar.CalendarProvider2@33b7cd1f)
,03-21 07:33:34.031  5370  5399 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-21 07:33:34.032  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:34.080   890  4371 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5402 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:34.083  5108  5131 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,03-21 07:33:34.208  5108  5131 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 07:33:34.253  5370  5370 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 07:33:34.272  5402  5402 I Exchange: EasService.onCreate
,03-21 07:33:34.275   890  1525 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-21 07:33:34.283  5370  5428 I Gmail   : Observing account changes for notifications
,03-21 07:33:34.308  5402  5430 I Exchange: RestartPingTask
,03-21 07:33:34.328  5402  5402 I Exchange: RestartPingsTask did not start any pings.
03-21 07:33:34.328  5402  5402 I Exchange: PSS stopIfIdle
03-21 07:33:34.328  5402  5402 I Exchange: PSS has no active accounts; stopping service.
,03-21 07:33:34.340  5370  5398 I Gmail   : getAccountsCursor
,03-21 07:33:34.350  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:34.352  5402  5402 I Exchange: onDestroy
,03-21 07:33:34.355   890   905 I ActivityManager: Killing 5206:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-21 07:33:34.410  1953  1970 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-21 07:33:34.479   890  1603 W libprocessgroup: failed to open /acct/uid_10039/pid_5206/cgroup.procs: No such file or directory
03-21 07:33:34.479  2634  2634 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-21 07:33:34.486   890  1252 I ActivityManager: Killing 5270:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,03-21 07:33:34.490  2634  2634 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-21 07:33:34.637   890  1495 W libprocessgroup: failed to open /acct/uid_10057/pid_5270/cgroup.procs: No such file or directory
,03-21 07:33:34.641  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:34.648   890  1252 I ActivityManager: Killing 5233:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-21 07:33:34.674  5370  5442 E SQLiteLog: (283) recovered 68 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-21 07:33:34.729  5370  5446 I Gmail   : notifyAccountChanged
,03-21 07:33:34.731  5370  5434 I Gmail   : getAccountsCursor
,03-21 07:33:34.733  5370  5446 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:34.738   890  1307 W libprocessgroup: failed to open /acct/uid_10016/pid_5233/cgroup.procs: No such file or directory
03-21 07:33:34.738  5370  5446 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:34.741   890  1307 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,03-21 07:33:34.747  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:34.752  1300  1854 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-21 07:33:34.762  5370  5446 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:34.764  5370  5446 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:34.798   890  1307 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5448 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-21 07:33:34.874  5448  5448 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-21 07:33:34.878  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:34.883  1300  1300 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
,03-21 07:33:34.922  5370  5399 I Gmail   : getAccountsCursor
,03-21 07:33:34.928  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:34.976  2034  2493 E MDM     : [188] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-21 07:33:34.983  2034  2034 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-21 07:33:34.985  1953  5473 D LocationInitializer: Restart initialization of location
,03-21 07:33:34.994  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:35.043   890  1559 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5477 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-21 07:33:35.078  2034  2075 W GCoreFlp: No location to return for getLastLocation()
03-21 07:33:35.078  2034  5474 W FusedLocationProvider: location=null
,03-21 07:33:35.218  5353  5353 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-21 07:33:35.219  5353  5353 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 07:33:35.222   890  1511 I ActivityManager: Killing 4980:com.android.vending/u0a32 (adj 15): empty #7
,03-21 07:33:35.345   890  1252 W libprocessgroup: failed to open /acct/uid_10032/pid_4980/cgroup.procs: No such file or directory
,03-21 07:33:35.511   890  1495 I art     : Explicit concurrent mark sweep GC freed 15278(807KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 3.338ms total 135.029ms
,03-21 07:33:35.607   890  1578 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5504 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-21 07:33:35.651   890  1525 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5520 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-21 07:33:35.653   890  1525 I ActivityManager: Killing 5316:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-21 07:33:35.838  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:35.898   890  1579 I ActivityManager: Killing 5353:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-21 07:33:36.005   890  1252 W libprocessgroup: failed to open /acct/uid_10090/pid_5316/cgroup.procs: No such file or directory
03-21 07:33:36.011   890  1603 W libprocessgroup: failed to open /acct/uid_10005/pid_5353/cgroup.procs: No such file or directory
,03-21 07:33:36.015  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:36.015  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:36.072  5520  5520 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 07:33:36.255  5520  5552 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-21 07:33:36.255  5520  5552 I Babel_SMS: MmsConfig.loadMmsSettings
03-21 07:33:36.255  5520  5552 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-21 07:33:36.255  5520  5552 I Babel_SMS: MmsConfig.loadFromDatabase
,03-21 07:33:36.310  5520  5552 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-21 07:33:36.310  5520  5552 I Babel_SMS: MmsConfig.loadFromResources
,03-21 07:33:36.325  5520  5552 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-21 07:33:36.326  5520  5552 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-21 07:33:36.406  5520  5520 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-21 07:33:36.409  5520  5520 I Babel_Crash: startup - clean
,03-21 07:33:36.425   303   394 I ThermalEngine: Sensor:xo_therm_pu2:38000 mC
,03-21 07:33:36.426  5520  5559 I Babel   : deleted: false for 0
,03-21 07:33:36.527   890  1578 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5561 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:36.548   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.705ms
,03-21 07:33:36.568   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 19.062ms
,03-21 07:33:36.582  5520  5520 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:36.588   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.899ms
,03-21 07:33:36.593  5520  5520 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-21 07:33:36.599  5520  5520 W VideoCapabilities: Unsupported mime video/mpeg2
,03-21 07:33:36.617  5561  5561 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-21 07:33:36.617  5561  5561 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-21 07:33:36.617  5561  5561 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:33:36.618  5561  5561 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-21 07:33:36.646  5520  5520 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-21 07:33:36.654  5520  5520 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-21 07:33:36.655  5520  5520 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:36.658  5520  5520 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:36.665  5520  5520 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-21 07:33:36.710   890  1559 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5583 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:36.788   890  1307 I ActivityManager: Killing 5402:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-21 07:33:36.812  5520  5535 W art     : Suspending all threads took: 8.171ms
,03-21 07:33:36.839  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:36.926   890  4371 W libprocessgroup: failed to open /acct/uid_10060/pid_5402/cgroup.procs: No such file or directory
,03-21 07:33:36.930  5520  5520 I vclib   : onServiceConnected
,03-21 07:33:36.931  5520  5520 W Babel   : Attempted to change video mute state without an active call.
,03-21 07:33:36.954  5520  5520 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:33:36.954  5520  5520 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:33:36.994  5520  5520 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 07:33:37.042  5583  5583 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 07:33:37.053  5520  5520 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-21 07:33:37.053  5520  5520 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 07:33:37.162  5583  5583 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-21 07:33:37.176  5583  5583 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:37.177  5583  5583 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:37.228  5583  5583 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 07:33:37.228  5583  5583 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
03-21 07:33:37.230  5583  5628 D Ads     : Skipping gmscore version check
03-21 07:33:37.231  5583  5583 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
03-21 07:33:37.234  5583  5583 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
03-21 07:33:37.260  1580  1580 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15307196 new=com.google.android.velvet.VelvetApplication@15307196
03-21 07:33:37.260  5477  5629 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-21 07:33:37.266  1953  5052 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
03-21 07:33:37.266  1953  5052 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-21 07:33:37.271  5583  5583 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-21 07:33:37.309   890  1252 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5631 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:37.351  1953  5052 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-21 07:33:37.368  1953  2062 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-21 07:33:37.412  5631  5631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 07:33:37.460  5477  5629 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 198 ms] updated apps [took 198 ms] 
,03-21 07:33:37.463   890  1559 I ActivityManager: Killing 5370:com.google.android.gm/u0a63 (adj 15): empty #7
,03-21 07:33:37.572   279   279 I SFPerfTracer:      triggers: (rate: 15:356) (compose: 0:1) (post: 0:1) (render: 0:2) (38:1108 frames) (39:1198)
03-21 07:33:37.572   279   279 D SFPerfTracer:        layers: (3:11) (FocusedStackFrame (0xb751b5c0): 0:14)* (DimLayer (0xb7566ed8): 0:6)* (StatusBar (0xb7524258): 39:166) (NavigationBar (0xb75254e8): 0:34) (com.android.systemui.ImageWallpaper (0xb75278d8): 0:36)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7586730): 0:54)- (Starting com.test.thalitest (0xb752ab30): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb74d5c78): 0:56) 
,03-21 07:33:37.675   890  1511 W libprocessgroup: failed to open /acct/uid_10063/pid_5370/cgroup.procs: No such file or directory
,03-21 07:33:37.853   890  1603 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5664 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:37.966  5664  5664 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-21 07:33:37.994   890  1511 I ActivityManager: Killing 5448:com.motorola.context/u0a8 (adj 15): empty #7
,03-21 07:33:38.275   890  1521 W libprocessgroup: failed to open /acct/uid_10008/pid_5448/cgroup.procs: No such file or directory
,03-21 07:33:38.277   890  1231 V AlarmManager: send {26ad15cf, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,03-21 07:33:38.279   890  1231 V AlarmManager: send {31933f79, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,03-21 07:33:38.282  5664  5664 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2aae08be(com.android.providers.calendar.CalendarProvider2@33b7cd1f)
,03-21 07:33:38.294   890   890 V AlarmManager: done {3895ed9a, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [5424ms]
,03-21 07:33:38.307  5664  5692 E SQLiteLog: (284) automatic index on view_events(_id)
,03-21 07:33:38.318   890   890 V AlarmManager: done {165c95f2, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [5069ms]
,03-21 07:33:38.330  5583  5693 I Finsky  : [635] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(164): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-21 07:33:38.365   890  1307 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5698 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:38.390  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:38.397  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:38.398  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:38.515  5698  5723 I Gmail   : getAccountsCursor
,03-21 07:33:38.517  5698  5724 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-21 07:33:38.521  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:38.594   890  1307 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5727 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:38.683  1953  2062 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-21 07:33:38.697  5727  5727 I Exchange: EasService.onCreate
,03-21 07:33:38.700   890  1525 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-21 07:33:38.714  5727  5751 I Exchange: RestartPingTask
,03-21 07:33:38.717  5698  5698 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-21 07:33:38.721  5698  5750 I Gmail   : Observing account changes for notifications
,03-21 07:33:38.754  1953  2062 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-21 07:33:38.760  5727  5727 I Exchange: RestartPingsTask did not start any pings.
03-21 07:33:38.760  5727  5727 I Exchange: PSS stopIfIdle
03-21 07:33:38.761  5727  5727 I Exchange: PSS has no active accounts; stopping service.
,03-21 07:33:38.779  5698  5723 I Gmail   : getAccountsCursor
,03-21 07:33:38.849  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:38.908   890  1603 I art     : Explicit concurrent mark sweep GC freed 11283(568KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.537ms total 127.012ms
,03-21 07:33:38.915  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:38.925   890  1307 I ActivityManager: Killing 5504:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-21 07:33:39.174   890  1521 W libprocessgroup: failed to open /acct/uid_10019/pid_5504/cgroup.procs: No such file or directory
,03-21 07:33:39.176  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:39.176  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:39.177  5727  5727 I Exchange: onDestroy
,03-21 07:33:39.189  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:39.217  5698  5768 E SQLiteLog: (283) recovered 69 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-21 07:33:39.235   890  1603 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5771 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-21 07:33:39.268   890  1603 I ActivityManager: Killing 5561:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-21 07:33:39.293  5698  5770 I Gmail   : notifyAccountChanged
,03-21 07:33:39.294  5698  5724 I Gmail   : getAccountsCursor
,03-21 07:33:39.297  5698  5770 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:39.301  5698  5770 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-21 07:33:39.308  5698  5770 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:39.309  5698  5770 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-21 07:33:39.310  5664  5664 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-21 07:33:39.310  5664  5664 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-21 07:33:39.385   890  1521 W libprocessgroup: failed to open /acct/uid_10027/pid_5561/cgroup.procs: No such file or directory
,03-21 07:33:39.398  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:39.407  5771  5771 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-21 07:33:39.421   890  1525 I ActivityManager: Killing 5477:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-21 07:33:39.515   890  1252 W libprocessgroup: failed to open /acct/uid_10039/pid_5477/cgroup.procs: No such file or directory
,03-21 07:33:39.528   890   890 V AlarmManager: done {26ad15cf, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1470ms]
03-21 07:33:39.528   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=15.11 rxSuccessRate=16.76 targetRoamBSSID=any RSSI=-42
03-21 07:33:39.529   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=24777 interval=30000 maxinterval=300000
03-21 07:33:39.529   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-21 07:33:39.529   890  1242 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-21 07:33:39.529   890  1242 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
03-21 07:33:39.530  1416  1416 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-21 07:33:39.530   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-21 07:33:39.530   293  1656 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
,03-21 07:33:39.531   890  1242 E WifiStateMachine: [1,458,542,019,531 ms] noteScanstart no scan source
,03-21 07:33:39.536   890   890 V AlarmManager: done {31933f79, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [1479ms]
,03-21 07:33:39.582   890   906 I ActivityManager: Killing 5631:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-21 07:33:39.595   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 2
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 3
,03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 1
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 6
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 6
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 7
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 9
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-BSS-REMOVED 8
03-21 07:33:39.596   293  1656 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-21 07:33:39.596   293  1656 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-21 07:33:39.597   484   505 D TCMD    : NL - Read 56 bytes from update socket.
03-21 07:33:39.597   484   505 D TCMD    : NL - message type is RTM_NEWLINK
03-21 07:33:39.597   484   505 D TCMD    : Listening for incoming client connection request
,03-21 07:33:39.600   890  1242 E WifiStateMachine: [1,458,542,019,600 ms] noteScanEnd no scan source
,03-21 07:33:39.601   890  1242 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@2418e5d5 sup_state=COMPLETED debouncing=false
,03-21 07:33:39.665   890  1559 W libprocessgroup: failed to open /acct/uid_10090/pid_5631/cgroup.procs: No such file or directory
,03-21 07:33:39.708  5698  5755 I Gmail   : getAccountsCursor
,03-21 07:33:39.712  2034  2034 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 07:33:40.852  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:41.972  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-21 07:33:41.972  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:42.077   890  1307 I ActivityManager: Killing 5520:com.google.android.talk/u0a70 (adj 15): empty #7
,03-21 07:33:42.132   890  1227 D BatteryService: uevent={POWER_SUPPLY_TEMP=336, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311028, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-152, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,03-21 07:33:42.188   890  1559 W libprocessgroup: failed to open /acct/uid_10070/pid_5520/cgroup.procs: No such file or directory
,03-21 07:33:42.192  2518  2583 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-21 07:33:42.831   890  1231 V AlarmManager: send {2a04a232, *walarm*:android.content.syncmanager.SYNC_ALARM}
,03-21 07:33:42.832   890   890 V AlarmManager: done {2a04a232, *walarm*:android.content.syncmanager.SYNC_ALARM} [1ms]
,03-21 07:33:43.732  5698  5748 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-21 07:33:44.617  4754  4902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 07:33:44.617  4754  4902 I jxcore-log: 
,03-21 07:33:44.622  4754  4902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 07:33:44.622  4754  4902 I jxcore-log: 
,03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:33:44.626  4754  4902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-21 07:33:44.628  4754  4902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-21 07:33:44.631  4754  4902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 07:33:44.631  4754  4902 I jxcore-log: 
,03-21 07:33:44.634  4754  4902 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 07:33:44.634  4754  4902 I jxcore-log: 
,03-21 07:33:44.987  1300  1300 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-21 07:33:44.987  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:45.440  4754  4902 I jxcore-log: Unit Test app is loaded
03-21 07:33:45.440  4754  4902 I jxcore-log: 
,03-21 07:33:45.448  4754  4902 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 07:33:45.448  4754  4902 I jxcore-log: 
,03-21 07:33:45.456  4754  4902 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,03-21 07:33:45.460  4754  4902 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-21 07:33:45.460  4754  4902 I jxcore-log: 
,03-21 07:33:45.463  4754  4754 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 07:33:45.465  4754  4902 I jxcore-log: logCallback not set !!!!
03-21 07:33:45.465  4754  4902 I jxcore-log: 
,03-21 07:33:45.470  4754  4902 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-21 07:33:45.470  4754  4902 I jxcore-log:   bluetooth: 'on',
03-21 07:33:45.470  4754  4902 I jxcore-log:   wifi: 'on',
03-21 07:33:45.470  4754  4902 I jxcore-log:   cellular: 'doNotCare',
03-21 07:33:45.470  4754  4902 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-21 07:33:45.470  4754  4902 I jxcore-log: 
,03-21 07:33:45.470  4754  4902 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 07:33:45.470  4754  4902 I jxcore-log: 
,03-21 07:33:45.986  5809  5809 D AndroidRuntime: 
03-21 07:33:45.986  5809  5809 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-21 07:33:45.992  5809  5809 D AndroidRuntime: CheckJNI is OFF
,03-21 07:33:46.267  5809  5809 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 07:33:46.281   890  1130 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-21 07:33:46.281   890  1130 I ActivityManager: Killing 4754:com.test.thalitest/u0a109 (adj 0): stop com.test.thalitest
,03-21 07:33:46.336   890  1156 W PackageSettings: Skipping PackageSetting{2446ea24 com.example.hello/10568} due to missing metadata
,03-21 07:33:46.355   890  4371 I WindowState: WIN DEATH: Window{20661d42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-21 07:33:46.355   890  1245 D WifiService: Client connection lost with reason: 4
,03-21 07:33:46.429   303   394 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-21 07:33:46.493   890  1130 W ActivityManager: Force removing ActivityRecord{11586ca5 u0 com.test.thalitest/.MainActivity t9}: app died, no saved state
,03-21 07:33:46.504  1483  3976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-21 07:33:46.509   890   906 W ActivityManager: Spurious death for ProcessRecord{35d18d39 4754:com.test.thalitest/u0a109}, curProc for 4754: null
03-21 07:33:46.509   890  1156 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-21 07:33:46.564  3072  3072 I art     : Explicit concurrent mark sweep GC freed 11701(1705KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 770us total 45.438ms
,03-21 07:33:46.582  1580  1580 I art     : Explicit concurrent mark sweep GC freed 2547(135KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 489us total 55.065ms
,03-21 07:33:46.593   890  1234 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:33:46.599  2034  2108 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 07:33:46.616  2634  2634 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-21 07:33:46.620  2634  2634 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-21 07:33:46.629  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 07:33:46.629  1425  1425 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 07:33:46.638  2634  2634 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-21 07:33:46.640  1649  5828 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 07:33:46.643  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 07:33:46.646  1425  5827 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 07:33:46.689   890  1603 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5833 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:46.692  2634  2634 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-21 07:33:46.716  2634  2634 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-21 07:33:46.717  2634  2634 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 07:33:46.765   890  1521 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4754 uid 10109
,03-21 07:33:46.766  5833  5833 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-21 07:33:46.767  5833  5833 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-21 07:33:46.767  5833  5833 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-21 07:33:46.767  5833  5833 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-21 07:33:46.775   890   890 I art     : Explicit concurrent mark sweep GC freed 23132(1642KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 11.795ms total 216.326ms
,03-21 07:33:46.777   890  1156 I art     : WaitForGcToComplete blocked for 153.049ms for cause Explicit
,03-21 07:33:46.780  1425  1425 I Keyboard.Facilitator: onFinishInput()
,03-21 07:33:46.806   890  1145 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,23569
,03-21 07:33:46.807   890  1145 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,23134 (total)
,03-21 07:33:46.853  1425  5827 I Decoder : createOrResetDecoder
,03-21 07:33:46.877   890  1578 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5857 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-21 07:33:46.897   890   906 I ActivityManager: Killing 5583:com.android.vending/u0a32 (adj 15): empty #7
,03-21 07:33:46.950   890   890 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 07:33:46.951   890   890 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-21 07:33:46.955   890  1156 I art     : Explicit concurrent mark sweep GC freed 5381(303KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 4.586ms total 177.069ms
,03-21 07:33:47.021  2034  2034 I ConfigService: onCreate
,03-21 07:33:47.024  5809  5809 D AndroidRuntime: Shutting down VM
,03-21 07:33:47.041   890  1579 W libprocessgroup: failed to open /acct/uid_10032/pid_5583/cgroup.procs: No such file or directory
,03-21 07:33:47.055  1580  1580 I Launcher: Deferring update until onResume
,03-21 07:33:47.062  1300  1300 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-21 07:33:47.076  5857  5857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-21 07:33:47.088  1425  5827 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 07:33:47.095   890  1156 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5875 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-21 07:33:47.095   890  1263 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-21 07:33:47.096   890  1263 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-21 07:33:47.142   890  1252 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5894 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:33:47.149   890  1603 I ActivityManager: Killing 5727:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-21 07:33:47.175  1425  5827 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 07:33:47.187  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 07:33:47.187  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 07:33:47.195   890  1509 W libprocessgroup: failed to open /acct/uid_10060/pid_5727/cgroup.procs: No such file or directory
,03-21 07:33:47.202   890  1603 I ActivityManager: Killing 5771:com.motorola.context/u0a8 (adj 15): empty #7
,03-21 07:33:47.255   890   905 W libprocessgroup: failed to open /acct/uid_10008/pid_5771/cgroup.procs: No such file or directory
,03-21 07:33:47.279   890  1231 V AlarmManager: send {20a97cdd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,03-21 07:33:47.280   890   890 V AlarmManager: done {20a97cdd, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [2ms]
,03-21 07:33:47.295  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 07:33:47.295  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-21 07:33:47.325  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 07:33:47.325  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-21 07:33:47.335  1425  5827 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-21 07:33:47.338  5894  5894 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-21 07:33:47.344  1425  5827 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-21 07:33:47.344  1425  5827 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 07:33:47.344  1425  5827 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 07:33:47.345  1425  5827 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 07:33:47.345  1425  5827 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-21 07:33:47.447  5894  5894 E RollingFileStream: Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,03-21 07:33:47.456  5894  5894 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-21 07:33:47.469  5894  5894 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:47.470  5894  5894 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-21 07:33:47.769   279   689 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
