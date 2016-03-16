#### Test 63012666c2ddc84_thali04_motorola-XT1072 Logs


```
--------- beginning of main
03-16 06:29:37.429  1710  1710 I art     : Explicit concurrent mark sweep GC freed 17574(935KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 13MB/23MB, paused 1.969ms total 86.411ms
03-16 06:29:37.456  1710  1710 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
03-16 06:29:37.466  1710  1710 I GCoreUlr: DispatchingService.onCreate()
,03-16 06:29:37.575  1710  2014 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
--------- beginning of system
03-16 06:29:37.592   881  1553 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5227 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
03-16 06:29:37.680  1710  5222 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
03-16 06:29:37.685  1710  5206 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
03-16 06:29:37.687  5227  5227 D PhoneMonitor: Register our PhoneStateListener
03-16 06:29:37.741  3466  3617 I art     : Explicit concurrent mark sweep GC freed 2967(116KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 799us total 34.115ms
03-16 06:29:37.749  5227  5227 V SetupWizard: Connected to Gservices successfully
03-16 06:29:37.763  5176  5176 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 06:29:37.763  5176  5176 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
03-16 06:29:37.767   881  1577 I ActivityManager: Killing 3957:com.android.defcontainer/u0a10 (adj 15): empty #7
03-16 06:29:37.818   881  1529 W libprocessgroup: failed to open /acct/uid_10010/pid_3957/cgroup.procs: No such file or directory
03-16 06:29:37.870   881  1494 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5256 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 06:29:37.903  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
03-16 06:29:37.903  5225  5225 D AndroidRuntime: 
03-16 06:29:37.903  5225  5225 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 06:29:37.906  1710  2731 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
03-16 06:29:37.907   881  1515 I ActivityManager: Killing 5087:com.google.android.configupdater/u0a54 (adj 15): empty #7
03-16 06:29:37.908  5225  5225 D AndroidRuntime: CheckJNI is OFF
03-16 06:29:37.925  1710  5222 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
03-16 06:29:37.978   881   897 W libprocessgroup: failed to open /acct/uid_10054/pid_5087/cgroup.procs: No such file or directory
03-16 06:29:37.994  1710  5222 I GCoreUlr: Unbound from all location providers
03-16 06:29:37.994  1710  5222 I GCoreUlr: Place inference reporting - stopped
03-16 06:29:37.997  1710  5206 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10016, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
03-16 06:29:38.000  1710  1710 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
03-16 06:29:38.014  1710  1710 I GCoreUlr: DispatchingService.onDestroy()
03-16 06:29:38.014  1710  1710 I GCoreUlr: Stopping handler for UlrDispSvcFast
03-16 06:29:38.019  1710  1710 I GCoreUlr: Unbound from all location providers
03-16 06:29:38.019  1710  1710 I GCoreUlr: Place inference reporting - stopped
03-16 06:29:38.081  5256  5286 I Gmail   : getAccountsCursor
03-16 06:29:38.084  5256  5287 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
03-16 06:29:38.090  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 06:29:38.148  5225  5225 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 06:29:38.160   881  3180 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5291 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 06:29:38.169   881  1529 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-16 06:29:38.197   279  1147 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (241 us)
03-16 06:29:38.219  1474  4185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 06:29:38.220  5225  5225 D AndroidRuntime: Shutting down VM
03-16 06:29:38.265   881  1515 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5311 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 06:29:38.269   881  1502 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-16 06:29:38.274  2865  2865 E ActivityThread: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-16 06:29:38.274  2865  2865 E ActivityThread: java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5312)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
03-16 06:29:38.274  2865  2865 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
03-16 06:29:38.296   881  1595 I ActivityManager: Activity reported stop, but no longer stopping: ActivityRecord{30dee298 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
03-16 06:29:38.298  5256  5321 I Gmail   : Observing account changes for notifications
03-16 06:29:38.303  1474  4185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-16 06:29:38.339  5291  5291 I Exchange: EasService.onCreate
03-16 06:29:38.353  5291  5331 I Exchange: RestartPingTask
03-16 06:29:38.356  5256  5256 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-16 06:29:38.370  5291  5291 I Exchange: RestartPingsTask did not start any pings.
03-16 06:29:38.371  5291  5291 I Exchange: PSS stopIfIdle
03-16 06:29:38.371  5291  5291 I Exchange: PSS has no active accounts; stopping service.
03-16 06:29:38.424  5256  5287 I Gmail   : getAccountsCursor
,03-16 06:29:38.431  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:38.450  5291  5291 I Exchange: onDestroy
03-16 06:29:38.455   881   897 I ActivityManager: Killing 5056:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 06:29:38.523  5311  5311 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-16 06:29:38.532   881  1513 W libprocessgroup: failed to open /acct/uid_10019/pid_5056/cgroup.procs: No such file or directory
,03-16 06:29:38.580  2865  2865 D 3CDM.DeviceAdminSetupReceiver: received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,03-16 06:29:38.581  2865  2865 D 3CDM.DeviceAdminSetupReceiver: time to show notification
,03-16 06:29:38.589   881  1515 I ActivityManager: Killing 5117:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 06:29:38.604  5311  5311 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8344-8346)
03-16 06:29:38.604  5311  5311 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 06:29:38.636  5311  5311 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b293827}
,03-16 06:29:38.637  5311  5311 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 06:29:38.638  5311  5311 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 06:29:38.655  5311  5311 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 06:29:38.656  5311  5311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:29:38.657  5311  5311 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 06:29:38.662   881  1653 W libprocessgroup: failed to open /acct/uid_10039/pid_5117/cgroup.procs: No such file or directory
,03-16 06:29:38.665  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:38.670  1289  1312 W ResourcesManager: Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,03-16 06:29:38.687  5311  5311 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 06:29:38.693  5311  5311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 06:29:38.696  5311  5311 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 06:29:38.699  5311  5311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-16 06:29:38.699  5311  5311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-16 06:29:38.699  5311  5311 I Adreno-EGL: Build Date: 10/28/14 Tue
03-16 06:29:38.699  5311  5311 I Adreno-EGL: Local Branch: 
03-16 06:29:38.699  5311  5311 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-16 06:29:38.699  5311  5311 I Adreno-EGL: Local Patches: NONE
03-16 06:29:38.699  5311  5311 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-16 06:29:38.732  5256  5350 E SQLiteLog: (283) recovered 41 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 06:29:38.751   881  3180 I ActivityManager: Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5352 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,03-16 06:29:38.793   279   736 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (25:179 vsyncs) (27:940)
,03-16 06:29:38.798   881  1098 D BluetoothManagerService: Message: 20
03-16 06:29:38.798   881  1098 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eaf45b0:true
,03-16 06:29:38.840  1289  1289 E ActivatableNotificationView:  oops Width=0 ActualHeight=128
,03-16 06:29:38.851  5352  5352 W ResourcesManager: Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,03-16 06:29:38.905  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 06:29:38.978  5256  5351 I Gmail   : notifyAccountChanged
,03-16 06:29:38.981  5256  5336 I Gmail   : getAccountsCursor
,03-16 06:29:38.988  5256  5351 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 06:29:38.992  5311  5311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:29:38.995  5256  5351 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 06:29:39.004  5256  5351 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 06:29:39.005  5256  5351 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 06:29:39.049   881  1494 I art     : Explicit concurrent mark sweep GC freed 18533(911KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.866ms total 160.793ms
,03-16 06:29:39.056  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:39.072  5311  5311 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 06:29:39.090  5311  5311 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-16 06:29:39.116   881   896 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=5387 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 06:29:39.120  5311  5311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:29:39.120  5311  5311 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 06:29:39.186  5311  5409 D OpenGLRenderer: Render dirty regions requested: true
,03-16 06:29:39.206  5311  5311 D Atlas   : Validating map...
,03-16 06:29:39.216  5311  5363 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 06:29:39.218   881  1653 I ActivityManager: Killing 5032:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,03-16 06:29:39.258   881  3180 W libprocessgroup: failed to open /acct/uid_10088/pid_5032/cgroup.procs: No such file or directory
,03-16 06:29:39.273  5256  5286 I Gmail   : getAccountsCursor
,03-16 06:29:39.280  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:39.301  5311  5409 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 06:29:39.308  5311  5409 D OpenGLRenderer: Enabling debug mode 0
,03-16 06:29:39.355  1414  1414 I Keyboard.Facilitator: onFinishInput()
,03-16 06:29:39.361   881  1099 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,1140
03-16 06:29:39.361   881  1099 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s141ms
,03-16 06:29:39.455  5311  5415 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 06:29:39.455  5311  5415 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 06:29:39.486  5311  5311 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5311
,03-16 06:29:39.587   881  1241 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5422 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 06:29:39.630   881  1595 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5439 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 06:29:39.631   881  1595 I ActivityManager: Killing 5227:com.google.android.setupwizard/u0a35 (adj 15): empty #7
03-16 06:29:39.651   311   311 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.032ms
,03-16 06:29:39.672   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.049ms
,03-16 06:29:39.693   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.171ms
,03-16 06:29:39.713   881  1529 I ActivityManager: Killing 5291:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,03-16 06:29:39.748   881  3180 W libprocessgroup: failed to open /acct/uid_10035/pid_5227/cgroup.procs: No such file or directory
,03-16 06:29:39.755   881  1502 W libprocessgroup: failed to open /acct/uid_10060/pid_5291/cgroup.procs: No such file or directory
,03-16 06:29:39.771  5439  5439 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 06:29:39.889  5311  5409 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-16 06:29:39.889  5311  5409 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-16 06:29:39.905  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 06:29:40.015  5439  5463 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-16 06:29:40.016  5439  5463 I Babel_SMS: MmsConfig.loadMmsSettings
,03-16 06:29:40.018  5439  5463 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 06:29:40.018  5439  5463 I Babel_SMS: MmsConfig.loadFromDatabase
,03-16 06:29:40.051  5439  5463 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-16 06:29:40.051  5439  5463 I Babel_SMS: MmsConfig.loadFromResources
,03-16 06:29:40.053  5439  5463 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 06:29:40.053  5439  5463 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,03-16 06:29:40.125  5439  5439 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 06:29:40.133  5439  5439 I Babel_Crash: startup - clean
,03-16 06:29:40.159  5439  5466 I Babel   : deleted: false for 0
,03-16 06:29:40.174  5311  5311 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 06:29:40.178   279   279 I SFPerfTracer:      triggers: (rate: 13:543) (compose: 0:1) (post: 0:1) (render: 0:4) (18:923 frames) (19:1006)
03-16 06:29:40.179   279   279 D SFPerfTracer:        layers: (3:12) (FocusedStackFrame (0xb81217d0): 0:14)* (DimLayer (0xb81cdde0): 0:8)* (StatusBar (0xb8136db0): 0:137) (NavigationBar (0xb8138ac8): 0:30) (com.android.systemui.ImageWallpaper (0xb813a7e0): 0:35)* (Starting com.motorola.ccc.ota (0xb81d87c0): 0:36)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb81d1ff0): 0:44)- (Starting com.test.thalitest (0xb81d87c0): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb81daeb8): 19:28) 
,03-16 06:29:40.289   881   897 I ActivityManager: Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5468 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,03-16 06:29:40.308  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,03-16 06:29:40.309  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 06:29:40.314  5311  5413 D jxcore_app_log: JniHelper::setJavaVM(0xb7bf7310), pthread_self() = -1208134216
,03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 06:29:40.320  5311  5413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@376fcba3 added. We now have 1 listener(s)
03-16 06:29:40.321   881  1653 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 06:29:40.324  5311  5413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-16 06:29:40.326  5311  5413 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 06:29:40.327  5311  5413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-16 06:29:40.327  5311  5413 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 06:29:40.327  5311  5413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 06:29:40.331  5311  5413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2131d61e added. We now have 1 listener(s)
,03-16 06:29:40.332  5311  5413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 06:29:40.340   881  1235 D WifiService: New client listening to asynchronous messages
,03-16 06:29:40.342  5311  5413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-16 06:29:40.347  5439  5439 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 06:29:40.353  5311  5413 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-16 06:29:40.353  5311  5413 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-16 06:29:40.353  5439  5439 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,03-16 06:29:40.356  5311  5413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 06:29:40.356   881  1529 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 06:29:40.357  5311  5413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-16 06:29:40.359  5439  5439 W VideoCapabilities: Unsupported mime video/mpeg2
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 06:29:40.363  5311  5413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 06:29:40.363  5311  5413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 06:29:40.363  5311  5413 D io.jxcore.node.ConnectivityMonitor: start: OK
03-16 06:29:40.365  5311  5311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 06:29:40.367  5311  5311 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 06:29:40.391  5439  5439 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
03-16 06:29:40.395  5311  5311 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 06:29:40.418  5439  5439 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 06:29:40.420  5439  5439 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-16 06:29:40.423  5439  5439 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 06:29:40.427  5439  5439 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 06:29:40.568   881  1552 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5493 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
03-16 06:29:40.569   881  1552 I ActivityManager: Killing 5256:com.google.android.gm/u0a63 (adj 15): empty #7
,03-16 06:29:40.596  5439  5453 W art     : Suspending all threads took: 6.337ms
,03-16 06:29:40.635  5468  5490 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-16 06:29:40.730   881  1529 W libprocessgroup: failed to open /acct/uid_10063/pid_5256/cgroup.procs: No such file or directory
,03-16 06:29:40.749  5439  5439 I vclib   : onServiceConnected
03-16 06:29:40.750  5439  5439 W Babel   : Attempted to change video mute state without an active call.
,03-16 06:29:40.782  5493  5493 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 06:29:40.783  5493  5493 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 06:29:40.783  5493  5493 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 06:29:40.784  5493  5493 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 06:29:40.785  5439  5439 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-16 06:29:40.790  5439  5439 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 06:29:40.833  5439  5439 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 06:29:40.912  5387  5514 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
03-16 06:29:40.912  1571  1571 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2bcef040 new=com.google.android.velvet.VelvetApplication@2bcef040
,03-16 06:29:40.919  5439  5439 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 06:29:40.919  5439  5439 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 06:29:40.943  1944  5519 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 06:29:40.952  1944  5519 I PkgBroadcastIntentOp: Null package name or gms related package.  Ignoreing.
,03-16 06:29:40.980   881  1494 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5520 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 06:29:41.000  1944  5519 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,03-16 06:29:41.008  1944  2173 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 06:29:41.051  5520  5520 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 06:29:41.164  5387  5514 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 251 ms] updated apps [took 251 ms] 
,03-16 06:29:41.364   881  1494 I ActivityManager: Killing 5352:com.motorola.context/u0a8 (adj 15): empty #7
,03-16 06:29:41.467   881  1241 W libprocessgroup: failed to open /acct/uid_10008/pid_5352/cgroup.procs: No such file or directory
,03-16 06:29:41.708   881  1529 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5558 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:29:41.750   881  1221 V AlarmManager: send {16c48085, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,03-16 06:29:41.770   881  1653 I ActivityManager: Killing 5176:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-16 06:29:41.888   881  1502 W libprocessgroup: failed to open /acct/uid_10005/pid_5176/cgroup.procs: No such file or directory
,03-16 06:29:41.977   881  1252 D TaskPersister: removeObsoleteFile: deleting file=8_task_thumbnail.png
,03-16 06:29:42.060  5558  5558 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 06:29:42.162  5311  5488 W jxcore-log: Initializing JXcore engine
03-16 06:29:42.162  5311  5488 W jxcore-log: JXcore engine is ready
,03-16 06:29:42.208  5558  5558 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 06:29:42.230  5558  5558 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 06:29:42.233  5558  5558 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 06:29:42.226  5488  5488 W Thread-554: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9653]" dev="sockfs" ino=9653 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,03-16 06:29:42.226  5488  5488 W Thread-554: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 06:29:42.226  5488  5488 W Thread-554: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7619]" dev="sockfs" ino=7619 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-16 06:29:42.226  5488  5488 W Thread-554: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[22807]" dev="sockfs" ino=22807 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-16 06:29:42.265  5311  5488 W jxcore-log: Starting JXcore engine
,03-16 06:29:42.312  5558  5602 D Ads     : Skipping gmscore version check
,03-16 06:29:42.314  5558  5558 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 06:29:42.315  5558  5558 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 06:29:42.326  5558  5558 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 06:29:42.366  5558  5558 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 06:29:42.417   881  1515 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5604 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,03-16 06:29:42.418   881  1515 I ActivityManager: Killing 5422:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 06:29:42.435  5311  5488 W jxcore-log: Platform android
03-16 06:29:42.435  5311  5488 W jxcore-log: 
03-16 06:29:42.435  5311  5488 W jxcore-log: Process ARCH arm
03-16 06:29:42.435  5311  5488 W jxcore-log: 
,03-16 06:29:42.540   881  1653 W libprocessgroup: failed to open /acct/uid_10019/pid_5422/cgroup.procs: No such file or directory
,03-16 06:29:42.596  1944  2173 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 06:29:42.613  5604  5604 D PhoneMonitor: Register our PhoneStateListener
,03-16 06:29:42.628   881  1502 I ActivityManager: Killing 5493:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,03-16 06:29:42.773   881  1653 I art     : Explicit concurrent mark sweep GC freed 12248(633KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.788ms total 116.828ms
,03-16 06:29:42.800  1944  2173 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,03-16 06:29:42.818  1944  2173 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 06:29:42.823   881   896 W libprocessgroup: failed to open /acct/uid_10027/pid_5493/cgroup.procs: No such file or directory
,03-16 06:29:42.844  1710  3630 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,03-16 06:29:42.859  1944  5626 I CheckinService: Checking schedule, now: 1458106182859 next: 1458106200624
03-16 06:29:42.859  1944  5626 I CheckinService: active receiver: disabled
,03-16 06:29:42.924   881  1553 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5628 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 06:29:43.051   881  1494 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5648 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:29:43.090   881  1494 I ActivityManager: Killing 5387:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,03-16 06:29:43.125  5311  5488 I jxcore-log: JXcore Cordova bridge is ready!
03-16 06:29:43.125  5311  5488 I jxcore-log: 
,03-16 06:29:43.126  5311  5488 W jxcore-log: JXcore engine is started
,03-16 06:29:43.134  5311  5413 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 06:29:43.138   881  1553 W libprocessgroup: failed to open /acct/uid_10039/pid_5387/cgroup.procs: No such file or directory
,03-16 06:29:43.145  5311  5311 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 06:29:43.150  5648  5648 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-16 06:29:43.150  5648  5648 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-16 06:29:43.150  5648  5648 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 06:29:43.150  5648  5648 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-16 06:29:43.155  5311  5488 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 06:29:43.155  5311  5488 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 06:29:43.163  5311  5311 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 06:29:43.164  5311  5311 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 06:29:43.183  1474  4185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 06:29:43.185  5311  5413 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 06:29:43.192  1474  4185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-16 06:29:43.242   881   896 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5669 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-16 06:29:43.252  2865  2865 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-16 06:29:43.254  2865  2865 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-16 06:29:43.257   881  1502 I ActivityManager: Killing 5520:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-16 06:29:43.258  2865  2865 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 06:29:43.262  2865  2865 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-16 06:29:43.264  2865  2865 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 06:29:43.328   881  1529 W libprocessgroup: failed to open /acct/uid_10090/pid_5520/cgroup.procs: No such file or directory
,03-16 06:29:43.329  2865  2865 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-16 06:29:43.330  2865  2865 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-16 06:29:43.331  2865  2865 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-16 06:29:43.337  1289  1289 I SBar.MotoNetworkCtrlr: onReceive: WifiManager.RSSI_CHANGED_ACTION Received
03-16 06:29:43.338  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 06:29:43.383  5311  5311 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 06:29:43.389  1414  1414 I Keyboard.Facilitator: onFinishInput()
,03-16 06:29:43.411   881  1099 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,11378
03-16 06:29:43.411   881  1099 I LaunchCheckinHandler: Displayed com.motorola.ccc.ota/.ui.DownloadActivity,cp,ca,5190 (total)
,03-16 06:29:43.504  1944  5519 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 06:29:43.532  1944  5519 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,03-16 06:29:43.550  5673  5673 D AndroidRuntime: 
03-16 06:29:43.550  5673  5673 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 06:29:43.558  5673  5673 D AndroidRuntime: CheckJNI is OFF
,03-16 06:29:43.648  1944  1944 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,03-16 06:29:43.809  5673  5673 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 06:29:43.824   881  1082 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-16 06:29:43.824   881  1082 I ActivityManager: Killing 5311:com.test.thalitest/u0a109 (adj 1): stop com.test.thalitest
,03-16 06:29:43.870   881  1235 D WifiService: Client connection lost with reason: 4
,03-16 06:29:43.879   881  1297 I WindowState: WIN DEATH: Window{27f6293c u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-16 06:29:43.909   881  1135 W PackageSettings: Skipping PackageSetting{3f39d0de com.example.hello/10568} due to missing metadata
,03-16 06:29:44.014   881  1595 W ActivityManager: Spurious death for ProcessRecord{2ea8aeeb 5311:com.test.thalitest/u0a109}, curProc for 5311: null
03-16 06:29:44.015   881  1135 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-16 06:29:44.046  5669  5697 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-16 06:29:44.050  1414  1414 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-16 06:29:44.054  1710  2014 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 06:29:44.070   881  1223 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 06:29:44.093  3312  3312 I art     : Explicit concurrent mark sweep GC freed 9830(1616KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 1.059ms total 58.806ms
,03-16 06:29:44.105  1414  5725 I Keyboard.Facilitator.DecoderInitializer: run()
,03-16 06:29:44.118  1944  2173 E Icing   : Package com.test.thalitest not found
,03-16 06:29:44.119  1414  5725 I Decoder : createOrResetDecoder
,03-16 06:29:44.126   279   736 I SFPerfTracer:      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (43:294 vsyncs) (45:1070)
,03-16 06:29:44.133   881  1221 V AlarmManager: send {2e7386a8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,03-16 06:29:44.134   881  1221 V AlarmManager: send {99060ce, *alarm*:com.android.server.WifiManager.action.START_SCAN}
03-16 06:29:44.137  5558  5558 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-16 06:29:44.155  1571  1571 I art     : Explicit concurrent mark sweep GC freed 2222(119KB) AllocSpace objects, 2(72KB) LOS objects, 24% free, 13MB/17MB, paused 615us total 119.555ms
,03-16 06:29:44.175  1944  1944 D AsyncTaskServiceImpl: Submit a task: k
,03-16 06:29:44.233   881   896 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5728 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 06:29:44.260  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:44.268  1710  1710 I ConfigService: onCreate
,03-16 06:29:44.292  1944  5747 D k       : Processing package: com.test.thalitest
,03-16 06:29:44.297   881   881 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-16 06:29:44.297   881   881 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 06:29:44.298  1944  5747 W k       : Failed to find package com.test.thalitest
,03-16 06:29:44.302   881   881 V AlarmManager: done {2e7386a8, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [172ms]
,03-16 06:29:44.305  5728  5728 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 06:29:44.311  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:44.313  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:44.327  1944  1944 E Vision  : Failed to find package com.test.thalitest
,03-16 06:29:44.334  1944  5727 W BaseAppContext: Using Auth Proxy for data requests.
03-16 06:29:44.334  1944  5727 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:29:44.356  1944  5727 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:29:44.366  1414  5725 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-16 06:29:44.415   881  1502 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5750 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-16 06:29:44.423  1414  5725 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
03-16 06:29:44.425  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-16 06:29:44.425  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-16 06:29:44.426  5728  5728 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@3411c428(com.android.providers.calendar.CalendarProvider2@3444e541)
,03-16 06:29:44.474  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-16 06:29:44.474  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-16 06:29:44.475  1944  5727 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:29:44.476   881  1252 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-16 06:29:44.477   881  1252 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
03-16 06:29:44.477   881  1252 D TaskPersister: removeObsoleteFile: deleting file=9_task_thumbnail.png
,03-16 06:29:44.478  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-16 06:29:44.478  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-16 06:29:44.481  1414  5725 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-16 06:29:44.483  1571  1571 I Launcher: Deferring update until onResume
,03-16 06:29:44.484  1414  5725 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-16 06:29:44.484  1414  5725 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-16 06:29:44.484  1414  5725 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-16 06:29:44.485  1414  5725 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-16 06:29:44.485  1414  5725 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-16 06:29:44.517   881  1135 I art     : Explicit concurrent mark sweep GC freed 23999(1644KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/32MB, paused 3.601ms total 396.686ms
,03-16 06:29:44.520  1944  5727 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 06:29:44.559  1944  5722 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,03-16 06:29:44.602  5673  5673 D AndroidRuntime: Shutting down VM
,03-16 06:29:44.652   881  1135 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=5774 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 06:29:44.675   311   311 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 23.679ms
,03-16 06:29:44.676  5669  5697 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 620 ms] updated apps [took 620 ms] 
,03-16 06:29:44.683   881  1552 I ActivityManager: Killing 3376:com.google.android.calendar/u0a49 (adj 15): empty #7
,03-16 06:29:44.697   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.763ms
,03-16 06:29:44.718   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.649ms
,03-16 06:29:44.819   881  1595 W libprocessgroup: failed to open /acct/uid_10049/pid_3376/cgroup.procs: No such file or directory
,03-16 06:29:44.831   881  3180 I ActivityManager: Killing 5604:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,03-16 06:29:44.909  1289  1289 I SBar.MotoNetworkCtrlr: updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,03-16 06:29:44.932   881  1494 W libprocessgroup: failed to open /acct/uid_10035/pid_5604/cgroup.procs: No such file or directory
,03-16 06:29:45.404   881  1135 F PackageManager: Unable to write package manager settings, current changes will be lost at reboot
03-16 06:29:45.404   881  1135 F PackageManager: java.io.IOException: write failed: EBADF (Bad file number)
03-16 06:29:45.404   881  1135 F PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-16 06:29:45.404   881  1135 F PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-16 06:29:45.404   881  1135 F PackageManager: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
03-16 06:29:45.404   881  1135 F PackageManager: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:119)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.internal.util.FastXmlSerializer.startTag(FastXmlSerializer.java:366)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.server.pm.Settings.writeDisabledSysPackageLPr(Settings.java:1879)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.server.pm.Settings.writeLPr(Settings.java:1682)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1174)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:798)
03-16 06:29:45.404   881  1135 F PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 06:29:45.404   881  1135 F PackageManager: 	at android.os.Looper.loop(Looper.java:135)
03-16 06:29:45.404   881  1135 F PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 06:29:45.404   881  1135 F PackageManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-16 06:29:45.404   881  1135 F PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
03-16 06:29:45.404   881  1135 F PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
03-16 06:29:45.404   881  1135 F PackageManager: 	at libcore.io.Posix.write(Posix.java:223)
03-16 06:29:45.404   881  1135 F PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-16 06:29:45.404   881  1135 F PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-16 06:29:45.404   881  1135 F PackageManager: 	... 15 more
,03-16 06:29:45.429  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:45.474  1944  5727 E GameAgent: Caller attempted to insert game data for non-existent package.
03-16 06:29:45.474  1944  5727 E GameAgent: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
03-16 06:29:45.474  1944  5727 E GameAgent: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at com.google.android.gms.games.broker.GameAgent.registerGame(GameAgent.java:1573)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at com.google.android.gms.games.broker.DataBroker.registerGame(DataBroker.java:3309)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-16 06:29:45.474  1944  5727 E GameAgent: 	at java.lang.Thread.run(Thread.java:818)
,03-16 06:29:45.481  5728  5728 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-16 06:29:45.482  5728  5728 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,03-16 06:29:45.486  1944  2173 I Icing   : Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,03-16 06:29:45.488  1944  2173 I Icing   : Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,03-16 06:29:45.499   881  1494 I ActivityManager: Killing 5628:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,03-16 06:29:45.518   881  1241 W libprocessgroup: failed to open /acct/uid_10019/pid_5628/cgroup.procs: No such file or directory
,03-16 06:29:45.556  5558  5584 I qtaguid : Failed write_ctrl(u 37) res=-1 errno=22
03-16 06:29:45.556  5558  5584 I qtaguid : Untagging socket 37 failed errno=-22
,03-16 06:29:45.556  5558  5584 W NetworkManagementSocketTagger: untagSocket(37) failed with errno -22
,03-16 06:29:45.560  5558  5558 D Finsky  : [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,03-16 06:29:45.574  5558  5594 E PlayEventLogger: Could not write string (client_ve: ""
03-16 06:29:45.574  5558  5594 E PlayEventLogger: exp <
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603130
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603248
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603505
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 739
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602035
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602049
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602373
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602392
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602623
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602624
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602761
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602795
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12602981
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603044
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603067
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603101
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603131
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603159
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603193
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603210
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603385
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603406
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603428
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603513
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603514
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603602
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603746
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603787
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603788
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603844
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12603948
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604079
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604142
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604155
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604230
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604266
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604268
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12604305
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12605120
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   play_experiment: 12605124
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 18
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 19
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 20
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 21
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 24
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 35
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 56
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 153
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 241
03-16 06:29:45.574  5558  55,94 E PlayEventLogger:   unsupported_play_experiment: 254
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 259
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 303
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 473
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 578
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 580
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 741
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 744
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 748
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 793
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 855
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 910
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602000
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602001
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602002
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602005
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602007
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602010
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602011
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602020
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602028
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602036
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602037
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602038
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602040
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602042
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602044
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602048
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602051
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602052
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602053
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602055
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602056
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602057
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602062
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602063
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602064
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602068
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602073
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602091
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602092
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602093
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602098
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602104
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602106
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602117,
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602120
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602123
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602125
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602128
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602142
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602143
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602144
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602145
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602150
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602152
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602155
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602313
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602314
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602322
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602350
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602351
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602370
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602377
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602418
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupported_play_experiment: 12602430
03-16 06:29:45.574  5558  5594 E PlayEventLogger:   unsupport
,03-16 06:29:45.585  5750  5750 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-16 06:29:45.585  5750  5750 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-16 06:29:45.585  5750  5750 I GAv4    :   adb logcat -s GAv4
,03-16 06:29:45.600  5750  5750 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-16 06:29:45.633  5750  5750 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-16 06:29:45.638  5750  5808 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-16 06:29:45.638  5750  5808 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-16 06:29:45.639  1414  5725 E native  : dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
03-16 06:29:45.639  1414  5725 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,03-16 06:29:45.649   881  1552 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5810 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,03-16 06:29:45.660  1710  1710 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 06:29:45.663  5750  5809 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-16 06:29:45.665  5750  5808 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-16 06:29:45.674  5750  5750 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-16 06:29:45.679  1944  2173 I Icing   : Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,03-16 06:29:45.702  1944  2173 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
03-16 06:29:45.702  1944  2173 E Icing   : Could not init tag ds.tag.deleted
,03-16 06:29:45.728  1944  2173 I Icing   : Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
,03-16 06:29:45.733  1944  2173 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
03-16 06:29:45.733  1944  2173 E Icing   : Writing status failed
,03-16 06:29:45.734  1944  2173 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,03-16 06:29:45.963   279   713 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-16 06:29:45.976  2145  2157 E MP-Decision: Error(-22) changing core 2 status to offline
03-16 06:29:45.977  2145  2157 E MP-Decision: Error(-22) changing core 1 status to offline

```
