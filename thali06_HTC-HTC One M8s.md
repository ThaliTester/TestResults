#### Test 55634150e857e16_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  966): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4769 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=arm64-v8a
,--------- beginning of main
D/Process (  966): killProcessQuiet, pid=4192
I/ActivityManager(  966): Killing 4192:com.htc.updater/u0a84 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/libc    ( 4687): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4687): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4687): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    ( 4687): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4687): [NET] android_getaddrinfo_proxy+
D/libc    ( 4687): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/ActivityManager(  966): Recipient 4192
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4687): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4687): [NET] android_getaddrinfofornet+,hn 13(0x3231362e35382e),sn(),hints(known),family 0,flags 4
D/libc    ( 4687): [NET] android_getaddrinfofornet-, SUCCESS
V/AlarmManager(  966): sending alarm PendingIntent{2ba2eb18: PendingIntentRecord{248f9971 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=55003, Int=259200000
V/AlarmManager(  966): sending alarm PendingIntent{3091ffd7: PendingIntentRecord{2167a0c4 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452528623873, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{35215eba: PendingIntentRecord{7ee316b android broadcastIntent}}, i=com.android.server.WifiManager.action.START_SCAN, t=1, cnt=1, w=1452528616958, Int=20000
D/libc    ( 4687): [NET] android_getaddrinfofornet+,hn 24(0x7777772e676f6f),sn(),hints(known),family 0,flags 4
D/libc    ( 4687): [NET] android_getaddrinfofornet-, err=8
I/iu.UploadsManager( 4547): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
W/ActivityManager(  966): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/iu.UploadsManager( 4547): End new media; added: 0, uploading: 0, time: 44 ms
E/cutils-trace( 4794): Error opening trace file: Permission denied (13)
I/Gmail   ( 4769): getAccountsCursor
D/CustomizationManager( 4794): ====startRecUseTime====
D/htc.customization.log.level( 4794):  is 
W/CustomizationLogLevel( 4794): Level value is invalid, use default level 2
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4769): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.AttachmentService, state=2, flag=1, pid=4769, uid=10106, userID:0
W/ActivityManager(  966): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4769): Observing account changes for notifications
W/ActivityManager(  966): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  966): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4769, uid=10106, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4769, uid=10106, userID:0
E/Gmail   ( 4769): Error finding the version of the Email provider.....
E/Gmail   ( 4769): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4769): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4769): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4769): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4769): 	at android.os.Looper.loop(Looper.java:155)
E/Gmail   ( 4769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/WIFI_ICON( 1254): WifiActivity: 3
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 5
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/WifiTrafficPoller(  966):  packet count Tx=45 Rx=75
E/WifiTrafficPoller(  966): notifying of data activity 3
W/EmailMigration( 4769): We do not support migrating this version of the Email provider.
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=4769, uid=10106, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=4769, uid=10106, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=4769, uid=10106, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=4769, uid=10106, userID:0
I/Gmail   ( 4769): getAccountsCursor
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CustomizationManager( 4794):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4794): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4794): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4794): Parsing tag category name = system
I/CustomizationCIDLoader( 4794): Parsing tag category name = application
I/CustomizationCIDLoader( 4794): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4794): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4794): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4794): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4794): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4794): add string-array item, value = 42507
I/CustomizationCIDLoader( 4794): add string-array item, value = 21902
I/CustomizationCIDLoader( 4794): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4794): add string-array item, value = 23420
I/CustomizationCIDLoader( 4794): add string-array item, value = 22299
I/CustomizationCIDLoader( 4794): add string-array item, value = 24002
I/CustomizationCIDLoader( 4794): add string-array item, value = 23210
I/CustomizationCIDLoader( 4794): add string-array item, value = 23205
I/CustomizationCIDLoader( 4794): add string-array item, value = 23806
I/CustomizationCIDLoader( 4794): add string-array item, value = 23430
I/CustomizationCIDLoader( 4794): add string-array item, value = 23408
I/CustomizationCIDLoader( 4794): add string-array item, value = 27205
I/CustomizationCIDLoader( 4794): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4794): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4794):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4794):  All configurations done spent 0.104 (s)
E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:829678228] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=0.3, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:829678229] gl hn u24 rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1366): environment dirty rate=18 [11][2][0]
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=5.65 txretriesrate=0.00 rxrate=9.23 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  966):  isHighRSSI       ---> score=65
I/ActivityManager(  966): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4833 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1254): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  966): handleMessage: X
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/ActivityManager(  966): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorServiceAlternate, state=2, flag=1, pid=4769, uid=10106, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.android.email.service.EasAuthenticatorService, state=2, flag=1, pid=4769, uid=10106, userID:0
W/ActivityManager(  966): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityThread( 4769): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1034d0b that was originally bound here
E/ActivityThread( 4769): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1034d0b that was originally bound here
E/ActivityThread( 4769): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4769): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4769): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1906)
E/ActivityThread( 4769): 	at android.app.ContextImpl.bindService(ContextImpl.java:1889)
E/ActivityThread( 4769): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4769): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4769): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4769): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4769): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4769): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4769): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4769): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4769): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4769): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4769): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4769): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  966): Unbind failed: could not find connection for android.os.BinderProxy@29437c8c
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4794 on display 0
W/asset   (  966): Copying FileAsset 0x557061a200 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  966): acquireHCC(1f6dfd5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
D/PMS     (  966): acquireHCC(20e63ea): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
D/PMS     (  966): acquireWL(35d2a451): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 966 1000 null
I/AnimationUtil(  966): isHTCRecent(HelloWorld/Recent screens.)/5
I/ActivityManager(  966): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4859 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SQLiteLog( 4769): (283) recovered 1001 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/FeedHostManager( 1612): [onPause]
I/FeedProviderManager( 1612): onPause
I/FeedHostManager( 1612): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@2e86e9fa
I/SocialFeedProvider( 1612): +onPause
I/SocialFeedProvider( 1612): -onPause
W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/asset   ( 4859): Copying FileAsset 0xac148f98 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1612): [trimMemory] 20
E/ActivityThread( 1612): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1612): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1612): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3624)
E/ActivityThread( 1612): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3712)
E/ActivityThread( 1612): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread( 1612): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
E/ActivityThread( 1612): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1612): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 1612): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/ActivityThread( 1612): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1612): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1612): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread( 1612): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/StatusBarManagerService(  966): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
E/AndroidHttpClient( 4486): Leak found
E/AndroidHttpClient( 4486): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 4486): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 4486): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 4486): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 4486): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 4486): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 4486): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 4486): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 4486): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 4486): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 4486): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 4486): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 4486): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 4486): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 4486): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 4486): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 4486): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  966): Activity reported stop, but no longer stopping: ActivityRecord{26ec5909 u0 com.htc.launcher/.Launcher t7}
,I/WebViewFactory( 4859): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 4859): Time to load native libraries: 12 ms (timestamps 7465-7477)
I/LibraryLoader( 4859): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4859): Binding Chromium to main looper Looper (main, tid 1) {1267f022}
I/LibraryLoader( 4859): Expected native library version number "",actual native library version number ""
I/chromium( 4859): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4859): Initializing chromium process, singleProcess=true
W/art     ( 4859): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4859): ApplicationContext is null in ApplicationStatus
W/chromium( 4859): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4859): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4859): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4859): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4859): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4859): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4859): Local Branch: 
I/Adreno-EGL( 4859): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4859): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4859):                  d74aa161a12b9c6fc6332151
I/Gmail   ( 4769): notifyAccountChanged
I/Gmail   ( 4769): getAccountsCursor
I/Gmail   ( 4769): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/System.err(  966): java.lang.Throwable: stack dump
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f46d3e:true
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothAdapter( 4859): 473492590: getState(). Returning 12
I/Gmail   ( 4769): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  966): acquireWL(36039a33): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4769 10106 null
I/Gmail   ( 4769): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  966): acquireWL(36039a33): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4769 10106 null
I/Gmail   ( 4769): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
D/PMS     (  966): acquireWL(36039a33): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 4769 10106 null
I/Gmail   ( 4769): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4769): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: (has extras) }
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=4769, uid=10106, userID:0
I/ActivityManager(  966): Killing 4226:com.htc.android.worldclock/u0a90 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4226
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/Gmail   ( 4769): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/LocationManagerService(  966): getProviders()=[passive]
W/art     ( 4859): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4859): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  966): Recipient 4226
D/SystemWebViewEngine( 4859): CordovaWebView is running on device made by: HTC
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.SearchActivity, state=1, flag=1, pid=4833, uid=10085, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.googlequicksearchbox.VoiceSearchActivity, state=1, flag=1, pid=4833, uid=10085, userID:0
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.icingsync.ApplicationLaunchReceiver, state=1, flag=1, pid=4833, uid=10085, userID:0
I/ActivityManager(  966): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4912 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
W/art     ( 4859): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4859): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 4859): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/WifiService(  966): New client listening to asynchronous messages
E/WifiTrafficPoller(  966): ADD_CLIENT: 6
W/BroadcastQueue(  966): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/ActivityManager(  966): Start proc com.htc.club for broadcast com.htc.club/com.mcrm.autonotification.Autostart: pid=4947 uid=10181 gids={50181, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/FindExtension( 4859): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/Process (  966): killProcessQuiet, pid=4002
I/ActivityManager(  966): Killing 4002:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
D/WIFI_ICON( 1254): WifiActivity: 1
E/WifiTrafficPoller(  966):  packet count Tx=45 Rx=80
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  966): notifying of data activity 1
I/art     (  966): Explicit concurrent mark sweep GC freed 14398(734KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.540ms total 168.320ms
I/ActivityManager(  966): Recipient 4002
I/InputMethodManager( 4859): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2b1729ff, mServedView=org.apache.cordova.engine.SystemWebView{21e2c3cc VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@fdb615
I/InputMethodManagerService(  966): Disable input method client, pid=1612
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  966): Enable input method client, pid=4859
I/PhoneStatusBar( 1254): setImeWindowStatus(false,false)
D/Process (  966): killProcessQuiet, pid=4252
I/ActivityManager(  966): Killing 4252:com.google.android.configupdater/u0a98 (adj 15): empty #18
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/XT9_C   ( 1431): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1431): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1431): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1431): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 4859): Cannot call determinedVisibility() - never saw a connection for the pid: 4859
I/chromium( 4859): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  966): Recipient 4252
D/JsMessageQueue( 4859): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4859): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/PMS     (  966): releaseWL(35d2a451): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  966): Displayed com.example.hello/.MainActivity: +1s221ms
I/Gmail   ( 4769): master sync=false, engine sync=true
I/Gmail   ( 4769): getAccountsCursor
D/jxcore_app_log( 4859): JniHelper::setJavaVM(0xaafdb8f8), pthread_self() = -1405961120
D/JX-Cordova( 4859): jxcore cordova android initializing
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4769): master sync=false, engine sync=true
D/GCM     ( 1952): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1952): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4547): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4947): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4947): [NET] android_getaddrinfo_proxy+
D/libc    ( 4947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 48(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
I/ActivityManager(  966): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4983 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4547, uid=10024, userID:0
W/jxcore-log( 4859): Initializing JXcore engine
W/jxcore-log( 4859): JXcore engine is ready
W/jxcore-log( 4859): Starting JXcore engine
W/ResourcesManager( 4983): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4983): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TelephUtils( 1575): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 91
D/AccFlag ( 1575): sku_id=118
I/MultiDex( 4983): VM with version 2.1.0 has multidex support
I/MultiDex( 4983): install
I/MultiDex( 4983): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  966): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=5010 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/TelephUtils( 1575): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1575): sku_id=118
D/LocationInitializer( 4547): Restart initialization of location
I/GLSUser ( 1952): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1952): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1952): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1952): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ContactMessageStore( 1575): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1575): MSG_NOTIFY_CS_TO_SYNC <<
V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephUtils( 1575): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 91
D/AccFlag ( 1575): sku_id=118
V/JNIHelp ( 4983): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TelephUtils( 1575): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1575): sku_id=118
W/ActivityThread( 4983): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4983): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1503e2f5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4983): Installed default security provider GmsCore_OpenSSL
I/art     ( 1952): Explicit concurrent mark sweep GC freed 13636(797KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 827us total 43.906ms
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4947): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4947): [NET] android_getaddrinfofornet-, SUCCESS
W/jxcore-log( 4859): Platform android
W/jxcore-log( 4859): 
W/jxcore-log( 4859): Process ARCH arm
W/jxcore-log( 4859): 
D/WearableService( 4983): callingUid 10024, callindPid: 4983
D/DotMatrix( 1361): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1361): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1254): reapply : com.google.android.gms 2 40
W/Search.LoginHelper( 4833): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 4833): com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
W/Search.LoginHelper( 4833): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 4833): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4833): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 4833): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4833): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 4833): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 4833): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 4833): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 4833): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 4833): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/VelvetNetworkClient( 4833): Failed to get auth token
E/MDM     ( 1862): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ImageRamCache( 5010): create image Cache, size: 31457280.
I/ImageRamCache( 5010): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5010): create image Cache, size: 31457280.
I/jxcore-log( 4859): JXcore Cordova bridge is ready!
I/jxcore-log( 4859): 
W/jxcore-log( 4859): JXcore engine is started
I/FeedSettings( 5010): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 5010): GroupBudget 0.500000 0.380000
I/FeedSettings( 5010): GroupBudget 60 45 15
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 3,sn(),hints(known),family 0,flags 4
D/libc    ( 4947): [NET] android_getaddrinfofornet-, err=8
I/Prism.ExternalStringMa_( 5010): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 5010): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 5010): loadGridSize() with Alternative
D/CustomHighlightReceiver( 5010): [custom highlight] onReceive
D/CustomHighlightService( 5010): [custom highlight] onHandleIntent
E/jxcore-log( 4859): >> HTC-HTC One M8s
E/jxcore-log( 4859): 
I/jxcore-log( 4859): Total memory 1931808768
I/jxcore-log( 4859): 
I/jxcore-log( 4859): Free memory 84934656
I/jxcore-log( 4859): 
I/jxcore-log( 4859): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4859): 
I/jxcore-log( 4859): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4859): 
I/jxcore-log( 4859): userPath [ 'www', 'www' ]
I/jxcore-log( 4859): 
I/ActivityManager(  966): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5041 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/jxcore-log( 4859): Size 1080 1776
I/jxcore-log( 4859): 
D/NewsDB  ( 5010): set custom highlight []
I/jxcore-log( 4859): Screen Brightness 142
I/jxcore-log( 4859): 
E/jxcore-log( 4859): Dummy Error Log.
E/jxcore-log( 4859): 
I/art     (  407): Explicit concurrent mark sweep GC freed 8670(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 189us total 18.512ms
D/CustomHighlightService( 5010): [custom highlight] set tags 
I/art     (  407): Explicit concurrent mark sweep GC freed 3(96B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 200us total 17.074ms
D/Process (  966): killProcessQuiet, pid=4296
I/ActivityManager(  966): Killing 4296:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  407): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 197us total 21.291ms
W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  966): Recipient 4296
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  966):  packet count Tx=59 Rx=100
E/WifiTrafficPoller(  966): notifying of data activity 3
D/WIFI_ICON( 1254): WifiActivity: 3
I/ActivityManager(  966): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5063 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  966): Killing 4326:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4326
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  966): Recipient 4326
D/PMS     (  966): releaseHCC(1f6dfd5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  966): releaseHCC(20e63ea): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 4
D/libc    ( 4947): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    ( 4947): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4947): [NET] android_getaddrinfo_proxy+
D/libc    ( 4947): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 28(0x6874632d636c75),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/SMSBackup( 5063): Got a database change event
I/ActivityManager(  966): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5085 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  966): Killing 4397:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4397
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4947): [NET] android_getaddrinfo_proxy-, success
D/libc    ( 4947): [NET] android_getaddrinfofornet+,hn 13(0x3130342e38312e),sn(),hints(known),family 0,flags 4
D/libc    ( 4947): [NET] android_getaddrinfofornet-, SUCCESS
I/ActivityManager(  966): Recipient 4397
,I/jxcore-log( 4859): getBuffer is called!!!!,
I/jxcore-log( 4859): 
,I/MusicStore( 5085): Database version: 120,
,I/ActivityManager(  966): Waited long enough for: ServiceRecord{27627651 u0 com.htc.HTCSpeaker/.NGFService},
,D/VoldConnector(  966): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  966): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  966): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5085): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/PMS     (  966): releaseWL(36039a33): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null,
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL true Token 1,
,D/WifiDataStallTracker(  966): updateDataStallInfo: mDataStallTxRxSum={txSum=67 rxSum=63} preTxRxSum={txSum=21 rxSum=16}
D/WifiDataStallTracker(  966): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  966): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,W/ResourcesManager( 5085): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5085): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5085): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  966): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5114 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,V/AlarmManager(  966): sending alarm PendingIntent{38d546e5: PendingIntentRecord{288725ba com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59823, Int=0
,W/ActivityThread( 5085): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5085): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34ee55b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5085): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5085): GMSCore installation verified
,I/ConfigStore( 5085): Config Database version: 1
,I/ActivityManager(  966): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5137 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5085, uid=10159, userID:0,
,D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
,D/MediaRouterService(  966): Client com.google.android.music (pid 5085): Registered
,D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: },
,I/MediaRouter( 5085): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/MdScBoot( 5114): [417.1.] 30@-160957 -> 40
V/MusicLeanback( 5085): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/MdScBootUi( 5114): [417.1.2.] boot 118,
,I/NetworkMonitor( 5085): type=WIFI subType= reason=null isConnected=true,
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
,E/WifiTrafficPoller(  966):  packet count Tx=83 Rx=123
,D/MdScSimSt( 5114): [417.1.2.] qry 118: 0+1 running 0
,I/NetworkMonitor( 5085): type=WIFI subType= reason=null isConnected=true,
E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=9.2 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:829681248] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=5.7, 0.0, 0.0  rx=9.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:829681249] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SIGNAL_POLL'
,I/wpa_supplicant( 1366): environment dirty rate=7 [38][3][0],
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
,E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=21.83 txretriesrate=0.00 rxrate=30.11 userTriggerdPenalty0
,E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  966):  isHighRSSI       ---> score=65
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5085, uid=10159, userID:0
I/ActivityManager(  966): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=5168 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
E/WifiStateMachine(  966): handleMessage: X
D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -60, 3
,D/WIFI_ICON( 1254): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/GHttpClientFactory( 5085): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5085): Using platform SSLCertificateSocketFactory,
,W/ResourcesManager( 5168): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,D/Process (  966): killProcessQuiet, pid=4418,
I/ActivityManager(  966): Killing 4418:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  966): Recipient 4418,
,D/Process (  966): killProcessQuiet, pid=4442
I/ActivityManager(  966): Killing 4442:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 4442
,D/Process (  966): killProcessQuiet, pid=4465,
I/ActivityManager(  966): Killing 4465:com.android.smith/1000 (adj 15): empty #17,
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/CalendarProvider2( 5168): Created com.android.providers.calendar.CalendarAlarmManager@1db7cab3(com.htc.providers.calendar.HtcCalendarProvider@20760870)
,I/ActivityManager(  966): Recipient 4465,
,D/CalendarProvider2( 5168): wait start:true
,D/CalendarProvider2( 5168): wait end:false
,D/AutoSetting( 1671): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE,
,I/ActivityManager(  966): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5196 uid=10077 gids={50077, 9997, 3003} abi=arm64-v8a,
,D/AutoSetting( 1671): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1671): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1671): service - requestNLP() NetworkLocationProvider not enabled,
D/AutoSetting( 1671): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1671): service - handleMessage() setting current location null,
,D/Process (  966): killProcessQuiet, pid=4375,
I/ActivityManager(  966): Killing 4375:com.android.settings/1000 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PhoneMonitor( 5196): Register our PhoneStateListener
,I/HtcModeClient( 3314): handler message = 4011
,E/HtcModeClient( 3314): Check connection and retry 4 times.
,I/ActivityManager(  966): Recipient 4375
,D/MobileConnectivityChangeReceiver( 5196): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
D/MobileConnectivityChangeReceiver( 5196): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  966): Killing 3530:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=3530
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/PhoneMonitor( 5196): onServiceStateChanged state="3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1EriInd= -1EriMode= -1RadioPowerSv: false EmergOnly=false PhoneType: 1 VoiceRoaming: false DataRoaming: false IMSRegState: -1" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,D/PhoneMonitor( 5196): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_POWER_OFF(3) D:STATE_POWER_OFF(3) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  966): Recipient 3530
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  966):  packet count Tx=84 Rx=129
,D/PMS     (  966): acquireWL(18e980ed): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 4547 10024 WorkSource{10024 com.google.android.gms}
,I/art     (  966): Explicit concurrent mark sweep GC freed 12700(643KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 1.369ms total 179.199ms
,D/PMS     (  966): acquireWL(332a89b3): PARTIAL_WAKE_LOCK  Checkin Service 0x1 4547 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  966): releaseWL(18e980ed): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/CheckinService( 4547): Checking schedule, now: 1452528628485 next: 1452528330633
,I/CheckinService( 4547): active receiver: enabled
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=4547, uid=10024, userID:0
,I/CheckinService( 4547): Preparing to send checkin request
I/EventLogService( 4547): Accumulating logs since 1452528298160
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=4547, uid=10024, userID:0,
,I/iu.SyncManager( 4547): SYNC; picasa accounts,
,D/NetworkLogImpl( 4547): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4547): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,I/iu.UploadsManager( 4547): num queued entries: 0
,I/iu.UploadsManager( 4547): num updated entries: 0
,I/iu.SyncManager( 4547): NEXT; no task
,D/ChimeraCfgMgr( 4547): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 4547): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ActivityManager(  966): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5227 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/libc    ( 4651): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
D/libc    ( 4651): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4651): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    ( 4651): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4651): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4651): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,I/CheckinRequestBuilder( 4547): Checkin reason type: 8 attempt count: 1
,E/WifiTrafficPoller(  966): ADD_CLIENT: 7,
D/WifiService(  966): New client listening to asynchronous messages
I/ActivityManager(  966): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 4547): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1952): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1952): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1952): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1952): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 4651): [NET] android_getaddrinfo_proxy-, success
,W/Kids    ( 4547): [AccountUtils] Account not ready
,W/Kids    ( 4547): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 4547): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 4547): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 4547): 	at com.google.android.gms.auth.p.c(SourceFile:550),
W/Kids    ( 4547): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 4547): 	at com.google.android.gms.kids.account.k.d(SourceFile:103),
W/Kids    ( 4547): 	,at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 4547): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 4547): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 4547): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 4547): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 4547): 	at java.lang.Thread.run(Thread.java:818)
D/DotMatrix( 1361): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1361): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/Babel   ( 4651): connection state changed from UNKNOWN to CONNECTED
I/RemoteViews( 1254): reapply : com.google.android.gms 2 40
,I/CalendarProvider2( 5168): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
W/ContentResolver( 5168): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  966): Killing 4523:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4523
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 4523
,I/GLSUser ( 1952): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1952): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1952): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1952): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1952): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1361): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1361): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 4547): awaiting user notification for token,
,I/RemoteViews( 1254): reapply : com.google.android.gms 4 40
,I/ActivityManager(  966): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5256 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,D/VoldConnector(  966): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
,W/ContextImpl( 5227): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
,D/VoldConnector(  966): SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
,W/ContextImpl( 5227): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
I/GAV2    ( 4769): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 5256): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5256): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,D/VoldConnector(  966): SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/},
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
W/ContextImpl( 5227): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 5227): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5227):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5227):   adb logcat -s GAv4
,D/VoldConnector(  966): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
,W/ContextImpl( 5227): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
I/MultiDex( 5256): VM with version 2.1.0 has multidex support
I/MultiDex( 5256): install
I/MultiDex( 5256): VM has multidex support, MultiDex support library is disabled.
,I/GAv4-SVC( 4547): Google Analytics 7.8.99 is starting up.,
,W/GAv4    ( 5227): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 5256): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/GAv4    ( 5227): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7
,E/WifiTrafficPoller(  966):  packet count Tx=89 Rx=135
,W/GAv4    ( 5227): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 5256): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5256): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1503e2f5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5256): Installed default security provider GmsCore_OpenSSL
,W/global  ( 5227): [apache-http] Connection GC has been deprecated!,
,W/global  ( 5227): [apache-http] Connection GC has been deprecated!
,I/WVCdm   (  401): CdmEngine::OpenSession
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  401): Service_Initialize: starts!
,D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000,
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 6,
D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48bb000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48bb000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  541): got the req here! ret=0,
D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds,
,D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1452528629
D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1452528629; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! ,
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf49e6928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1,
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab6ed660, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
,I/WebViewFactory( 5227): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab6c4a90, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab6ac5f8, idLength=0xffcc2218
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
,D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xffcc222e, maximum = 0xffcc222f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0,
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffcc229c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=3156377609
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab6e1058
D/DrmWidevineDash(  401): message_length=1611, signature=0xab6c0f30, signature_length=0xffcc21fc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,I/LibraryLoader( 5227): Time to load native libraries: 25 ms (timestamps 2545-2570),
,I/LibraryLoader( 5227): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5227): Binding Chromium to main looper Looper (main, tid 1) {3e0f40c4}
I/LibraryLoader( 5227): Expected native library version number "",actual native library version number ""
,I/chromium( 5227): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5227): Initializing chromium process, singleProcess=true
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  401): CdmEngine::CloseSession
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
W/art     ( 5227): Attempt to remove local handle scope entry from IRT, ignoring
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 6
D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,E/SysUtils( 5227): ApplicationContext is null in ApplicationStatus
,W/chromium( 5227): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5227): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5227): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5227): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5227): Local Branch: 
I/Adreno-EGL( 5227): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5227): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5227):                  d74aa161a12b9c6fc6332151
,W/AudioManagerAndroid( 5227): Requires BLUETOOTH permission
,I/SocialFeedProvider( 1612): +disConnect socialManager
,I/SocialFeedProvider( 1612): disconnect socialManager
,I/SocialFeedProvider( 1612): -disConnect socialManager
,I/NSApplication( 5227): Starting up...
,I/ActivityManager(  966): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5322 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  966): killProcessQuiet, pid=4486
,I/ActivityManager(  966): Killing 4486:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 4486
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 7
D/WIFI_ICON( 1254): WifiActivity: 1
E/WifiTrafficPoller(  966):  packet count Tx=89 Rx=137
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiTrafficPoller(  966): notifying of data activity 1
,E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: ConnectedState
,E/WifiStateMachine(  966):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=21.8, 0.0, 0.0  rx=30.1 bcn=0 [on:0 tx:0 rx:0 period:2989] from screen [on:0 period:829684265] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
E/WifiStateMachine(  966): processMsg: L2ConnectedState
E/WifiStateMachine(  966):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-60 f=2412 sc=60 link=72 tx=21.8, 0.0, 0.0  rx=30.1 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:829684266] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966):  get link layer stats 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SIGNAL_POLL'
V/AlarmManager(  966): sending alarm PendingIntent{f26dfb: PendingIntentRecord{fdd7e18 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452528630107, Int=0
I/wpa_supplicant( 1366): environment dirty rate=0 [6][0][0]
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  966): fetchRssiLinkSpeedAndFrequencyNative rssi=-60 linkspeed=72
E/WifiConfigStore(  966): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-60 "NG700"WPA_PSK
E/WifiStateMachine(  966): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=13.91 txretriesrate=0.00 rxrate=20.56 userTriggerdPenalty0
E/WifiStateMachine(  966):  good link -> stuck count =0
E/WifiStateMachine(  966):  badRSSI count0 lowRSSI count0 --> score 60
E/WifiStateMachine(  966):  isHighRSSI       ---> score=65
D/WifiWatchdogStateMachine(  966): RSSI current: 3 new: -60, 3
D/WIFI_ICON( 1254): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  966): handleMessage: X
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/SocialManager[SocialBiLogHelper]( 5010): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5010): last commit ulog time 1452491432917
I/SocialManager[SocialBiLogHelper]( 5010): skip commit this time
,E/cutils-trace( 5345): Error opening trace file: Permission denied (13),
I/dex2oat ( 5345): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5345): dex2oat: override thread count:4
,I/dex2oat ( 5345): dex2oat took 101.815ms (threads: 4),
,I/Adreno-EGL( 5256): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5256): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5256): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5256): Local Branch: 
I/Adreno-EGL( 5256): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5256): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5256):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  966): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5353 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
D/Process (  966): killProcessQuiet, pid=4036,
I/ActivityManager(  966): Killing 4036:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/Adreno-EGL( 5256): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5256): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5256): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5256): Local Branch: 
I/Adreno-EGL( 5256): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5256): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5256):                  d74aa161a12b9c6fc6332151
,I/ActivityManager(  966): Recipient 4036
,I/WVCdm   (  401): CdmEngine::OpenSession,
I/WVCdm   (  401): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  401): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15,
D/DrmWidevineDash(  401): Service_Initialize: starts!
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
E/QSEECOMAPI: (  401): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  401): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  401): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  401): App is not loaded in QSEE
,D/QSEECOMAPI: (  401): Loaded image: APP id = 7,
,D/DrmWidevineDash(  401): Service_Initialize: ends! returns 0
,D/QSAPPSVER(  401): qsapps_get_capabilities: Capability from secure side: 0x0,
D/QSAPPSVER(  401): qsapps_get_capabilities: returns 0,
D/DrmWidevineDash(  401): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ba000
E/DrmWidevineDash(  401): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf48ba000
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/DrmLibTime(  541): got the req here! ret=0
D/DrmLibTime(  541): command id, time_cmd_id = 770
D/DrmLibTime(  541): time_getutcsec starts!
D/DrmLibTime(  541): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  541): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  541): QSEE Time Listener: time_get_modem_time
D/DrmLibTime(  541): QSEE Time Listener: Checking if ATS_MODEM is set or not.
E/QC-time-services(  541): Receive Passed == base = 13, unit = 1, operation = 2, result = 0
D/DrmLibTime(  541): QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
D/DrmLibTime(  541): QSEE Time Listener: Retrieved Android system time: 1452528630
,D/DrmLibTime(  541): time_getutcsec returns 0, sec = 1452528630; nsec = 0
D/DrmLibTime(  541): time_getutcsec finished! 
D/DrmLibTime(  541): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  541): before calling ioctl to read the next time_cmd
E/QC-time-services(  476): Daemon: Time-services: Waiting to acceptconnection
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,W/ResourcesManager( 5353): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  401): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: starts! SID=0xf4ae6928
D/DrmWidevineDash(  401): OEMCrypto_OpenSession Session ID = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  401): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: starts! randomData=0xab6dbe28, dataLength=8
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab6bad18, wrapped_rsa_key_length=1280
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  401): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  401): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  401): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  401): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: starts! deviceID=0xab6ac638, idLength=0xffcc2218
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
D/DrmWidevineDash(  401): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: wv_app_version = 24
D/DrmWidevineDash(  401): OEMCrypto_SupportsUsageTable: ends! returns 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: starts!, current = 0xffcc222e, maximum = 0xffcc222f
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GetHDCPCapability: ends! returns 0,
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): hlos api version =  9
D/DrmWidevineDash(  401): tz api version =  9
D/DrmWidevineDash(  401): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xffcc229c
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,D/DrmWidevineDash(  401): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  401): PrepareKeyRequest: nonce=1813298799
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab6e1058
D/DrmWidevineDash(  401): message_length=1646, signature=0xab6d2e40, signature_length=0xffcc21fc
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,D/Process (  966): killProcessQuiet, pid=4687
I/ActivityManager(  966): Killing 4687:com.google.android.youtube/u0a176 (adj 15): empty #17
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4547, uid=10024, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4547, uid=10024, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4547, uid=10024, userID:0
,I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4547, uid=10024, userID:0
,D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  401): CdmEngine::CloseSession,
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: starts! SID=1
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  401): L3 Terminate.
D/DrmWidevineDash(  401): OEMCrypto_Terminate: starts!
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
D/QSEECOMAPI: (  401): SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
D/DrmWidevineDash(  401): Service_Uninitialize: starts!
D/QSEECOMAPI: (  401): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  401): QSEECom_shutdown_app, app_id = 7
,D/DrmWidevineDash(  401): Service_Uninitialize: ends! returns 0x0,
D/DrmWidevineDash(  401): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  966): Recipient 4687
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,D/BluetoothManagerService(  966): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3106550a mBinding = false
W/Settings:Agent(  966): MONITOR_LOG
W/Settings:Agent(  966): name: bluetooth_on
W/Settings:Agent(  966): value: 0
W/Settings:Agent(  966): >> traceCallingStack()
W/Settings:Agent(  966): Process.myPid(): 966
W/Settings:Agent(  966): Process.myTid(): 1648
W/Settings:Agent(  966): Process.myUid(): 1000
W/Settings:Agent(  966): 
W/Settings:Agent(  966): 
W/System.err(  966): java.lang.Throwable: stack dump
,W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  966): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  966): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  966): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  966): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  966): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  966): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  966): 
W/Settings:Agent(  966): << traceCallingStack(): 7(ms)
,D/AccTypeManager( 1772): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,W/ResourcesManager( 1575): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/BluetoothManagerService(  966): Message: MESSAGE_DISABLE
W/SystemReader(  966): Cannot find grip_rejection_width, use default value instead
D/BluetoothManagerService(  966): Sending off request.
D/BluetoothAdapterState( 3158): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3158): Setting state to 13
I/BluetoothAdapterState( 3158): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService(  966): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 3158): onBluetoothDisable(),
I/bt-btif ( 3158): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 3158): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 3158): BTM_SetDiscoverability
I/bt-btm  ( 3158): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/PMS     (  966): acquireWL(360062ad): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3158 1002 null
D/bt-btm  ( 3158): disc_mode 0000
I/bt-btm  ( 3158): evt_type=0x0 p-cb->evt_type=0x0 
,I/bt-btm  ( 3158): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  966): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 3158): Scan Mode:21
D/WifiService(  966): New client listening to asynchronous messages
,D/AccTypeManager( 1772): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WifiManager( 4859): setWifiEnabled: Base Package Name=com.example.hello, uid=10374
D/WifiService(  966): setWifiEnabled: false pid=4859, uid=10374
I/IntentController( 1254): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
I/bt-btm  ( 3158): BTM_SetConnectability
I/WifiService(  966): isSprintWifiRestricted(): false
I/bt-btm  ( 3158): btm_ble_set_connectability mode=0x0 combined_mode=0x1
I/WifiService(  966): isMdmWifiRestricted(): false
D/bt-btm  ( 3158): disc_mode 0000
I/bt-btm  ( 3158): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
W/Settings:Agent(  966): MONITOR_LOG
W/Settings:Agent(  966): name: wifi_on
W/Settings:Agent(  966): value: 0
W/Settings:Agent(  966): >> traceCallingStack()
W/Settings:Agent(  966): Process.myPid(): 966
W/Settings:Agent(  966): Process.myTid(): 1820
W/Settings:Agent(  966): Process.myUid(): 1000
W/Settings:Agent(  966): 
W/Settings:Agent(  966): 
,D/NGFService( 3822): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,W/ResourcesManager(  966): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/BluetoothAdapterState( 3158): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btif ( 3158): BTA_JvDeleteRecord
I/bt-btif ( 3158): BTA_JvRfcommStopServer
D/bt-btm  ( 3158): BTM_FreeSCN 
E/bt-btif ( 3158): cmd socket is not created
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:14
W/Prism.AllAppsManager( 1612): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
E/BtOppRfcommListener( 3158): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/Prism.ItemManager( 1612): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1612): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,V/BluetoothSapService( 3158): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/System.err(  966): java.lang.Throwable: stack dump
,I/bt-btm  ( 3158): BTM_SEC_CLR[13]: id 55
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:13
I/bt-btm  ( 3158): BTM_SEC_CLR[14]: id 56
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:12
I/bt-btm  ( 3158): BTM_SEC_CLR[15]: id 57
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:11
I/bt-btm  ( 3158): BTM_SEC_CLR[16]: id 58
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:10
I/bt-btm  ( 3158): BTM_SEC_CLR[17]: id 59
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 3158): BTM_SEC_CLR[18]: id 60
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 3158): Write Extended Inquiry Response to controller
I/bt-btm  ( 3158): Write Extended Inquiry Response to controller
I/bt-btm  ( 3158): Write Extended Inquiry Response to controller
I/bt-btm  ( 3158): Write Extended Inquiry Response to controller
,I/Prism.ItemManager( 5010): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5010): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Launcher( 1612): Deferring update until onResume
D/Launcher( 1612): waitUntilResume // bindAppsUpdated
,W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x000f
I/bt-btm  ( 3158): BTM_SetDiscoverability
I/bt-btm  ( 3158): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 3158): disc_mode 0000
I/bt-btm  ( 3158): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 3158): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 3158): BTM_SetConnectability
I/bt-btm  ( 3158): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3158): disc_mode 0000
D/bt-btm  ( 3158): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 3158): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 3158): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 3158): BTM_IsInquiryActive
I/bt-btm  ( 3158): BTM_CancelRemoteDeviceName()
I/bt-btm  ( 3158): btm_ble_clear_white_list
W/bt-btif ( 3158): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/bt-btif ( 3158): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 3158): AG evt (hdl 0x0002): State 0, Event 0x0501
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btm  ( 3158): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 3158): BTM_FreeSCN 
I/bt-btm  ( 3158): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 3158): AVRC_Close handle:0
D/bt-btif ( 3158): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 3158): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/AccTypeManager( 1772): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,V/BluetoothPbapReceiver( 3158): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3158): ***********state = 13
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:4
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt-sdp  ( 3158): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3158): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0013
I/bt-att  ( 3158): GATT_Deregister gatt_if=3
I/bt-att  ( 3158): GATT_Listen gatt_if=3
I/bt-btm  ( 3158): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3158): BTM_ReadConnectability
,I/bt-btm  ( 3158): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3158): disc_mode 0000
I/bt-att  ( 3158): GATT_Deregister gatt_if=4
I/bt-att  ( 3158): GATT_Listen gatt_if=4
I/bt-btm  ( 3158): BTM_BleUpdateAdvFilterPolicy
I/bt-btm  ( 3158): BTM_ReadConnectability
I/bt-btm  ( 3158): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 3158): disc_mode 0000
E/bt-btif ( 3158): bta_gattc_deregister Deregister Failedm unknown client cif
I/BtOppRfcommListener( 3158): stopping Accept Thread
I/BtOppRfcommListener( 3158): BluetoothSocket listen thread finished
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  966): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  966): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  966): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  966): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  966): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  966): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
E/ExternalAccountType( 1772): Unsupported attribute readOnly
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  966): 
W/Settings:Agent(  966): << traceCallingStack(): 47(ms)
,I/QuickSettingBluetooth( 1254): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF,
D/PhoneApp( 1575): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  966): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5383 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
V/BluetoothPbapService( 3158): Pbap Service closeService in
V/BluetoothPbapService( 3158): successfully stopped pbap service
V/BluetoothPbapService( 3158): Pbap Service closeService out
V/BluetoothPbapService( 3158): Pbap Service onDestroy
,V/BluetoothPbapService( 3158): Pbap Service closeService in
,V/BluetoothPbapService( 3158): Pbap Service closeService out
I/bt-btm  ( 3158): btm_ble_clear_white_list_complete
,I/CheckinRequestBuilder( 4547): Classify the device as Phone.
,D/WifiController(  966): handleMessage: E msg.what=155656
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): transitionTo: destState=ApStaDisabledState
D/WifiController(  966): handleMessage: new destination call exit/enter
D/WifiController(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  966): invokeExitMethods: DeviceActiveState
D/WifiController(  966): invokeExitMethods: StaEnabledState
D/WifiController(  966): moveTempStackToStateStack: i=0,j=1
D/WifiController(  966): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=ApStaDisabledState
D/WifiController(  966): invokeEnterMethods: ApStaDisabledState
D/WifiController(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131084
E/WifiStateMachine(  966): processMsg: ConnectedState
E/WifiStateMachine(  966):  ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  966): processMsg: L2ConnectedState
I/jxcore-log( 4859): ****TEST TOOK:  5213  ms ****
I/jxcore-log( 4859): 
E/WifiStateMachine(  966):  L2ConnectedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
I/jxcore-log( 4859): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4859): 
E/WifiStateMachine(  966):  ConnectModeState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState !CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine(  966): transitionTo: destState=WaitForP2pDisableState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
E/WifiStateMachine(  966): invokeExitMethods: ConnectedState
E/WifiStateMachine(  966): WifiStateMachine: Leaving Connected state
D/WifiPerfLock(  966): release()
E/WifiStateMachine(  966): PerfLock released for exiting ConnectedState
E/WifiStateMachine(  966): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
E/WifiStateMachine(  966): invokeExitMethods: L2ConnectedState
,E/WifiStateMachine(  966): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - exit - invokeExitMethods
E/WifiStateMachine(  966): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  966): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  966): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER POWERMODE 0'
I/wpa_supplicant( 1366): Power_Mode_Type mode = 0
D/WifiP2pService(  966): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1366): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/WifiP2pService(  966): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1366): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  966): setDhcpActive: false
V/NativeCrypto( 1952): Read error: ssl=0x5570349c90: I/O error during system call, Connection timed out
E/WifiStateMachine(  966): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService(  966): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  966): setDetailed state send new extra info<unknown ssid>
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  966): NetworkAgent != null
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NetworkPolicy(  966): mWifiStateReceiver: meteredHint=false,EPS mode=false
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED connected
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 13(0x3139322e313638),sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiStateMachine(  966): autoRoamSetBSSID any key="NG700"WPA_PSK
E/WifiConfigStore(  966): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/WifiHW  (  966): QCOM Debug skip set_network part for security concern!
D/wpa_supplicant( 1366): wlan0: Control interface command 'SET_NETWORK [REMOVED]'
D/wpa_supplicant( 1366): CTRL_IFACE: SET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 1366): CTRL_IFACE: value - hexdump(len=3): [REMOVED]
D/PMS     (  966): acquireWL(2dc712de): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1952 10024 WorkSource{10024 com.google.android.gms}
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SAVE_CONFIG"
D/wpa_supplicant( 1366): wlan0: Control interface command 'SAVE_CONFIG'
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/wpa_supplicant( 1366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 1366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1366): CTRL_IFACE: SAVE_CONFIG - Configuration updated
E/WifiStateMachine(  966): invokeExitMethods: ConnectModeState
E/WifiStateMachine(  966): invokeExitMethods: DriverStartedState
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
D/WifiP2pService(  966): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 1952): SSL shutdown failed: ssl=0x5570349c90: I/O error during system call, Broken pipe
D/WifiP2pService(  966): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1366): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  966): Unexpected BatchedScanResults :null
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 1366): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  966): noteBatchedScanstop()
E/WifiStateMachine(  966): [1,452,528,631,282 ms] noteScanEnd no scan source
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
E/WifiStateMachine(  966): invokeEnterMethods: WaitForP2pDisableState
E/WifiStateMachine(  966): handleMessage: X
D/WifiNetworkAgent(  966): NetworkAgent: NetworkAgent channel lost
,D/libc    (  966): [NET] android_getaddrinfofornet+,hn 6,sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 25(0x666538303a3a39),sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiMonitor(  966): stopMonitoring(p2p0) = com.android.server.wifi.p2p.WifiP2pServiceImpl$P2pStateMachine@1f0d32a3
W/PackageManager(  966): Unable to load service info ResolveInfo{b991424 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  966): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  966): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  966): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/ConnectivityService(  966): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
E/WifiStateMachine(  966): handleMessage: E msg.what=131205
D/WifiP2pService(  966): P2pDisablingState
E/WifiStateMachine(  966): processMsg: WaitForP2pDisableState
D/WifiP2pService(  966): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): p2p socket connection lost
D/WifiP2pService(  966): P2pDisabledState
D/WifiDisplayController(  966): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
E/WifiStateMachine(  966):  WaitForP2pDisableState !CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
E/WifiStateMachine(  966): transitionTo: destState=SupplicantStoppingState
D/WifiP2pService(  966): P2pDisabledState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
D/WifiP2pService(  966): DefaultState{ when=0 what=131333 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  966): invokeExitMethods: WaitForP2pDisableState
E/WifiStateMachine(  966): invokeExitMethods: SupplicantStartedState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
E/WifiStateMachine(  966): invokeEnterMethods: SupplicantStoppingState
E/WifiStateMachine(  966): Call handleNetworkDisconnect() in SupplicantStoppingState
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5383): -onCreate()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): ValidatedState{ when=-4ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): DefaultState{ when=-4ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Validated
E/WifiStateMachine(  966): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$13400 - enter - invokeEnterMethods
E/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/PMS     (  966): releaseWL(2dc712de): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER POWERMODE 0'
D/WifiP2pService(  966): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1366): Power_Mode_Type mode = 0
D/WifiP2pService(  966): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1366): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ConnectivityService(  966): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/wpa_supplicant( 1366): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 1366): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 8192
D/WifiDataStallTracker(  966): setDhcpActive: false
E/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  966): stopping supplicant
W/WifiHW  (  966): QCOM Debug wifi_send_command "TERMINATE"
D/wpa_supplicant( 1366): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 1366): wlan0: Removing interface wlan0
E/WifiStateMachine(  966): setWifiState: disabling
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 1366): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 1366): TDLS: Tear down peers
D/wpa_supplicant( 1366): wpa_driver_nl80211_disconnect(reason_code=3)
E/WifiStateMachine(  966): handleMessage: X
D/WIFI_ICON( 1254): updateWifiState: WIFI_STATE_CHANGED disabled
I/IntentController( 1254): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1254): receive.wifiConnect:true wifiAPname:<unknown ssid> elapse:1
I/QuickSettingWifi( 1254): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1254): receive.wifiConnect:false wifiAPname:null elapse:1
,V/Settings:HtcSettingsApplication( 5383): [5383/5383] onCreate()
I/art     ( 4547): Explicit concurrent mark sweep GC freed 12813(1149KB) AllocSpace objects, 25(500KB) LOS objects, 30% free, 4MB/6MB, paused 675us total 58.558ms
D/wpa_supplicant( 1366): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 1366): wlan0: Deauthentication notification
D/wpa_supplicant( 1366): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 1366): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 1366): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1366): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1366): enter disconnect check
I/wpa_supplicant( 1366): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412]
D/wpa_supplicant( 1366): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 1366): wlan0: Ignore connection failure indication since interface has been put into disconnected state
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/WifiMonitor(  966): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  966): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiMonitor(  966): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
E/WifiStateMachine(  966): handleMessage: E msg.what=147460
E/WifiStateMachine(  966): processMsg: SupplicantStoppingState
D/Tethering(  966): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  966): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  966): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  966):  SupplicantStoppingState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64197
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  966):  DefaultState !NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=64198
E/WifiStateMachine(  966): handleMessage: X
D/wpa_supplicant( 1366): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1366): wlan0: Disconnect event - remove keys
D/PMS     (  966): acquireWL(1b26e2dd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x558efa6f88 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1366):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1366): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1366): nl80211: Set wlan0 operstate 1->0 (DORMANT)
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  966): sendTetherStateChangedBroadcast 0, 0, 0
D/wpa_supplicant( 1366): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1366): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1366): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1366): nl80211: Skip set_sup,p_port(unauthorized) while not associated
D/wpa_supplicant( 1366): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1366): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1366): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1366): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1366): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1366): EAPOL: External notification - portEnabled=0
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 1366): EAPOL: External notification - portValid=0
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  966): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/WifiStateMachine(  966): handleMessage: E msg.what=147462
E/WifiStateMachine(  966): processMsg: SupplicantStoppingState
E/WifiStateMachine(  966):  SupplicantStoppingState !SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=64201  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  966): processMsg: DefaultState
I/QuickSettingWifi( 1254): receive.wifiConnect:false wifiAPname:null elapse:1
I/QuickSettingWifi( 1254): receive.wifiState:WIFI_STATE_DISABLING setEnable:false
,E/WifiStateMachine(  966):  DefaultState !SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=64202  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine(  966): handleMessage: X
,D/PMS     (  966): acquireWL(35b3cfd9): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5383 1000 null
,W/ContextImpl( 5383): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/bt-btm  ( 3158): BTM_BleGetVendorCapabilities
W/bt-btif ( 3158): ag scb idx 1 not allocated
W/bt-btif ( 3158): ag scb idx 2 not allocated
E/bt-btif ( 3158): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3158): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3158): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3158): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3158): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3158): L2CAP - PSM: 0x0017 not found for deregistration
E/bt-btif ( 3158): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt_userial_mct( 3158): pthread_join() FAILED result:3
,I/BackupManagerService(  966): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  966): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5418 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/PMS     (  966): releaseWL(35b3cfd9): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  966): acquireWL(363be526): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5383 1000 null
,D/WISPrService( 5383): >>>>>WISPrService start isConnected = true<<<<<
,D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  966): java.lang.Throwable: stack dump
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@301b6d7b:true
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
,D/WifiService(  966): New client listening to asynchronous messages
,V/GmsNetworkLocationProvi( 1862): DISABLE,
I/art     (  407): Explicit concurrent mark sweep GC freed 8656(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 188us total 26.971ms
,D/BluetoothAdapter( 5383): 34300282: getState(). Returning 13
,D/ConnectivityManager.CallbackHandler( 1254): CM callback handler got msg 524292
D/ConnectivityService(  966): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  966):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  966):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  966): Disconnected - quitting
D/ConnectivityService(  966): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
I/SecurityController( 1254): onLost 100
D/Nat464Xlat(  966): requiresClat: netType=1, connected=false, mIsClatEnabled=true, hasIPv4Address=true
E/WifiTrafficPoller(  966): ADD_CLIENT: 8
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL true Token 11 num clients 8
,E/WifiTrafficPoller(  966):  packet count Tx=95 Rx=142
E/WifiTrafficPoller(  966): notifying of data activity 3
D/WIFI_ICON( 1254): WifiActivity: 3
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 150us total 16.936ms
D/WifiDataStallTracker(  966): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  966): stopDataStallAlarm 
D/WifiScanningService(  966): SCAN_AVAILABLE : 1
D/RttService(  966): SCAN_AVAILABLE : 1
,V/AudioService(  966): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  966):     Client/Owner: Client
V/AudioService(  966):     GroupId: 
V/AudioService(  966):     Passphrase: 
,V/AudioService(  966):     SessionId: 0
V/AudioService(  966):     IP Address: }
D/WifiScanningService(  966): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbDeviceManager(  966): [USBNET] bCheckSuppFunc: cdc_network
D/HtcEffectManagerBase(  966): onEventChanged id=5 status=false
D/HtcEffectManager(  966): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  966): convertEffect before=902
D/HtcEffectManager(  966): convertEffect after=902
D/RttService(  966): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetService(  966): BroadcastReceiver::onReceive+
E/WifiStateMachine(  966): handleMessage: E msg.what=131101
E/WifiStateMachine(  966): processMsg: SupplicantStoppingState
D/UsbnetService(  966): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
E/WifiStateMachine(  966):  SupplicantStoppingState !CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  966): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  966): handleMessage: X
I/ActivityManager(  966): Killing 4769:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4769
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/WIFI    (  966): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  966): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  966):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  966): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isSkipMobile=false
D/WIFI    (  966): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] released
D/NetworkManagementService(  966): Removing idletimer
E/WifiStateMachine(  966): enter WifiNetworkFactory startNetwork. mIPTStart:false
D/PMS     (  966): acquireWL(a5eab6b): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 966 1000 null
D/usbnet  (  966): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  966): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=false
D/usbnet  (  966):   my score=70, my filter=[ Transports:  Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  966): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/usbnet  (  966): evalRequest: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] requested
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 141us total 21.009ms
,I/ActivityManager(  966): Recipient 4769
,D/PMS     (  966): acquireWL(24bc6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(24bc6c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/WifiTrafficPoller(  966): ADD_CLIENT: 9,
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  966):  packet count Tx=95 Rx=142
E/WifiTrafficPoller(  966): notifying of data activity 0
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 12
E/WifiDataStallTracker(  966): ENABLE_DATA_MONITOR_POLL false Token 1
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 13
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 14
,E/WifiStateMachine(  966): handleMessage: E msg.what=131131
E/WifiStateMachine(  966): processMsg: SupplicantStoppingState
E/WifiStateMachine(  966):  SupplicantStoppingState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_GET_CONFIGURED_NETWORKS uid=1000 1000 0 num=1
D/BluetoothInputDevice( 5383): BluetoothInputDevice()
E/WifiStateMachine(  966): handleMessage: X
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 9
,D/libc    ( 4547): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4547): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4547): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 4547): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4547): [NET] android_getaddrinfo_proxy+
D/libc    ( 4547): [NET] android_getaddrinfo_proxy get netid:0
D/HtcBtWidget_BTWidgetProvider( 5418): onBTStateChanged() for widget: 
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/HtcBtWidget_BTWidgetProvider( 5418): updateWidget(context) for widget: 
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4547): [NET] android_getaddrinfo_proxy-, NODATA
,E/CheckinTask( 4547): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/wpa_supplicant( 1366): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush
D/WifiMonitor(  966): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 4 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=30 dispatchEvent: BLACKLIST CLEAR 
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 3 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush
D/wpa_supplicant( 1366): wlan0: BSS: Remove id 2 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush
D/wpa_supplicant( 1366): wlan0: Cancelling delayed sched scan
D/wpa_supplicant( 1366): wlan0: Cancelling scan request
D/wpa_supplicant( 1366): wlan0: Cancelling authentication timeout
E/wpa_supplicant( 1366): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 a0:c5:62:7a:49:97
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 38:f8:89:11:e9:11
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 06:7c:34:12:7f:81
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 64:7c:34:12:7f:81
D/WifiMonitor(  966): Event [IFNAME=wlan0 BLACKLIST REMOVE 00:00:00:00:00:00]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=37 dispatchEvent: BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 1366): Remove interface wlan0 from radio phy0
,I/GCoreNlp( 1862): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/wpa_supplicant( 1366): nl80211: Remove monitor interface: refcount=0,
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=29 linkmode=0 (kernel-control), operstate=6 (IF_OPER_UP)
,I/ActivityManager(  966): Killing 4833:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  966): killProcessQuiet, pid=4833
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/cutils-trace( 5406): Error opening trace file: Permission denied (13),
,D/CustomizationManager( 5406): ====startRecUseTime====,
D/htc.customization.log.level( 5406):  is 
W/CustomizationLogLevel( 5406): Level value is invalid, use default level 2
D/wpa_supplicant( 1366): nl80211: Set mode ifindex 29 iftype 2 (STATION),
D/wpa_supplicant( 1366): nl80211: Unsubscribe mgmt frames handle 0x888888dd06720989 (mode change)
I/wpa_supplicant( 1366): htc_wext_command_deinit +
I/wpa_supplicant( 1366): htc_wext_command_deinit -
I/wpa_supplicant( 1366): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false,
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 1366): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 1366): p2p0: Removing interface p2p0
D/wpa_supplicant( 1366): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 1366): TDLS: Tear down peers
D/wpa_supplicant( 1366): p2p0: State: DISCONNECTED -> DISCONNECTED,
D/wpa_supplicant( 1366): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 1366): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 1366): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1366): EAPOL: External notification - portValid=0
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-TERMINATING ,
E/WifiStateMachine(  966): handleMessage: E msg.what=147458
E/WifiStateMachine(  966): processMsg: SupplicantStoppingState
E/WifiStateMachine(  966):  SupplicantStoppingState !SUP_DISCONNECTION_EVENT 38 0
E/WifiStateMachine(  966): Supplicant connection lost
D/WifiMonitor(  966): Disconnecting from the supplicant, no more events
,D/CustomizationManager( 5406):  Read ACC file spent 0.034 (s)
,D/CIDMapFileReader( 5406): Parsing tag item name = HTC__001,
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__M27,
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5406): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5406): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 5406): Parsing tag category name = system
,I/CustomizationCIDLoader( 5406): Parsing tag category name = application
,I/CustomizationCIDLoader( 5406): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5406): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5406): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5406): Parsing tag category name = Settings,
I/CustomizationCIDLoader( 5406): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5406): add string-array item, value = 42507
I/CustomizationCIDLoader( 5406): add string-array item, value = 21902
I/CustomizationCIDLoader( 5406): add string-array item, value = 26006:26001.26002.26003
,I/CustomizationCIDLoader( 5406): add string-array item, value = 23420
I/CustomizationCIDLoader( 5406): add string-array item, value = 22299
I/CustomizationCIDLoader( 5406): add string-array item, value = 24002
I/CustomizationCIDLoader( 5406): add string-array item, value = 23210
I/CustomizationCIDLoader( 5406): add string-array item, value = 23205
I/CustomizationCIDLoader( 5406): add string-array item, value = 23806
I/CustomizationCIDLoader( 5406): add string-array item, value = 23430
I/CustomizationCIDLoader( 5406): add string-array item, value = 23408
I/CustomizationCIDLoader( 5406): add string-array item, value = 27205
I/CustomizationCIDLoader( 5406): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 23210:D:2:0
,I/CustomizationCIDLoader( 5406): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5406): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5406):  Read CID file spent 0.070 (s)
D/CustomizationManager( 5406):  All configurations done spent 0.070 (s)
,I/ActivityManager(  966): Recipient 4833,
D/WifiService(  966): Client connection lost with reason: 4
,D/WISPrService( 5383): >>>>>WISPrService start isConnected = false<<<<<,
D/PMS     (  966): releaseWL(360062ad): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
D/WISPrService( 5383): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/ConnectivityService(  966): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/bt-btif ( 3158): HAL bt_hal_cbacks->adapter_state_changed_cb
E/ConnectivityService(  966): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/BluetoothAdapterState( 3158): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
E/ConnectivityService(  966): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92e7:c4ff:fee6:4cf8/64,192.168.1.130/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/BluetoothAdapterService( 3158): mProfilesStarted : true supportedProfileServices.length : 6
D/PMS     (  966): releaseWL(1b26e2dd): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/CheckinService( 4547): Checking schedule, now: 1452528631896 next: 1452528641543
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=4547, uid=10024, userID:0
I/CheckinService( 4547): active receiver: disabled
D/HtcPowerSaver(  966): updateBatteryInfo
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1254): closing low battery warning: level=100
D/HeadsetStateMachine( 3158): Disconnected process message: 10, size: 0
V/NetworkPolicy(  966): ensureActiveMobilePolicyLocked()
D/Tethering(  966): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/PMS     (  966): acquireWL(3514ee86): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
D/Tethering(  966): TetherMasterSM: InitialState processMessage what=UPSTREAM_CHANGED
D/NetworkPolicy(  966): ensureActiveMobilePolicyLocked: SIM state invalid, slotId= -1000, subId=-1000 . Return.
D/DotMatrix( 1361): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,V/NetworkPolicy(  966): updateNetworkEnabledLocked()
D/DotMatrix( 1361): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
V/NetworkPolicy(  966): updateIfacesLocked()
D/DotMatrix( 1361): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
V/NetworkPolicy(  966): updateNotificationsLocked()
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateNotificationsLocked()
D/NetworkManagementService(  966): isBandwidthControlEnabled: doneSignal.getCount()= 0
,D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DATA_ICON( 1254): updateConnectivity android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE Type:-1/Status:0
,D/DATA_ICON( 1254): dataConnected: false/false
,D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/NotificationService(  966): plugged=true pluggin=true
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: ApStaDisabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
D/WISPrService( 5383): >>>>>WISPrService start isConnected = false<<<<<
D/HeadsetService( 3158): Received stop request...Stopping profile...
D/PMS     (  966): releaseWL(3514ee86): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WISPrService( 5383): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=httpproxy
,D/BluetoothPan( 5383): BluetoothPan()
D/WISPrService( 5383): >>>>>WISPrService start isConnected = false<<<<<
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
D/BluetoothManagerService(  966): registerStateChangeCallback+
V/NetworkPolicy(  966): updateNotificationsLocked()
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=callernameid
D/WISPrService( 5383): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothManagerService(  966): Registered receivers: 10
,E/WifiDataStallTracker(  966): DATA_MONITOR_POLL false Token 2
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
D/HeadsetStateMachine( 3158): Exit Disconnected: -1
I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,D/BluetoothMap( 5383): Create BluetoothMap proxy object
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 11
E/BluetoothMap( 5383): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothSap( 5383): BluetoothSap() call bindService
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 12
,I/ActivityManager(  966): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=5467 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/ContextImpl( 5383): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 ,
D/BluetoothAdapterState( 3158): Stopping profile services that were post enabled
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon
D/BluetoothHeadset(  966): Proxy object disconnected
D/PMS     (  966): releaseWL(332a89b3): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothFtpService( 3158): ACTION_STATE_CHANGED: state: 13mHasStarted: true
E/BluetoothFtpService:RfcommSocketAcceptThread( 3158): Shutdown
D/BluetoothHeadset( 1254): Proxy object disconnected
D/BluetoothHeadset( 3822): Proxy object disconnected
D/NGFService( 3822): BluetoothHeadset onServiceDisconnected: main
I/QuickSettingMiniLite( 1254): btListener.disconnect:HEADSET
D/PMS     (  966): acquireWL(ff446d1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/LocationProviderProxy(  966): applying state to connected service
D/BluetoothMasReceiver( 3158): Bluetooth STATE CHANGED to 13
D/BluetoothPbap( 5383): BluetoothPbap()
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 13
D/A2dpService( 3158): Received stop request...Stopping profile...
D/A2dpStateMachine( 3158): Exit Disconnected: -1
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
D/PMS     (  966): releaseWL(ff446d1): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothA2dp(  966): Proxy object disconnected
D/BluetoothA2dp( 3822): Proxy object disconnected
D/NGFService( 3822): BluetoothA2dp onServiceDisconnected: main
D/HidService( 3158): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
D/LocalBluetoothProfileManager( 5383): LocalBluetoothProfileManager construction complete
D/HealthService( 3158): Received stop request...Stopping profile...
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=fota
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
I/art     ( 1952): Explicit concurrent mark sweep GC freed 10939(574KB) AllocSpace objects, 8(672KB) LOS objects, 49% free, 4MB/8MB, paused 721us total 46.603ms
D/PanService( 3158): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
D/LocationProviderProxy(  966): applying state to connected service
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=supl
D/BtGatt.DebugUtils( 3158): handleDebugAction() action=null
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=emergency
D/DockEventReceiver( 5383): finishStartingService: stopping service
D/BtGatt.GattService( 3158): Received stop request...Stopping profile...
D/BtGatt.GattService( 3158): stop()
D/BtGatt.AdvertiseManager( 3158): advertise clients cleared
D/BluetoothInputDevice( 5383): Proxy object connected
D/HidProfile( 5383): Bluetooth service connected
D/PMS     (  966): acquireWL(26c8b5a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/BluetoothAdapter( 5383): 34300282: getState(). Returning 13
D/PMS     (  966): releaseWL(26c8b5a4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/BluetoothPan( 5383): BluetoothPAN Proxy object connected
D/PanProfile( 5383): Bluetooth service connected
D/SapServerProfile( 5383): Bluetooth service connected
D/BluetoothInputDevice( 5383): Proxy object disconnected
D/HidProfile( 5383): Bluetooth ser,vice disconnected
D/BluetoothPan( 5383): BluetoothPAN Proxy object disconnected
D/PMS     (  966): acquireWL(ba57f0d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/PanProfile( 5383): Bluetooth service disconnected
D/BluetoothAdapterService( 3158): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1db7cab3
D/PMS     (  966): releaseWL(363be526): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/PMS     (  966): releaseWL(ba57f0d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,W/BluetoothHeadsetServiceJni( 3158): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3158): Cleaning up Bluetooth Handsfree callback object
D/PMS     (  966): acquireWL(6b7ff09): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
,W/BluetoothHidServiceJni( 3158): Cleaning up Bluetooth HID Interface...
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=verizon800
W/BluetoothHidServiceJni( 3158): Cleaning up Bluetooth GID callback object
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=hipri
D/PMS     (  966): releaseWL(6b7ff09): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,V/BluetoothSapReceiver( 3158): SapReceiver onReceive 
V/BluetoothSapReceiver( 3158): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3158):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3158): startService = false
,W/BluetoothHealthServiceJni( 3158): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3158): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3158): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3158): Cleaning up Bluetooth PAN callback object
,I/art     (  966): Explicit concurrent mark sweep GC freed 38061(2MB) AllocSpace objects, 4(208KB) LOS objects, 33% free, 16MB/25MB, paused 1.576ms total 207.712ms
,D/MdScPhnSt( 5114): [107.3.]  listen tmrbb8
,W/BluetoothHeadset( 1254): Proxy not attached to service,
I/QuickSettingMiniLite( 1254): updateLiteState:no connect device!
,D/BluetoothAdapterState( 3158): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3158): Setting state to 10
I/BluetoothAdapterState( 3158): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  966): +onBluetoothStateChange prev=13 new=10
,D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 3158): Entering OffState
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  966): Broadcasting onBluetoothStateChange(false) to 13 receivers.
D/BluetoothHeadset(  966): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1254): onBluetoothStateChange: up=false
D/AuthorizationBluetoothService( 1952): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 5383): onBluetoothStateChange: up=false
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ims
D/PackageManager(  966): deletePackageAsUser: pkg=com.example.hello, pid=5406, uid=2000 userid=0
,D/BluetoothA2dp(  966): onBluetoothStateChange: up=false
,D/BluetoothPan( 5383): onBluetoothStateChange on: false
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=default
,I/ActivityManager(  966): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  966): Killing 4859:com.example.hello/u0a374 (adj 0): stop com.example.hello
D/Process (  966): killProcessQuiet, pid=4859
I/wpa_ctrl(  966): [wpa_ctrl_close] ctrl=0x5570340390
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,I/wpa_ctrl(  966): [wpa_ctrl_close] ctrl=0x5570340510
D/BluetoothHeadset( 1575): onBluetoothStateChange: up=false
,W/HtcWrapAdjustableCursorFactory( 5467): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
D/MessageFrequencyProvider( 5467): onCreate
,W/PackageSettings(  966): Skipping PackageSetting{8e91e2a com.test.thalitest/10366} due to missing metadata,
,D/WifiService(  966): Client connection lost with reason: 4
,I/WindowState(  966): WIN DEATH: Window{1e2720 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  966): Recipient 4859
,E/InputEventReceiver( 1431): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{603629e uid 10374 pid 4859} (c)'
,W/ActivityManager(  966): Force removing ActivityRecord{338e06db u0 com.example.hello/.MainActivity t8}: app died, no saved state
,E/WifiStateMachine(  966): setWifiState: disabled
,D/BluetoothHeadset( 1575): onBluetoothStateChange: up=false
I/ActivityManager(  966): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/MdProvGlob( 5137): remove item 101 (p2d4in206) for 15:android.intent.action.ANY_DATA_STATE
,D/MdScDataSum( 5114): [107.3.] summary 118:p2 ignore,
,W/ActivityManager(  966): Spurious death for ProcessRecord{3602850e 4859:com.example.hello/u0a374}, curProc for 4859: null
,D/BluetoothHeadset( 1575): onBluetoothStateChange: up=false
,V/GetPrviateResource( 5467): GetPrviateResource
V/GetPrviateResource( 5467): GetPrviateResource
D/PMS     (  966): acquireWL(3a711b2f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1862 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1361): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1361): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1361): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/BluetoothSap( 5383): onBluetoothStateChange on: false
V/BluetoothSapService( 3158): cleanup: mService: com.android.bluetooth.sap.BluetoothSapService@2af193df
W/Settings( 4651): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothMap( 5383): onBluetoothStateChange: up=false
E/BluetoothMap( 5383): 
E/BluetoothMap( 5383): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@bc8c6a3
E/BluetoothMap( 5383): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1135)
E/BluetoothMap( 5383): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1940)
E/BluetoothMap( 5383): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/BluetoothMap( 5383): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
E/BluetoothMap( 5383): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 5383): 	at android.os.Binder.execTransact(Binder.java:454)
,D/MdProvGlob( 5137): remove item 101 (p2in196) for 15:android.intent.action.ANY_DATA_STATE
D/BluetoothA2dp( 3822): onBluetoothStateChange: up=false
D/AccTypeManager( 1772): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/WifiStateMachine(  966): Enter handleNetworkDisconnect
,E/WifiStateMachine(  966): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - handleNetworkDisconnect - access$12300 - processMessage
W/GeofencerStateMachine( 1862): Ignoring removeGeofence because network location is disabled.
D/PMS     (  966): releaseWL(3a711b2f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
E/WifiStateMachine(  966): setSuspendOptimizationsNative: 1 true -want false stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiDataStallTracker(  966): setDhcpActive: false
D/WifiP2pService(  966): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/MessageCustFlag( 5467): sense_version=6.0
D/WifiP2pService(  966): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothHeadset( 3822): onBluetoothStateChange: up=false
D/WIFI_ICON( 1254): updateWifiState: WIFI_STATE_CHANGED disabled
D/BTAccessoryUtil( 5467): createReceiver
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1254): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/FeedHostManager( 1612): [onResume]
I/FeedProviderManager( 1612): onResume
E/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/BluetoothPbap( 5383): onBluetoothStateChange: up=false
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/Settings( 1862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ConnectivityHelper( 1612): [getCurrentConnectionType] no network connection
I/SocialFeedProvider( 1612): +onResume
I/SocialFeedProvider( 1612): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1612): -onResume
W/SystemReader(  966): Cannot find grip_rejection_width, use default value instead
D/WifiStateMachine(  966): Exit handleNetworkDisconnect
E/WifiStateMachine(  966): [MLHD] Error! unhandled message 6 { when=-703ms what=147458 arg1=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966): transitionTo: destState=InitialState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  966): invokeExitMethods: SupplicantStoppingState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
D/PMS     (  966): acquireWL(1496cfd4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 966 1000 null
E/WifiStateMachine(  966): invokeEnterMethods: InitialState
D/BTAccessoryUtil( 5467): registerReceiver return intent = null
,D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED disconnected
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  966): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  966): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothAdapter( 1588): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@5c2d85d
D/BluetoothAdapter( 1588): onBluetoothServiceDown: done
D/BluetoothAdapter( 2421): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@281b4172
D/BluetoothAdapter( 2421): onBluetoothServiceDown: done
D/BluetoothAdapter(  966): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@3106550a
,D/BluetoothAdapter(  966): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3822): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@36146da0
D/BluetoothAdapter( 3822): onBluetoothServiceDown: done
D/BluetoothAdapter( 3158): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@275a5f0f
D/BluetoothAdapter( 3158): onBluetoothServiceDown: done
D/MessageCustFlag( 5467): sku_id=118
,D/HtcBuildUtils( 5467): getRATByHtcTelephonyCapability:1
,W/SystemReader( 5467): Cannot find qct_8960_interface, use default value instead
D/BluetoothAdapter( 5383): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@36146da0
D/BluetoothAdapter( 5383): onBluetoothServiceDown: done
,D/AccTypeManager( 1772): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/BluetoothAdapter( 1254): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@37ed0762
D/BluetoothAdapter( 1254): onBluetoothServiceDown: done
I/InputMethodManagerService(  966): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/BluetoothAdapter( 1575): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@2af864ce
D/BluetoothAdapter( 1575): onBluetoothServiceDown: done
D/BluetoothAdapter( 1862): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@21eebeb
D/BluetoothAdapter( 1862): onBluetoothServiceDown: done
D/BluetoothManagerService(  966): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3106550a mBinding = false
D/BluetoothManagerService(  966): Sending unbind request.
D/StatusBarManagerService(  966): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  966): hiding MENU key
,D/WISPrService( 5383): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothManagerService(  966): Bluetooth State Change Intent: 13 -> 10
,D/WISPrService( 5383): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/MdProvGlob( 5137): remove item 101 (p2d1in81) for 15:android.intent.action.ANY_DATA_STATE
D/FindExtension( 1612): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
D/AccTypeManager( 1772): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ThreadedRenderer( 1612): Defer allocateBuffers to drawing time
,I/QuickSettingWifi( 1254): receive.wifiState:WIFI_STATE_DISABLED setEnable:true,
I/bt-btif ( 3158): HAL bt_hal_cbacks->thread_evt_cb
I/IntentController( 1254): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3822): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3822): Bluetooth Adapter: OFF
D/LocalBluetoothProfileManager( 5383): setBluetoothStateOff
W/BluetoothEventManager( 5383): unregister mProfileBroadcastReceiver fail
I/QuickSettingWifi( 1254): receive.wifiConnect:false wifiAPname:null elapse:0
W/InputMethodManagerService(  966): Got RemoteException sending setActive(false) notification to pid 4859 uid 10374
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  966): Enable input method client, pid=1612
,D/TetherPref( 5383): persistRestoreBluetoothState false
,I/art     ( 3158): System.exit called, status: 0
,E/ExternalAccountType( 1772): Unsupported attribute readOnly
,D/MmsConfig( 5467): packageName: com.htc.vvm.att does not exist
D/MessageCustFlag( 5467): sku_id=118
,D/MessagingShortcutReceiver( 5467): keep hiding shortcut bubble
,W/ResourcesManager(  966): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MessagingShortcut( 5467): updateMsgShortcut, msg count> -1
,D/SettingsManager( 5467): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@1db7cab3
,D/BluetoothAdapter( 1254): 990061945: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1254): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/MessagingShortcut( 5467): After query: 0
D/MessagingShortcut( 5467): mPresentUnreadCount: -1
,D/PhoneApp( 1575): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/MessageUtils( 5467): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 5467): setMsgShortcutDrawable> 0, false
D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
D/MessagingShortcut( 5467): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1361): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1361): [EventService] reorderNotification, total:0
D/DotMatrix( 1361): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1361): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  966): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=5512 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  966): Recipient 3158
I/ActivityManager(  966): Process com.android.bluetooth (pid 3158) has died
W/ActivityManager(  966): Scheduling restart of crashed service com.android.bluetooth/.sap.BluetoothSapService in 1000ms
W/ActivityManager(  966): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMasService in 1000ms
I/BroadcastQueue(  966): Schedule to resend BroadcastRecord{9e33b2b u-1 android.bluetooth.adapter.action.STATE_CHANGED callingPid=966 callingUid=1000} for ResolveInfo{20097b88 com.android.bluetooth/.pbap.BluetoothPbapReceiver m=0x108000} of com.android.bluetooth
,I/ActivityManager(  966): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=5533 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,W/PackageManager(  966): Unable to load service info ResolveInfo{2ebee9cc com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  966): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  966): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  966): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/MdProvGlob( 5137): remove item 101 (p2d10in155) for 15:android.intent.action.ANY_DATA_STATE
,I/art     (  966): Explicit concurrent mark sweep GC freed 18124(1342KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/25MB, paused 2.777ms total 243.024ms
,W/asset   (  966): Copying FileAsset 0x557061aad0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/MdProvGlob( 5137): remove item 101 (p2d1in26) for 15:android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 5512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1612): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1612): loadItems() com.htc.launcher.pageview.WidgetManager@3a6a1b1 +
I/Prism.WidgetManager( 1612): onLoadItems() +
,I/Prism.ItemManager( 5010): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 5010): loadItems() com.htc.launcher.pageview.WidgetManager@30296234 +
,I/Prism.WidgetManager( 5010): onLoadItems() +
,W/ResourcesManager( 5533): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/MdProvGlob( 5137): remove item 101 (p2d1in52) for 15:android.intent.action.ANY_DATA_STATE,
D/MdScDataSum( 5114): [107.12.] summary 118:p1 ignore
,W/ResourcesManager( 1612): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/MdProvGlob( 5137): remove item 101 (p2d1in23) for 15:android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 5010): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TodoTaskshortcut( 5512): update TASK shortcut>,
D/MdProvGlob( 5137): remove item 101 (p2d1in26) for 15:android.intent.action.ANY_DATA_STATE,
,D/AdapterServiceConfig( 5533): Adding HeadsetService
,D/AdapterServiceConfig( 5533): Adding A2dpService
D/AdapterServiceConfig( 5533): Adding HidService
D/AdapterServiceConfig( 5533): Adding HealthService
D/AdapterServiceConfig( 5533): Adding PanService
,D/AdapterServiceConfig( 5533): Adding GattService
,V/BluetoothPbapReceiver( 5533): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5533): ***********state = 10
,E/BluetoothMasService( 5533): BluetoothMasObexConnectionManager: mIsEmailEnabled: true,
D/PMS     (  966): acquireWL(3ea0c190): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5383 1000 null
,W/ContextImpl( 5383): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 ,
,D/BluetoothMasService( 5533): Add permission for SmsProvider.,
,D/PMS     (  966): releaseWL(3ea0c190): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/System.err(  966): java.lang.Throwable: stack dump
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22c2af:true
V/BluetoothMasService( 5533): Starting MAS instances
D/BluetoothAdapter( 5533): 128868502: getState() :  mService = null. Returning STATE_OFF
D/HtcBtWidget_BTWidgetProvider( 5418): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 5418): updateWidget(context) for widget: 
D/PMS     (  966): acquireWL(287866bc): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5383 1000 null
I/MailMessageReceiver( 5533): reg:com.android.bluetooth.btservice.AdapterApp@30b10417 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2b67f004
D/DockEventReceiver( 5383): finishStartingService: stopping service
D/PMS     (  966): releaseWL(287866bc): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,I/MailManager( 5533): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2b67f004
V/EmailUtils( 5533): Manager Instance is not NULL
,I/ActivityManager(  966): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=5557 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/MdProvGlob( 5137): remove item 101 (p2in50) for 15:android.intent.action.ANY_DATA_STATE
,D/JobSchedulerService(  966): Receieved: android.intent.action.PACKAGE_REMOVED
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=mms
,E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL false Token 15 num clients 7
D/TaskPersister(  966): removeObsoleteFile: deleting file=8_task.xml
E/WifiTrafficPoller(  966): TRAFFIC_STATS_POLL false Token 15 num clients 7
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=cbs
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 15
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=ia
D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=dun
,D/WifiService(  966): >>>>>>>>ACTION_ANY_DATA_CONNECTION_STATE_CHANGED<<<<<<<<iSlotNum=0 sReason=dataEnabled sApnType=internet
,I/PhoneStatusBar( 1254): setImeWindowStatus(false,false)
,D/MdScDataSum( 5114): [107.1a.] summary 118:p1 ignore
,D/PMS     (  966): acquireWL(3f7bf1c1): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5512 10069 null
,D/PMS     (  966): acquireWL(7b4ed66): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5512 10069 null
,D/PMS     (  966): releaseWL(3f7bf1c1): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 5512): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5512): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 5512): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 5512): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 5512): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5512): 	at android.os.Looper.loop(Looper.java:155)
,W/System.err( 5512): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  966): releaseWL(7b4ed66): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 5512): stopSelfResult true
,D/Process (  966): killProcessQuiet, pid=4912
I/ActivityManager(  966): Killing 4912:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  966): acquireWL(1a6cd154): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1952 10024 WorkSource{10024 com.google.android.gms}
,I/HtcModeClient( 3314): handler message = 4011
E/HtcModeClient( 3314): Check connection and retry 5 times.
I/ActivityManager(  966): Recipient 4912
,D/Tethering(  966): interfaceRemoved wlan0,
E/Tethering(  966): attempting to remove unknown iface (wlan0), ignoring
,D/MtpReceiver( 3944): [MTP][handleUsbStateAsync]+,
D/MtpReceiver( 3944): [MTP][handleUsbStateAsync]1:1-,
D/MtpReceiver( 3944): [MTP][handleUsbState]+
,D/HtcAdjCursorFactory( 5557): Set CursorWindow size to: 4194304 KB, Tid: 5577
,D/PMS     (  966): releaseWL(1a6cd154): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  966): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5583 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
,D/NfcHandover( 1588): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,W/OpenGLRenderer( 1612): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/MtpReceiver( 3944): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3944): [MTP][handleUsbState]-
D/MtpReceiver( 3944): [MTP][handleMessage]-
,D/MtpService( 3944): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3944): TotalSize=1886532,MediaCacheLimit=6000
D/EmailUtils( 5533): ============NULL aList========
V/EmailUtils( 5533): <-getEmailAccountIdList
V/BluetoothMasService( 5533): onCreate: mIsEmailEnabled: true
I/ActivityManager(  966): Killing 4947:com.htc.club/u0a181 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4947
D/MtpService( 3944): [isMtpConnected] connected: true
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/PMS     (  966): acquireWL(136faec0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 4547 10024 null
,W/ResourcesManager( 1612): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5010): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Tethering(  966): interfaceLinkStateChanged p2p0, false,
D/Tethering(  966): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,E/MediaScannerService( 3944): [onStartCommand] --- Should not be here, redirect request. ----
,E/MediaScannerService( 3944): [handleMessage] --- Should not be here, ignore request. ----
,W/asset   ( 1612): Copying FileAsset 0x557089c5f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,W/asset   ( 5010): Copying FileAsset 0x55703f2fd0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,
,I/ActivityManager(  966): Recipient 4947,
D/Tethering(  966): interfaceRemoved p2p0
E/Tethering(  966): attempting to remove unknown iface (p2p0), ignoring
,E/Prism.WidgetManager( 1612): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1612): onLoadItems() -
,I/Prism.ItemManager( 1612): loadItems() com.htc.launcher.pageview.WidgetManager@3a6a1b1 -
I/Prism.ItemManager( 1612): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1612): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.WidgetManager( 5010): onLoadItems() -
,I/Prism.ItemManager( 5010): loadItems() com.htc.launcher.pageview.WidgetManager@30296234 -
I/Prism.ItemManager( 5010): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5010): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Process (  966): killProcessQuiet, pid=5041,
I/ActivityManager(  966): Killing 5041:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/SQLiteDatabase( 5583): Failed to open database '/data/data/com.nero.android.htc.sync/databases/nccontentprovider.db'.,
E/SQLiteDatabase( 5583): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5583): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5583): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5583): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5583): 	,at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/SQLiteDatabase( 5583): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 5583): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
,E/SQLiteDatabase( 5583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5583): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5583): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 5583): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5583): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 5583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  966): Recipient 5041,
E/AndroidRuntime( 5583): FATAL EXCEPTION: main
E/AndroidRuntime( 5583): Process: com.nero.android.htc.sync, PID: 5583
,E/AndroidRuntime( 5583): java.lang.RuntimeException: Unable to get provider com.nero.android.neroconnect.contentprovider.NCContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 5583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5583): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 5583): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5583): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 5583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5583): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5583): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5583): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5583): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5583): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/AndroidRuntime( 5583): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 5583): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 5583): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 5583): 	... 11 more
,E/MediaScannerServiceEx( 3944): [getStorageMaskIdFromPath] path is null
,D/MediaScannerServiceEx( 3944): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
,D/MediaScannerServiceEx( 3944): [handleExternalVolume] ext storage
,D/MediaProviderUtils( 3944): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3944): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3944): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3944): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3944): [AliveExtStorageRows]+65537, 11223344
,D/Process (  966): killProcessQuiet, pid=5063
I/ActivityManager(  966): Killing 5063:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5063
,D/BluetoothMasReceiver( 5533): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 5533): onDestroy: mIsEmailEnabled: true
,V/BluetoothSapReceiver( 5533): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5533): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5533):  Bluetooth Adapter state = 10
V/BluetoothSapReceiver( 5533): startService = false
E/ActivityManager(  966): App crashed! Process: com.nero.android.htc.sync
D/Process (  966): killProcessQuiet, pid=5085
,I/ActivityManager(  966): Killing 5085:com.google.android.music:main/u0a159 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  966): Recipient 5085
,D/MediaRouterService(  966): Client com.google.android.music (pid 5085): Died!
,D/AuthorizationBluetoothService( 1952): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ErrorReport(  966): HtcErrorReportManager Begin---add error logs to dropbox
,W/System.err(  966): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
W/System.err(  966): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
,W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  966): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 14 more
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  966): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 12 more
W/System.err(  966): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  966): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 14 more
E/ErrorReport(  966): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  966): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452528633773.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  966): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  966): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  966): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442),
E/ErrorReport(  966): 	... 4 more
,W/ActivityManager(  966): Can't addPackageDependency on system process
,D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
,D/Process (  966): killProcessQuiet, pid=5168
I/ActivityManager(  966): Killing 5168:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  966): Recipient 5168
,I/iu.UploadsManager( 4547): End new media; added: 0, uploading: 0, time: 969 ms,
,D/PMS     (  966): releaseWL(136faec0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/PMS     (  966): releaseWL(1496cfd4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=196614
E/WifiStateMachine(  966): processMsg: InitialState
E/WifiStateMachine(  966):  InitialState !CMD_ON_QUIT 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
,E/WifiStateMachine(  966):  DefaultState !CMD_ON_QUIT 0 0,
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131155
E/WifiStateMachine(  966): processMsg: InitialState
E/WifiStateMachine(  966):  InitialState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3874] from screen [on:0 period:829688162] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:829688163] gl hn u24 rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131165
E/WifiStateMachine(  966): processMsg: InitialState
E/WifiStateMachine(  966):  InitialState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState !CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine(  966): handleMessage: X

```
