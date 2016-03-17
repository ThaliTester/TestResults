#### Test 62509094764c200_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,03-17 06:45:01.584   881  1596 W libprocessgroup: failed to open /acct/uid_10019/pid_4523/cgroup.procs: No such file or directory
--------- beginning of main
03-17 06:45:01.857  2565  2565 D OtaApp  : [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
03-17 06:45:01.859  2565  2565 D OtaApp  : [debug] > UpdateReceiver: Received true from doSanityCheck.
03-17 06:45:01.859  2565  2565 D OtaApp  : [debug] > In cancelAnyPendingIntentSetPreviously
03-17 06:45:01.862   881  1244 I ActivityManager: START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
03-17 06:45:01.885  2565  2565 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-17 06:45:01.889  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-17 06:45:01.897  2565  2565 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-17 06:45:01.902  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-17 06:45:01.904  2565  2565 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
03-17 06:45:01.908  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-17 06:45:01.925  2565  2565 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-17 06:45:01.932  2565  2565 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-17 06:45:01.947  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-17 06:45:02.010  2565  2639 I SundryService: onHandleIntent(): action=com.motorola.ccc.notification.action.NOTIFY
03-17 06:45:02.010  2565  2639 D WaitableIntentService: setWaitEnabled(): mWaitCount=0 isWaitEnabled=false
03-17 06:45:02.010  2565  2639 D SundryService: onHandleIntent(): isWaitEnabled=false
03-17 06:45:02.010  2565  2639 D WaitableIntentService: ServiceHandler.handleMessage: mWaitCount=0
03-17 06:45:02.051   881   897 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4708 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:45:02.070  4693  4693 D AndroidRuntime: 
03-17 06:45:02.070  4693  4693 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 06:45:02.074  4693  4693 D AndroidRuntime: CheckJNI is OFF
03-17 06:45:02.096  1962  1973 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-17 06:45:02.108  2565  2565 D GetNotificationsWS: unbindWebServices(): un-registering our AIDL callback...
03-17 06:45:02.218  4708  4737 I Gmail   : getAccountsCursor
03-17 06:45:02.222  4708  4738 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-17 06:45:02.229  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 06:45:02.287  4693  4693 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 06:45:02.308   881  1244 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=4742 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:45:02.308   881  1571 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 06:45:02.333   279  1134 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (145 us)
03-17 06:45:02.353  1466  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 06:45:02.365  4693  4693 D AndroidRuntime: Shutting down VM
03-17 06:45:02.412   881  1534 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4761 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:45:02.434   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 22.257ms
03-17 06:45:02.454   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 19.378ms
03-17 06:45:02.478   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.988ms
03-17 06:45:02.481  1466  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 06:45:02.504   881  1596 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-17 06:45:02.522  4708  4780 I Gmail   : Observing account changes for notifications
03-17 06:45:02.538  4742  4742 I Exchange: EasService.onCreate
03-17 06:45:02.543  4742  4783 I Exchange: RestartPingTask
03-17 06:45:02.552  4708  4708 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-17 06:45:02.558  4742  4742 I Exchange: RestartPingsTask did not start any pings.
03-17 06:45:02.558  4742  4742 I Exchange: PSS stopIfIdle
03-17 06:45:02.558  4742  4742 I Exchange: PSS has no active accounts; stopping service.
,03-17 06:45:02.606   881  1132 I ActivityManager: Waited long enough for: ServiceRecord{a0d5c03 u0 com.motorola.ccc.checkin/.CheckinService}
,03-17 06:45:02.607   293   523 I MDMCTBK : NetlinkHandler, power_supply subsys
03-17 06:45:02.607   293   523 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-17 06:45:02.607   293   523 I MDMCTBK : checkDefaultInst, current pid is = 293
03-17 06:45:02.607   293   523 I MDMCTBK : checkDefaultInst, pid match
03-17 06:45:02.607   293   523 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-17 06:45:02.607   293   523 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-17 06:45:02.607   293   523 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-17 06:45:02.626  4708  4738 I Gmail   : getAccountsCursor
,03-17 06:45:02.636  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:45:02.643  4742  4742 I Exchange: onDestroy
,03-17 06:45:02.649   881   897 I ActivityManager: Killing 4561:com.android.chrome/u0a52 (adj 15): empty #7
,03-17 06:45:02.665  4761  4761 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-17 06:45:02.696   881  1596 W libprocessgroup: failed to open /acct/uid_10052/pid_4561/cgroup.procs: No such file or directory
,03-17 06:45:02.720  4761  4761 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3744-3748)
03-17 06:45:02.720  4761  4761 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:45:02.741  4761  4761 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bfc55c7}
,03-17 06:45:02.741  4761  4761 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:45:02.742  4761  4761 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 06:45:02.759  4761  4761 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 06:45:02.760  4761  4761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:45:02.762  4761  4761 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 06:45:02.787  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:45:02.788  4761  4761 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 06:45:02.789  2565  2565 D 3CDM.DeviceAdminPushReceiver: Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-17 06:45:02.789  2565  2565 D 3CDM.DeviceAdminPushReceiver: Type: null
03-17 06:45:02.789  2565  2565 D 3CDM.DeviceAdminPushReceiver: Data: null
,03-17 06:45:02.792  2565  2636 D 3CDM.Service: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
03-17 06:45:02.793  2565  2636 D 3CDM.Service: Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
03-17 06:45:02.793  2565  2636 D 3CDM.Service: DeviceAdmin - syncWithCCC
03-17 06:45:02.793  2565  2636 D 3CDM.Service: blur.service.littlesister.gpsFixWaitTime = 60000
03-17 06:45:02.793  2565  2636 D 3CDM.Service: com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
03-17 06:45:02.793  2565  2636 D 3CDM.Service: blur.service.cred.locationToken = null
03-17 06:45:02.793  2565  2636 D 3CDM.Service: com.motorola.ccc.cce.email.marketing.optin.default = false
03-17 06:45:02.793  2565  2636 D 3CDM.Service: blur.service.littlesister.reportLevel2 = NONE
03-17 06:45:02.793  2565  2636 D 3CDM.Service: com.motorola.blur.adminfeed.device_admin_always_allowed = 1
03-17 06:45:02.793  2565  2636 D 3CDM.Service: com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,03-17 06:45:02.798  4602  4802 I CE-UpdateModelService: ACTION_REGISTRATION_COMPLETE
,03-17 06:45:02.799  4761  4761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 06:45:02.799  4761  4761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 06:45:02.801  4761  4761 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 06:45:02.801  4761  4761 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 06:45:02.801  4761  4761 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 06:45:02.801  4761  4761 I Adreno-EGL: Local Branch: 
03-17 06:45:02.801  4761  4761 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 06:45:02.801  4761  4761 I Adreno-EGL: Local Patches: NONE
03-17 06:45:02.801  4761  4761 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 06:45:02.803  2565  2636 D 3CDM.Service: Sync to CCE settings done, instantiate Locate now.
,03-17 06:45:02.809   881  1637 I ActivityManager: Killing 4107:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 06:45:02.822  4708  4803 E SQLiteLog: (283) recovered 110 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 06:45:02.879   881  1139 D BluetoothManagerService: Message: 20
03-17 06:45:02.879   881  1139 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6bf2297:true
,03-17 06:45:02.914  4708  4804 I Gmail   : notifyAccountChanged
,03-17 06:45:02.915  4708  4787 I Gmail   : getAccountsCursor
,03-17 06:45:02.918  4708  4804 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 06:45:02.923  4708  4804 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 06:45:02.932  4708  4804 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 06:45:02.933  4708  4804 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 06:45:02.942   881  1535 W libprocessgroup: failed to open /acct/uid_10090/pid_4107/cgroup.procs: No such file or directory
,03-17 06:45:02.949  1291  1291 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-17 06:45:02.949  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:02.951  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:45:02.954  2565  2636 D BSUtils : set .setup.DeviceAdminSetupReceiver enabled
,03-17 06:45:02.972  1746  1746 D WearableService: callingUid 10016, callindPid: 1746
,03-17 06:45:02.977  1962  4818 D LocationInitializer: Restart initialization of location
,03-17 06:45:02.985  1746  1746 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 06:45:02.989  1746  4816 E MDM     : [212] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 06:45:03.003  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:45:03.022  1746  1996 W GCoreFlp: No location to return for getLastLocation()
,03-17 06:45:03.022  1746  4819 W FusedLocationProvider: location=null
,03-17 06:45:03.076   881  1535 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=4825 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:45:03.127   279   731 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (33:190 vsyncs) (35:916)
,03-17 06:45:03.153  4761  4761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:45:03.162   279   279 I SFPerfTracer:      triggers: (rate: 13:550) (compose: 0:1) (post: 0:1) (render: 0:2) (9:840 frames) (10:918)
03-17 06:45:03.163   279   279 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb7dec7b8): 0:11)* (DimLayer (0xb7de2470): 0:4) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7de4aa8): 0:38)- (StatusBar (0xb7de8008): 0:131) (NavigationBar (0xb7dfe038): 0:34) (com.android.systemui.ImageWallpaper (0xb7e054a8): 0:33)* (Starting com.motorola.ccc.ota (0xb7e17828): 0:39)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e19f20): 1:50)* (Starting com.test.thalitest (0xb7de4aa8): 10:21) 
,03-17 06:45:03.166  4825  4825 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 06:45:03.170  4761  4761 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 06:45:03.186  4761  4761 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-17 06:45:03.192  4761  4761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:45:03.192  4761  4761 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:45:03.199  3005  3026 D Checkin : publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,03-17 06:45:03.212  4708  4737 I Gmail   : getAccountsCursor
,03-17 06:45:03.216  1746  1746 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:45:03.217  4825  4825 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@11aa8f48(com.android.providers.calendar.CalendarProvider2@16f721e1)
,03-17 06:45:03.230   881   881 V AlarmManager: done {45e8045, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [6243ms]
03-17 06:45:03.237  4825  4848 E SQLiteLog: (284) automatic index on view_events(_id)
,03-17 06:45:03.263   881  1596 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4850 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 06:45:03.281  4761  4859 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:45:03.294  4761  4761 D Atlas   : Validating map...
,03-17 06:45:03.411   881  1658 I art     : Explicit concurrent mark sweep GC freed 12228(627KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.475ms total 115.847ms
,03-17 06:45:03.416  4761  4810 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 06:45:03.430  4850  4850 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:45:03.452  4761  4859 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 06:45:03.457  4761  4859 D OpenGLRenderer: Enabling debug mode 0
,03-17 06:45:03.507  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-17 06:45:03.512   881  1140 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1146
,03-17 06:45:03.512   881  1140 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s146ms
,03-17 06:45:03.561  4761  4873 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 06:45:03.561  4761  4873 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 06:45:03.598  4761  4761 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4761
,03-17 06:45:03.674  4850  4881 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-17 06:45:03.674  4850  4881 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 06:45:03.674  4850  4881 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
03-17 06:45:03.674  4850  4881 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 06:45:03.706  4850  4881 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 06:45:03.706  4850  4881 I Babel_SMS: MmsConfig.loadFromResources
03-17 06:45:03.709  4850  4881 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 06:45:03.711  4850  4881 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-17 06:45:03.796  4761  4761 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 06:45:03.806  4850  4850 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 06:45:03.817  4850  4850 I Babel_Crash: startup - clean
,03-17 06:45:03.845  4850  4884 I Babel   : deleted: false for 0
,03-17 06:45:03.890  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:03.996   881  1637 I ActivityManager: Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=4886 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 06:45:03.998   881  1571 I ActivityManager: Killing 4645:com.qualcomm.timeservice/u0a96 (adj 15): empty #7
,03-17 06:45:04.172   881  1596 W libprocessgroup: failed to open /acct/uid_10096/pid_4645/cgroup.procs: No such file or directory
,03-17 06:45:04.203  4761  4859 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-17 06:45:04.203  4761  4859 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 06:45:04.246  4761  4871 D jxcore_app_log: JniHelper::setJavaVM(0xb7041310), pthread_self() = -1220631344
,03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 06:45:04.253  4761  4871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302b7343 added. We now have 1 listener(s)
,03-17 06:45:04.253   881   897 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-17 06:45:04.258  4761  4871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-17 06:45:04.260  4761  4871 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 06:45:04.262  4761  4871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
,03-17 06:45:04.262  4761  4871 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 06:45:04.262  4761  4871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 06:45:04.269  4761  4871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2618da3e added. We now have 1 listener(s)
03-17 06:45:04.270  4761  4871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-17 06:45:04.271  4825  4825 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 06:45:04.271  4825  4825 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 06:45:04.277   881  1658 I ActivityManager: Killing 4666:com.google.android.deskclock/u0a55 (adj 15): empty #7
,03-17 06:45:04.285   881  1237 D WifiService: New client listening to asynchronous messages
,03-17 06:45:04.288  4761  4871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-17 06:45:04.294  4761  4871 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-17 06:45:04.294  4761  4871 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-17 06:45:04.325  4850  4850 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:45:04.338  4850  4850 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-17 06:45:04.353  4850  4850 W VideoCapabilities: Unsupported mime video/mpeg2
,03-17 06:45:04.384  4850  4850 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 06:45:04.392  4850  4850 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:45:04.395  4850  4850 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:45:04.398  4850  4850 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:45:04.403  4850  4850 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:45:04.432   881  1572 W libprocessgroup: failed to open /acct/uid_10055/pid_4666/cgroup.procs: No such file or directory
,03-17 06:45:04.434  4761  4871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 06:45:04.434   881  1491 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 06:45:04.435  4761  4871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
03-17 06:45:04.436   881  1534 I ActivityManager: Killing 4742:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-17 06:45:04.502   881   897 W libprocessgroup: failed to open /acct/uid_10060/pid_4742/cgroup.procs: No such file or directory
,03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:45:04.508  4761  4871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 06:45:04.508  4761  4871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 06:45:04.508  4761  4871 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 06:45:04.510  4761  4761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:45:04.513  4761  4761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-17 06:45:04.517  4850  4850 I vclib   : onServiceConnected
,03-17 06:45:04.532  4850  4850 W Babel   : Attempted to change video mute state without an active call.
,03-17 06:45:04.546  4761  4761 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 06:45:04.586   881  1234 E WifiStateMachine: WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=24.31 rxSuccessRate=24.22 targetRoamBSSID=any RSSI=-48
03-17 06:45:04.586   881  1234 E WifiStateMachine: WifiStateMachine CMD_START_SCAN with age=10907 interval=30000 maxinterval=300000
03-17 06:45:04.586   881  1234 E WifiStateMachine: WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
03-17 06:45:04.586   881  1234 E WifiStateMachine: WifiStateMachine CMD_START_SCAN full=false
03-17 06:45:04.586   881  1234 E WifiStateMachine: WifiStateMachine starting scan for "NG700"WPA_PSK with 2457
,03-17 06:45:04.587  1436  1436 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
03-17 06:45:04.588   293  1639 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
03-17 06:45:04.588   293  1639 D MDMCTBK : Event received = CTRL-EVENT-SCAN-STARTED 
03-17 06:45:04.588   881  1234 E WifiStateMachine: [1,458,193,504,588 ms] noteScanstart no scan source
,03-17 06:45:04.622   881   881 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=4911 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 06:45:04.622   881   881 V AlarmManager: done {2a1b7095, *alarm*:com.android.server.WifiManager.action.START_SCAN} [6167ms]
,03-17 06:45:04.653   293  1639 D MDMCTBK : reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
03-17 06:45:04.653   293  1639 D MDMCTBK : Event received = CTRL-EVENT-SCAN-RESULTS 
03-17 06:45:04.653   492   514 D TCMD    : NL - Read 56 bytes from update socket.
03-17 06:45:04.653   492   514 D TCMD    : NL - message type is RTM_NEWLINK
03-17 06:45:04.653   492   514 D TCMD    : Listening for incoming client connection request
,03-17 06:45:04.656   881  1234 E WifiStateMachine: [1,458,193,504,656 ms] noteScanEnd no scan source
,03-17 06:45:04.660   881  1234 E WifiStateMachine: wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@240eae8b sup_state=COMPLETED debouncing=false
,03-17 06:45:04.672   881  1658 I ActivityManager: Killing 4708:com.google.android.gm/u0a63 (adj 15): empty #7
,03-17 06:45:04.772   881  1462 W libprocessgroup: failed to open /acct/uid_10063/pid_4708/cgroup.procs: No such file or directory
,03-17 06:45:04.892  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:05.138   881  1534 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4935 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 06:45:05.175   881  1462 I ActivityManager: Killing 4602:com.motorola.context/u0a8 (adj 15): empty #7
,03-17 06:45:05.284   881   896 W libprocessgroup: failed to open /acct/uid_10008/pid_4602/cgroup.procs: No such file or directory
,03-17 06:45:05.329   881  1658 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4957 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-17 06:45:05.408  4850  4850 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 06:45:05.413  4850  4850 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:45:05.472   303   397 I ThermalEngine: Sensor:xo_therm_pu2:37000 mC
,03-17 06:45:05.475  4850  4850 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 06:45:05.499  4761  4906 W jxcore-log: Initializing JXcore engine
03-17 06:45:05.499  4761  4906 W jxcore-log: JXcore engine is ready
,03-17 06:45:05.570   881  1535 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4984 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:45:05.571   881  1535 I ActivityManager: Killing 4825:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 06:45:05.584  4850  4850 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:45:05.584  4850  4850 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 06:45:05.580  4906  4906 W Thread-520: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5621]" dev="sockfs" ino=5621 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 06:45:05.580  4906  4906 W Thread-520: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 06:45:05.580  4906  4906 W Thread-520: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9445]" dev="sockfs" ino=9445 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-17 06:45:05.580  4906  4906 W Thread-520: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[20416]" dev="sockfs" ino=20416 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-17 06:45:05.600  4957  4978 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-17 06:45:05.604  4761  4906 W jxcore-log: Starting JXcore engine
,03-17 06:45:05.723   881   897 W libprocessgroup: failed to open /acct/uid_10005/pid_4825/cgroup.procs: No such file or directory
,03-17 06:45:05.744  4761  4906 W jxcore-log: Platform android
03-17 06:45:05.744  4761  4906 W jxcore-log: 
,03-17 06:45:05.744  4761  4906 W jxcore-log: Process ARCH arm
03-17 06:45:05.744  4761  4906 W jxcore-log: 
,03-17 06:45:05.766  4984  4984 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-17 06:45:05.767  4984  4984 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-17 06:45:05.767  4984  4984 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 06:45:05.767  4984  4984 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 06:45:05.941  1291  1291 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-17 06:45:05.941  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:05.967  4911  5005 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,03-17 06:45:05.970  1573  1573 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1011ff60 new=com.google.android.velvet.VelvetApplication@1011ff60
,03-17 06:45:06.040   881  1637 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5009 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 06:45:06.045  1962  5015 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 06:45:06.047  1962  5015 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-17 06:45:06.118  1962  2186 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 06:45:06.120  1962  5015 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-17 06:45:06.148  5009  5009 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:45:06.200  4761  4906 I jxcore-log: JXcore Cordova bridge is ready!
03-17 06:45:06.200  4761  4906 I jxcore-log: 
,03-17 06:45:06.201  4761  4906 W jxcore-log: JXcore engine is started
,03-17 06:45:06.205  4761  4871 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 06:45:06.207  4761  4761 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-17 06:45:06.216  4761  4906 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 06:45:06.216  4761  4906 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 06:45:06.223  4761  4761 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 06:45:06.224  4761  4761 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-17 06:45:06.248  1466  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 06:45:06.251  4761  4871 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 06:45:06.255  1466  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 06:45:06.270  2565  2565 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 06:45:06.272  4911  5005 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 304 ms] updated apps [took 304 ms] 
03-17 06:45:06.272  2565  2565 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-17 06:45:06.273  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 06:45:06.275  2565  2565 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 06:45:06.276  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 06:45:06.281  2565  2565 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 06:45:06.283  2565  2565 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 06:45:06.284  2565  2565 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 06:45:06.319  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-17 06:45:06.320  4761  4761 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 06:45:06.352   881  1140 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,4489
03-17 06:45:06.352   881  1140 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,3986 (total)
,03-17 06:45:06.574  5031  5031 D AndroidRuntime: 
03-17 06:45:06.574  5031  5031 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 06:45:06.578  5031  5031 D AndroidRuntime: CheckJNI is OFF
,03-17 06:45:06.631   881  1658 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5037 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:45:06.670   881  1462 I ActivityManager: Killing 4268:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,03-17 06:45:06.742   881  1571 W libprocessgroup: failed to open /acct/uid_10016/pid_4268/cgroup.procs: No such file or directory
,03-17 06:45:06.763  5037  5037 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 06:45:06.805  5031  5031 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 06:45:06.823   881  1132 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-17 06:45:06.827   881  1132 I ActivityManager: Killing 4761:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-17 06:45:06.870   881  1237 D WifiService: Client connection lost with reason: 4
,03-17 06:45:06.894  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:06.902  1746  1781 I art     : Explicit concurrent mark sweep GC freed 49781(2MB) AllocSpace objects, 33(528KB) LOS objects, 40% free, 13MB/22MB, paused 1.267ms total 126.959ms
,03-17 06:45:06.913   881  1515 I WindowState: WIN DEATH: Window{26532afe u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 06:45:06.934   881  1148 W PackageSettings: Skipping PackageSetting{4d1f4fe com.example.hello/10568} due to missing metadata
,03-17 06:45:07.071   881  1491 W ActivityManager: Spurious death for ProcessRecord{4334458 4761:com.test.thalitest/u0a109}, curProc for 4761: null
,03-17 06:45:07.074  5037  5037 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@11aa8f48(com.android.providers.calendar.CalendarProvider2@16f721e1)
,03-17 06:45:07.089   881  1148 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-17 06:45:07.097   279   279 I SFPerfTracer:      triggers: (rate: 13:553) (compose: 0:1) (post: 0:1) (render: 0:2) (16:930 frames) (17:1028)
03-17 06:45:07.097   279   279 D SFPerfTracer:        layers: (4:12) (FocusedStackFrame (0xb7dec7b8): 0:16)* (DimLayer (0xb7de2470): 0:7) (StatusBar (0xb7de8008): 0:150) (NavigationBar (0xb7dfe038): 0:47) (com.android.systemui.ImageWallpaper (0xb7e054a8): 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7e19f20): 0:51)- (Starting com.test.thalitest (0xb7de4aa8): 0:38)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7e18208): 1:79)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7de5488): 17:27) 
,03-17 06:45:07.128  1746  2021 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 06:45:07.135  1418  1418 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-17 06:45:07.136   881  1226 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 06:45:07.163  1418  5073 I Keyboard.Facilitator.DecoderInitializer: run()
,03-17 06:45:07.164  3005  3005 I art     : Explicit concurrent mark sweep GC freed 12579(1731KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 7MB/12MB, paused 735us total 63.479ms
,03-17 06:45:07.182  1418  5073 I Decoder : createOrResetDecoder
,03-17 06:45:07.215  1573  1573 I art     : Explicit concurrent mark sweep GC freed 2178(116KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 470us total 103.519ms
,03-17 06:45:07.261   881   897 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5081 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:45:07.304  1746  1746 I ConfigService: onCreate
,03-17 06:45:07.331   881   881 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 06:45:07.331   881   881 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 06:45:07.343   881  1254 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
,03-17 06:45:07.344   881  1254 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-17 06:45:07.344   881  1254 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-17 06:45:07.344   881  1254 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-17 06:45:07.353   279   731 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (25:286 vsyncs) (27:1031)
,03-17 06:45:07.366  1418  5073 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-17 06:45:07.423  1418  5073 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-17 06:45:07.426  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-17 06:45:07.426  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-17 06:45:07.436  1573  1573 I Launcher: Deferring update until onResume
,03-17 06:45:07.441   881   897 I ActivityManager: Killing 4886:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-17 06:45:07.443  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,03-17 06:45:07.443  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-17 06:45:07.445  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-17 06:45:07.445  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-17 06:45:07.481   881  1148 I art     : Explicit concurrent mark sweep GC freed 28562(1917KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 21MB/32MB, paused 1.599ms total 251.763ms
,03-17 06:45:07.532  1418  5073 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-17 06:45:07.532  1418  5073 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-17 06:45:07.532  1418  5073 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-17 06:45:07.532  1418  5073 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-17 06:45:07.532  1418  5073 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-17 06:45:07.532  1418  5073 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-17 06:45:07.549  5031  5031 D AndroidRuntime: Shutting down VM
,03-17 06:45:07.612   881  1571 W libprocessgroup: failed to open /acct/uid_10088/pid_4886/cgroup.procs: No such file or directory
,03-17 06:45:07.663   881  1148 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5103 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 06:45:07.686   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 23.854ms
,03-17 06:45:07.708   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.575ms
,03-17 06:45:07.729   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.325ms
,03-17 06:45:07.828  5081  5081 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 06:45:07.895  1291  1291 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-17 06:45:08.080  5081  5081 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-17 06:45:08.103  5081  5081 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 06:45:08.103  5081  5147 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/library.db'.
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-17 06:45:08.103  5081  5147 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:45:08.104  5081  5081 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: Failed to write crash file cnt=0, ts=0.
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804305: open failed: EROFS (Read-only file system)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at libcore.io.Posix.open(Native Method)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 06:45:08.114  5081  5147 W Finsky.CrashDetector: 	... 6 more
--------- beginning of crash
03-17 06:45:08.114  5081  5147 E AndroidRuntime: FATAL EXCEPTION: libraries-thread
03-17 06:45:08.114  5081  5147 E AndroidRuntime: Process: com.android.vending, PID: 5081
03-17 06:45:08.114  5081  5147 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-17 06:45:08.114  5081  5147 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 06:45:08.119  5081  5148 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: Can't write: system_app_crash
03-17 06:45:08.131   881  5149 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 06:45:08.131   881  5149 E DropBoxManagerService: 	... 5 more
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:4082)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 06:45:08.134  5081  5151 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 06:45:08.152   881  1534 I ActivityManager: Killing 4984:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
03-17 06:45:08.175  1962  2186 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-17 06:45:08.186   881  5153 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:45:08.187   881  1132 D Atlas   : Validating map...
,03-17 06:45:08.192   881  1534 I ActivityManager: Killing 4935:com.google.android.partnersetup/u0a19 (adj 15): empty #8
,03-17 06:45:08.212   881  1572 W libprocessgroup: failed to open /acct/uid_10027/pid_4984/cgroup.procs: No such file or directory
,03-17 06:45:08.213   881  1491 W libprocessgroup: failed to open /acct/uid_10019/pid_4935/cgroup.procs: No such file or directory
,03-17 06:45:08.214  5037  5037 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 06:45:08.214  5037  5037 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-17 06:45:08.218   881  1462 I ActivityManager: Killing 4911:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-17 06:45:08.242   881  1658 W libprocessgroup: failed to open /acct/uid_10039/pid_4911/cgroup.procs: No such file or directory
,03-17 06:45:08.480   279   692 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
