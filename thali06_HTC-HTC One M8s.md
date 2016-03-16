#### Test 62509094c147163_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
03-16 08:37:21.808   967  1139 D PMS     : acquireWL(3ab9005): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 967 1000 WorkSource{1000},
03-16 08:37:21.808   967  1139 V AlarmManager: sending alarm PendingIntent{35704373: PendingIntentRecord{134bf230 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180254, Int=0
03-16 08:37:21.808   967  1139 V AlarmManager: sending alarm PendingIntent{3ecc085a: PendingIntentRecord{37072a8b android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202071, Int=0
03-16 08:37:21.808   967  1139 V AlarmManager: sending alarm PendingIntent{f85a768: PendingIntentRecord{375a2781 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=192038, Int=0
03-16 08:37:21.828   967  1614 D PMS     : acquireWL(18325026): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.828   967   967 D PMS     : releaseWL(3ab9005): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
03-16 08:37:21.838  1220  2437 D WeatherUtility: Weather sync is On
03-16 08:37:21.838  1220  2437 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-16 08:37:21.858   967  2337 D PMS     : acquireWL(53be467): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.888   967  1623 D PMS     : releaseWL(18325026): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.898  1854  1854 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 08:37:21.928   967  1613 D PMS     : releaseWL(53be467): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.928   967  2337 D PMS     : acquireWL(218345b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.938   967  1614 D PMS     : releaseWL(218345b9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.948   967  1358 D PMS     : acquireWL(2a393dfe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.948   967  1615 D PMS     : releaseWL(2a393dfe): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.948   967  1758 D PMS     : acquireWL(1bb6f95f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:21.978   967  1613 D PMS     : acquireWL(b5d4fac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.038   967   988 D PMS     : acquireWL(21e73c0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.068   967  1762 D PMS     : releaseWL(1bb6f95f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.068  1854  6369 I VacuumService: Vacuum at: now=1458113842084 tag=VacuumService
03-16 08:37:22.088  1854  6370 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-16 08:37:22.108   967  1537 D PMS     : releaseWL(b5d4fac): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.108   967  1763 D PMS     : acquireWL(2825ba98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.158   967  1160 D PMS     : releaseWL(2825ba98): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.158   967  1763 D PMS     : acquireWL(2807e844): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.168   967  1762 D PMS     : releaseWL(2807e844): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:22.188  6366  6372 E cutils-trace: Error opening trace file: Permission denied (13)
03-16 08:37:22.208  1854  6370 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-16 08:37:22.208  1854  6370 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 08:37:22.208  1854  6370 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 08:37:22.208  1854  6370 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-16 08:37:22.218  1854  6370 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 08:37:22.258  1854  6370 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-16 08:37:22.258  1854  6370 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-16 08:37:22.258  1854  6370 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
03-16 08:37:22.268  1220  1220 I RemoteViews: reapply : com.google.android.gms 3 40
03-16 08:37:22.268  1331  1364 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-16 08:37:22.268  1331  1364 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfofornet-, err=8
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfo_proxy+
03-16 08:37:22.288  1854  6370 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-16 08:37:22.288   401  6386 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-16 08:37:22.288   401  6386 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
03-16 08:37:22.348  6366  6366 D CustomizationManager: ====startRecUseTime====
03-16 08:37:22.348  6366  6366 D htc.customization.log.level:  is 
03-16 08:37:22.348  6366  6366 W CustomizationLogLevel: Level value is invalid, use default level 2
03-16 08:37:22.368   401  6386 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-16 08:37:22.368   401  6386 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-16 08:37:22.368  1854  6370 D libc    : [NET] android_getaddrinfo_proxy-, success
03-16 08:37:22.428  6366  6366 D CustomizationManager:  Read ACC file spent 0.050 (s)
03-16 08:37:22.428  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__001
03-16 08:37:22.428  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__102
03-16 08:37:22.428  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-16 08:37:22.438  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__032
03-16 08:37:22.438  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-16 08:37:22.438  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__002
03-16 08:37:22.438  6366  6366 D CIDMapFileReader: Parsing tag item name = HTC__031
03-16 08:37:22.438  6366  6366 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = system
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = application
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = Settings
03-16 08:37:22.438  6366  6366 I CustomizationCIDLoader: Parsing tag category name = ACC
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 42507
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 21902
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23420
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 22299
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 24002
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23210
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23205
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23806
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23430
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23408
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 27205
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-16 08:37:22.448  6366  6366 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-16 08:37:22.448  6366  6366 D CustomizationManager:  Read CID file spent 0.096 (s)
03-16 08:37:22.448  6366  6366 D CustomizationManager:  All configurations done spent 0.096 (s)
03-16 08:37:22.488   967  1614 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6366 on display 0
03-16 08:37:22.498   967  1061 D PMS     : acquireHCC(17cebbba): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 967 1000 null
03-16 08:37:22.498   967  1061 D PMS     : acquireHCC(c14ca6b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 967 1000 null
03-16 08:37:22.498   967  1614 W asset   : Copying FileAsset 0x55a25db6c0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-16 08:37:22.528   967  1614 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6389 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 08:37:22.548   455   455 I art     : Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 249us total 17.304ms
03-16 08:37:22.548  1331  1331 D DotMatrix: [EventService]  onDisplayChanged: 0
03-16 08:37:22.548   967   967 V ActivityManager: Display changed displayId=0
03-16 08:37:22.548  1331  1331 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
03-16 08:37:22.558   455   455 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 217us total 17.590ms
03-16 08:37:22.578   455   455 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 217us total 13.601ms
03-16 08:37:22.588  6389  6389 W asset   : Copying FileAsset 0xabfcbfa0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-16 08:37:22.598  1617  1617 I TrimMemoryManager: [trimMemory] 20
03-16 08:37:22.608  1854  6370 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-16 08:37:22.608  1854  6370 D libc    : [NET] android_getaddrinfofornet-, err=8
03-16 08:37:22.608  1854  6370 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-16 08:37:22.608  1854  6370 D libc    : [NET] android_getaddrinfofornet-, err=8
03-16 08:37:22.718  6389  6389 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-16 08:37:22.758  6389  6389 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 3017-3026),
,03-16 08:37:22.758  6389  6389 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-16 08:37:22.778  6389  6389 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ae9aad9},
03-16 08:37:22.778  6389  6389 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 08:37:22.778  6389  6389 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-16 08:37:22.788  6389  6389 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-16 08:37:22.798  6389  6389 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-16 08:37:22.798  6389  6389 E SysUtils: ApplicationContext is null in ApplicationStatus,
,03-16 08:37:22.848  1854  6370 W Uploader: No account for auth token provided
,03-16 08:37:22.858  6389  6389 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
03-16 08:37:22.858  6389  6389 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 08:37:22.858  6389  6389 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 08:37:22.858  6389  6389 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-16 08:37:22.858  6389  6389 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-16 08:37:22.858  6389  6389 I Adreno-EGL: Build Date: 03/09/15 Mon
03-16 08:37:22.858  6389  6389 I Adreno-EGL: Local Branch: 
03-16 08:37:22.858  6389  6389 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-16 08:37:22.858  6389  6389 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-16 08:37:22.858  6389  6389 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-16 08:37:22.908   967  1758 W System.err: java.lang.Throwable: stack dump
03-16 08:37:22.908   967  1758 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-16 08:37:22.908   967  1758 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-16 08:37:22.908   967  1758 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-16 08:37:22.908   967  1758 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-16 08:37:22.908   967  1044 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
,03-16 08:37:22.908   967  1044 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35c339e0:true
,03-16 08:37:22.908  6389  6425 D BluetoothAdapter: 448863125: getState(). Returning 12,
,03-16 08:37:22.958  1854  6370 W Uploader: No account for auth token provided,
,03-16 08:37:22.978  6389  6389 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-16 08:37:22.988  6389  6389 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 08:37:22.998  6389  6389 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,03-16 08:37:23.008  6389  6389 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-16 08:37:23.008  6389  6389 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 08:37:23.058   967  1656 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
03-16 08:37:23.058  6389  6423 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 08:37:23.078  1854  6370 W Uploader: No account for auth token provided,
,03-16 08:37:23.088   967  1043 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
03-16 08:37:23.088   967  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:23.088   967  1043 D StatusBarManagerService: hiding MENU key
,03-16 08:37:23.088   967  1043 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-16 08:37:23.088   967  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:23.088   967  1043 D StatusBarManagerService: hiding MENU key
,03-16 08:37:23.108  6389  6389 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,03-16 08:37:23.208  6389  6389 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@11d2c426, mServedView=org.apache.cordova.engine.SystemWebView{29e54867 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@19596614
,03-16 08:37:23.208   967  1762 I InputMethodManagerService: Disable input method client, pid=1617
03-16 08:37:23.208   967  1762 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-16 08:37:23.218  1220  1220 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-16 08:37:23.218  6389  6389 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-16 08:37:23.228   967  1047 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +664ms (total +719ms)
,03-16 08:37:23.268  1854  6370 W Uploader: No account for auth token provided
,03-16 08:37:23.268  6389  6389 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6389,
,03-16 08:37:23.348  6389  6389 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-16 08:37:23.388  1854  6370 W Uploader:  no longer exists, so no auth token.
,03-16 08:37:23.448  6389  6440 D jxcore_app_log: JniHelper::setJavaVM(0xaae5e8f8), pthread_self() = -1407603544
,03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 08:37:23.448  6389  6440 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce90e98 added. We now have 1 listener(s)
03-16 08:37:23.448   967   987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 08:37:23.458  6389  6440 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
03-16 08:37:23.458  6389  6440 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,03-16 08:37:23.458  6389  6440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,03-16 08:37:23.458  6389  6440 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 08:37:23.458  6389  6440 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ebb1957 added. We now have 1 listener(s)
03-16 08:37:23.458  6389  6440 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 08:37:23.458   967  1151 D WifiService: New client listening to asynchronous messages
03-16 08:37:23.458   967   967 E WifiTrafficPoller: ADD_CLIENT: 9
,03-16 08:37:23.468  6389  6440 D BluetoothAdapter: 448863125: getState(). Returning 12
,03-16 08:37:23.468  6389  6440 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-16 08:37:23.468  6389  6440 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 08:37:23.468  6389  6440 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 08:37:23.468  6389  6440 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 08:37:23.468  6389  6440 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-16 08:37:23.468  6389  6440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-16 08:37:23.468   967   988 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-16 08:37:23.478  6389  6440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77,
,03-16 08:37:23.478  6389  6440 D BluetoothAdapter: 448863125: getState(). Returning 12
,03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 08:37:23.478  6389  6440 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 08:37:23.478  6389  6440 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 08:37:23.478  6389  6440 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 08:37:23.478  6389  6389 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:37:23.488  6389  6389 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 08:37:23.498  6389  6389 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 08:37:23.508   967  1613 D PMS     : releaseWL(21e73c0a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
03-16 08:37:23.508   967  1615 D PMS     : acquireWL(3a69f772): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:23.528   967   988 D PMS     : releaseWL(3a69f772): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-16 08:37:23.528   967  1624 D PMS     : acquireWL(3caf47c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:23.538   967  1615 D PMS     : releaseWL(3caf47c3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-16 08:37:24.318  6389  6446 W jxcore-log: Initializing JXcore engine,
03-16 08:37:24.318  6389  6446 W jxcore-log: JXcore engine is ready
,03-16 08:37:24.378  6389  6446 W jxcore-log: Starting JXcore engine,
,03-16 08:37:24.458  6389  6446 W jxcore-log: Platform android
03-16 08:37:24.458  6389  6446 W jxcore-log: 
,03-16 08:37:24.458  6389  6446 W jxcore-log: Process ARCH arm
03-16 08:37:24.458  6389  6446 W jxcore-log: 
,03-16 08:37:24.498   967  1061 D PMS     : releaseHCC(17cebbba): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-16 08:37:24.498   967  1061 D PMS     : releaseHCC(c14ca6b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,03-16 08:37:24.818  6389  6446 I jxcore-log: JXcore Cordova bridge is ready!
03-16 08:37:24.818  6389  6446 I jxcore-log: 
03-16 08:37:24.818  6389  6446 W jxcore-log: JXcore engine is started
,03-16 08:37:24.818  6389  6440 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-16 08:37:24.818  6389  6389 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 08:37:24.838  6389  6446 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 08:37:24.838  6389  6446 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 08:37:24.838  6389  6389 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 08:37:24.838  6389  6389 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 08:37:24.858   967  1763 D Process : killProcessQuiet, pid=6138
03-16 08:37:24.858   967  1763 I ActivityManager: Killing 6138:com.htc.cs.dm/u0a99 (adj 15): empty #17
,03-16 08:37:24.858   967  1763 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,03-16 08:37:25.018   967  1358 I ActivityManager: Recipient 6138,
,03-16 08:37:25.078  6389  6440 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 232ms. Plugin should use CordovaInterface.getThreadPool().,
,03-16 08:37:25.128  6389  6389 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@12e5d12d that was originally registered here. Are you missing a call to unregisterReceiver()?,
03-16 08:37:25.128  6389  6389 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@12e5d12d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335),
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:25.128  6389  6389 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:37:25.138  6389  6389 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@27ac7c44 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:25.138  6389  6389 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@27ac7c44 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84),
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:25.138  6389  6389 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:37:25.158  6447  6450 E cutils-trace: Error opening trace file: Permission denied (13),
,03-16 08:37:25.208  6447  6447 D CustomizationManager: ====startRecUseTime====,
03-16 08:37:25.208  6447  6447 D htc.customization.log.level:  is 
03-16 08:37:25.208  6447  6447 W CustomizationLogLevel: Level value is invalid, use default level 2
,03-16 08:37:25.268  6447  6447 D CustomizationManager:  Read ACC file spent 0.034 (s),
,03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__001
03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__102
03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__032
03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__002
,03-16 08:37:25.278  6447  6447 D CIDMapFileReader: Parsing tag item name = HTC__031
03-16 08:37:25.278  6447  6447 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
,03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = system
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = application
,03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = Settings
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: Parsing tag category name = ACC
,03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 42507,
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 21902
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23420
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 22299
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 24002
,03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23210
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23205
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23806
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23430
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23408
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 27205
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0,
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0,
03-16 08:37:25.278  6447  6447 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-16 08:37:25.278  6447  6447 D CustomizationManager:  Read CID file spent 0.069 (s)
03-16 08:37:25.278  6447  6447 D CustomizationManager:  All configurations done spent 0.070 (s)
,03-16 08:37:25.308   967  1623 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=6447, uid=2000 userid=0,
,03-16 08:37:25.318   967  1026 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg
,03-16 08:37:25.318   967  1026 I ActivityManager: Killing 6389:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest
,03-16 08:37:25.328   967  1026 D Process : killProcessQuiet, pid=6389
03-16 08:37:25.328   967  1026 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,03-16 08:37:25.398   967  1613 I ActivityManager: Recipient 6389,
03-16 08:37:25.398   967  1151 D WifiService: Client connection lost with reason: 4
03-16 08:37:25.398  1392  1392 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{12afda4b uid 10195 pid 6389} (c)'
,03-16 08:37:25.408   967  1110 W PackageSettings: Skipping PackageSetting{a89fb8b com.example.hello/10374} due to missing metadata,
,03-16 08:37:25.438   967  1110 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed
,03-16 08:37:25.458   967  1613 W ActivityManager: Spurious death for ProcessRecord{2512840 6389:com.test.thalitest/u0a195}, curProc for 6389: null
,03-16 08:37:25.468  1331  1331 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
03-16 08:37:25.468  1331  1331 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
03-16 08:37:25.468  1331  1331 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
,03-16 08:37:25.468  1766  2184 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
03-16 08:37:25.468   967  1148 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
03-16 08:37:25.478   967  1147 D PMS     : acquireWL(1851d379): PARTIAL_WAKE_LOCK  NetworkStats 0x1 967 1000 null
,03-16 08:37:25.488  1766  2184 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
03-16 08:37:25.488   967   987 D PMS     : acquireWL(b349d1f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
03-16 08:37:25.488  1797  2234 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 08:37:25.498   967  2337 D PMS     : releaseWL(b349d1f): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
03-16 08:37:25.498   967  1141 W SystemReader: Cannot find grip_rejection_width, use default value instead
,03-16 08:37:25.518   967  1025 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false,
03-16 08:37:25.528  5037  5037 I art     : Explicit concurrent mark sweep GC freed 854(45KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 902us total 90.308ms
03-16 08:37:25.538  1708  6465 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-16 08:37:25.538   967  1147 D PMS     : releaseWL(1851d379): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
03-16 08:37:25.538   967  1148 V NetworkPolicy: writePolicyLocked()
,03-16 08:37:25.538  1549  1549 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,03-16 08:37:25.548  1766  2184 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,03-16 08:37:25.548  1535  6466 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,03-16 08:37:25.548   967  1025 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 08:37:25.558  1617  1617 I art     : Explicit concurrent mark sweep GC freed 54217(3MB) AllocSpace objects, 20(1232KB) LOS objects, 34% free, 30MB/46MB, paused 908us total 112.062ms,
03-16 08:37:25.558  1617  1617 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
,03-16 08:37:25.558  1617  2079 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
03-16 08:37:25.558  1617  2079 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,03-16 08:37:25.568  1535  6466 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,03-16 08:37:25.568  1617  1617 I Launcher: Deferring update until onResume
03-16 08:37:25.568  1617  1617 D Launcher: waitUntilResume // bindAppsRemoved
,03-16 08:37:25.578  1766  2184 E ExternalAccountType: Unsupported attribute readOnly
03-16 08:37:25.578   967  1148 V NetworkPolicy: updateNetworkEnabledLocked()
03-16 08:37:25.578   967  1148 V NetworkPolicy: updateNotificationsLocked(),
03-16 08:37:25.578   967  2337 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,03-16 08:37:25.658   967   967 I art     : Explicit concurrent mark sweep GC freed 40867(3MB) AllocSpace objects, 9(736KB) LOS objects, 33% free, 16MB/24MB, paused 1.669ms total 211.680ms
,03-16 08:37:25.658   967  1110 I art     : WaitForGcToComplete blocked for 186.782ms for cause Explicit
,03-16 08:37:25.758  6467  6467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 ,
,03-16 08:37:25.768   967  1043 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-16 08:37:25.768   967  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:25.768   967  1043 D StatusBarManagerService: hiding MENU key
,03-16 08:37:25.768   967   967 W PackageManager: Unable to load service info ResolveInfo{162ee0fc com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
03-16 08:37:25.768   967   967 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
03-16 08:37:25.768   967   967 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
,03-16 08:37:25.768   967   967 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 08:37:25.768   967   967 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:25.768   967   967 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
03-16 08:37:25.768   967   967 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
03-16 08:37:25.768   967   967 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 08:37:25.768   967   967 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 08:37:25.768   967   967 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
03-16 08:37:25.768   967   967 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
03-16 08:37:25.768   967  1043 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-16 08:37:25.778   967  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 08:37:25.778   967  1043 D StatusBarManagerService: hiding MENU key
,03-16 08:37:25.788  1617  1617 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-16 08:37:25.798  1617  1617 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,03-16 08:37:25.818   967  1358 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6389 uid 10195,
03-16 08:37:25.818   967  1358 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-16 08:37:25.838   967  1110 I art     : Explicit concurrent mark sweep GC freed 6270(339KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.398ms total 175.245ms,
,03-16 08:37:25.838   967   967 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 08:37:25.848   967  1177 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
,03-16 08:37:25.848  1854  1854 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-16 08:37:25.848  1854  1854 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
03-16 08:37:25.848   967  1613 D PMS     : acquireWL(3e921490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1854 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:25.858   967  1110 W asset   : Copying FileAsset 0x55a2524030 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,03-16 08:37:25.858   967  1160 D PMS     : releaseWL(3e921490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-16 08:37:25.868  1220  1220 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-16 08:37:25.908  2162  6498 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
03-16 08:37:25.908  2162  2162 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
03-16 08:37:25.908  2162  2162 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-16 08:37:25.908  2162  2162 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,03-16 08:37:25.908  2162  2162 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,03-16 08:37:25.918  2162  6498 D AccountUtils: Clearing selected account for com.test.thalitest
,03-16 08:37:25.928   967  1612 D PMS     : acquireWL(60279cb): PARTIAL_WAKE_LOCK  AsyncService 0x1 6029 10167 null
,03-16 08:37:25.938   967  1613 D PMS     : acquireWL(30545866): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6029 10167 null
,03-16 08:37:25.938   967  1537 D PMS     : releaseWL(60279cb): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,03-16 08:37:25.938  2162  6498 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-16 08:37:25.938   967  1160 D PMS     : releaseWL(30545866): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,03-16 08:37:25.948  5037  6505 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-16 08:37:25.978  2162  6506 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,03-16 08:37:25.988  2162  6506 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-16 08:37:25.988  2162  6506 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-16 08:37:25.988  2162  6506 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
03-16 08:37:25.998   967  1623 I ActivityManager: Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=6509 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1,
03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
03-16 08:37:25.998  2162  6506 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-16 08:37:26.008  2162  6506 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,03-16 08:37:26.008  2162  6506 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-16 08:37:26.008  2162  6506 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
03-16 08:37:26.008   967  1623 D PMS     : acquireWL(226d249f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 2162 10024 null
03-16 08:37:26.008  1854  1854 I ConfigService: onCreate
03-16 08:37:26.008  2162  2162 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-16 08:37:26.008   967  2337 D PMS     : releaseWL(226d249f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,03-16 08:37:26.028   967  1624 D PMS     : acquireWL(2850da84): PARTIAL_WAKE_LOCK  Icing 0x1 2162 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:26.038  2162  4813 I Icing   : doRemovePackageData com.test.thalitest
,03-16 08:37:26.038  2162  6531 I PeopleContactsSync: CP2 sync disabled
03-16 08:37:26.038  2162  6508 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 08:37:26.038   967  1358 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2162, uid=10024, userID:0,
,03-16 08:37:26.038   967   988 D PMS     : releaseWL(2850da84): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-16 08:37:26.048  2162  6508 W BaseAppContext: Using Auth Proxy for data requests.,
,03-16 08:37:26.048   967  1537 D PMS     : acquireWL(3f67c869): PARTIAL_WAKE_LOCK  Icing 0x1 2162 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:26.078   967  1762 D PMS     : releaseWL(3f67c869): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms},
,03-16 08:37:26.088  6509  6509 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6509 dbg=false s=true
,03-16 08:37:26.088  6509  6509 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest],
03-16 08:37:26.088   967  1613 D PMS     : acquireWL(3868b9ab): PARTIAL_WAKE_LOCK  Icing 0x1 2162 10024 WorkSource{10024 com.google.android.gms}
,03-16 08:37:26.088  5037  6505 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] ,
03-16 08:37:26.088  6509  6509 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,03-16 08:37:26.098  6509  6509 I DeviceManagement: WorkflowService: Starting workflow service
,03-16 08:37:26.098  6509  6535 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@34620c9e] args=[Bundle[mParcelledData.dataSize=112]],
03-16 08:37:26.098  6509  6535 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,03-16 08:37:26.098  6509  6535 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
03-16 08:37:26.098  6509  6535 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,03-16 08:37:26.108  6509  6535 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-16 08:37:26.118   967  1615 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=6536 uid=10100 gids={50100, 9997, 3003} abi=arm64-v8a
,03-16 08:37:26.158  6509  6535 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,03-16 08:37:26.158  6509  6558 I DeviceManagement: SessionStateController: Checking invariants...
,03-16 08:37:26.238   967  1614 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=6561 uid=10019 gids={50019, 9997, 1028, 1015, 1023} abi=arm64-v8a,
,03-16 08:37:26.248  6303  6303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,03-16 08:37:26.268  6303  6585 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-16 08:37:26.268  6303  6585 D PowerUsageService: removed uid = 10195,
,03-16 08:37:26.278   967   987 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=6586 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,03-16 08:37:26.288   967   987 D Process : killProcessQuiet, pid=6162,
03-16 08:37:26.288   967   987 I ActivityManager: Killing 6162:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
03-16 08:37:26.288   967   987 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-16 08:37:26.318  6509  6558 W FileUtils: Failed to chmod(/data/data/com.htc.cs.dm/databases/provisioning.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system),
03-16 08:37:26.318  6509  6558 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-16 08:37:26.318  6509  6558 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x55a1e08060
,03-16 08:37:26.328  6561  6561 D ExternalStorage: After updating volumes, found 1 active roots,
,03-16 08:37:26.408   967  1763 I ActivityManager: Recipient 6162,
,03-16 08:37:26.508  6509  6558 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,03-16 08:37:26.518  6509  6535 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.,
03-16 08:37:26.518  6509  6535 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,03-16 08:37:26.528  6509  6535 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
03-16 08:37:26.528  6509  6535 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.htc.cs.dm/databases/provisioning.db, handle: 0x55a1e08060
,03-16 08:37:26.538  6586  6586 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 08:37:26.538  6509  6535 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@34620c9e]java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.,
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:90)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:319)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:26.538  6509  6535 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 08:37:26.548  6509  6509 I DeviceManagement: WorkflowService: Stopping workflow service
03-16 08:37:26.548   967   988 D Process : killProcessQuiet, pid=5605
03-16 08:37:26.548   967   988 I ActivityManager: Killing 5605:com.htc.mediamanager/u0a28 (adj 15): empty #17
03-16 08:37:26.548   967   988 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-16 08:37:26.668   967  1615 I ActivityManager: Recipient 5605
,03-16 08:37:26.798  6191  6191 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-16 08:37:26.798  6191  6191 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 08:37:26.808  6586  6609 E SQLiteDatabase: Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.,
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:26.808  6586  6609 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: Couldn't open MyDB.db for writing (will try read-only):
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabas,e.open(SQLiteDatabase.java:834)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at com.htc.task.dm.DatabaseHelper.getReadableDB(DatabaseHelper.java:60)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at com.htc.task.util.TaskULog.uLogDefaultAccount(TaskULog.java:220)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at com.htc.task.util.TaskULog.checkDefaultAccount(TaskULog.java:213)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at com.htc.task.TodoService.onHandleIntent(TodoService.java:106)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
03-16 08:37:26.808  6586  6609 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 08:37:26.808  6586  6609 W SQLiteOpenHelper: Opened MyDB.db in read-only mode
03-16 08:37:26.828   967  1615 I ActivityManager: Killing 6249:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
03-16 08:37:26.828   967  1615 D Process : killProcessQuiet, pid=6249
03-16 08:37:26.828   967  1615 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-16 08:37:26.878  6536  6560 D Documents: Update found 7 roots in 678ms,
,03-16 08:37:26.938   967   988 I ActivityManager: Recipient 6249,
,03-16 08:37:26.948  6536  6608 D Documents: Update found 7 roots in 623ms
,03-16 08:37:27.058  1617  2079 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
03-16 08:37:27.058  1617  2079 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@c6bff08 +
03-16 08:37:27.058  1617  2079 I Prism.WidgetManager: onLoadItems() +
,03-16 08:37:27.098  2162  4813 I Icing   : Indexing FBE7E5D8BA1B80556F1315772AF6A2582D6BF376 from com.google.android.googlequicksearchbox
,03-16 08:37:27.128  1617  2079 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,03-16 08:37:27.178  2162  4813 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
03-16 08:37:27.178  2162  4813 E Icing   : Could not init tag ds.tag.deleted
,03-16 08:37:27.288  2162  4813 I Icing   : Indexing done FBE7E5D8BA1B80556F1315772AF6A2582D6BF376
,03-16 08:37:27.298  2162  4813 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,03-16 08:37:27.298  2162  4813 E Icing   : Writing status failed
,03-16 08:37:27.308  2162  4813 E Icing   : Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,03-16 08:37:27.308   967  1758 D PMS     : releaseWL(3868b9ab): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,03-16 08:37:27.308   967  1762 I ActivityManager: Killing 6272:com.htc.bgp/u0a11 (adj 15): empty #17
03-16 08:37:27.308   967  1762 D Process : killProcessQuiet, pid=6272,
03-16 08:37:27.308   967  1762 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,

```
