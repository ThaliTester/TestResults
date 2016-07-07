#### Test 7578926821ef376_thali06_HTC-HTC One M9 Logs


```
--------- beginning of system,
07-07 20:25:58.334  1107  4115 D PMS     : acquireWL(113b924c): PARTIAL_WAKE_LOCK  AsyncService 0x1 7991 10126 null
--------- beginning of main
07-07 20:25:58.334  3497  3497 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8
07-07 20:25:58.354  1107  3457 D PMS     : releaseWL(113b924c): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-07 20:25:58.364  1107  3418 I ActivityManager: Start proc 8022:com.android.vending/u0a57 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
07-07 20:25:58.364  1107  3418 D Process : killProcessQuiet, pid=7585
07-07 20:25:58.364  1107  3418 I ActivityManager: Killing 7585:com.htc.updater/u0a68 (adj 15): empty #17
07-07 20:25:58.364  1107  3418 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-07 20:25:58.374  6495  8028 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-07 20:25:58.384  8022  8022 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:25:58.384  8022  8022 W HTCLOG  : mask=0x18
07-07 20:25:58.384  1107  1162 I ActivityManager: Recipient 7585
07-07 20:25:58.424  3497  3911 I ContextualWidget: MFU.onDataSetChanged
07-07 20:25:58.424  3497  3911 I ContextualWidget: handleMessage, what=1001 mode=GettingOut maxcount=8
07-07 20:25:58.424  3497  3911 I ContextualWidget: updateMFULaunchCountIfNeeded update=false days=0
07-07 20:25:58.494  6495  8028 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
07-07 20:25:58.494  1107  3457 D PMS     : acquireWL(3301e277): PARTIAL_WAKE_LOCK  Icing 0x1 6495 10020 WorkSource{10020 com.google.android.gms}
07-07 20:25:58.534  6495  6583 I Icing   : updateResources: need to parse owf{com.google.android.gms}
07-07 20:25:58.534  8044  8044 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-07 20:25:58.534  8044  8044 W HTCLOG  : mask=0x18
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: error sending REQ[fc:95; creat:1467720984996; type:boc-723119010: devices/registerdevice
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: ProtoBuf:
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: null
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: Creation stack:
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: java.lang.Throwable
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at boc.<init>(SourceFile:2476)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at boc.a(SourceFile:2506)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at bxx.a(SourceFile:88)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:3328)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: Origin stack:
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: java.lang.Throwable
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:1175)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at btp.b(SourceFile:1867)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at btl.u(SourceFile:1301)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:829)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:25:58.544  7817  7853 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: error sending REQ[fc:6; creat:1467915939840; type:bme-591065565: userphotoalbums
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: ProtoBuf:
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: null
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: Creation stack:
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: java.lang.Throwable
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at bma.<init>(SourceFile:50)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: Origin stack:
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: java.lang.Throwable
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-07 20:25:58.584  7817  7854 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
07-07 20:25:58.594  1107  3495 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=8022, uid=10057, userID:0
07-07 20:25:58.614  8022  8022 W global  : [apache-http] Connection GC has been deprecated!
07-07 20:25:58.624  8022  8022 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(428): Initializing network with DFE https://android.clients.google.com/fdfe/
07-07 20:25:58.644  7712  7771 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
07-07 20:25:58.724  8022  8022 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(168): Dirty, need more hygiene.
07-07 20:25:58.744  8022  8022 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-07 20:25:58.744  8022  8022 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-07 20:25:58.744  3497  3911 I ContextualWidget: MFU.onLoadComplete
07-07 20:25:58.754  3497  3911 I ContextualWidget: Download enabled: true, Recommend enabled: true
07-07 20:25:58.754  3497  3911 I ContextualWidget: sync all data, download=0 recommend=4
07-07 20:25:58.754  3497  3911 I ContextualWidget: sync all data, mode=GettingOut count=9
07-07 20:25:58.754  3497  3911 I ContextualWidget: notifyDataChanged, list size 8
07-07 20:25:58.754  3497  3497 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, item count: 8, original: 8, first add: false
07-07 20:25:58.754  8022  8071 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-07 20:25:58.754  8022  8071 W HTCLOG  : mask=0x18
07-07 20:25:58.754  4310  4310 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
07-07 20:25:58.774  1107  4147 I PackageManager:  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=8022, uid=10057, userID:0
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfofornet-, err=8
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfo_proxy+
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-07 20:25:58.784   516  8074 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
07-07 20:25:58.784   516  8074 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-07 20:25:58.784   516  8074 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-07 20:25:58.784   516  8074 D libc    : [NET] android_getaddrinfofornet-, err=7
07-07 20:25:58.784  8022  8068 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-07 20:25:58.784  8044  8076 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-07 20:25:58.784  8044  8076 W HTCLOG  : mask=0x18
07-07 20:25:58.784  8044  8076 E cutils-trace: Error opening trace file: Permission denied (13)
07-07 20:25:58.804  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-07 20:25:58.804  3497  3862 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1881d7c4 +
07-07 20:25:58.804  3497  3862 I Prism.WidgetManager: onLoadItems() +
07-07 20:25:58.804  8022  8022 I Finsky  : [1] com.google.android.finsky.j.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-07 20:25:58.804  8022  8022 I Finsky  : [1] com.google.android.finsky.j.j.run(214): Finished loading 1 libraries.
07-07 20:25:58.824  3497  3862 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-07 20:25:58.834  1107  4108 D Process : killProcessQuiet, pid=7611
07-07 20:25:58.834  1107  4108 I ActivityManager: Killing 7611:com.htc.mobiledata:remote/u0a39 (adj 15): empty #17
07-07 20:25:58.834  1107  4108 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
07-07 20:25:58.834  8044  8044 D CustomizationManager: ====startRecUseTime====
07-07 20:25:58.834  8044  8044 D htc.customization.log.level:  is 
07-07 20:25:58.844  8044  8044 W CustomizationLogLevel: Level value is invalid, use default level 2
07-07 20:25:58.894  3497  3497 I ContextualWidget: updateItemPosition item size=8   {-696942466=4, -335140367=0, -1138981812=6, 956745593=1, 1475455068=3, -157894107=7, 534392203=5, -33266553=2}
07-07 20:25:58.894  3497  3911 I ContextualWidget: handleMessage, what=1028 mode=GettingOut maxcount=8
07-07 20:25:58.904  1107  3418 I ActivityManager: Recipient 7611
07-07 20:25:58.914  8044  8044 D CustomizationManager:  Read ACC file spent 0.040 (s)
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__001
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__002
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__016
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__031
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__032
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__102
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-07 20:25:58.914  8044  8044 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-07 20:25:58.914  8044  8044 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: Parsing tag category name = application
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: Parsing tag category name = system
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: Parsing tag category name = Settings
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: Parsing tag category name = ACC
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 42507
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 21902
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23420
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 22299
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 24002
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23210
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23205
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23806
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23430
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23408
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27205
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-07 20:25:58.914  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-07 20:25:58.924  8044  8044 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-07 20:25:58.924  8044  8044 D CustomizationManager:  Read CID file spent 0.081 (s)
07-07 20:25:58.924  8044  8044 D CustomizationManager:  All configurations done spent 0.082 (s)
07-07 20:25:58.924  1107  5679 I art     : Explicit concurrent mark sweep GC freed 31808(1668KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.850ms total 138.813ms
07-07 20:25:58.954  8022  8022 I Finsky  : [1] com.google.android.finsky.c.l.a(270): result=false type=4
07-07 20:25:58.964  3497  3862 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-07 20:25:58.964  1107  3925 I ActivityManager: Start proc 8093:com.google.android.partnersetup/u0a23 for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver
07-07 20:25:58.964  1107  3418 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8044 on display 0
07-07 20:25:58.974  1107  1159 D PMS     : acquireHCC(324b0303): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1107 1000 null
07-07 20:25:58.974  8022  8022 I Finsky  : [1] com.google.android.finsky.services.bc.a(1050): Restore complete with 0 success and 0 failed.
07-07 20:25:58.974  1107  1159 D PMS     : acquireHCC(1c2d6280): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1107 1000 null
07-07 20:25:58.984  8093  8093 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:25:58.984  8093  8093 W HTCLOG  : mask=0x18
07-07 20:25:58.984  1107  3418 V WindowManager: addAppToken: AppWindowToken{3ff0cc5f token=Token{4ba7cfe ActivityRecord{25620b9 u0 com.test.thalitest/.MainActivity t109}}} to stack=1 task=109 at 0
07-07 20:25:58.984  1107  3418 D PMS     : acquireWL(84626ac): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1107 1000 null
07-07 20:25:58.984  8044  8044 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-07 20:25:58.984  8044  8044 W HTCLOG  : mask=0x18
07-07 20:25:58.984  8044  8091 W HTCLOG  : use specified tag [Vector], func [0].
07-07 20:25:58.984  8044  8091 W HTCLOG  : mask=0x18
07-07 20:25:58.994  3497  3497 I FeedHostManager: [onPause]
07-07 20:25:58.994  3497  3497 I FeedProviderManager: onPause
07-07 20:25:58.994  3497  3497 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@15dd1c70
07-07 20:25:58.994  3497  3497 I ContextualWidget: onPause
07-07 20:25:58.994  3497  3497 I ContextualWidget: notifyWidgetDeactive
07-07 20:25:58.994  1107  1150 I AnimationUtil: isHTCRecent(ThaliTest/Recents screens.)/7
07-07 20:25:58.994  3497  4850 I SocialFeedProvider: +onPause
07-07 20:25:58.994  3497  4850 I SocialFeedProvider: -onPause
07-07 20:25:58.994  1107  1150 V WindowManager: Adding window Window{c31e857 u0 Starting com.test.thalitest} at 2 of 7 (after Window{fe41342 u0 com.htc.launcher/com.htc.launcher.Launcher})
07-07 20:25:59.004  3462  4195 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-07 20:25:59.004  3462  4195 D PhoneApp: -- N1 =1
07-07 20:25:59.004  3462  4195 D PhoneApp: -- N2 =0
07-07 20:25:59.004  3462  4195 D PhoneApp: -- N3 =0
07-07 20:25:59.004  1107  4108 I ActivityManager: Start proc 8115:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-07 20:25:59.014  8115  8115 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:25:59.014  8115  8115 W HTCLOG  : mask=0x18
07-07 20:25:59.024  1107  3540 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-07 20:25:59.044  3497  3497 I TrimMemoryManager: [trimMemory] 20
07-07 20:25:59.054  1107  3424 I ActivityManager: Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
07-07 20:25:59.054  1107  3457 I ActivityManager: Resuming delayed broadcast
07-07 20:25:59.054  1107  1143 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-07 20:25:59.054  3069  3069 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-07 20:25:59.054  1107  1143 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{c31e857 u0 Starting com.test.thalitest}
07-07 20:25:59.054  3069  3069 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-07 20:25:59.054  1107  1143 D StatusBarManagerService: hiding MENU key
07-07 20:25:59.054  1107  4108 I ActivityManager: Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
07-07 20:25:59.064  1107  3424 I ActivityManager: Resuming delayed broadcast
07-07 20:25:59.064  3643  3643 E PackageActionReceiver: ACTION_PACKAGE_ADDED
07-07 20:25:59.064  1107  1127 D Process : killProcessQuiet, pid=7634
07-07 20:25:59.064  1107  1127 I ActivityManager: Killing 7634:com.htc.mobiledata/u0a39 (adj 15): empty #17
07-07 20:25:59.064  1107  1127 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
07-07 20:25:59.094  3497  3862 W asset   : Copying FileAsset 0xacb09180 (zip:/data/app/com.gameloft.android.gdc-1/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-07 20:25:59.144  3497  3862 I Prism.WidgetManager: onLoadItems() -
07-07 20:25:59.144  3497  3862 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1881d7c4 -
07-07 20:25:59.154  3497  3862 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-07 20:25:59.154  3497  3862 W PackageManager: Failure retrieving resources for com.test.thalitest: Resource ID #0x0
07-07 20:25:59.154  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-07 20:25:59.154  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-07 20:25:59.154  3497  3497 I Launcher: Deferring update until onResume
07-07 20:25:59.154  3497  3497 D Launcher: waitUntilResume // bindAppsAdded
07-07 20:25:59.164  1107  3457 I ActivityManager: Recipient 7634
07-07 20:25:59.174  3372  8139 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.test.thalitest
07-07 20:25:59.174  3372  8139 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-07 20:25:59.174  4994  4994 I [MirrorLinkServer]PackageInstalledReceiver: PackageInstalledReceiver Received::Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.htc.mirrorlinkserver/.PackageInstalledReceiver (has extras) }
07-07 20:25:59.174  4994  4994 D [MirrorLinkServer]PackageInstalledReceiver: Counter : 1
07-07 20:25:59.174  4994  4994 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-07 20:25:59.174  4994  4994 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_ADDED
07-07 20:25:59.174  4994  4994 D [MirrorLinkServer]MirrorLinkServer: New Application installed : com.test.thalitest
07-07 20:25:59.174  4994  4994 D [MirrorLinkServer]d: onApplicationInstalled
07-07 20:25:59.174  4994  4994 W [MirrorLinkServer]d: Cannot find find the  com.mirrorlink.android.app.LAUNCH intent.
07-07 20:25:59.184  4994  4994 I [MirrorLinkServer]d: com.test.thalitest is not a MirrorLink-aware app.
07-07 20:25:59.184  3497  3497 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_ADDED
07-07 20:25:59.184  3497  3497 I ContextualWidget: package com.test.thalitest added
07-07 20:25:59.184  4994  8140 I [MirrorLinkServer]d: Database Update Progress State : false
07-07 20:25:59.184  4994  8140 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-07 20:25:59.184  1107  3495 I ActivityManager: Delay finish: com.htc.launcher/.receiver.PackageStateReceiver
07-07 20:25:59.184  4994  4994 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-07 20:25:59.184  4994  4994 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-07 20:25:59.184  4994  4994 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-07 20:25:59.184  4994  4994 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-07 20:25:59.184  4994  4994 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
07-07 20:25:59.184  3497  3911 I ContextualWidget: handleMessage, what=1003 mode=GettingOut maxcount=8
07-07 20:25:59.194  3497  3497 I PendingUpdateTask: run pending update task - max:8, ori:8, incoming:8
07-07 20:25:59.204  8115  8115 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
,07-07 20:25:59.254  8115  8115 I LibraryLoader: Time to load native libraries: 26 ms (timestamps 865-891)
07-07 20:25:59.254  8115  8115 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:25:59.264  8115  8115 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {279398f3}
,07-07 20:25:59.264  8115  8115 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-07 20:25:59.264  8115  8115 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-07 20:25:59.274  8115  8115 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:25:59.274  8115  8115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:25:59.274  8115  8115 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:25:59.294  8115  8144 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-07 20:25:59.304  8115  8148 D BluetoothAdapter: 291789232: getState() :  mService = null. Returning STATE_OFF
,07-07 20:25:59.304  8115  8115 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-07 20:25:59.304  8115  8115 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
07-07 20:25:59.304  8115  8115 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
,07-07 20:25:59.314  8115  8115 W HTCLOG  : use specified tag [libEGL], func [3].
07-07 20:25:59.314  8115  8115 W HTCLOG  : mask=0x18
,07-07 20:25:59.314  8115  8115 W HTCLOG  : use specified tag [libEGL], func [3].,
07-07 20:25:59.314  8115  8115 W HTCLOG  : mask=0x18
07-07 20:25:59.314  8115  8115 I Adreno  : QUALCOMM build                   : 065751b, 
07-07 20:25:59.314  8115  8115 I Adreno  : Build Date                       : 04/15/15
07-07 20:25:59.314  8115  8115 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-07 20:25:59.314  8115  8115 I Adreno  : Local Branch                     : 
07-07 20:25:59.314  8115  8115 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-07 20:25:59.314  8115  8115 I Adreno  : Remote Branch                    : NONE
07-07 20:25:59.314  8115  8115 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING,
,07-07 20:25:59.324  3497  3911 I ContextualWidget: MFU.onDownloadDataSetChanged
,07-07 20:25:59.324  3497  3911 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-07 20:25:59.334  3497  3497 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 37e2896d-9da6-4da3-b1d9-fa0aae359324, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
07-07 20:25:59.334  3497  3497 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 37e2896d-9da6-4da3-b1d9-fa0aae359324, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-07 20:25:59.334  1107  3424 I ActivityManager: Resuming delayed broadcast
,07-07 20:25:59.334  1107  3925 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,07-07 20:25:59.334  6239  8149 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-07 20:25:59.394  8115  8155 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,07-07 20:25:59.404  8115  8115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:25:59.414  8115  8115 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,07-07 20:25:59.424  8115  8115 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-07 20:25:59.434  8115  8115 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-07 20:25:59.434  8115  8115 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-07 20:25:59.444  1107  1142 I ActivityManager: Waited long enough for: ServiceRecord{ab87d1a u0 com.htc.club/com.mcrm.autonotification.NotificationService},
07-07 20:25:59.444  1107  1142 I ActivityManager: Resuming delayed broadcast
,07-07 20:25:59.454  6239  8149 I ApplicationLogger: canRun() : Opted Out
,07-07 20:25:59.454  6239  8149 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,07-07 20:25:59.464  1107  3457 I ActivityManager: Start proc 8166:com.htc.cs.dm/u0a88 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
,07-07 20:25:59.464  8166  8166 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:25:59.464  8166  8166 W HTCLOG  : mask=0x18
07-07 20:25:59.464  8115  8179 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,07-07 20:25:59.464  8115  8179 W HTCLOG  : mask=0x18
,07-07 20:25:59.474  1107  3423 V WindowManager: Adding window Window{2a0d7109 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{c31e857 u0 Starting com.test.thalitest})
,07-07 20:25:59.504  8115  8115 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-07 20:25:59.504  8115  8115 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-07 20:25:59.504  8115  8115 W HTCLOG  : mask=0x18
07-07 20:25:59.504  8115  8115 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-07 20:25:59.504  8115  8115 W HTCLOG  : mask=0x18
,07-07 20:25:59.504  8166  8166 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8166 dbg=false s=true
,07-07 20:25:59.504  8166  8166 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
,07-07 20:25:59.504  8115  8179 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
07-07 20:25:59.504  8115  8179 W HTCLOG  : mask=0x18
07-07 20:25:59.504  8115  8179 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-07 20:25:59.504  8115  8179 W HTCLOG  : mask=0x18
07-07 20:25:59.504  8115  8179 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-07 20:25:59.504  8115  8179 W HTCLOG  : mask=0x18
,07-07 20:25:59.504  8115  8179 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-07 20:25:59.504  8115  8179 W HTCLOG  : mask=0x18
,07-07 20:25:59.514  8115  8179 W HTCLOG  : use specified tag [Surface], func [3].
07-07 20:25:59.514  8115  8179 W HTCLOG  : mask=0x18
07-07 20:25:59.514  8115  8179 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-07 20:25:59.514  8115  8179 W HTCLOG  : mask=0x18
07-07 20:25:59.514  8115  8179 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-07 20:25:59.514  8115  8179 W HTCLOG  : mask=0x18
,07-07 20:25:59.514  1107  3424 I ActivityManager: Start proc 8189:com.google.android.apps.docs/u0a90 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver,
,07-07 20:25:59.514  1107  3424 I ActivityManager: Killing 7662:com.htc.autobot/u0a27 (adj 15): empty #17
07-07 20:25:59.524  1107  3424 D Process : killProcessQuiet, pid=7662
07-07 20:25:59.524  1107  3424 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 ,
,07-07 20:25:59.524  8189  8189 W HTCLOG  : use specified tag [FDManager], func [0].
,07-07 20:25:59.524  8189  8189 W HTCLOG  : mask=0x18
,07-07 20:25:59.564  8115  8115 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@38860ed1, mServedView=org.apache.cordova.engine.SystemWebView{303e2d36 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@cbb1da4
,07-07 20:25:59.584  1107  3495 I InputMethodManagerService: Disable input method client, pid=3497
07-07 20:25:59.584  1107  3495 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-07 20:25:59.584  1107  3495 I InputMethodManagerService: Enable input method client, pid=8115
07-07 20:25:59.584  3069  3069 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-07 20:25:59.584  1107  3946 I ActivityManager: Recipient 7662
,07-07 20:25:59.624  8115  8115 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8115,
07-07 20:25:59.624  1107  3424 D PMS     : releaseWL(84626ac): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-07 20:25:59.624  1107  1150 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +636ms
,07-07 20:25:59.664  6495  6583 I Icing   : Indexing E7E0925662843324D4EEB09F3BC5C5BCEC2A972A from com.google.android.gms
,07-07 20:25:59.694  8115  8115 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:25:59.704  6495  6583 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,07-07 20:25:59.714  8189  8189 D DocsApplication: Plugin installer initialized.
07-07 20:25:59.714  6495  6583 I Icing   : Indexing done E7E0925662843324D4EEB09F3BC5C5BCEC2A972A
,07-07 20:25:59.724  8189  8189 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3c606e57 com.google.android.apps.docs}
,07-07 20:25:59.734  8189  8189 D TAG     : onCreate()
,07-07 20:25:59.744  8115  8213 D jxcore_app_log: JniHelper::setJavaVM(0xab7eeb70), pthread_self() = -1401354816
,07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-07 20:25:59.744  8115  8213 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b83128 added. We now have 1 listener(s)
07-07 20:25:59.754  1107  3925 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-07 20:25:59.754  8115  8213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:3C:62:6A
,07-07 20:25:59.754  8189  8189 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-07 20:25:59.754  8115  8213 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:3C:62:6A"
,07-07 20:25:59.754  8115  8213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-07 20:25:59.754  8115  8213 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000,
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:3C:62:6A
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 20:25:59.754  8115  8213 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be04927 added. We now have 1 listener(s)
07-07 20:25:59.754  8115  8213 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:25:59.764  8115  8213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-07 20:25:59.764  1107  2946 D WifiService: New client listening to asynchronous messages
07-07 20:25:59.764  8115  8213 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-07 20:25:59.764  3497  3497 I ContextualWidget: updateItemPosition item size=8   {-696942466=4, -335140367=0, -1138981812=6, 956745593=1, 1475455068=3, -157894107=7, 534392203=5, -33266553=2}
07-07 20:25:59.764  3497  3911 I ContextualWidget: handleMessage, what=1028 mode=GettingOut maxcount=8
,07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-07 20:25:59.764  1107  4108 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,07-07 20:25:59.764  8115  8213 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:3C:62:6A
07-07 20:25:59.764  8115  8213 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-07 20:25:59.764  8115  8213 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-07 20:25:59.764  8115  8213 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:25:59.764  8115  8213 D io.jxcore.node.ConnectivityMonitor: start: OK
07-07 20:25:59.764  8115  8213 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:25:59.834  1107  2903 V AlarmManager: sending alarm PendingIntent{34f7ae79: PendingIntentRecord{2e468fca com.android.vending startService}}, i=null, t=0, cnt=1, w=1467915959736, Int=0
,07-07 20:25:59.834  8022  8022 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false,
,07-07 20:25:59.854  4310  4310 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
,07-07 20:25:59.854  8115  8115 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfofornet-, err=8,
07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfo_proxy+
,07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-07 20:25:59.894   516  8223 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-07 20:25:59.894   516  8223 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
,07-07 20:25:59.894   516  8223 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-07 20:25:59.894   516  8223 D libc    : [NET] android_getaddrinfofornet-, err=7
07-07 20:25:59.894  8022  8057 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-07 20:25:59.894  8022  8022 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-07 20:25:59.904  4310  4310 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:25:59.914  8022  8058 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
,07-07 20:25:59.914  8022  8058 D libc    : [NET] android_getaddrinfofornet-, err=8
07-07 20:25:59.914  8022  8022 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,07-07 20:25:59.954  1107  3495 I ActivityManager: Start proc 8225:com.google.android.gms:car/u0a20 for service com.google.android.gms/.car.CarService
,07-07 20:25:59.964  4310  4310 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:25:59.964  8225  8225 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:25:59.964  8225  8225 W HTCLOG  : mask=0x18
,07-07 20:25:59.964  1107  1159 D PMS     : releaseHCC(324b0303): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-07 20:25:59.974  1107  1159 D PMS     : releaseHCC(1c2d6280): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-07 20:25:59.994  1107  2903 V AlarmManager: sending alarm PendingIntent{38561d2b: PendingIntentRecord{33cfb588 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=61631, Int=0,
,07-07 20:26:00.014  8225  8225 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-07 20:26:00.014  8225  8225 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-07 20:26:00.024  3069  3886 I ClockController: schedule update now=1467915960029 next=59971
07-07 20:26:00.024  3069  3069 I Clock   : updateClock:20:26 Europe/Brussels
07-07 20:26:00.024  3069  3069 I Clock   : updateClock:20:26 Europe/Brussels
,07-07 20:26:00.024  3069  3069 I Clock   : updateClock:20:26 Europe/Brussels
,07-07 20:26:00.024  3069  4518 D WeatherUtility: Weather sync is On
07-07 20:26:00.024  3069  4518 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,07-07 20:26:00.044  8225  8225 D GmsApplication: Forcing legacy multidex for PROD_LMP build.
,07-07 20:26:00.054  8225  8225 I MultiDex: VM with version 2.1.0 has multidex support,
,07-07 20:26:00.054  8225  8225 I MultiDex: install
07-07 20:26:00.054  8225  8225 I MultiDex: MultiDexExtractor.load(/data/app/com.google.android.gms-1/base.apk, false)
,07-07 20:26:00.064  8022  8057 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-07 20:26:00.064  8022  8057 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-07 20:26:00.064  8225  8225 I MultiDex: loading existing secondary dex files
07-07 20:26:00.064  8022  8022 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-07 20:26:00.064  8225  8225 I MultiDex: load found 4 secondary dex files
,07-07 20:26:00.074  8225  8225 I MultiDex: install done
,07-07 20:26:00.124   571   571 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-07 20:26:00.134  8225  8225 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x7a8
,07-07 20:26:00.134  8225  8225 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0x80
,07-07 20:26:00.134  8225  8225 W linker  : /data/app/com.google.android.gms-1/lib/arm64/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x169
07-07 20:26:00.134  8225  8225 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-07 20:26:00.184  8225  8225 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-07 20:26:00.194  8225  8225 D ChimeraCfgMgr: Reading stored module config
,07-07 20:26:00.234  1107  2903 I ActivityManager: Start proc 8250:com.htc.bgp/u0a8 for service com.htc.flexnet/.FlexNetService
07-07 20:26:00.234  1107  2903 V AlarmManager: sending alarm PendingIntent{36ea234: PendingIntentRecord{16b7e5d2 com.htc.flexnet startService}}, i=ACTION_CAMPNETWORK_NOT_IN_SERVICE_OR_ROAMING, t=2, cnt=1, w=61848, Int=0
,07-07 20:26:00.244  8250  8250 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:26:00.244  8250  8250 W HTCLOG  : mask=0x18
,07-07 20:26:00.294  8225  8243 W art     : Suspending all threads took: 16.676ms
,07-07 20:26:00.304  8250  8250 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-07 20:26:00.324  8250  8250 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,07-07 20:26:00.324  8250  8250 W HTCLOG  : mask=0x18
,07-07 20:26:00.344  8250  8250 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@92e0029(com.htc.providers.calendar.HtcCalendarProvider@3558bfae)
,07-07 20:26:00.364  8250  8275 D CalendarProvider2: wait start:true
,07-07 20:26:00.364  1107  4147 D PMS     : acquireWL(1bcede93): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 8250 10008 null,
07-07 20:26:00.364  8250  8275 D CalendarProvider2: wait end:false
,07-07 20:26:00.384  8250  8250 D FlexNetS: registerStateListener
07-07 20:26:00.394  1107  3946 D PMS     : releaseWL(1bcede93): PARTIAL_WAKE_LOCK  SWITCH_NETWORK_MODE_WAKE_LOCK_0 0x1 null
07-07 20:26:00.394  8250  8250 D FlexNetS: getServiceState:2
07-07 20:26:00.394  8250  8250 D FlexNetS: unregisterStateListener
,07-07 20:26:00.424  8225  8249 D NativeLibraryUtils: Install completed successfully. count=19 extracted=0
,07-07 20:26:00.454  6495  6583 I Icing   : Indexing CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF from com.google.android.googlequicksearchbox
,07-07 20:26:00.494  8225  8225 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>,
07-07 20:26:00.494  8225  8225 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-07 20:26:00.494  8225  8225 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,07-07 20:26:00.504  8225  8225 D CAR.SERVICE: onBind
07-07 20:26:00.504  8225  8225 D CAR.SERVICE: CSB onClientsConnected
,07-07 20:26:00.504  8225  8225 D CAR.TEL.Service: Binding to InCallService
,07-07 20:26:00.514  1107  4115 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
,07-07 20:26:00.514  8225  8225 E CAR.TEL.Service: Failed to bind to InCallService,
,07-07 20:26:00.554  6495  6583 I Icing   : Indexing done CF3FE6BD92DAECCC594E8F8BDE8C89D040E637CF
,07-07 20:26:00.594  8225  8245 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1,
07-07 20:26:00.594  8225  8245 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-07 20:26:00.594  1107  3423 D PMS     : releaseWL(3301e277): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-07 20:26:00.604  8225  8245 D ChimeraFileApk: Primary ABI of requesting process is arm64-v8a
,07-07 20:26:00.604  8225  8245 D ChimeraFileApk: Classloading successful. Optimized code found.
07-07 20:26:00.614  8225  8245 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-07 20:26:00.654  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,07-07 20:26:00.654  3497  3862 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1881d7c4 +
07-07 20:26:00.654  3497  3862 I Prism.WidgetManager: onLoadItems() +
,07-07 20:26:00.674  8225  8245 D GoogleCertificatesImpl: Fetched 163 Google release certificates,
,07-07 20:26:00.674  8225  8245 D CAR.SERVICE: Package validated; name: com.android.vending
,07-07 20:26:00.684  3497  3862 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,07-07 20:26:00.684  8115  8219 W jxcore-log: Initializing JXcore engine,
07-07 20:26:00.684  8115  8219 W jxcore-log: JXcore engine is ready
,07-07 20:26:00.684  8225  8245 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.,
,07-07 20:26:00.744  8115  8219 W jxcore-log: Starting JXcore engine,
,07-07 20:26:00.814  8022  8038 E AndroidHttpClient: Leak found
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.google.android.volley.a.<init>(SourceFile:218)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.google.android.volley.a.a(SourceFile:186)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:176)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: ,	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:139)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(SourceFile:112)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(SourceFile:428)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
,07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
,07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-07 20:26:00.814  8022  8038 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-07 20:26:00.814  8115  8219 W jxcore-log: Platform android
07-07 20:26:00.814  8115  8219 W jxcore-log: 
07-07 20:26:00.814  8115  8219 W jxcore-log: Process ARCH arm,
07-07 20:26:00.814  8115  8219 W jxcore-log: 
,07-07 20:26:00.934  3497  3862 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,07-07 20:26:00.994  8115  8219 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:26:00.994  8115  8219 I jxcore-log: 
07-07 20:26:00.994  8115  8219 W jxcore-log: JXcore engine is started
,07-07 20:26:01.004  8115  8213 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:26:01.004  8115  8115 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,07-07 20:26:01.014  8115  8219 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 20:26:01.014  8115  8219 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 20:26:01.014  8115  8115 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-07 20:26:01.014  8115  8115 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 20:26:01.044  8115  8115 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-07 20:26:01.044  1107  1127 D PMS     : acquireWL(18918d0b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1107 1000 null
07-07 20:26:01.044  8115  8213 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
07-07 20:26:01.044  8115  8115 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-07 20:26:01.044  8189  8289 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-07 20:26:01.044  8189  8289 W HTCLOG  : mask=0x18
07-07 20:26:01.054  1107  3540 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-07 20:26:01.074  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-07 20:26:01.074  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-07 20:26:01.074  3497  3497 I FeedHostManager: [onResume]
,07-07 20:26:01.074  3497  3497 I FeedProviderManager: onResume
07-07 20:26:01.074  3497  4850 I SocialFeedProvider: +onResume
07-07 20:26:01.074  3497  4850 I SocialFeedProvider: updateAccounts - Accounts is no change
07-07 20:26:01.074  3497  4850 I SocialFeedProvider: -onResume
07-07 20:26:01.074  3497  3497 I ConnectivityHelper: [getCurrentConnectionType] no network connection
07-07 20:26:01.074  3497  3497 I ContextualWidget: onResume
07-07 20:26:01.074  3497  3497 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-07 20:26:01.074  3497  3497 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-07 20:26:01.074  3497  3911 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-07 20:26:01.074  3497  3497 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-07 20:26:01.084  3069  3069 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true),
07-07 20:26:01.084  1107  1143 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-07 20:26:01.084  3069  3069 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-07 20:26:01.084  1107  1143 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{fe41342 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-07 20:26:01.084  1107  1143 D StatusBarManagerService: hiding MENU key
,07-07 20:26:01.094  3497  3497 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-07 20:26:01.094  3497  3497 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-07 20:26:01.094  3069  3069 I PhoneStatusBar: setImeWindowStatus(false,false)
07-07 20:26:01.094  1107  3495 I InputMethodManagerService: Disable input method client, pid=8115
07-07 20:26:01.094  1107  3495 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-07 20:26:01.094  1107  3495 I InputMethodManagerService: Enable input method client, pid=3497
,07-07 20:26:01.104  1107  3429 D PMS     : acquireWL(1466f27e): PARTIAL_WAKE_LOCK  AsyncService 0x1 7991 10126 null
,07-07 20:26:01.124  1107  1127 D PMS     : releaseWL(1466f27e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-07 20:26:01.124  8189  8189 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-07 20:26:01.124  1107  3429 I ActivityManager: Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
07-07 20:26:01.124  1107  3424 I ActivityManager: Resuming delayed broadcast
07-07 20:26:01.134  3497  3862 E Prism.WidgetManager: The same lists. No need to update. skip it.
07-07 20:26:01.134  3497  3862 I Prism.WidgetManager: onLoadItems() -
07-07 20:26:01.134  3497  3862 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1881d7c4 -
,07-07 20:26:01.144  1107  3946 D PMS     : releaseWL(18918d0b): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null,
,07-07 20:26:01.154  1107  1143 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-07 20:26:01.154  1107  1143 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{fe41342 u0 com.htc.launcher/com.htc.launcher.Launcher}
07-07 20:26:01.154  1107  1143 D StatusBarManagerService: hiding MENU key
07-07 20:26:01.154  3069  3069 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-07 20:26:01.154  3069  3069 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
,07-07 20:26:01.174  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961181
,07-07 20:26:01.174  8115  8115 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
07-07 20:26:01.174  8115  8115 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-07 20:26:01.174  8115  8115 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-07 20:26:01.174  8115  8115 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-07 20:26:01.174  8115  8115 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-07 20:26:01.174  8115  8115 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:26:01.174  8115  8115 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:26:01.174  8115  8115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:26:01.174  8115  8115 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b83128 removed from the list
07-07 20:26:01.174  8115  8115 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:26:01.174  8115  8115 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1be04927 removed from the list
07-07 20:26:01.174  8115  8115 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:26:01.174  8115  8115 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 20:26:01.194  8115  8115 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 20:26:01.214  8294  8294 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-07 20:26:01.214  8294  8294 W HTCLOG  : mask=0x18
,07-07 20:26:01.214  6495  8028 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,07-07 20:26:01.224  6495  8021 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,07-07 20:26:01.234  6495  8028 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-07 20:26:01.234  6495  6495 D AsyncTaskServiceImpl: Submit a task: nwp
,07-07 20:26:01.234  1107  3457 I ActivityManager: Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver,
07-07 20:26:01.244  1107  3925 D PMS     : acquireWL(31d65fd7): PARTIAL_WAKE_LOCK  Icing 0x1 6495 10020 WorkSource{10020 com.google.android.gms}
,07-07 20:26:01.244  6495  8028 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
07-07 20:26:01.244  6495  6583 D nwp     : Processing package: com.test.thalitest
,07-07 20:26:01.254  8115  8115 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8115
,07-07 20:26:01.284  6495  6583 D GassUtils: Found app info for package com.test.thalitest:19. Hash: c54b0979c92367c90c11058a0bc3a47f427c6241204b15c1acc95cf19a856617
,07-07 20:26:01.284  6495  6583 D nwp     : Found info for package com.test.thalitest in db.
07-07 20:26:01.284  1107  3429 D PMS     : releaseWL(31d65fd7): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
,07-07 20:26:01.294  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915961309
,07-07 20:26:01.314  1107  3418 D PMS     : acquireWL(1df2cee2): PARTIAL_WAKE_LOCK  Icing 0x1 6495 10020 WorkSource{10020 com.google.android.gms},
,07-07 20:26:01.314  3497  4387 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961327
,07-07 20:26:01.384  8250  8250 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
07-07 20:26:01.384  8250  8250 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
07-07 20:26:01.384  4310  4310 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-07 20:26:01.394  1107  3457 D Process : killProcessQuiet, pid=7688
07-07 20:26:01.394  1107  3457 I ActivityManager: Killing 7688:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
07-07 20:26:01.394  1107  3457 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19304 
,07-07 20:26:01.414  1107  3925 I ActivityManager: Recipient 7688
,07-07 20:26:01.414  3497  4387 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915961421
,07-07 20:26:01.424  3497  4351 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-07 20:26:01.434  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961445
,07-07 20:26:01.454  8294  8306 W HTCLOG  : use specified tag [cutils-trace], func [0].,
07-07 20:26:01.454  8294  8306 W HTCLOG  : mask=0x18
07-07 20:26:01.454  8294  8306 E cutils-trace: Error opening trace file: Permission denied (13)
,07-07 20:26:01.494  1107  1142 I ActivityManager: Waited long enough for: ServiceRecord{213a1666 u0 com.nero.android.htc.sync/.PowerDisconService},
07-07 20:26:01.494  1107  1142 I ActivityManager: Resuming delayed broadcast
,07-07 20:26:01.524  8294  8294 D CustomizationManager: ====startRecUseTime====
07-07 20:26:01.524  8294  8294 D htc.customization.log.level:  is ,
07-07 20:26:01.524  8294  8294 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-07 20:26:01.544  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915961557
,07-07 20:26:01.564  3497  4327 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961575
,07-07 20:26:01.584  1107  3495 I ActivityManager: Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,07-07 20:26:01.584  8294  8294 D CustomizationManager:  Read ACC file spent 0.032 (s)
,07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__001
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__002
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__016
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__031
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__032
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__102,
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__J15
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-07 20:26:01.594  8294  8294 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-07 20:26:01.594  8022  8058 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,07-07 20:26:01.594  8294  8294 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-07 20:26:01.594  8022  8058 D libc    : [NET] android_getaddrinfofornet-, err=8
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = application
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = system
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = Settings
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = ACC
07-07 20:26:01.594  8022  8022 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 42507
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 21902
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003,
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23420
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 22299
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 24002
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23210
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23205
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23806
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23430
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23408,
,07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27205
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27202:27205
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27216:27202.27205
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0,
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
,07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27202:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: add string-array item, value = 27216:C:1:0
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-07 20:26:01.594  8294  8294 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-07 20:26:01.594  8294  8294 D CustomizationManager:  Read CID file spent 0.070 (s)
07-07 20:26:01.594  8294  8294 D CustomizationManager:  All configurations done spent 0.070 (s)
07-07 20:26:01.594  8022  8022 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,07-07 20:26:01.614  8022  8022 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,07-07 20:26:01.624  8022  8022 W InstanceID/Rpc: Found 10020
,07-07 20:26:01.624  8022  8022 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(787): Giving up. (failures=6)
,07-07 20:26:01.634  1107  3495 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8294, uid=2000
07-07 20:26:01.634  3497  4094 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-07 20:26:01.634  1107  1142 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-07 20:26:01.634  1107  1142 D Process : killProcessQuiet, pid=8115
07-07 20:26:01.634  1107  1142 I ActivityManager: Killing 8115:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
07-07 20:26:01.634  1107  1142 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,07-07 20:26:01.684  1107  1161 W PackageSettings: Skipping PackageSetting{357ce3d9 com.example.hello/10193} due to missing metadata,
,07-07 20:26:01.704  4310  7289 D DeviceConnectionService: client connected with version: 8486000
,07-07 20:26:01.704   527   527 W HTCLOG  : use specified tag [Vector], func [0].
07-07 20:26:01.704   527   527 W HTCLOG  : mask=0x18
,07-07 20:26:01.724  1107  1127 I ActivityManager: Recipient 8115,
,07-07 20:26:01.724  3244  3244 W HTCLOG  : use specified tag [InputEventReceiver], func [0].
07-07 20:26:01.724  1107  2946 D WifiService: Client connection lost with reason: 4
07-07 20:26:01.724  3244  3244 W HTCLOG  : mask=0x18
07-07 20:26:01.724  3244  3244 E InputEventReceiver: Looper::removeFd(33) is failed, result(0), input channel 'ClientState{36200f0e uid 10000 pid 8115} (c)'
07-07 20:26:01.724  3497  4327 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915961735
,07-07 20:26:01.744  3497  3911 I ContextualWidget: handleMessage, what=1017 mode=GettingOut maxcount=8
07-07 20:26:01.744  1107  3457 D LocationManagerService: getAllProviders()=[passive, gps, network]
,07-07 20:26:01.744  3497  4107 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961750
,07-07 20:26:01.744  1107  3423 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-07 20:26:01.744  1107  3423 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
07-07 20:26:01.744  1107  3925 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
07-07 20:26:01.754  1107  1161 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-07 20:26:01.764  1107  1127 W ActivityManager: Spurious death for ProcessRecord{2930b492 8115:com.test.thalitest/u0a0}, curProc for 8115: null
,07-07 20:26:01.774  3184  3184 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-07 20:26:01.774  3184  3184 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-07 20:26:01.774  1107  4115 D PMS     : acquireWL(2dd9fa60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4310 10020 WorkSource{10020 com.google.android.gms}
07-07 20:26:01.774  4994  4994 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
07-07 20:26:01.774  4994  4994 D [MirrorLinkServer]MirrorLinkServer: ACTION_PACKAGE_REMOVED intent received
07-07 20:26:01.774  4994  4994 D [MirrorLinkServer]MirrorLinkServer: Counter : 1
07-07 20:26:01.774  4994  4994 D [MirrorLinkServer]MirrorLinkConnectionReceiver: notifyMlSevrer
07-07 20:26:01.774  4310  4761 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-07 20:26:01.774  1107  2906 W SystemReader: Cannot find grip_rejection_width, use default value instead
,07-07 20:26:01.784  4994  4994 I [MirrorLinkServer]MirrorLinkServer: onStartCommand() Action : android.intent.action.PACKAGE_REMOVED
,07-07 20:26:01.784  1107  3946 D PMS     : releaseWL(2dd9fa60): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10020 com.google.android.gms}
07-07 20:26:01.784  4994  4994 D [MirrorLinkServer]MirrorLinkServer: Application Removed
07-07 20:26:01.784  4994  4994 D [MirrorLinkServer]MirrorLinkServer:  Application removed : com.test.thalitest
07-07 20:26:01.784  4994  4994 D [MirrorLinkServer]d: onApplicationRemoved
07-07 20:26:01.784  4994  4994 I [MirrorLinkServer]d: Package name found : com.test.thalitest
,07-07 20:26:01.794  1107  2943 V NetworkPolicy: ACTION_UID_REMOVED for uid=10000
07-07 20:26:01.794  1107  2942 D PMS     : acquireWL(26e0adbf): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1107 1000 null
07-07 20:26:01.794  1107  3457 I ActivityManager: Resuming delayed broadcast
07-07 20:26:01.794  4994  8325 I [MirrorLinkServer]c: onApplicationUpdationCompleted, sending broadcast
07-07 20:26:01.794  8022  8022 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-07 20:26:01.794  4994  4994 I [MirrorLinkServer]MirrorLinkServer: Broadcast Received::Intent { act=com.htc.HTCMirrorLinkServer.PACKAGE_UPDATE_COMPLETED }
07-07 20:26:01.794  4994  4994 D [MirrorLinkServer]MirrorLinkServer: ML_PACKAGE_UPDATE_COMPLETED intent received
07-07 20:26:01.794  4994  4994 D [MirrorLinkServer]MirrorLinkServer: Counter : 0
07-07 20:26:01.794  4994  4994 I [MirrorLinkServer]MirrorLinkConnectionReceiver: checkAndStopMLSession
07-07 20:26:01.794  4994  4994 I [MirrorLinkServer]MirrorLinkConnectionReceiver: Stopping Service
07-07 20:26:01.794  3643  4100 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-07 20:26:01.804  8022  8022 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected,
,07-07 20:26:01.804  3643  4100 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-07 20:26:01.814  6239  6239 I art     : Explicit concurrent mark sweep GC freed 18190(1160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 3MB/5MB, paused 413us total 54.798ms
,07-07 20:26:01.814  3643  4100 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,07-07 20:26:01.814  1107  2903 V AlarmManager: sending alarm PendingIntent{1c30b578: PendingIntentRecord{2ad80451 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1467915961610, Int=0
07-07 20:26:01.814  1107  2942 D PMS     : releaseWL(26e0adbf): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-07 20:26:01.824  1107  2943 V NetworkPolicy: writePolicyLocked()
,07-07 20:26:01.824  8189  8189 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-07 20:26:01.824  8022  8022 I Finsky  : [1] com.google.android.finsky.utils.bh.run(2302): Package state data is missing for com.test.thalitest
,07-07 20:26:01.834  1107  2943 D NetworkPolicy: notifyPoliciesChangeLocked: no change
,07-07 20:26:01.834  3643  4100 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-07 20:26:01.834  1107  2943 V NetworkPolicy: updateNetworkEnabledLocked()
07-07 20:26:01.834  1107  2943 V NetworkPolicy: updateNotificationsLocked()
,07-07 20:26:01.854  1107  4108 D Process : killProcessQuiet, pid=7740,
07-07 20:26:01.854  1107  4108 I ActivityManager: Killing 7740:com.google.android.gm.exchange/u0a156 (adj 15): empty #17,
07-07 20:26:01.854  1107  4108 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
07-07 20:26:01.854  3643  4100 E ExternalAccountType: Unsupported attribute readOnly,
,07-07 20:26:01.864  3462  3462 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED,
07-07 20:26:01.864  1107  1141 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-07 20:26:01.934  1107  3745 I art     : Explicit concurrent mark sweep GC freed 36344(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 1.619ms total 156.134ms
07-07 20:26:01.934  1107  1161 I art     : WaitForGcToComplete blocked for 148.134ms for cause Explicit
,07-07 20:26:01.934  1107  1127 I ActivityManager: Recipient 7740
,07-07 20:26:01.944  3497  8324 D HtcTelephonyManager: wrong phone slot in non-dual projects,
,07-07 20:26:01.944  3497  4107 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915961959
,07-07 20:26:01.964  1107  1141 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-07 20:26:01.964  3497  4533 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
07-07 20:26:01.964  1107  1107 W PackageManager: Unable to load service info ResolveInfo{2e1110ec com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-07 20:26:01.964  1107  1107 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:01.964  1107  1107 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
,07-07 20:26:01.964  1107  1107 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-07 20:26:01.984  3497  4351 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915961990
07-07 20:26:01.984  1107  4147 I ActivityManager: Start proc 8327:com.htc.autobot/u0a27 for broadcast com.htc.autobot/.AlarmReceiver
,07-07 20:26:01.994  1107  4147 I ActivityManager: Killing 6093:com.htc.sense.mms/u0a54 (adj 15): empty #17
07-07 20:26:01.994  1107  4147 D Process : killProcessQuiet, pid=6093
07-07 20:26:01.994  1107  4147 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19461 com.android.server.am.ActivityManagerService.trimApplications:19731 
,07-07 20:26:01.994  8327  8327 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:26:01.994  8327  8327 W HTCLOG  : mask=0x18
,07-07 20:26:02.004  1107  3495 I ActivityManager: Recipient 6093,
,07-07 20:26:02.044  3497  8324 D HtcTelephonyManager: wrong phone slot in non-dual projects,
,07-07 20:26:02.054  1107  1107 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-07 20:26:02.074  1107  1161 I art     : Explicit concurrent mark sweep GC freed 8470(497KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 1.948ms total 142.776ms
,07-07 20:26:02.084  3497  4351 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962092
,07-07 20:26:02.104  3497  4387 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962110,
,07-07 20:26:02.104   500   500 E TPD     : [TPD][ERR] can't open /proc/6093/status...
,07-07 20:26:02.144  8294  8294 I art     : System.exit called, status: 0,
,07-07 20:26:02.214  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
07-07 20:26:02.214  3497  3862 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-07 20:26:02.214  3417  3417 D Nfc-Utils: isNxpCodebase: isNxp=false,
,07-07 20:26:02.234  3497  4387 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962245
,07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 4
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfofornet-, err=8
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfo_proxy+
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,07-07 20:26:02.244   516  8352 D libc    : [NET] android_getaddrinfofornet+,hn 28(0x7265636f6d6d65),sn(),hints(known),family 0,flags 1024
07-07 20:26:02.244   516  8352 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-07 20:26:02.244   516  8352 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-07 20:26:02.244   516  8352 D libc    : [NET] android_getaddrinfofornet-, err=7
07-07 20:26:02.244  3497  8324 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
07-07 20:26:02.244  3497  8324 E ServerCorridor: BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-07 20:26:02.244  3497  8324 W System.err: com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:192)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:98)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:367)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.prism.feed.corridor.recommendation.RecommendationNService.getWelcomeAppSuggest(RecommendationNService.java:125)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.syncRecommendedApps(HtcContextualWidgetService.java:374)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:168)
07-07 20:26:02.244  3497  8324 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.244  3497  8324 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.244  3497  8324 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.244  3497  8324 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.244  3497  8324 W System.err: Caused by: java.lang.Throwable: Unable to resolve host "recommend-prism.htcsense.com": No address associated with hostname
07-07 20:26:02.244  3497  8324 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
07-07 20:26:02.244  3497  8324 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
07-07 20:26:02.244  3497  8324 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:403)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:116)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
07-07 20:26:02.244  3497  8324 W System.err: 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:137)
,07-07 20:26:02.244  3497  8324 W System.err: 	... 9 more
07-07 20:26:02.254  3497  4296 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962264
07-07 20:26:02.254  8327  8327 D AlarmReceiver: ACTION_RESTART_INTENT
,07-07 20:26:02.254  3937  8351 I art     : Explicit concurrent mark sweep GC freed 2335(90KB) AllocSpace objects, 0(0B) LOS objects, 67% free, 969KB/2MB, paused 357us total 29.061ms,
07-07 20:26:02.264  3643  3643 V LoadDialerReceiver: LoadDialerReceiver.onReceive
07-07 20:26:02.264  8327  8327 D LocalBluetoothProfile: getPriorityOnValue = 100
07-07 20:26:02.264  8327  8327 D LocalBluetoothProfile: getPriorityOffValue = 0
,07-07 20:26:02.264  7879  7879 D ProviderChangeReceiver: ---------------------------------------------------
07-07 20:26:02.264  7879  7879 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-07 20:26:02.274  7879  8355 D HtcAlertService: start to updateAlertNotification!
,07-07 20:26:02.274  8327  8327 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
07-07 20:26:02.274  8022  8022 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(2100): Skipping verification because network inactive
07-07 20:26:02.274  8327  8327 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,07-07 20:26:02.274  1107  1162 I ActivityManager: Delay finish: com.android.vending/com.google.android.vending.verifier.VerifyInstalledPackagesReceiver
,07-07 20:26:02.284  7879  8355 D HtcAlertService: No fired or scheduled alerts
,07-07 20:26:02.284  7879  8355 D HtcAlertUtils: -- cancelReminderNotification --
,07-07 20:26:02.284  7879  8355 D HtcAlertUtils: broadcastExistReminder!
,07-07 20:26:02.284  3184  3184 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,07-07 20:26:02.314  8327  8361 D HtcModeClient: start the htcmodeservice thread
,07-07 20:26:02.314  8327  8361 D HtcModeClient: initCanAgent
,07-07 20:26:02.324  8327  8361 I CANMesgAgentLocalSocket: CANAgent Id = 0
,07-07 20:26:02.324  8327  8361 D HtcModeClient: sense info: version = none, id = 2,
,07-07 20:26:02.334  8327  8361 D HtcModeClient: display info: width = 1080, height = 1776
07-07 20:26:02.334  8327  8361 D HtcModeClient: display info: mode = 10
,07-07 20:26:02.344  4310  4778 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
07-07 20:26:02.344  4310  4780 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/shared_prefs/sizeCache.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
07-07 20:26:02.344  4310  4778 W HTCLOG  : mask=0x18
,07-07 20:26:02.344  4310  4778 E SQLiteDBG: func: executeNonQuery, errno: 30, error msg: Read-only file system, path: /data/data/com.google.android.gms/databases/playlog.db, handle: 0x55b2c25770
,07-07 20:26:02.354  4310  4778 E ClearcutService: could not write to store: java.io.IOException: Could not end transaction after writing to SQLite
07-07 20:26:02.354  4310  4778 E SQLiteLog: (2570) os_unix.c:30184: (30) unlink(/data/data/com.google.android.gms/databases/playlog.db-wal) - 
,07-07 20:26:02.364  3497  4296 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962377
,07-07 20:26:02.374  6495  6618 I Icing   : Indexing E7E0925662843324D4EEB09F3BC5C5BCEC2A972A from com.google.android.gms,
,07-07 20:26:02.384  3497  4407 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.,
,07-07 20:26:02.394  6495  6618 I Icing   : Indexing done E7E0925662843324D4EEB09F3BC5C5BCEC2A972A
,07-07 20:26:02.394  6495  6618 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
07-07 20:26:02.394  6495  6618 E Icing   : Writing status failed
07-07 20:26:02.394  1107  3457 D PMS     : releaseWL(1df2cee2): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10020 com.google.android.gms}
07-07 20:26:02.404  1107  1127 I ActivityManager: Resuming delayed broadcast
,07-07 20:26:02.404  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962414
,07-07 20:26:02.414  1107  3495 D PMS     : acquireWL(a2d265b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4310 10020 WorkSource{10020 com.google.android.gms}
,07-07 20:26:02.424  8327  8327 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,07-07 20:26:02.424  3497  4180 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-07 20:26:02.424  3690  3892 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-07 20:26:02.424  3690  3892 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-07 20:26:02.424  3690  3892 W HTCLOG  : mask=0x18
07-07 20:26:02.424  3690  3892 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x55b2b30c90
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: BT_TURNON_BYME = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: CONNECTION_READY = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: PHONE_PULGIN = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: Force_AWAKE = false
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: PHONE_PULGIN = true
07-07 20:26:02.424  8327  8327 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,07-07 20:26:02.424  1107  1162 I ActivityManager: Delay finish: com.android.providers.contacts/.PackageIntentReceiver,
,07-07 20:26:02.434  3690  3892 W ContactsProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850),
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2162)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at com.android.providers.contacts.HtcContactsProvider2.performBackgroundTask(HtcContactsProvider2.java:11533)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1819)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.434  3690  3892 W ContactsProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:26:02.434  3690  8364 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-07 20:26:02.434  8327  8363 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,07-07 20:26:02.444  8327  8363 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,07-07 20:26:02.454  3690  8364 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,07-07 20:26:02.454  3690  8364 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x55b2b30c90
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:275)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:174)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.454  3690  8364 W VoicemailContentProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:26:02.454  3690  8364 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
07-07 20:26:02.454  1107  3418 D PMS     : releaseWL(a2d265b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10020 com.google.android.gms}
07-07 20:26:02.454  3690  8364 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.contacts/databases/contacts2.db, handle: 0x55b2b30c90
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:174)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	,at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.464  3690  8364 W VoicemailContentProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.464  1107  4147 I ActivityManager: Resuming delayed broadcast
,07-07 20:26:02.484  1107  4147 I ActivityManager: Start proc 8365:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,07-07 20:26:02.494  8365  8365 W HTCLOG  : use specified tag [FDManager], func [0].,
07-07 20:26:02.494  8365  8365 W HTCLOG  : mask=0x18
,07-07 20:26:02.494  3497  4180 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962504
,07-07 20:26:02.504  3497  4396 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962516,
07-07 20:26:02.514   564   564 I art     : Explicit concurrent mark sweep GC freed 8642(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 165us total 25.685ms
,07-07 20:26:02.514  3497  4396 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak,
,07-07 20:26:02.524   564   564 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 122us total 17.182ms
,07-07 20:26:02.534  3069  3069 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-07 20:26:02.544   564   564 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 113us total 18.020ms
,07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: error sending REQ[fc:96; creat:1467720984996; type:boc-723119010: devices/registerdevice
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: ProtoBuf:
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: null
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: Creation stack:
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: java.lang.Throwable
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at bnw.<init>(SourceFile:443)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at boc.<init>(SourceFile:2476)
,07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at boc.a(SourceFile:2506)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at bxx.a(SourceFile:88)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:3328)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
,07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: Origin stack:
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: java.lang.Throwable
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:1175)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at btp.b(SourceFile:1867)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at btl.u(SourceFile:1301)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:829)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.554  7817  7853 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
,07-07 20:26:02.554  7817  7853 E SQLiteLog: (3850) statement aborts at 28: [UPDATE messages SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
07-07 20:26:02.554  7817  7853 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-07 20:26:02.554  7817  7853 W HTCLOG  : mask=0x18
07-07 20:26:02.554  7817  7853 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.talk/databases/message_store.db, handle: 0xac5599c0
07-07 20:26:02.554  7817  7853 E Babel   : Uncaught exception in background thread Thread[default_queuethalitester@gmail.com,5,main]
07-07 20:26:02.554  7817  7853 E Babel   : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-07 20:26:02.554  7817  7853 E Babel   : 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-07 20:26:02.554  7817  7853 E Babel   : 	at byk.a(SourceFile:2058)
07-07 20:26:02.554  7817  7853 E Babel   : 	at byo.run(SourceFile:1156)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: FATAL EXCEPTION: default_queuethalitester@gmail.com
07-07 20:26:02.554  7817  7817 E AndroidRuntime: Process: com.google.android.talk, PID: 7817
07-07 20:26:02.554  7817  7817 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at byk.a(SourceFile:2058)
07-07 20:26:02.554  7817  7817 E AndroidRuntime: 	at byo.run(SourceFile:1156)
07-07 20:26:02.564  1107  1162 E ActivityManager: App crashed! Process: com.google.android.talk
07-07 20:26:02.564  3643  3643 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,07-07 20:26:02.574  1107  8386 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.574  1107  8386 E DropBoxManagerService: 	... 5 more
,07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: error sending REQ[fc:7; creat:1467915939840; type:bme-591065565: userphotoalbums
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: ProtoBuf:
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: null
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: Creation stack:
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: java.lang.Throwable
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at bng.<init>(SourceFile:300)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	,at bnw.<init>(SourceFile:443)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at bma.<init>(SourceFile:50)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at bme.<init>(SourceFile:344)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at bvf.a(SourceFile:26)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:5093)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.g(SourceFile:4568)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.a(SourceFile:887)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.onHandleIntent(SourceFile:766)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: Origin stack:
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: java.lang.Throwable
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.e(SourceFile:1157)
,07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.f(SourceFile:3214)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.realtimechat.RealTimeChatService.s(SourceFile:2980)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.a(SourceFile:132)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.stickers.StickersModule.v_(SourceFile:105)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.google.android.apps.hangouts.phone.EsApplication.onCreate(SourceFile:566)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
,07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: ,	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-07 20:26:02.594  7817  7854 I Babel_RequestWriter: ]; took 0 ms (error code == 101)
07-07 20:26:02.604  7817  7854 E SQLiteLog: (3850) statement aborts at 28: [UPDATE messages SET server_target_retry=?,server_fail_count=?,fail_count=? WHERE _id=?] disk I/O error
07-07 20:26:02.604  7817  7854 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.talk/databases/message_store.db, handle: 0xac5599c0
07-07 20:26:02.604  7817  7854 E Babel   : Uncaught exception in background thread Thread[ui_queuethalitester@gmail.com,5,main]
07-07 20:26:02.604  7817  7854 E Babel   : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-07 20:26:02.604  7817  7854 E Babel   : 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-07 20:26:02.604  7817  7854 E Babel   : 	at byk.a(SourceFile:2058)
07-07 20:26:02.604  7817  7854 E Babel   : 	at byo.run(SourceFile:1156)
07-07 20:26:02.604  3497  3497 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
07-07 20:26:02.604  3497  3497 I ContextualWidget: package com.test.thalitest removed
07-07 20:26:02.604  3497  3911 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
07-07 20:26:02.604  3372  8387 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
07-07 20:26:02.614  3372  8387 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
07-07 20:26:02.614  3372  8387 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-07 20:26:02.614  3372  8387 W HTCLOG  : mask=0x18
07-07 20:26:02.614  3372  8387 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.sense.hsp/databases/registry.db, handle: 0x55b2c04390
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: provider may killed!
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(,SQLiteStatement.java:64)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.614  3372  8387 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.614  3497  4396 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962624
07-07 20:26:02.614  3372  8387 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
07-07 20:26:02.614  1107  4115 I ActivityManager: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
07-07 20:26:02.614  6239  8389 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-07 20:26:02.624  3497  8388 I ContextualWidget: com.test.thalitest is not installed
07-07 20:26:02.624  3497  8388 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
07-07 20:26:02.624  3497  8388 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
07-07 20:26:02.624  3497  8388 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-07 20:26:02.624  3497  8388 W HTCLOG  : mask=0x18
07-07 20:26:02.624  3497  8388 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac447cf8
07-07 20:26:02.624  3497  8388 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
07-07 20:26:02.624  3497  8388 E AndroidRuntime: Process: com.htc.launcher, PID: 3497
07-07 20:26:02.624  3497  8388 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.624  3497  8388 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.624  1107  3418 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-07 20:26:02.624  1107  3418 E ActivityManager: App crashed! Process: com.htc.launcher
07-07 20:26:02.634  1107  3418 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-07 20:26:02.634  1107  3418 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-07 20:26:02.634  1107  3418 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:02.634  1107  3418 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.634  1107  1143 D StatusBarManagerService: setSystemUiVisibility(0xc0000000)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.634  1107  1143 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{1a885628 u0 Application Error: com.google.android.talk}
07-07 20:26:02.634  1107  3418 W System.err: 	... 14 more
07-07 20:26:02.634  1107  1143 D StatusBarManagerService: hiding MENU key
07-07 20:26:02.634  1107  3418 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-07 20:26:02.634  1107  3418 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:02.634  1107  3418 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-07 20:26:02.644  1107  8390 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-07 20:26:02.644  1107  8390 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1467915962648.dbox_tmp: open failed: EROFS (Read-only file system)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.644  1107  8390 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.644  1107  8390 E ErrorReport: 	... 4 more
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-07 20:26:02.634  1107  3418 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-07 20:26:02.634  1107  3418 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-07 20:26:02.634  1107  3418 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:02.634  1107  3418 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.634  1107  3418 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.634  1107  3418 W System.err: 	... 14 more
07-07 20:26:02.634  3069  3069 I PhoneStatusBar: setSystemUiNavVisibility(swipe=false hasFocus=false hasPolicy=false shadeState=true)
07-07 20:26:02.644  1107  3418 D PMS     : acquireWL(28628172): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 1107 1000 null
07-07 20:26:02.634  3069  3069 I PhoneStatusBar: hiding the MENU button mLongPressHomeMenu = false
07-07 20:26:02.644  1107  3540 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-07 20:26:02.644  1107  3540 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.644  1107  3540 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.644  1107  3540 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:02.644  1107  3540 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-07 20:26:02.644  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-07 20:26:02.644  1107  3540 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.644  1107  3540 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.644  1107  3540 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.644  1107  3540 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.654  3497  3497 I FeedHostManager: [onPause]
07-07 20:26:02.654  3497  3497 I FeedProviderManager: onPause
07-07 20:26:02.654  3497  3497 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@15dd1c70
07-07 20:26:02.654  1107  3540 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.654  1107  3540 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.654  1107  3540 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.654  1107  3540 W System.err: 	... 12 more
07-07 20:26:02.654  3497  3497 I ContextualWidget: onPause
07-07 20:26:02.654  3497  3497 I ContextualWidget: notifyWidgetDeactive
07-07 20:26:02.654  3497  4850 I SocialFeedProvider: +onPause
07-07 20:26:02.654  3497  4850 I SocialFeedProvider: -onPause
07-07 20:26:02.654  3497  4767 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
07-07 20:26:02.664  1107  3495 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
07-07 20:26:02.664  6239  8389 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-07 20:26:02.664  6239  8389 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-07 20:26:02.664  6239  8389 W HTCLOG  : mask=0x18
07-07 20:26:02.664  6239  8389 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55b2b030a0
07-07 20:26:02.674  1107  3495 V WindowManager: addAppToken: AppWindowToken{303d7f1f token=Token{27d342be ActivityRecord{636579 u0 com.htc.launcher/.Launcher t110}}} to stack=0 task=110 at 0
07-07 20:26:02.674  3497  3497 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@2c5e7010 for type 0
07-07 20:26:02.674  3497  4327 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962684
07-07 20:26:02.684  3497  4327 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
07-07 20:26:02.694  3497  3497 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@2c5e7010 for type 1
07-07 20:26:02.694  3497  3497 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@2c5e7010 for type 3
07-07 20:26:02.694  3497  3497 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@2c5e7010 for type 2
,07-07 20:26:02.704  1107  3540 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,07-07 20:26:02.714  3497  3497 I OrientationManager: [release]
07-07 20:26:02.714  3497  3497 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20
07-07 20:26:02.714  3497  3497 I ContextualWidget: onDestroy
07-07 20:26:02.714  3497  3911 I ContextualWidget: handleMessage, what=1030 mode=GettingOut maxcount=8
07-07 20:26:02.714  3497  3911 I ContextualWidget: release
,07-07 20:26:02.724  6239  8389 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,07-07 20:26:02.734  6239  8389 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-07 20:26:02.734  6239  8389 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6239
07-07 20:26:02.734  6239  8389 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282),
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.734  6239  8389 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.734  1107  3429 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.734  1107  8393 E DropBoxManagerService: 	... 5 more
07-07 20:26:02.734  3497  3497 I ContextualWidget: new instance com.htc.launcher.htcwidget.HtcContextualWidgetController@c2b615a
07-07 20:26:02.734  3497  3497 I ContextualWidget: unlockModeChange
07-07 20:26:02.734  3497  3497 I ContextualWidget: notifyWidgetDeactive
07-07 20:26:02.754  1107  3457 I ActivityManager: Delaying start of: ServiceRecord{1cca0888 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
,07-07 20:26:02.774  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@2beaeb3 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.774  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$GoogleBackupReceiver@2beaeb3 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:98)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.774  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:26:02.784  3497  4327 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962798
,07-07 20:26:02.804  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@56be422 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.804  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.FeedSevenDaysNotification$HTCAccountAddedReceiver@56be422 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	,at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.util.FeedSevenDaysNotification.<init>(FeedSevenDaysNotification.java:95)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:535)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529),
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.804  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@5cf8f9c that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.804  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$NightModeSyncReceiver@5cf8f9c that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202),
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:839)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.804  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.814  3497  4762 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915962825
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@f0cd6cd that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.calendar.CalendarFeedAdapter$TimeZoneChangeReceiver@f0cd6cd that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProv,iderContext$WrappedContext.registerReceiver(FeedProviderContext.java:325)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedAdapter.<init>(CalendarFeedAdapter.java:98)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.feed.local.calendar.CalendarFeedProvider.onCreate(CalendarFeedProvider.java:19)
07-07 20:26:02.814  3497  3497 E ActivityThread: ,	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.814  3497  3497 E ActivityThread: ,	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@1194fdf7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$7@1194fdf7 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202),
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:674)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
,07-07 20:26:02.824  3497  4762 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@139d12c9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.local.getstarted.GetStartedFeedProvider$1@139d12c9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.feed.local.getstarted.GetStartedFeedProvider.onCreate(GetStartedFeedProvider.java:75)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-07 20:26:02.814  3497  3497 E ActivityThread: ,	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@1ae095f6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.feed.socialfeedprovider.SocialFeedProvider$6@1ae095f6 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext$WrappedContext.registerReceiver(FeedProviderContext.java:338)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	,at com.htc.feed.socialfeedprovider.SocialFeedProvider.onCreate(SocialFeedProvider.java:617)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.performCreate(FeedProvider.java:84)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProvider.init(FeedProvider.java:64)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderContext.loadFeedProvider(FeedProviderContext.java:154)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.registerProvider(FeedProviderManager.java:602)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1223)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager$16.call(FeedProviderManager.java:1194)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	,at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1c6f6be9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$CustomHighlightReceiver@1c6f6be9 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:817)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@1feb830f that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E Ac,tivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.util.ConnectivityHelper$ConnectivityChangeReceiver@1feb830f that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:489)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:209)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:826)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 I OrientationManager: [init] currentOrienation: 1
07-07 20:26:02.814  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$LaunchCoobeReceiver@25c9dda5 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$L,aunchCoobeReceiver@25c9dda5 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:843)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.814  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 E ResourceType: Style contains key with bad entry: 0x01010504
07-07 20:26:02.824  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@269b1496 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedPushReceiver@269b1496 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:153)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 W HtcWrapConfigurationActivity: no reset icon com.htc.launcher.Launcher@392b2868, false
07-07 20:26:02.824  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@27f277b1 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.libfeedframework.FeedProviderManager$RestoreCompleteReceiver@27f277b1 that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.libfeedframework.FeedProviderManager.<init>(FeedProviderManager.java:152)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.<init>(FeedHostManager.java:503)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:118)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@3efc1967 for type 0
07-07 20:26:02.824  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@2b19d57a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$SummonSnapToReceiver@2b19d57a that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:847)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@3efc1967 for type 1
07-07 20:26:02.824  3497  3497 E ActivityThread: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@2d88206e that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.htc.launcher.Launcher has leaked IntentReceiver com.htc.launcher.feeds.FeedHostManager$FilterSettingReceiver@2d88206e that was originally registered here. Are you missing a call to unregisterReceiver()?
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:980)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:742)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1781)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1761)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:496)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.util.HtcWrapConfigurationActivity.registerReceiver(HtcWrapConfigurationActivity.java:202)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.registerReceivers(FeedHostManager.java:822)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManager.onCreate(FeedHostManager.java:857)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.onCreate(FeedHostManagerProxy.java:175)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.feeds.FeedHostManagerProxy.bind(FeedHostManagerProxy.java:134)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedHostManager(Launcher.java:1360)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.Launcher.bindFeedCustomization(Launcher.java:6751)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.bindFeedCustomization(LauncherModel.java:1529)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.access$1200(LauncherModel.java:1262)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask$1.onFeedCustomization(LauncherModel.java:1315)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$FeedCustomizationTask.doRun(LauncherLoader.java:663)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader$Task.run(LauncherLoader.java:121)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.load(LauncherLoader.java:982)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherLoader.triggerToLoad(LauncherLoader.java:1009)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.LauncherModel$LoaderTask.run(LauncherModel.java:1477)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$TagRunnable.run(TaskWorker.java:156)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at com.htc.launcher.task.TaskWorker$DeferredHandler$Impl.handleMessage(TaskWorker.java:230)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.824  3497  3497 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.844  3497  3497 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@3efc1967 for type 3
07-07 20:26:02.844  3497  3497 D HtcThemeUtils: Register com.htc.launcher.util.HtcWrapConfigurationActivity$2@3efc1967 for type 2
07-07 20:26:02.854  1107  3457 W AppWidgetServiceImpl: startListening(),set useForground = true
07-07 20:26:02.854  1107  3457 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-07 20:26:02.854  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-07 20:26:02.854  1107  3457 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherTransClock4x1}
07-07 20:26:02.854  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.874  6495  8320 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: Couldn't open games_3a3529a.db for writing (will try read-only):
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseGmsContentProvider.query(BaseGmsContentProvider.java:191)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:408)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.superQuery(:com.google.android.gms:540)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.chimera.ContentProvider.query(:com.google.android.gms:172)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.chimera.container.ContentProviderProxy.query(:com.google.android.gms:420)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.AccountAgent.getAccount(AccountAgent.java:86)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.games.broker.DataBroker.getClientContextsForAllDatastores(DataBroker.java:3782)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:30)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:177)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:02.874  6495  8320 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:02.884  6495  8320 W SQLiteOpenHelper: Opened games_3a3529a.db in read-only mode
07-07 20:26:02.884  1107  1142 I ActivityManager: Start proc 8396:com.htc.widget.hmsproc2/u0a36 for broadcast com.htc.widget.weatherclock/.WeatherTransClock4x1
,07-07 20:26:02.884  1107  3457 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-07 20:26:02.884  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-07 20:26:02.884  1107  3457 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider}
07-07 20:26:02.884  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-07 20:26:02.884  1107  3457 D AppWidgetServiceImpl: sendEnableIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-07 20:26:02.884  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_ENABLED
07-07 20:26:02.884  1107  3457 D AppWidgetServiceImpl: sendUpdateIntentLocked for ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider}
07-07 20:26:02.884  1107  3457 W AppWidgetServiceImpl: use FLAG_RECEIVER_FOREGROUND to send android.appwidget.action.APPWIDGET_UPDATE
07-07 20:26:02.894  3497  3497 I ContextualWidget: onCreate
07-07 20:26:02.894  3497  8392 I ContextualWidget: handleMessage, what=1029 mode=GettingOut maxcount=8
07-07 20:26:02.894  3497  8392 I ContextualWidget: initialize()
07-07 20:26:02.894  3372  3413 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_address
07-07 20:26:02.894  3372  3413 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.894  3372  3413 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.894  3497  3497 W ResourceType: Invalid package identifier when getting bag for resource number 0x00000014
07-07 20:26:02.894  8396  8396 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:26:02.894  8396  8396 W HTCLOG  : mask=0x18
07-07 20:26:02.904  3497  3497 D AbsListView:  setHtcScrollEnabled item height = 190
07-07 20:26:02.914  3497  3497 I FeedScrollGridView: velocity 0.850000
07-07 20:26:02.914  3372  3699 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_address
07-07 20:26:02.914  3372  3699 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.914  3372  3699 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.914  3497  8392 I ContextualWidget: loadLocations size = 0, home: 0, work: 0
07-07 20:26:02.914  3372  3408 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_wifi
07-07 20:26:02.914  3372  3408 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.924  3372  3408 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.924  6495  8395 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQor84Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
07-07 20:26:02.924  6495  8395 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjMgKDI4Njc2MzctMDQ4KRjgq-AR
07-07 20:26:02.924  6495  8395 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsKvgEQ
07-07 20:26:02.924  6495  8395 I GCore-Chimera-Crash: ==
07-07 20:26:02.924  6495  8395 I GCore-Chimera-Crash: GCore-Chimera-Crash
07-07 20:26:02.924  6495  8395 E AndroidRuntime: FATAL EXCEPTION: GamesProviderWorker
07-07 20:26:02.924  6495  8395 E AndroidRuntime: Process: com.google.android.gms, PID: 6495
07-07 20:26:02.924  6495  8395 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:311)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:843)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.initialize(ImageStore.java:149)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at com.google.android.gms.games.provider.ImageStore.<init>(ImageStore.java:78)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at com.google.android.gms.games.provider.GamesDataStore.initialize(GamesDataStore.java:111)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1730)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1651)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:02.924  6495  8395 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:02.924  1107  4115 E ActivityManager: App crashed! Process: com.google.android.gms
07-07 20:26:02.924  3372  3412 D [LocationSvProvider]: query uri = content://com.htc.locationservicessettingprovider.provider/table_wifi
07-07 20:26:02.934  3372  3412 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
07-07 20:26:02.934  3372  3412 D [LocationSvProvider]: No data in AddressInfo database, do not sync to LocationInfo
,07-07 20:26:02.934  1107  8417 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:02.934  1107  8417 E DropBoxManagerService: 	... 5 more
,07-07 20:26:02.934  1107  1143 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-07 20:26:02.934  1107  1143 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-07 20:26:02.944  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-07 20:26:02.944  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
07-07 20:26:02.944  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-07 20:26:02.944  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-07 20:26:02.944  3497  3497 D HtcFooter: layerDrawableIndex = 0
,07-07 20:26:02.954  3497  4762 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915962961
,07-07 20:26:02.954  3497  3497 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk is neither a directory nor file (type=1).
07-07 20:26:02.954  3497  3497 D HtcThemeUtils: AssetMaanger addAssetPath WeatherClock fail!
,07-07 20:26:02.964  1107  1142 I ActivityManager: Waited long enough for: ServiceRecord{3fb6138 u0 com.aiqidii.mercury/.service.ls.LocalServerControllerService}
,07-07 20:26:02.974  3497  4190 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-07 20:26:02.974  1107  1142 I ActivityManager: Start proc 8418:com.htc.launcher:biclient/u0a59 for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService
,07-07 20:26:02.984  3497  8392 I ContextualWidget: loadwifis , home: 0, work: 0
07-07 20:26:02.984  3497  3497 I FeedActionBar: updateLastUpdatedTime(in String) LAST UPDATED 1:00
,07-07 20:26:02.994  3497  8392 I ContextualWidget: updateUserConsent() - location: false, data: false
,07-07 20:26:02.994   525  8433 E MM_OSAL : FileSource::FileSource,
07-07 20:26:02.994   525  8433 E MM_OSAL : FileSource::FileSource m_bEveryThingOK 1
,07-07 20:26:02.994   525  8433 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/mmosal_logmask.cfg , Mode 0
07-07 20:26:02.994   525  8433 E MM_OSAL : Open or read fail on /data/mmosal_logmask.cfg. Possible permission denied issue. Looking for /data/misc/media/mmosal_logmask.cfg
07-07 20:26:02.994  3497  4533 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915963006
07-07 20:26:02.994   525  8433 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/misc/media/mmosal_logmask.cfg , Mode 0
,07-07 20:26:03.004   525  8433 W QCOMExtractor: Sample Bit is, 16, set to kKeyBitsPerSample,
07-07 20:26:03.004  8418  8418 W HTCLOG  : use specified tag [FDManager], func [0].
07-07 20:26:03.004  8418  8418 W HTCLOG  : mask=0x18
,07-07 20:26:03.004   525  8433 W MediaExtractor: Sample Bit is, 16, support QCOMExtractor
,07-07 20:26:03.014   525  8432 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-07 20:26:03.014   525  8433 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-07 20:26:03.014   525  8433 E FLACDecoder: qti_flac: Parser returned -1011
,07-07 20:26:03.014   525  8432 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-07 20:26:03.014  3497  4533 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
07-07 20:26:03.014   525  8432 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-07 20:26:03.014  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-07 20:26:03.014  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-07 20:26:03.034   525  8433 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-07 20:26:03.034   525  8433 E FLACDecoder: qti_flac: Parser returned -1011
,07-07 20:26:03.044  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
,07-07 20:26:03.044  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility(),
07-07 20:26:03.044  3497  3497 I PagedView: IndicatorPagedView.nCapability with type count = 1 and capability = 20
07-07 20:26:03.044  3497  4070 I BlinkFeedStateMonitor: checkState, feed:true, subsribed:true, loc:false
,07-07 20:26:03.054  8396  8449 D WeatherUtility: Weather sync is On
,07-07 20:26:03.064   525  8455 E MM_OSAL : FileSource::FileSource,
07-07 20:26:03.064   525  8455 E MM_OSAL : FileSource::FileSource m_bEveryThingOK 1,
07-07 20:26:03.064   525  8455 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/mmosal_logmask.cfg , Mode 0,
07-07 20:26:03.064   525  8455 E MM_OSAL : Open or read fail on /data/mmosal_logmask.cfg. Possible permission denied issue. Looking for /data/misc/media/mmosal_logmask.cfg
07-07 20:26:03.064   525  8455 E MM_OSAL : MM_File_Create failed .Efs Error No -1 , File Name /data/misc/media/mmosal_logmask.cfg , Mode 0,
07-07 20:26:03.064   525  8455 W QCOMExtractor: Sample Bit is, 16, set to kKeyBitsPerSample,
07-07 20:26:03.064   525  8455 W MediaExtractor: Sample Bit is, 16, support QCOMExtractor
07-07 20:26:03.074   525  8454 W Utils   : Qcom parser, bits per sample supported is 16 or 24
,07-07 20:26:03.074  8418  8418 I MultiDex: VM with version 2.1.0 has multidex support,
07-07 20:26:03.074  8418  8418 I MultiDex: install
07-07 20:26:03.074  8418  8418 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-07 20:26:03.084   525  8455 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END 
07-07 20:26:03.084   525  8455 E FLACDecoder: qti_flac: Parser returned -1011
,07-07 20:26:03.084   525  8454 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-07 20:26:03.084   525  8454 W Utils   : Qcom parser, bits per sample supported is 16 or 24
07-07 20:26:03.084  3497  3497 I PagedView: IndicatorPagedView.nCapability with type count = 2 and capability = 20
,07-07 20:26:03.114   525  8455 E MMParserExtractor: FileSource::FILE_SOURCE_DATA_END ,
07-07 20:26:03.114   525  8455 E FLACDecoder: qti_flac: Parser returned -1011
07-07 20:26:03.114  3497  3497 I Prism.AllAppsOptionsMa_: getAllAppsAbility() false
07-07 20:26:03.114  3497  3497 I Prism.AllAppsOptionsMa_: removeAllAppsAbility()
,07-07 20:26:03.114  3497  3497 D CoworkInterfaceListener: loadMethod() = true
,07-07 20:26:03.114  3497  3497 D CoworkInterfaceListener: IsSecure: 1
07-07 20:26:03.114  3497  3497 D CoworkInterfaceListener: IsDuggable: 0
07-07 20:26:03.114  3497  3497 D CoworkInterfaceListener: isTestable: false
,07-07 20:26:03.114  3497  3497 D CoworkInterfaceListener: Enable CIListener: false,
07-07 20:26:03.124  3497  3497 I ContextualWidget: onResume
07-07 20:26:03.124  3497  3497 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-07 20:26:03.124  3497  8392 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-07 20:26:03.124  3497  3497 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
,07-07 20:26:03.124  3497  3497 I ContextualWidget: postSyncRecommendedApps, isReady=true allowAutoSync=true syncMode=1 isEnableRecommend=true
07-07 20:26:03.124  3497  3726 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-07 20:26:03.134  1107  3424 V WindowManager: Adding window Window{2a27af00 u0 com.htc.launcher/com.htc.launcher.Launcher} at 2 of 11 (after Window{fe41342 u0 com.htc.launcher/com.htc.launcher.Launcher EXITING})
,07-07 20:26:03.134  8418  8466 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-07 20:26:03.134  8418  8466 W HTCLOG  : mask=0x18
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: Failed to open database '/data/data/com.htc.launcher/databases/BiLogClient'.
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:164)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:03.134  8418  8466 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: FATAL EXCEPTION: IntentService[BiLogUploadService]
07-07 20:26:03.134  8418  8466 E AndroidRuntime: Process: com.htc.launcher:biclient, PID: 8418
07-07 20:26:03.134  8418  8466 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at com.htc.BiLogClient.BiLogUploadService.onHandleIntent(BiLogUploadService.java:164)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:03.134  8418  8466 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-07 20:26:03.144  1107  4108 E ActivityManager: App crashed! Process: com.htc.launcher:biclient
07-07 20:26:03.144  1107  4108 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-07 20:26:03.144  1107  4108 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-07 20:26:03.144  1107  4108 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:03.144  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:03.144  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:03.144  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,07-07 20:26:03.144  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-07 20:26:03.144  1107  4108 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-07 20:26:03.144  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-07 20:26:03.144  1107  4108 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:03.144  1107  4108 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:03.144  1107  4108 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:03.144  1107  4108 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:03.144  1107  4108 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:03.144  1107  4108 W System.err: ,	... 14 more
07-07 20:26:03.144  3497  3497 I FeedGridScroller: updateBottomBoundary() - 0 -> 309
07-07 20:26:03.154  1107  4108 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-07 20:26:03.154  1107  4108 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:03.154  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:03.154  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:03.154  1107  4108 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,07-07 20:26:03.154  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
,07-07 20:26:03.154  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,07-07 20:26:03.154  1107  4108 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-07 20:26:03.154  1107  8469 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-07 20:26:03.154  1107  8469 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467915963166.dbox_tmp: open failed: EROFS (Read-only file system)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-07 20:26:03.154  1107  8469 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:03.154  1107  8469 E ErrorReport: ,	at libcore.io.Posix.open(Native Method)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:03.154  1107  8469 E ErrorReport: 	... 4 more
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-07 20:26:03.154  1107  4108 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-07 20:26:03.154  1107  4108 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-07 20:26:03.154  1107  4108 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:03.154  1107  4108 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:03.154  1107  4108 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:03.154  1107  4108 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:26:03.154  1107  4108 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:03.154  1107  4108 W System.err: 	... 14 more
07-07 20:26:03.164  3497  8468 E BitmapFactory: Unable to decode stream: java.io.FileNotFoundException: /data/data/com.htc.launcher/files/.htc_theme/wallpaper/allapps.jpg: open failed: ENOENT (No such file or directory)
,07-07 20:26:03.164  3497  4533 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915963174
,07-07 20:26:03.164  1107  3540 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-07 20:26:03.164  3372  3412 E SQLiteLog: (3850) statement aborts at 83: [UPDATE data SET lastRequest=? WHERE type = 1] disk I/O error
,07-07 20:26:03.164  3372  3412 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.sense.hsp/databases/weathersync.db, handle: 0x55b2c333f0
07-07 20:26:03.164  3372  3412 W WSP     : [Provider] caught exception: disk I/O error (code 3850)
07-07 20:26:03.164  3372  3412 W WSP     : android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
07-07 20:26:03.164  3372  3412 W WSP     : 	at com.htc.sense.hsp.weather.provider.data.Provider.update(Unknown Source)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:258)
07-07 20:26:03.164  3372  3412 W WSP     : 	at android.os.Binder.execTransact(Binder.java:454)
07-07 20:26:03.164  1107  3540 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:26:03.164  1107  3540 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:26:03.164  1107  3540 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-07 20:26:03.164  1107  3540 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-07 20:26:03.164  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-07 20:26:03.164  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-07 20:26:03.164  8396  8449 W WeatherUtility: adding request is failed, request: 
07-07 20:26:03.164  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-07 20:26:03.164  1107  3540 W System.err: 	,at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-07 20:26:03.164  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-07 20:26:03.164  1107  3540 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-07 20:26:03.164  1107  3540 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:26:03.164  1107  3540 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-07 20:26:03.164  1107  3540 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:26:03.174  1107  3540 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:26:03.174  1107  3540 W System.err: 	at libcore.io.Posix.open(Native Method)
07-07 20:26:03.174  1107  3540 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,07-07 20:26:03.174  1107  3540 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:26:03.174  1107  3540 W System.err: 	... 12 more
07-07 20:26:03.174  8396  8449 D WeatherUtility: Weather sync is On
,07-07 20:26:03.174  3497  3497 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-07 20:26:03.184  3497  3497 I ThreadedRenderer: Defer allocateBuffers to drawing time
07-07 20:26:03.184  8396  8449 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-07 20:26:03.194  3372  3372 V WSP     : [SyncService] no data connection, stop sync service
,07-07 20:26:03.194  3497  4107 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
07-07 20:26:03.194  3497  8470 E BitmapFactory: Unable to decode stream: java.io.FileNotFoundException: /data/data/com.htc.launcher/files/.htc_theme/wallpaper/allapps.jpg: open failed: ENOENT (No such file or directory)
,07-07 20:26:03.194  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
07-07 20:26:03.194  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420,
07-07 20:26:03.194  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
,07-07 20:26:03.204  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420,
07-07 20:26:03.204  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
07-07 20:26:03.204  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
07-07 20:26:03.204  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
07-07 20:26:03.204  3497  3497 I Prism.ProxyView: onSizeChanged() w: 296, h: 420
07-07 20:26:03.204  3497  3497 D HtcFooter: layerDrawableIndex = 0
,07-07 20:26:03.214  8396  8449 D HtcThemeUtils: context=android.view.ContextThemeWrapper@92e0029, category=0, byUser=false, userHandle=0
07-07 20:26:03.224  3497  4351 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915963231
,07-07 20:26:03.224  8396  8449 D HtcThemeUtils: [CC][checkIfNeedRecreate] mNeedRecreate=false, mCategoryRes=null, mCategoryTheme=null, sameDefRes=false
,07-07 20:26:03.244  8396  8449 W HtcThemeUtils: Can not get alternative color from specificInfo:C:0:0:0:0:0:0:0:0:0:0:0:0, with category(0),
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: java.lang.IllegalArgumentException: Unknown color
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at android.graphics.Color.parseColor(Color.java:216)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.a(HtcThemeUtils.java:594)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.d(HtcThemeUtils.java:513)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.c(HtcThemeUtils.java:459)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.b(HtcThemeUtils.java:449)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.h.a(HtcThemeUtils.java:424)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:1112)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:1076)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.g.a(HtcThemeUtils.java:365)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.lib1.cc.c.c.a(HtcCommonUtil.java:372)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetTheme.init(WidgetTheme.java:29)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetTheme.<init>(WidgetTheme.java:22)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.res.WeatherTransClock4x1Res.<init>(WeatherTransClock4x1Res.java:16)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.view.WeatherTransClock4x1View.<init>(WeatherTransClock4x1View.java:34)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetUtils.getAllViews(WidgetUtils.java:42)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetConfigure$ConfigureTask.doInBackground(WidgetConfigure.java:160)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at com.htc.widget.weatherclock.util.WidgetConfigure$ConfigureTask.doInBackground(WidgetConfigure.java:144)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
,07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-07 20:26:03.244  8396  8449 W HtcThemeUtils: 	at java.lang.Thread.run(Thread.java:818)
,07-07 20:26:03.244  8396  8449 W HTCLOG  : use specified tag [ResourceType], func [0].
07-07 20:26:03.244  8396  8449 W HTCLOG  : mask=0x18
07-07 20:26:03.244  8396  8449 E ResourceType: Style contains key with bad entry: 0x01010504
07-07 20:26:03.244  3497  4351 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-07 20:26:03.254  8396  8449 D HtcThemeUtils: context=android.view.ContextThemeWrapper@92e0029, target=/data/data/com.htc.launcher/files/.htc_theme/CResources.apk
07-07 20:26:03.254  8396  8449 W HTCLOG  : use specified tag [asset], func [0].
07-07 20:26:03.254  8396  8449 W HTCLOG  : mask=0x18
07-07 20:26:03.254  8396  8449 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
07-07 20:26:03.254  8396  8449 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
07-07 20:26:03.254  8396  8449 D HtcThemeUtils: init done
,07-07 20:26:03.254  8396  8449 D HtcThemeUtils: context=com.htc.widget.weatherclock.util.WidgetService@3558bfae, target=/data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk
07-07 20:26:03.254  8396  8449 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/WeatherClock.apk is neither a directory nor file (type=0).
07-07 20:26:03.254  8396  8449 D HtcThemeUtils: AssetMaanger addAssetPath WeatherClock fail!
,07-07 20:26:03.254  1107  1150 I ActivityManager: Displayed com.htc.launcher/.Launcher: +467ms,
,07-07 20:26:03.274  1107  3925 D PMS     : releaseWL(28628172): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-07 20:26:03.344  3497  4351 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915963353,
,07-07 20:26:03.354  3497  4305 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915963368
,07-07 20:26:03.364  3497  4305 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-07 20:26:03.444  3497  4305 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915963458
,07-07 20:26:03.454   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=4 alpha=255 mask=-1 flags=0x220000 id=8
07-07 20:26:03.454   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-07 20:26:03.454   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=3 alpha=255 mask=-1 flags=0x220000 id=8
07-07 20:26:03.454   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-07 20:26:03.454   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=2 alpha=255 mask=-1 flags=0x220000 id=8
07-07 20:26:03.454   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-07 20:26:03.454   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=1 alpha=255 mask=-1 flags=0x220000 id=8
07-07 20:26:03.454   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-07 20:26:03.454   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: validateAndSet failed, error 108: Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: Bad ov dump:  mdp_overlay z=0 alpha=255 mask=-1 flags=0x220000 id=8
07-07 20:26:03.454   499   499 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
07-07 20:26:03.454   499   499 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
07-07 20:26:03.454   499   499 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,07-07 20:26:03.454   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-07 20:26:03.454   499   499 E qdoverlay: MdpCtrl close error in unset
,07-07 20:26:03.464  3497  4306 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915963473
,07-07 20:26:03.474  3497  4306 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-07 20:26:03.544  3497  4306 I ConfigManager: [DM]ConfigManager: getAppConfig done. status:GET_CONFIG_CACHE_OK ts:1467915963558,
,07-07 20:26:03.564  3497  4524 I ConfigManager: [DM]ConfigManager: Try to get AppConfig from Server but no Network connected -> Ignore.
,07-07 20:26:03.584  3497  4387 I ConfigManager: [DM]ConfigManager: getAppConfig running... status:GET_CONFIG_CACHE_OK ts:1467915963595,
,07-07 20:26:03.594  3497  4387 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/DM_CACHE.xml.bak
,07-07 20:26:03.614   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown,
07-07 20:26:03.614   499   499 E qdoverlay: MdpCtrl close error in unset
07-07 20:26:03.614   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
,07-07 20:26:03.614   499   499 E qdoverlay: MdpCtrl close error in unset
07-07 20:26:03.614   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-07 20:26:03.614   499   499 E qdoverlay: MdpCtrl close error in unset
07-07 20:26:03.614   499   499 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Cannot send after transport endpoint shutdown
07-07 20:26:03.614   499   499 E qdoverlay: MdpCtrl close error in unset

```
