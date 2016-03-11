#### Test 62509094a319d1d_thali04_motorola-XT1072 Logs


```
--------- beginning of main
V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
W/Settings( 2629): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
W/Settings( 2629): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2629): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
W/Settings( 2629): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/MotorolaSettings( 2629): no such table to get this name = privacy_droid_blast
W/System.err( 2629): java.lang.Exception
W/System.err( 2629): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 2629): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 2629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 2629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 2629): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 2629): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 2629): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 2629): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 2629): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 2629): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 2629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 2629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 2629): 	at java.lang.Thread.run(Thread.java:818)
I/global frequency( 2629): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
I/global frequency( 2629): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
D/Checkin ( 2629): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2629): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 2629): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
W/Settings( 2629): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2629): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
W/Settings( 2629): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
--------- beginning of system
I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=5054 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5054): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
W/Finsky  ( 4801): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4801): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  882): send {2e598f18, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
D/Finsky  ( 4801): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
D/DeviceConnectionService( 1687): client connected with version: 8296000
I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5077 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  882): Killing 4771:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/Finsky  ( 4801): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4801): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/CalendarProvider2( 4994): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4994): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_4771/cgroup.procs: No such file or directory
I/ActivityManager(  882): Killing 4890:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
D/AndroidRuntime( 5052): 
D/AndroidRuntime( 5052): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5052): CheckJNI is OFF
I/ActivityManager(  882): Killing 3614:com.android.defcontainer/u0a10 (adj 15): empty #8
I/ContactLocale( 5077): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/libprocessgroup(  882): failed to open /acct/uid_10060/pid_4890/cgroup.procs: No such file or directory
W/libprocessgroup(  882): failed to open /acct/uid_10010/pid_3614/cgroup.procs: No such file or directory
I/ActivityManager(  882): Killing 4994:com.android.providers.calendar/u0a5 (adj 15): empty #7
W/libprocessgroup(  882): failed to open /acct/uid_10005/pid_4994/cgroup.procs: No such file or directory
D/AndroidRuntime( 5052): Calling main entry com.android.commands.am.Am
I/ActivityManager(  882): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5112 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  882): Killing 4910:com.google.process.gapps/u0a16 (adj 15): empty #7
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_4910/cgroup.procs: No such file or directory
D/AndroidRuntime( 5052): Shutting down VM
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5129 uid=10569 gids={50569, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/ActivityThread( 2629): Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2629): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity}
E/ActivityThread( 2629): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3396)
E/ActivityThread( 2629): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3477)
E/ActivityThread( 2629): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
E/ActivityThread( 2629): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1321)
E/ActivityThread( 2629): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2629): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2629): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 2629): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2629): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 2629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
I/ActivityManager(  882): Activity reported stop, but no longer stopping: ActivityRecord{33f148c5 u0 com.motorola.ccc.ota/.ui.DownloadActivity t8}
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5149 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 4664:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_4664/cgroup.procs: No such file or directory
,W/asset   ( 5149): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5149): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5149): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5149): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1936): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1936): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1936): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1936): Submit a task: k
,I/ActivityManager(  882): Killing 4956:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/WebViewFactory( 5129): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_4956/cgroup.procs: No such file or directory
,W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,I/art     (  882): Explicit concurrent mark sweep GC freed 15927(703KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.440ms total 143.640ms
,D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/LibraryLoader( 5129): Time to load native libraries: 2 ms (timestamps 225-227)
D/k       ( 1936): Processing package: com.test.thalitest
D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/LibraryLoader( 5129): Expected native library version number "",actual native library version number ""
,D/GassUtils( 1936): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 1936): Found info for package com.test.thalitest in db.
,V/WebViewChromiumFactoryProvider( 5129): Binding Chromium to main looper Looper (main, tid 1) {b691197}
,I/LibraryLoader( 5129): Expected native library version number "",actual native library version number ""
I/chromium( 5129): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5129): Initializing chromium process, singleProcess=true
,W/art     ( 5129): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5186 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SysUtils( 5129): ApplicationContext is null in ApplicationStatus
,W/chromium( 5129): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5129): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (29:204 vsyncs) (31:1016)
,E/libEGL  ( 5129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5129): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5129): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5129): Local Branch: 
I/Adreno-EGL( 5129): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5129): Local Patches: NONE
I/Adreno-EGL( 5129): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e65597d:true
,D/BluetoothAdapter( 5129): 1067270128: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  882): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5219 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 25.753ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 376us total 24.623ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 23.498ms
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5238 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/GservicesProvider( 5219): Gservices pushing to system: true; secure/global: true
,W/art     ( 5129): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5129): onDetachedFromWindow called when already detached. Ignoring
,I/GoogleHttpClient( 5219): GMS http client unavailable, use old client
,D/SystemWebViewEngine( 5129): CordovaWebView is running on device made by: motorola
,W/art     ( 5129): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5129): Attempt to remove local handle scope entry from IRT, ignoring
I/GoogleHttpClient( 5219): GMS http client unavailable, use old client
,D/OpenGLRenderer( 5129): Render dirty regions requested: true
,D/Atlas   ( 5129): Validating map...
,W/chromium( 5129): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  882): Killing 4801:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_4801/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 5129): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5129): Enabling debug mode 0
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1311
,I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +1s311ms
,I/SFPerfTracer(  278):      triggers: (rate: 13:409) (compose: 0:1) (post: 0:1) (render: 0:2) (0:959 frames) (1:1034)
D/SFPerfTracer(  278):        layers: (3:13) (FocusedStackFrame (0xb7ef1c58): 0:14)* (DimLayer (0xb7f75448): 0:6)* (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb7f77b98): 0:45)- (StatusBar (0xb7f7ca38): 0:116) (NavigationBar (0xb7f7fea8): 0:34) (com.android.systemui.ImageWallpaper (0xb7f835f0): 0:6)* (Starting com.motorola.ccc.ota (0xb7f4fd78): 0:40)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7fa2b00): 0:56)- (Starting com.test.thalitest (0xb7f4fd78): 0:29) (com.test.thalitest/com.test.thalitest.MainActivity (0xb7fa4818): 1:4)* 
,E/Adreno-ES20( 5129): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5129): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/GAv4    ( 5238): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5238):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5238):   adb logcat -s GAv4
,I/UpdateIcingCorporaServi( 5186): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/BindingManager( 5129): Cannot call determinedVisibility() - never saw a connection for the pid: 5129
,W/GAv4    ( 5238): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5238): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5238): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5238): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,D/JsMessageQueue( 5129): Set native->JS mode to OnlineEventsBridgeMode
,I/Icing   ( 1936): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5238): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5238): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5238): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5305 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5054:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5054/cgroup.procs: No such file or directory
,W/ResourcesManager( 5305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Adreno-ES20( 5129): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5129): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/Icing   ( 1936): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,V/JNIHelp ( 5238): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/jxcore_app_log( 5129): JniHelper::setJavaVM(0xb74e8310), pthread_self() = -1215755888
D/JX-Cordova( 5129): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8877650 added. We now have 1 listener(s)
,I/art     ( 1936): Explicit concurrent mark sweep GC freed 60357(3MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 14MB/24MB, paused 1.518ms total 122.307ms
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5129): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5129): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5129): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5129): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ebd8e6f added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5129): addListener: New listener added - the number of listeners is now 1
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5129): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
D/WifiService(  882): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5129): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5129): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5129): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5129): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,W/System  ( 5238): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5238): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 5186): UpdateCorporaTask done [took 812 ms] updated apps [took 812 ms] 
,I/ActivityManager(  882): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5330 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 4867:com.google.android.gm/u0a63 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10063/pid_4867/cgroup.procs: No such file or directory
,W/ResourcesManager( 5330): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5330): Created com.android.providers.calendar.CalendarAlarmManager@2ca68dd8(com.android.providers.calendar.CalendarProvider2@f326531)
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5352 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5112:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_5112/cgroup.procs: No such file or directory
,D/Finsky  ( 5352): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{1c424711 u0 com.motorola.ccc.checkin/.CheckinService}
,D/Finsky  ( 5352): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5352): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5352): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5352): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5352): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5352): Skipping gmscore version check
,I/Icing   ( 1936): Indexing AF3945E421480F00A6230F0533E769ED0E1C70AE from com.google.android.googlequicksearchbox
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.ccc.UpdateModelReceiver: pid=5406 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/Finsky  ( 5352): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 5406): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Finsky  ( 5352): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5352): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 5149:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_5149/cgroup.procs: No such file or directory
,I/CE-UpdateModelService( 5406): ACTION_REGISTRATION_COMPLETE
,E/MDM     ( 1687): [171] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1936): Restart initialization of location
,D/AuthorizationBluetoothService( 1687): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/3CDM.DeviceAdminPushReceiver( 2629): Received an Intent - Action: com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
D/3CDM.DeviceAdminPushReceiver( 2629): Type: null
D/3CDM.DeviceAdminPushReceiver( 2629): Data: null
,D/3CDM.Service( 2629): com.motorola.cce.Actions.CCE_SEND_SETTINGS_RESPONSE
,W/GCoreFlp( 1687): No location to return for getLastLocation()
,W/FusedLocationProvider( 1687): location=null
,D/3CDM.Service( 2629): Received settings reponse intent with responsecode code: com.motorola.cce.sharedsettings.errorOk
D/3CDM.Service( 2629): DeviceAdmin - syncWithCCC
,D/3CDM.Service( 2629): blur.service.littlesister.gpsFixWaitTime = 60000
D/3CDM.Service( 2629): com.motorola.ccc.devicemanagement.capabilities = LOST,LOCK,RING,LOCATE,PING,MULTIPLE-LOCATE,WIPE,SYNC,CALL-FORWARDING,STOP-RING
,D/3CDM.Service( 2629): blur.service.cred.locationToken = null
D/3CDM.Service( 2629): com.motorola.ccc.cce.email.marketing.optin.default = false
D/3CDM.Service( 2629): blur.service.littlesister.reportLevel2 = NONE
D/3CDM.Service( 2629): com.motorola.blur.adminfeed.device_admin_always_allowed = 1
D/3CDM.Service( 2629): com.motorola.ccc.devicemanagement.motocare.url = www.motorola.com/support
,I/Icing   ( 1936): Indexing done AF3945E421480F00A6230F0533E769ED0E1C70AE
I/ActivityManager(  882): Killing 5238:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/3CDM.Service( 2629): Sync to CCE settings done, instantiate Locate now.
,I/CalendarProvider2( 5330): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5330): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     (  882): Explicit concurrent mark sweep GC freed 12008(631KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.591ms total 126.577ms
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_5238/cgroup.procs: No such file or directory
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task_thumbnail.png
,I/ActivityManager(  882): Killing 5077:android.process.acore/u0a7 (adj 15): empty #7
,D/BSUtils ( 2629): set .setup.DeviceAdminSetupReceiver enabled
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_5077/cgroup.procs: No such file or directory
,V/AlarmManager(  882): done {2e598f18, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [4315ms]
,D/Finsky  ( 5352): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5352): [652] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  882): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5430 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/jxcore-log( 5129): Initializing JXcore engine
W/jxcore-log( 5129): JXcore engine is ready
,W/jxcore-log( 5129): Starting JXcore engine
,D/ActivityThread( 5430): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 5430): getAccountsCursor
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=5454 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/.test.thalitest( 5129): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10569 path="socket:[5639]" dev="sockfs" ino=5639 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5129): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10569 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 5129): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10569 path="socket:[5762]" dev="sockfs" ino=5762 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 5129): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10569 path="socket:[23873]" dev="sockfs" ino=23873 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,V/AlarmManager(  882): send {18e74318, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,D/Finsky  ( 5352): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  882): done {18e74318, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [22ms]
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  882): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Exchange( 5454): EasService.onCreate
,I/Exchange( 5454): RestartPingTask
I/Gmail   ( 5430): Observing account changes for notifications
,W/Finsky  ( 5352): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/GAV2    ( 5430): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Exchange( 5454): RestartPingsTask did not start any pings.
I/Exchange( 5454): PSS stopIfIdle
I/Exchange( 5454): PSS has no active accounts; stopping service.
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 5129): Platform android
W/jxcore-log( 5129): 
W/jxcore-log( 5129): Process ARCH arm
W/jxcore-log( 5129): 
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5490 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/Gmail   ( 5430): getAccountsCursor
,I/Exchange( 5454): onDestroy
,I/ActivityManager(  882): Killing 5305:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ResourcesManager( 5490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5490): VM with version 2.1.0 has multidex support
,I/MultiDex( 5490): install
I/MultiDex( 5490): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_5305/cgroup.procs: No such file or directory
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5352): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/3CDM.DeviceAdminSetupReceiver( 2629): received com.motorola.ccc.devicemanagement.setup.action.ENABLED
,D/3CDM.DeviceAdminSetupReceiver( 2629): time to show notification
,E/SQLiteLog( 5430): (283) recovered 332 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/ResourcesManager( 1290): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,V/JNIHelp ( 5490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5490): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33ea28b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5490): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1687): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1936): Restart initialization of location
,E/ActivatableNotificationView( 1290):  oops Width=0 ActualHeight=128
,D/ChimeraCfgMgr( 5490): Reading stored module config
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1687): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1687): No location to return for getLastLocation()
W/FusedLocationProvider( 1687): location=null
,I/Gmail   ( 5430): notifyAccountChanged
I/Gmail   ( 5430): getAccountsCursor
,I/Gmail   ( 5430): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/Gmail   ( 5430): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5430): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5430): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5430): getAccountsCursor
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CAR.SERVICE( 5490): Connecting to CarCallService...
,D/NativeLibraryUtils( 5490): Install completed successfully. count=14 extracted=0
,I/art     ( 5490): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5490): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5490): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 5490): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 5490): Creating a new PhoneAdapter instance
,W/ActivityManager(  882): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5490): setListener: com.google.android.gms.car.dn@ac2e6d6
,W/ActivityManager(  882): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 5490): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 5490): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 5490): Package validated; name: com.android.vending
,V/Finsky  ( 5352): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/jxcore-log( 5129): JXcore Cordova bridge is ready!
I/jxcore-log( 5129): 
,W/jxcore-log( 5129): JXcore engine is started
,I/chromium( 5129): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5129): Skipped 176 frames!  The application may be doing too much work on its main thread.
,I/org.thaliproject.p2p.ThaliPermissions( 5129): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 5129): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5352): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5352): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  882): send {2e598f18, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5352): [1] DailyHygiene.reschedule: Scheduling new run in 83 minutes (failures=3)
,V/AlarmManager(  882): done {2e598f18, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [23ms]
,D/Finsky  ( 5352): [657] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1687): client connected with version: 8296000
,D/Finsky  ( 5352): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5352): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5352): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Killing 5454:com.google.android.gm.exchange/u0a60 (adj 15): empty #7
,I/ActivityManager(  882): Killing 5186:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10060/pid_5454/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5186/cgroup.procs: No such file or directory
,I/art     (  882): Explicit concurrent mark sweep GC freed 14536(723KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.954ms total 112.608ms
,I/ActivityManager(  882): Killing 4552:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:38000 mC
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_4552/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {31903f80, *walarm*:com.android.providers.calendar.intent.CalendarProvider2}
,V/AlarmManager(  882): done {31903f80, *walarm*:com.android.providers.calendar.intent.CalendarProvider2} [19ms]
,E/SQLiteLog( 5330): (284) automatic index on view_events(_id)
,V/AlarmManager(  882): send {1d3921fe, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {1d3921fe, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  882): send {22230d5f, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  882): done {22230d5f, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,I/GAV2    ( 5430): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 5129): INFO testUtils Toggling radios to: true
I/jxcore-log( 5129): 
,D/CAR.SERVICE( 5490): mConnectedToCar = false, abort
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  882): enable():  mBluetooth =null mBinding = false
,E/ActivityThread( 5490): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9b415fe that was originally bound here
E/ActivityThread( 5490): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9b415fe that was originally bound here
E/ActivityThread( 5490): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5490): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5490): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5490): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5490): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5490): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5490): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5490): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5490): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5490): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5490): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5490): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5490): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5490): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
E/ActivityThread( 5490): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 5490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
E/ActivityThread( 5490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5490): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5490): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5490): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5490): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,E/ActivityThread( 5490): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29e92af1 that was originally bound here
E/ActivityThread( 5490): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29e92af1 that was originally bound here
E/ActivityThread( 5490): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1081)
E/ActivityThread( 5490): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:975)
E/ActivityThread( 5490): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1902)
E/ActivityThread( 5490): 	at android.app.ContextImpl.bindService(ContextImpl.java:1885)
E/ActivityThread( 5490): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5490): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5490): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5490): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5490): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5490): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5490): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5490): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5490): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2790)
E/ActivityThread( 5490): 	at android.app.ActivityThread.access$1900(ActivityThread.java:148)
E/ActivityThread( 5490): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/ActivityThread( 5490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5490): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5490): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/ActivityThread( 5490): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5490): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/ActivityThread( 5490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,W/ActivityManager(  882): Unbind failed: could not find connection for android.os.BinderProxy@f01600a
,W/Settings( 1460): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothManagerService(  882): Message: 1
,D/BluetoothManagerService(  882): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 5129): Unit Test app is loaded
I/jxcore-log( 5129): 
,I/Choreographer( 5129): Skipped 294 frames!  The application may be doing too much work on its main thread.
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,D/WifiService(  882): setWifiEnabled: true pid=5129, uid=10569
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  882): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5551 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/Settings( 1460): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1460): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  882): setting operational mode to 1
,I/chromium( 5129): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/Settings( 1460): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.settings.SettingsTrigger$1.onChange:401 android.database.ContentObserver.onChange:130 android.database.ContentObserver.onChange:145 
,W/ResourcesManager( 5551): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5551): Adding HeadsetService
D/AdapterServiceConfig( 5551): Adding A2dpService
D/AdapterServiceConfig( 5551): Adding HidService
D/AdapterServiceConfig( 5551): Adding HealthService
D/AdapterServiceConfig( 5551): Adding PanService
D/AdapterServiceConfig( 5551): Adding GattService
,D/AdapterServiceConfig( 5551): Adding BluetoothMapService
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18b0ec44:true
D/BluetoothAdapterState( 5551): make
,I/bluedroid( 5551): init
,I/BluetoothAdapterState( 5551): Entering OffState
,I/bte_conf( 5551): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5551): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 5551): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5551): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 5551): get_profile_interface socket
I/bluedroid( 5551): get_profile_interface map_client
,I/GKI_LINUX( 5551): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5551): Address is:44:80:EB:7B:5A:05
,D/BluetoothAdapterProperties( 5551): Name is: XT1072
D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  882): Message: 40
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 5551): config_hci_snoop_log
,D/BluetoothManagerService(  882): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  882): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 5551): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5551): Setting state to 11
I/BluetoothAdapterState( 5551): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  882): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 5551): make
,I/BluetoothBondStateMachine( 5551): StableState(): Entering Off State
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=5594 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/HeadsetService( 5551): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 5551): classInitNative: succeeds
,D/BluetoothHeadset(  882): Proxy object connected
D/BluetoothHeadset( 1539): Proxy object connected
,D/BluetoothHeadset( 1504): Proxy object connected
D/HeadsetStateMachine( 5551): make
,I/BluetoothAdapterState( 5551): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 5551): max_hf_connections = 1
I/bluedroid( 5551): get_profile_interface handsfree
,D/HeadsetStateMachine( 5551): Enter Disconnected: -2, size: 0
,D/BluetoothHeadset( 1504): Proxy object connected
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,D/A2dpService( 5551): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 5551): classInitNative: succeeds
I/bluedroid( 5551): get_profile_interface avrcp
D/BluetoothA2dp(  882): Proxy object connected
,D/TCMD    (  493): NL - Read 1008 bytes from update socket.
,D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 1008 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,D/QsoftapCmd(  288): Got softap fwreload command we are passing on
,D/SoftapController(  288): Softap fwReload - Ok
,E/RemoteController( 5551): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 5551): classInitNative: succeeds
,D/A2dpStateMachine( 5551): make
,I/bluedroid( 5551): get_profile_interface a2dp
,I/GKI_LINUX( 5551): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
I/BluetoothHidServiceJni( 5551): classInitNative: succeeds
D/A2dpStateMachine( 5551): Enter Disconnected: -2
,D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring down wlan0
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/HidService( 5551): Received start request. Starting profile...
I/bluedroid( 5551): get_profile_interface hidhost
D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,I/BluetoothHealthServiceJni( 5551): classInitNative: succeeds
,D/HealthService( 5551): Received start request. Starting profile...
,I/bluedroid( 5551): get_profile_interface health
D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,I/BluetoothPanServiceJni( 5551): classInitNative(L105): succeeds
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
,D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  882): InitialState.processMessage what=4
,D/PanService( 5551): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5551): initializeNative(L110): pan
I/bluedroid( 5551): get_profile_interface pan
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
,D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,I/BtGatt.JNI( 5551): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 5551): handleDebugAction() action=null
,D/BtGatt.GattService( 5551): Received start request. Starting profile...
D/BtGatt.GattService( 5551): start()
I/bluedroid( 5551): get_profile_interface gatt
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
D/BtGatt.AdvertiseManager( 5551): advertise manager created
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,D/BluetoothMapService( 5551): Received start request. Starting profile...
,D/BluetoothMapService( 5551): start()
,D/BluetoothMapEmailSettingsLoader( 5551): Found 0 applications
D/BluetoothMapEmailAppObserver( 5551): createReceiver()
,D/BluetoothMapEmailAppObserver( 5551): initObservers()
D/BluetoothMapEmailAppObserver( 5551): getEnabledAccountItems()
,D/BluetoothAdapterService( 5551): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8303416
,D/HeadsetStateMachine( 5551): Proxy object connected
,D/HeadsetStateMachine( 5551): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5551): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterState( 5551): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5551): enable
D/HeadsetStateMachine( 5551): Disconnected process message: 11, size: 0
W/ResourcesManager( 5594): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/GKI_LINUX( 5551): gki_task_entry task_id=0 [BTU] starting
,I/bt_hci_bdroid( 5551): init
I/bt-btu  ( 5551): btu_task pending for preload complete event
,I/bt_vendor( 5551): bt-vendor : init
D/bt_userial_mct( 5551): userial_init
,I/bt_hwcfg( 5551): Starting hciattach daemon
I/bt_hwcfg( 5551): try to set false
,I/bt_hwcfg( 5551): Starting hciattach daemon
I/bt_hwcfg( 5551): try to set true
,I/qcom-bluetooth( 5627): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,E/WifiStateMachine(  882): setWifiState: enabling
,E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Killing 5406:com.motorola.context/u0a8 (adj 15): empty #7
,I/qcom-bluetooth( 5634): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5635): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 5630): Successfully initialized wpa_supplicant
I/wpa_supplicant( 5630): Long line in configuration file truncated
,I/wpa_supplicant( 5630): rfkill: Cannot open RFKILL control device
,D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,I/MDMCTBK (  290): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  290): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): wifi_connect_to_supplicant, current pid is = 290
,I/qcom-bluetooth( 5637): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/MDMCTBK (  290): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  290): wifi_close_sockets: Exit
E/MDMCTBK (  290): Attach monitor thread
,I/qcom-bluetooth( 5638): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/libmdmdetect( 5630): ESOC framework not supported
,E/Diag_Lib( 5630):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 5630): baseband property is set to [msm]
I/libmdmdetect( 5630): ESOC framework not supported
,I/qcom-bluetooth( 5640): /system/etc/init.qcom.bt.sh: LE Power Class: 1 
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_5406/cgroup.procs: No such file or directory
,E/wpa_supplicant( 5630):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5630): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5630): card_info[i].card_state: 0x0
E/wpa_supplicant( 5630): card_info[i].error_code: 0x0
E/wpa_supplicant( 5630): SIM/USIM not ready
E/wpa_supplicant( 5630): Error while reading SIM card status
,D/AuthorizationBluetoothService( 1687): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/wpa_supplicant( 5630): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5630): card_info[i].card_state: 0x0
E/wpa_supplicant( 5630): card_info[i].error_code: 0x0
E/wpa_supplicant( 5630): SIM/USIM not ready
I/wpa_supplicant( 5630): eap_proxy: Card not ready
,I/rmt_storage(  287): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb733b820
I/rmt_storage(  287): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  287): wakelock acquired: 1, error no: 42
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1221348040)
,E/wpa_supplicant( 5630): Line 31: unknown global field '�'.
E/wpa_supplicant( 5630): Line 31: Invalid configuration line '�'.
,I/wpa_supplicant( 5630): rfkill: Cannot open RFKILL control device
,D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,E/wpa_supplicant( 5630): baseband property is set to [msm]
I/libmdmdetect( 5630): ESOC framework not supported
,E/wpa_supplicant( 5630):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 5630): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5630): card_info[i].card_state: 0x0
E/wpa_supplicant( 5630): card_info[i].error_code: 0x0
E/wpa_supplicant( 5630): SIM/USIM not ready
E/wpa_supplicant( 5630): Error while reading SIM card status
,E/wpa_supplicant( 5630): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 5630): card_info[i].card_state: 0x0
E/wpa_supplicant( 5630): card_info[i].error_code: 0x0
E/wpa_supplicant( 5630): SIM/USIM not ready
I/wpa_supplicant( 5630): eap_proxy: Card not ready
,I/wpa_supplicant( 5630): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,I/MDMCTBK (  290): createWifiMonitorThread: Started the wifi monitor thread -1223397280
D/MDMCTBK (  290): wifi_wait_on_socket: Enter monitor thread
,I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1221348040) wakelock released: 1, error no: 0
I/rmt_storage(  287): 
I/rmt_storage(  287): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb733b820
,E/WifiStateMachine(  882): setSuspendOptimizations: 2 true
E/WifiStateMachine(  882): mSuspendOptNeedsDisabled 0
,E/WifiStateMachine(  882): Supplicant connection established
,E/WifiStateMachine(  882): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiConfigStore(  882): Loading config and enabling all networks 
D/MDMCTBK (  290): reply_len: 83 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
I/wpa_supplicant( 5630): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 5630): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-AVOID-FREQ ra
D/MDMCTBK (  290): Event received = CTRL-EVENT-AVOID-FREQ ra
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/WifiNative-HAL(  882): Setting external_sim to 1
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dd489c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x1702
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 5630): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=5648 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dd483c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x1016fe
I/WifiNative-HAL(  882): Could not start hal
D/WifiStateMachine(  882): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  882): handleScreenStateChanged Exit: true
,D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiScanningService(  882): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa237c9cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x2016fa
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring up p2p0
D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=-2ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2p socket connection successful
,D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/WifiNative-HAL(  882): p2pGetDeviceAddress
D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
D/WifiP2pService(  882): MCC mode enabled 0
D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
D/WifiP2pService(  882): InactiveState
I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 24ms
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): set country code US
E/WifiStateMachine(  882): set frequency band 2
D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  882): InactiveState{ when=-10ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 21.882ms
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  882): do suspend false
,E/SharedPreferencesImpl(  882): Couldn't create directory for SharedPreferences file shared_prefs/android_preferences.xml
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.460ms
,W/ResourcesManager( 5648): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Killing 5430:com.google.android.gm/u0a63 (adj 15): empty #7
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,W/libprocessgroup(  882): failed to open /acct/uid_10063/pid_5430/cgroup.procs: No such file or directory
,V/AlarmManager(  882): send {19bbc31a, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  882): done {19bbc31a, *alarm*:com.android.server.WifiManager.action.START_SCAN} [18ms]
,D/Checkin ( 3140): publish the event [tag = MOT_DEVICE_STATS_L1 event name = SettingLogs]
,D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,I/qcom-bluetooth( 5677): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 44:80:eb:7b:5a:05 
,I/qcom-bluetooth( 5678): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/bt_hwcfg( 5551): bluetooth satus is on
,D/bt_userial_mct( 5551): userial_open(port:0)
,I/bt_userial_vendor( 5551): Done intiailizing UART
,I/bt_userial_vendor( 5551): Done intiailizing UART
I/bt_userial_mct( 5551): CMD=53, EVT=53, ACL_Out=54, ACL_In=54
I/bt_vendor( 5551): Bluetooth Firmware and smd is initialized
,I/bt-btu  ( 5551): btu_task received preload complete event
,D/bt_userial_mct( 5551): Entering userial_read_thread()
,I/        ( 5551): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5551): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5551): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5551): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5551): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5551): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5551): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5551): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5551): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5551): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5551): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5551): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5551): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5551): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5551): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 5551): BTM_SecRegister:p_cb_info->p_le_callback == 0xa6d95d85 
E/bt-btm  ( 5551): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa6d95d85 
,E/bt-btif ( 5551): Calling BTA_HhEnable
E/bt-btif ( 5551): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 5551): Address is:44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): Bluetooth Adapter name changed to XT1072
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 0 f
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 0 f
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 1 f
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 1 f
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 2 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 2 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 3 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 4 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 5 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 6 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 7 2
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 7 2
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 8 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 9 0
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 10 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 11 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  290): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  290): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  493): NL - Read 56 bytes from update socket.
,D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,D/BluetoothAdapterProperties( 5551): Name is: XT1072
,D/BluetoothAdapterProperties( 5551): Scan Mode:20
D/BluetoothAdapterProperties( 5551): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5551): Adding bonded device:7C:F9:0E:37:96:AB
D/BluetoothAdapterProperties( 5551): Adding bonded device:E0:DB:10:14:E2:C0
D/BluetoothAdapterProperties( 5551): Adding bonded device:58:2A:F7:ED:96:BE
,E/BluetoothRemoteDevices( 5551): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:37:96:AB, value is empty for type: 10
,E/BluetoothRemoteDevices( 5551): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
,E/BluetoothRemoteDevices( 5551): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BluetoothManagerService(  882): Stored Bluetooth name: XT1072
,D/bte_conf( 5551): Device ID record 1 : primary
D/bte_conf( 5551):   vendorId            = 000f
D/bte_conf( 5551):   vendorIdSource      = 0001
D/bte_conf( 5551):   product             = 1200
D/bte_conf( 5551):   version             = 1436
,D/bte_conf( 5551):   clientExecutableURL = 
D/bte_conf( 5551):   serviceDescription  = 
D/bte_conf( 5551):   documentationURL    = 
,D/bte_conf( 5551): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5551): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5551): ScanMode =  20
D/BluetoothAdapterProperties( 5551): State =  11
D/BluetoothAdapterProperties( 5551): Setting state to 12
I/BluetoothAdapterState( 5551): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  882): Message: 60
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  882): Broadcasting onBluetoothStateChange(true) to 5 receivers.
,I/BluetoothAdapterState( 5551): Entering On State
,D/BluetoothHeadset(  882): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1504): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 5551): Scan Mode:21
,D/BluetoothAdapterProperties( 5551): Discoverable Timeout:120
,D/BluetoothHeadset( 1504): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1539): onBluetoothStateChange: up=true
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dd48fc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x10169e
I/WifiNative-HAL(  882): Could not start hal
E/WifiStateMachine(  882): [1,457,707,007,880 ms] noteScanEnd no scan source
,D/BluetoothA2dp(  882): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  882): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  882): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 5551): onReceive
D/BluetoothMapService( 5551): STATE_ON
,D/BluetoothMapMasInstance( 5551): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 5551): MAS initSocket()
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@16a34c6a sup_state=SCANNING debouncing=false
D/BluetoothManagerService(  882): Message: 40
D/BluetoothManagerService(  882): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/Telecom ( 1504): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothPanServiceJni( 5551): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
W/BluetoothAdapter( 5551): getBluetoothService() called with no BluetoothManagerCallback
,E/bt_mct  ( 5551): hci lib postload completed
,D/BluetoothMapMasInstance( 5551): Accepting socket connection...
,D/HeadsetStateMachine( 5551): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 5551): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 5551): mNumber:  mType: 128
D/HeadsetStateMachine( 5551): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 5551): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 5594): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/AuthorizationBluetoothService( 1687): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapter( 5551): getBluetoothService() called with no BluetoothManagerCallback
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:288 vsyncs) (2:1118)
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3165b6d4:true
,D/LocalBluetoothProfileManager( 5594): Adding local A2DP profile
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5594): Adding local HEADSET profile
,D/BluetoothManagerService(  882): Message: 30
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5551): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  882): Message: 30
,I/BtOppRfcommListener( 5551): Accept thread started.
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5594): Adding local MAP profile
D/BluetoothMap( 5594): Create BluetoothMap proxy object
,D/BluetoothManagerService(  882): Message: 30
,E/WifiConfigStore(  882): will read network variables netId=0
,D/BluetoothManagerService(  882): Message: 30
,D/LocalBluetoothProfileManager( 5594): LocalBluetoothProfileManager construction complete
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,D/DockEventReceiver( 5594): finishStartingService: stopping service
E/WifiConfigStore(  882): will read network variables netId=0
,D/BluetoothA2dp( 5594): Proxy object connected
D/A2dpProfile( 5594): Bluetooth service connected
,D/BluetoothHeadset( 5594): Proxy object connected
,D/HeadsetProfile( 5594): Bluetooth service connected
,D/BluetoothInputDevice( 5594): Proxy object connected
,D/HidProfile( 5594): Bluetooth service connected
,I/wpa_supplicant( 5630): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  290): Event received = Trying to associate with
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/BluetoothPan( 5594): BluetoothPAN Proxy object connected
D/PanProfile( 5594): Bluetooth service connected
E/wpa_supplicant( 5630): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,D/BluetoothMap( 5594): Proxy object connected
,D/MapProfile( 5594): Bluetooth service connected
D/BluetoothMap( 5594): getConnectedDevices()
,D/BluetoothPbap( 5594): Proxy object connected
,D/PbapServerProfile( 5594): Bluetooth service connected
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,D/TCMD    (  493): NL - Read 312 bytes from update socket.
,D/TCMD    (  493): NL - message type is RTM_NEWLINK
,D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 180 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 68 bytes from update socket.
,D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,D/TCMD    (  493): NL - Read 80 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 80 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
,D/TCMD    (  493): Listening for incoming client connection request
D/TCMD    (  493): NL - Read 68 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5630): wlan0: Associated with f4:f2:6d:22:99:3e
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with f4:f2:6d
,D/MDMCTBK (  290): Event received = Associated with f4:f2:6d
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 5630): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5630): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  290): Event received = WPA: Key negotiation com
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290):  STA Connected !!
,D/TCMD    (  493): NL - Read 1004 bytes from update socket.
D/TCMD    (  493): NL - message type is RTM_NEWLINK
D/TCMD    (  493): Listening for incoming client connection request
E/MDMCTBK (  290): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2422, reply_len: 4, ret: 0
D/MDMCTBK (  290): get_freq !!, resp=2422
I/MDMCTBK (  290): get_freq !!, Strip data
I/MDMCTBK (  290): get_freq !!, band = 2, freq = 2422
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=0,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,UpdateWifiBand band=2, current_band=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, Wifi Band changed, call setWifiCutback.
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
,I/MDMCTBK (  290): set_property_value, Values updated in the property=0,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 0, wlan0 = 0, data=0
I/MDMCTBK (  290): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  290): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
,I/MDMCTBK (  290): get_property_value, Values read from property=0,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223381496
I/MDMCTBK (  290): return from set_get_from_wpa_supplicant
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  290): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  290): , reply_len: 3, ret: 0
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/MDMCTBK (  290): MdmCutbackHndler, resp=OK
E/MDMCTBK (  290): 
D/MDMCTBK (  290): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 0
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 1
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dd48ec
,D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x100f12
I/WifiNative-HAL(  882): Could not start hal
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): calculateWifiScore() report new score 60
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,D/ConnectivityService(  882): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 5630): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 5630): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2239f785 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2239f785 target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 5717): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 5717): version 5.5.6 starting
,E/DHCPCD  ( 5717): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 5717): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 5717): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 5717): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5717): wlan0: discarding expired lease
I/DHCPCD  ( 5717): wlan0: broadcasting for a lease
D/DHCPCD  ( 5717): wlan0: sending DISCOVER (xid 0xcb5e310b), next in 3.90 seconds
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=339, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2362000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310125, SEQNUM=4352, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-95, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 5551): Disconnected process message: 10, size: 0
,I/DHCPCD  ( 5717): wlan0: offered 192.168.1.112 from 192.168.1.1
D/DHCPCD  ( 5717): wlan0: sending REQUEST (xid 0xcb5e310b), next in 4.14 seconds
,I/DHCPCD  ( 5717): wlan0: acknowledged 192.168.1.112 from 192.168.1.1
,I/DHCPCD  ( 5717): wlan0: leased 192.168.1.112 for 172800 seconds
D/DHCPCD  ( 5717): wlan0: adding IP address 192.168.1.112/24
D/DHCPCD  ( 5717): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 5717): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 5717): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 5717): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason BOUND
D/TCMD    (  493): NL - Read 60 bytes from update socket.
D/TCMD    (  493): NL - ignore NL message, type = 20
D/TCMD    (  493): Listening for incoming client connection request
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.112
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  882): Adding iface wlan0 to network 100
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
,E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=true scanperiod=20000
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  882): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882): Setting tx/rx TCP buffers to 131072,262144,3145728,4096,221184,3145728
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.112/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1936): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{14ee2944 u0 com.google.android.calendar/com.android.calendar.alerts.AlertService}
,I/ActivityManager(  882): Killing 5219:com.google.process.gapps/u0a16 (adj 15): empty #7
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Mar 2016 14:36:53 GMT], X-Android-Received-Millis=[1457707010562], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457707010370]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
,D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
I/ActivityManager(  882): Killing 3205:com.google.android.calendar/u0a49 (adj 15): empty #8
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1936): CM callback handler got msg 524290
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_5219/cgroup.procs: No such file or directory
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  882): failed to open /acct/uid_10049/pid_3205/cgroup.procs: No such file or directory
,I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5129): isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,V/io.jxcore.node.JXcoreExtension( 5129): isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,I/jxcore-log( 5129): INFO testUtils BLE multiple advertisement not supported
I/jxcore-log( 5129): 
,I/jxcore-log( 5129): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5129): 
,I/chromium( 5129): [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2dd48ec
D/wifi    (  882): halHandle = 0x0, mVM = 0xb74e8310, mCls = 0x1a52
I/WifiNative-HAL(  882): Could not start hal
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/AndroidRuntime( 5792): 
D/AndroidRuntime( 5792): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5792): CheckJNI is OFF
,D/AndroidRuntime( 5792): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10569 user=-1: uninstall pkg
,I/ActivityManager(  882): Killing 5129:com.test.thalitest/u0a569 (adj 0): stop com.test.thalitest
,W/PackageSettings(  882): Skipping PackageSetting{315ec22f com.example.hello/10568} due to missing metadata
,I/WindowState(  882): WIN DEATH: Window{25ba5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  882): Client connection lost with reason: 4
,W/ActivityManager(  882): Force removing ActivityRecord{65f6b u0 com.test.thalitest/.MainActivity t9}: app died, no saved state
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  882): Spurious death for ProcessRecord{4bcf9a6 5129:com.test.thalitest/u0a569}, curProc for 5129: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10569 user=0: pkg removed
,I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1687): Ignoring removeGeofence because network location is disabled.
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 3140): Explicit concurrent mark sweep GC freed 6015(312KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 940us total 80.280ms
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5811 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
,I/art     ( 1556): Explicit concurrent mark sweep GC freed 7535(545KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 512us total 122.855ms
,I/Decoder ( 1409): createOrResetDecoder
,D/OtaApp  ( 2629): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2629): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2629): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2629): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2629): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2629): publish the event [tag = MOT_OTA event name = LOG]
,I/ConfigService( 1687): onCreate
,W/InputMethodManagerService(  882): Got RemoteException sending setActive(false) notification to pid 5129 uid 10569
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/art     (  882): Explicit concurrent mark sweep GC freed 53051(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 20MB/31MB, paused 5.458ms total 216.884ms
,I/art     (  882): WaitForGcToComplete blocked for 210.039ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
,D/VoicemailCleanupService( 5811): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5844 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
,I/ContactLocale( 5811): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  882): Killing 5490:com.google.android.gms:car/u0a16 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SFPerfTracer(  278):      triggers: (rate: 13:411) (compose: 0:1) (post: 0:1) (render: 0:2) (5:1041 frames) (6:1137)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7ef1c58): 0:16)* (DimLayer (0xb7f75448): 0:6)* (StatusBar (0xb7f7ca38): 0:160) (NavigationBar (0xb7f7fea8): 0:34) (com.android.systemui.ImageWallpaper (0xb7f835f0): 0:6)* (Starting com.test.thalitest (0xb7f4fd78): 0:39)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb7fa4818): 0:46)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7f4fd78): 6:10) 
,I/art     (  882): Explicit concurrent mark sweep GC freed 7218(387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 8.466ms total 207.759ms
,D/TaskPersister(  882): removeObsoleteFile: deleting file=9_task.xml
,D/TaskPersister(  882): removeObsoleteFile: deleting file=8_task.xml
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_5490/cgroup.procs: No such file or directory
,W/asset   ( 5844): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5844): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Launcher( 1556): Deferring update until onResume
W/ResourcesManager( 5844): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5866 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 5352:com.android.vending/u0a32 (adj 15): empty #7
,W/ContextImpl( 5866): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/AndroidRuntime( 5792): Shutting down VM
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_5352/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1936): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1936): Clearing selected account for com.test.thalitest
,I/LocationSettingsChecker( 1936): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1936): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1687): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1687): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1936): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1936): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1936): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1936): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1936): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1936): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1936): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1936): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1936): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1936): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1936): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1936): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1936): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1936): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1936): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5892 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 1936): doRemovePackageData com.test.thalitest
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:37000 mC
,I/ActivityManager(  882): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5913 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Launcher( 1556): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f9d3ff0 new=com.google.android.velvet.VelvetApplication@3f9d3ff0
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5932 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/art     ( 1687): Explicit concurrent mark sweep GC freed 31545(2009KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 13MB/21MB, paused 2.037ms total 87.722ms
,E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e1762c2)
,E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@341858d3)
E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fa04c10)
E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32cd7309)
E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c7ce90e)
E/DataBuffer( 1687): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f05af2f)
,I/ActivityManager(  882): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5959 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 5913): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5913): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5967 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1460): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GAv4    ( 5932): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5932):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5932):   adb logcat -s GAv4
,W/GAv4    ( 5932): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5932): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5932): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5932): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5932): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5932): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 5932): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
