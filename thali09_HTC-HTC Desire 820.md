#### Test 50388019b17f598_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  907): Waited long enough for: ServiceRecord{42670240 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=2644 uid=10090 gids={50090, 3003, 5012, 1028}
,I/ActivityManager(  907): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
--------- beginning of /dev/log/main
I/WorldClock.Global( 2644): isHtcDevice = true
D/PMS     (  907): acquireWL(42a4d210): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 2644 10090 null
E/Prism.WidgetManager( 1251): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1251): onLoadItems() -
I/Prism.ItemManager( 1251): loadItems() com.htc.launcher.pageview.WidgetManager@41cb9d70 -
W/WorldClock.AlarmService( 2644): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
I/WorldClock.AlarmUtils( 2644): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmUtils( 2644): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 2644): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1108): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(42a4d210): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/WorldClock.Global( 2644): isHtcDevice = true
I/ActivityManager(  907): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2666 uid=10091 gids={50091, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=2337
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2337:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2337
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/OmaCPPushReceiverV2( 2666): initialCheck: sku=99, result=false
D/Process (  907): killProcessQuiet, pid=2349
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2686 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  907): Killing 2349:com.htc.aurora/u0a49 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  907): Resuming delayed broadcast
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2349
D/Process (  907): killProcessQuiet, pid=2364
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2701 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  907): Killing 2364:com.htc.aurora:remote/u0a49 (adj 15): empty #17
D/CustomizationManager( 2656): ====startRecUseTime====
D/htc.customization.log.level( 2656):  is 
W/CustomizationLogLevel( 2656): Level value is invalid, use default level 2
I/ActivityManager(  907): Recipient 2364
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 2701): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=2701 dbg=false s=true
I/DeviceManagement( 2701): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 2701): WorkflowService: Starting workflow service
I/ActivityManager(  907): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 2701): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41c573f0] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 2701): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2701): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 2701): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2701): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 2701): BackgroundController: *** Update after boot...
I/DeviceManagement( 2701): SessionStateController: Checking invariants...
D/CustomizationManager( 2656):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2656): Parsing tag item name = HTC__031
D/PhoneApp( 1219): EVENT_QUERY_MO_PACKAGES
V/CustomizationCIDLoader( 2656): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2656): Parsing tag category name = system
I/CustomizationCIDLoader( 2656): Parsing tag category name = application
D/PhoneApp( 1219): -- N1 =0
I/CustomizationCIDLoader( 2656): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2656): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2656): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2656): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2656): Parsing tag category name = Settings
D/CustomizationManager( 2656):  Read CID file spent 0.107 (s)
D/CustomizationManager( 2656):  All configurations done spent 0.108 (s)
D/PhoneApp( 1219): -- N2 =0
D/PhoneApp( 1219): -- N3 =0
W/HtcNativeFlag( 2656): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2656): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2656): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2656): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
W/asset   (  907): Copying FileAsset 0x69c76738 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1114964792
I/DeviceManagement( 2701): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 2701): SessionStateController: Checking invariants...
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2656
D/PMS     (  907): acquireHCC(42732a48): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4272a2b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
E/cutils-trace( 2656): Error opening trace file: No such file or directory (2)
I/SocialFeedProvider( 1251): +onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42104a58
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  907): acquireWL(427067d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2720 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1251): [trimMemory] 20
W/asset   ( 2720): Copying FileAsset 0x5d854c88 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/DeviceManagement( 2701): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
V/WebViewChromiumFactoryProvider( 2720): Binding Chromium to main looper Looper (main, tid 1) {41c2ae68}
I/LibraryLoader( 2720): Expected native library version number "",actual native library version number ""
I/chromium( 2720): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2720): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(42683630): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(42674ef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424f4210:true
D/BluetoothAdapter( 2720): 1103366240: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): releaseWL(42683630): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2720): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2720): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2720): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2720): Local Branch: 
I/Adreno-EGL( 2720): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2720): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2720):                  aa63bbd948f41d15fc72f585e
W/chromium( 2720): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/DeviceManagement( 2701): Perf: *** Cache update - start...
I/DeviceManagement( 2701): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 2701): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 2701): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 2701): Perf: Scan enabled apps - start...
W/dalvikvm( 2720): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2720): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2720): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2720): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2720): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2720): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2720): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2720): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2720): CordovaWebView is running on device made by: HTC
I/DeviceManagement( 2701): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
I/ActivityManager(  907): Waited long enough for: ServiceRecord{427aad98 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2755 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
W/AwContents( 2720): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +274ms
W/ResourceType( 2720): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2720): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c71ba8, mServedView=org.apache.cordova.engine.SystemWebView{41c37b80 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Disable input method client, pid=1251
I/InputMethodManagerService(  907): Enable input method client, pid=2720
W/AwContents( 2720): nativeOnDraw failed; clearing to background color.
D/PMS     (  907): releaseWL(427067d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/dalvikvm( 1960): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
D/PMS     (  907): acquireWL(4217d420): PARTIAL_WAKE_LOCK  Icing 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 2755): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  907): releaseWL(4217d420): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/HtcModeClient( 1482): handler message = 4011
E/HtcModeClient( 1482): Check connection and retry 3 times.
I/ActivityManager(  907): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
D/PMS     (  907): acquireWL(425048c0): PARTIAL_WAKE_LOCK  Icing 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2755, uid=10107, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2755, uid=10107, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2755, uid=10107, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2755, uid=10107, userID:0
I/Icing   ( 1960): Storage manager: low false usage 2.00MB avail 7.43GB capacity 7.85GB
W/dalvikvm( 1960): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
E/AndroidProtocolHandler( 2720): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2720): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2720): Set native->JS mode to OnlineEventsBridgeMode
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
D/jxcore_app_log( 2720): JniHelper::setJavaVM(0x41706010), pthread_self() = 1658344104
D/JX-Cordova( 2720): jxcore cordova android initializing
I/Gmail   ( 2755): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2755): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2755): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2755): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
W/jxcore-log( 2720): Initializing JXcore engine
W/jxcore-log( 2720): JXcore engine is ready
W/jxcore-log( 2720): Starting JXcore engine
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
I/Icing   ( 1960): updateResources: need to parse f{com.google.android.gms}
I/DeviceManagement( 2701): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/DeviceManagement( 2701): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/Icing   ( 1960): Internal init done: storage state 0
I/DeviceManagement( 2701): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2701): Perf: Scan enabled apps - complete: 819 ms
I/DeviceManagement( 2701): Perf: *** Enabled app cache update - complete: 821 ms
I/DeviceManagement( 2701): Perf: *** Config cache update - start...
I/DeviceManagement( 2701): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2701): ConfigCacheController: *** Updating stale config cache entries...
W/jxcore-log( 2720): Platform android
W/jxcore-log( 2720): 
W/jxcore-log( 2720): Process ARCH arm
W/jxcore-log( 2720): 
I/DeviceManagement( 2701): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2701): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2701): AlarmController: Scheduling TTL alarm for: 2015.11.24 at 21:02:33.348 CET (due to: com.htc.aurora)
I/Icing   ( 1960): Post-init done
I/DeviceManagement( 2701): Perf: *** Config cache update - complete: 29 ms
I/DeviceManagement( 2701): Perf: *** Cache update - complete: 852 ms
I/DeviceManagement( 2701): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41c573f0]
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2701, uid=10098, userID:0
I/DeviceManagement( 2701): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
I/jxcore-log( 2720): JXcore Cordova bridge is ready!
I/jxcore-log( 2720): 
W/jxcore-log( 2720): JXcore engine is started
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2755, uid=10107, userID:0
D/Process (  907): killProcessQuiet, pid=2380
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2380:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2380
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/jxcore-log( 2720): >> HTC-HTC Desire 820
E/jxcore-log( 2720): 
I/jxcore-log( 2720): Total memory 1964650496
I/jxcore-log( 2720): 
I/jxcore-log( 2720): Free memory 743362560
I/jxcore-log( 2720): 
I/jxcore-log( 2720): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2720): 
I/jxcore-log( 2720): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2720): 
I/jxcore-log( 2720): userPath [ 'www' ]
I/jxcore-log( 2720): 
I/jxcore-log( 2720): Size 720 1184
I/jxcore-log( 2720): 
I/jxcore-log( 2720): Screen Brightness 142
I/jxcore-log( 2720): 
E/jxcore-log( 2720): Dummy Error Log.
E/jxcore-log( 2720): 
D/Process (  907): killProcessQuiet, pid=2394
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(425048c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Killing 2394:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2394
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2805 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/jxcore-log( 2720): getBuffer is called!!!!
I/jxcore-log( 2720): 
,I/htcbackup-core( 2805): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 2805): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2805): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 2701): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 2701): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.lockscreen, com.htc.cirmodule, com.htc.autobot.cargps.provider, com.htc.feedback, com.htc.backupreset, com.qualcomm.privinit, com.htc.checkinprovider, android, com.htc.mirrorlinkserver, com.android.keychain, com.android.location.fused, com.qualcomm.timeservice, com.htc.home.personalize, com.android.inputdevices, com.htc.android.htcloglevel, com.htc.backup, com.htc.guide, com.htc.android.htcsetupwizard, com.android.providers.settings, com.htc.drive.activator, com.htc.usage, com.android.settings, com.htc.smartdim, com.android.CSDFunctionG, com.htc.htcpowermanager]
,I/DeviceManagement( 2701): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 2701): WorkflowService: Starting workflow service
I/DeviceManagement( 2701): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41f58550] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2701): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2701): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 2701): SessionStateController: Checking invariants...
,W/ContextImpl( 2805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/ActivityManager(  907): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41caabc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.htc.backup 2 8 5 15
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/DeviceManagement( 2701): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41cae528 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DeviceManagement( 2701): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41f58550]
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/ActivityManager(  907): Resuming delayed broadcast
I/DeviceManagement( 2701): WorkflowService: Stopping workflow service
I/RemoteViews.Performance( 1108): com.htc.backup 1 3 7 4
I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2827 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/RemoteViews.Performance( 1108): com.htc.backup 1 1 1 4
I/RemoteViews( 1108): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1108): com.htc.backup 1 1 1 4
I/RemoteViews.Performance( 1108): com.htc.backup 1 6 20 21
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(42732a48): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4272a2b8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/dalvikvm( 2827): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2827): VFY: unable to resolve instance field 46
,W/dalvikvm( 2827): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 2827): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 2827): MmsConfig.loadMmsSettings
,I/htcbackup-core( 2805): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
,V/JNIHelp ( 2827): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
V/AlarmManager(  907): sending alarm PendingIntent{42791de0: PendingIntentRecord{42a0f5d0 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=13, w=1440901414353, Int=604800000
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,W/dalvikvm( 2805): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/MmsCustomizationProvider( 2485): query uri: content://htc-mms-customization/mms-ua/ua_string
,I/RemoteViews.Performance( 1108): com.htc.backup 1 3 15
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1108): com.htc.backup 1 1 0 4
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1108): com.htc.backup 1 1 0 4
,I/RemoteViews( 1108): com.htc.backup (true,33751552)
,D/MmsCustomizationProvider( 2485): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/RemoteViews.Performance( 1108): com.htc.backup 3 0 1 4
,I/RemoteViews.Performance( 1108): com.htc.backup 1 13 21
,I/GAV2    ( 2586): Thread[GAThread,5,main]: No campaign data found.
I/Babel   ( 2827): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 2827): MmsConfig.loadFromDatabase
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2827, uid=10111, userID:0
,I/GAv4-SVC( 1960): Google Analytics 8.3.01 is starting up.
E/Babel   ( 2827): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 2827): MmsConfig.loadFromResources
,W/Settings( 2827): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 2827): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 2827): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2827, uid=10111, userID:0
,D/UPolicy ( 2805): IUserBehaviorLoggingService reference is gotten !
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2827, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2827, uid=10111, userID:0
V/Babel   ( 2827): babel boot account: thalitester@gmail.com
V/Babel   ( 2827): babel boot account: SMS
,I/ActivityManager(  907): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2858 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=2407
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2407:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ProviderInstaller( 2827): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  907): Recipient 2407
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  907): sending alarm PendingIntent{42644598: PendingIntentRecord{4267a1d0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46802, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42642818: PendingIntentRecord{42678d98 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46880, Int=0
,I/ActivityManager(  907): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2880 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  907): killProcessQuiet, pid=2429
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2429:com.htc.video/u0a57 (adj 15): empty #17
,D/ResetNotifyBootCompleteReceiver( 1219): Receive bootcomplete intent
,W/ContextImpl( 1219): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/HtcCupdXmlParser( 2880): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  907): Recipient 2429
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2896 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/ActivityThread( 2880): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,D/AppTag  ( 2896): getInstance(Context context)
,D/AppTag  ( 2896): getInstance(Context context)
,D/AppTag  ( 2896): onCreate()
,D/QXDM2SD:HtcNative( 1219): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/HtcCupdXmlParser( 2880): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2910 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=2447
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2447:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2447
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AlarmManager(  907): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  907): [AlarmQueuing] post alarm-list load task
,V/Settings:HtcSettingsApplication( 2910): [2910/2910] onCreate()
I/AlarmManager(  907): [AlarmQueuing] init alarm queuing list
W/ContextImpl( 2910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2922 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2935 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=2503
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2503:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2503
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41fa81e8
,D/HtcFingerPrintQuickLaunchProvider( 2935): -onCreate()
,V/Settings:HtcSettingsApplication( 2935): [2935/2935] onCreate()
,D/Process (  907): killProcessQuiet, pid=2546
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42495f88
W/ContextImpl( 2935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  907): Killing 2546:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=2558
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@4270d1b8
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  907): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  907): Killing 2558:com.htc.showme/u0a83 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2558
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2546
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
,D/TetherSettings( 2935): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2935): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2935): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2935): Cust_ConnectToPC   : spcsc>false
D/        ( 2935): Cust_ConnectToPC   : IPT>true
,D/        ( 2935): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2935): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2935): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2935): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2935): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2935): Cust_ConnectToPC   : spcsc>false
D/        ( 2935): Cust_ConnectToPC   : IPT>true
D/        ( 2935): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2935): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2935): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2935): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2935): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 2935): setISNotification
,D/SmartNS_Utility( 2935): usb_cable_connect = 1
,D/SmartNS_Utility( 2935): usb_denied = 0
,I/SmartNS_PSService( 2935): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (2935/1000)
D/SmartNS_Utility( 2935): usb_cable_connect = 1
D/SmartNS_Utility( 2935): usb_denied = 0
I/SmartNS_PSService( 2935): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (2935/1000)
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  907): killProcessQuiet, pid=2572
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2572:com.htc.updater/u0a85 (adj 15): empty #17
,I/RemoteViews( 1108): com.android.settings (true,33751552)
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41c88408 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.android.settings 2 6 0 10
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2572
,I/RemoteViews( 1108): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1108): com.android.settings 2 0 10
,I/ActivityManager(  907): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2950 uid=9987 gids={49987}
,I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4273fc70, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4273fc70, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4259fad8
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@4229f580
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@4273fc70
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4273fc70, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42633640 u0 ReceiverList{4262b408 907 system/1000/u0 local:425dea10}}
,D/NfcUiccLockService( 2950): -- To check whether previous opened channel needed to be closed ...
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 3
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4273fc70, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4259fad8
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@4229f580
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@4273fc70
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  907): killProcessQuiet, pid=2293
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2965 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  907): Killing 2293:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2293
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2977 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=2601
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2601:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2601
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42674ef8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,E/YouTube ( 2977): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2977): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2977): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2977): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2977/10168)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2977): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2977): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2977): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2977): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2977): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.youtube (pid 2977): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 2977): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 2977): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.youtube (2977/10168)
,I/GoogleConversionPing( 2977): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448385976&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/libc    ( 2977): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2977): [NET] getaddrinfo-,err=8
,D/libc    ( 2977): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2977): [NET] getaddrinfo-, 1
D/libc    ( 2977): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2977): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 2977): Error sending ping
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2977): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2977): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2977): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/MediaRouter( 2977): getSelectedRoute
,D/YouTube ( 2977): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2977/10168)
D/YouTube ( 2977): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 2977): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2977): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2644
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2644:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2644
,W/dalvikvm( 1960): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1960): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1960): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1960): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1960): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1960): Beginning GMS chimera module scan
,W/asset   ( 1960): Copying FileAsset 0x64e9f118 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/dalvikvm( 1960): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ChimeraCfgMgr( 1960): Beginning module configuration check
,D/ChimeraCfgMgr( 1960): Module APKs unchanged, check complete
I/ActivityManager(  907): Resuming delayed broadcast
,E/dalvikvm( 1960): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1960): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1960/10029)
D/PMS     (  907): acquireWL(429b3938): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1960): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1960): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1960): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1960): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  907): acquireWL(426e6c88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429b3938): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1960): COMPAT: Multi user not supported
,D/GCM     ( 1342): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  907): acquireWL(4276d9c8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1960): Checkin interval check for package: unspecified last checkin: 1448381099201 min interval config: 0 actual interval: 4877269
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1342/10029)
I/GCoreUlr( 1960): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1199): DispatchingService.onCreate()
I/CheckinService( 1960): Disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
,D/SystemUpdateService( 1960): onCreate
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
,D/SystemUpdateService( 1960): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1960): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
D/PMS     (  907): acquireWL(425173b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1960, uid=10029, userID:0
,V/AuthZen ( 1960): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1960, uid=10029, userID:0
D/PMS     (  907): acquireWL(428f8738): PARTIAL_WAKE_LOCK  Icing 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1960): Checking schedule, now: 1448385976554 next: 1448904036177
,I/CheckinService( 1960): active receiver: disabled
I/SystemUpdateService( 1960): cancelUpdate (empty URL)
,I/SystemUpdateService( 1960): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,I/GCoreUlr( 1199): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 1960): Handling event: android.intent.action.BOOT_COMPLETED
,D/PMS     (  907): releaseWL(428f8738): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/PMS     (  907): releaseWL(426e6c88): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 1960): onDestroy
D/PMS     (  907): releaseWL(4276d9c8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1960): Using Auth Proxy for data requests.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1199, uid=10029, userID:0
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1960): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1960): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 1960): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1960): Fetching signing key...
,I/AuthZen ( 1960): Signing key fetched successfully!
,I/GCoreUlr( 1199): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1199): Unbound from all location providers
D/PMS     (  907): acquireWL(4272be98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4272be98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425173b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,W/BaseAppContext( 1960): Using Auth Proxy for data requests.
,I/ActivityManager(  907): Resuming delayed broadcast
,D/AuthZenTransactionCache( 1960): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1960): Clearing transaction cache
D/PMS     (  907): acquireWL(429d0c08): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1960 10029 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(429d0bb8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1960 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1199): DispatchingService.onDestroy()
,I/GCoreUlr( 1199): Stopping handler for UlrDispSvcFast
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
D/PMS     (  907): acquireWL(429d0b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429d0b68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1199): Unbound from all location providers
,D/PMS     (  907): releaseWL(429d0c08): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  907): releaseWL(429d0bb8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
I/ActivityManager(  907): Resuming delayed broadcast
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1342): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,W/Auth    ( 1342): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/PMS     (  907): acquireWL(4278f000): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1342 10029 null
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  907): releaseWL(4278f000): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1960): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1342): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3065 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42746908): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42746908): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3065, uid=10074, userID:0
,D/Finsky  ( 3065): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3065/10074)
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3065/10074)
,D/Finsky  ( 3065): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3065): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3065): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3065, uid=10074, userID:0
,D/Volley  ( 3065): [276] DiskBasedCache.clear: Cache cleared.
,D/Process (  907): killProcessQuiet, pid=2666
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Ads     ( 3065): Skipping gmscore version check
,D/Volley  ( 3065): [283] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  907): Killing 2666:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2666
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022583
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022835
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023142
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023329
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023356
,D/Finsky  ( 3065): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3065): [1] Libraries$2.run: Finished loading 1 libraries.
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028904
V/AlarmManager(  907): sending alarm PendingIntent{420d9dc0: PendingIntentRecord{4272a3f8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20404, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42653df0: PendingIntentRecord{426b0090 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=46762, Int=259200000
,D/Finsky  ( 3065): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1294): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1294): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
V/AlarmManager(  907): sending alarm PendingIntent{41efb6f0: PendingIntentRecord{425f3c08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49514, Int=0
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
V/AlarmManager(  907): sending alarm PendingIntent{41edca88: PendingIntentRecord{426d2e68 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448362800000, Int=86400000
,D/TetherSettings( 2935): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2935): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2935): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2935): Cust_ConnectToPC   : spcsc>false
D/        ( 2935): Cust_ConnectToPC   : IPT>true
D/        ( 2935): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2935): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2935): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2935): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2935): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 2935): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  907): Resuming delayed broadcast
,D/Finsky  ( 3065): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SmartNS_PSService( 2935): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2935): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2935):  defaultType:0
W/ContextImpl( 2935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/WeatherUtility( 1108): can't get weather sync account
,I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3104 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1108): request cur loc, but there is no sys cur
,D/browser ( 3104): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3104): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3104): Loading: swewebviewchromium
,I/LibraryLoader( 3104): Time to load native libraries: 44 ms (timestamps 7666-7710)
,I/LibraryLoader( 3104): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3104): Initializing chromium process, renderers=9
,I/LibraryLoader( 3104): Expected native library version number "",actual native library version number ""
,I/chromium( 3104): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/GAV2    ( 2755): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1482): handler message = 4011
,E/HtcModeClient( 1482): Check connection and retry 4 times.
,W/chromium( 3104): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3104): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3104): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3104): Local Branch: 
I/Adreno-EGL( 3104): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3104): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3104):                  aa63bbd948f41d15fc72f585e
,D/Process (  907): killProcessQuiet, pid=2686
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Killing 2686:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1263): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1482): SIM state: ABSENT
I/SIMStateChangeReceiver( 1482): phoneType = 0
,I/SIMStateChangeReceiver( 1482): remove notification
I/ActivityManager(  907): Recipient 2686
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3145 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3157 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=2755
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2755:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2485): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2485): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2485): onReceive()
,D/ExchangePolicystatus( 2485): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2485): onReceive(): else
,D/Process (  907): killProcessQuiet, pid=2805
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1219): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2805:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3172 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  907): Recipient 2755
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3157): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3172): onCreate
D/ProviderChangeReceiver( 3172): ---------------------------------------------------
,D/ProviderChangeReceiver( 3172): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3172): start to updateAlertNotification!
W/ContextImpl( 2910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Recipient 2805
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 3172): No fired or scheduled alerts
,D/HtcAlertUtils( 3172): -- cancelReminderNotification --
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3190 uid=10041 gids={50041}
D/HtcAlertUtils( 3172): broadcastExistReminder!
W/AccTypeManager( 3157): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3157): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  907): killProcessQuiet, pid=2701
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2701:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/ExternalAccountType( 3157): Unsupported attribute readOnly
,D/Process (  907): killProcessQuiet, pid=2827
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Recipient 2701
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3203 uid=10078 gids={50078}
I/ActivityManager(  907): Killing 2827:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3157): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3157): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3157): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3203): Got a database change event
,E/ExternalAccountType( 3157): Unsupported attribute readOnly
D/Process (  907): killProcessQuiet, pid=2858
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3215 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  907): Killing 2858:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2858
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2827
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3215): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3231 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 3215): request cur loc, but there is no sys cur
W/Settings( 3215): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3231): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3231): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 918
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3231): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/WifiManager( 2720): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 917
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
I/ActivityManager(  907): Resuming delayed broadcast
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: false pid=2720, uid=10396
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
I/jxcore-log( 2720): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 2720): 
I/jxcore-log( 2720): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2720): 
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3246 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=2880
I/ActivityManager(  907): Killing 2880:com.htc.htccupd/u0a17 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2880
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 2 11 17
,D/PMS     (  907): acquireWL(425fabc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3246 10071 null
,D/PMS     (  907): acquireWL(42787d48): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3246 10071 null
,D/PMS     (  907): releaseWL(425fabc0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3246): update TASK shortcut>
,I/TodoTaskNotifyService( 3246): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3246): stopSelfResult true
D/PMS     (  907): releaseWL(42787d48): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3263 uid=10082 gids={50082, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=2896
,I/ActivityManager(  907): Killing 2896:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 2896
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3275 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3287 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  907): killProcessQuiet, pid=2950
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  907): killProcessQuiet, pid=2922
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2950:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  907): Killing 2922:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  907): Recipient 2950
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2922
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3287): create image Cache, size: 31457280.
I/ImageRamCache( 3287): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3287): create image Cache, size: 12582912.
,I/FeedSettings( 3287): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3287): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3287): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3287): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3287): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3287): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3287): [custom highlight] onReceive
,D/CustomHighlightService( 3287): [custom highlight] onHandleIntent
,D/NewsDB  ( 3287): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3287): [custom highlight] set tags 
,D/SMSBackup( 3203): Got a database change event
,I/ActivityManager(  907): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2485): keep hiding shortcut bubble
D/MessagingShortcut( 2485): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2485): After query: 0
D/MessagingShortcut( 2485): mPresentUnreadCount: -1
D/MessagingShortcut( 2485): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2485): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1526): [EventService] reorderNotification, total:0
D/DotMatrix( 1526): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1526): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3246): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1219): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  907): killProcessQuiet, pid=2965
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2965:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2965
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3303 uid=10091 gids={50091, 3003, 5012}
,E/cutils-trace( 3261): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022583
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022835
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023142
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023329
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023356
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028904
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3324 uid=10091 gids={50091, 3003, 5012}
,D/MessagingNotification( 2485): New incoming message, can't cancel notification now
,D/MessagingNotification( 2485): newMsgCnt: 0, false
,D/MdScBoot( 3303): [108.1.] 30@-182551 -> 40@-182619
,D/Process (  907): killProcessQuiet, pid=2977
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 2977:com.google.android.youtube/u0a168 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3065
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3065:com.android.vending/u0a74 (adj 15): empty #17
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1960, uid=10029, userID:0
,D/WearableService( 1199): callingUid 10029, callindPid: 1199
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1960, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,E/MDM     ( 1199): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/CustomizationManager( 3261): ====startRecUseTime====
,D/htc.customization.log.level( 3261):  is 
,W/CustomizationLogLevel( 3261): Level value is invalid, use default level 2
,D/LocationInitializer( 1960): Restart initialization of location
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Recipient 3065
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2977
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.youtube (pid 2977): Died!
,D/CustomizationManager( 3261):  Read ACC file spent 0.060 (s)
,D/CIDMapFileReader( 3261): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3261): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 3261): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3261): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3261): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3261): Parsing tag category name = system
,I/CustomizationCIDLoader( 3261): Parsing tag category name = application
I/CustomizationCIDLoader( 3261): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 3261): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3261): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3261): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3261): Parsing tag category name = Settings
,D/CustomizationManager( 3261):  Read CID file spent 0.106 (s)
,D/CustomizationManager( 3261):  All configurations done spent 0.106 (s),
W/HtcNativeFlag( 3261): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3261): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3261): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3261): Fail to get flag for type 'language', use default value: -1,
,W/GCoreFlp( 1199): No location to return for getLastLocation()
,W/FusedLocationProvider( 1342): location=null
D/PMS     (  907): acquireWL(42a44f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42a44f98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022583
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022835
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023142
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023329
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023356
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028904
I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3261, uid=2000 user=0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1342/10029)
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2720
W/asset   (  907): Copying FileAsset 0x6ffb9a20 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  907): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 2720:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{424ac190 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{423855c8 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/ActivityManager(  907): Resuming delayed broadcast
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1526): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1526): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
V/GmsCoreStatsServiceLauncher( 1960): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/AccTypeManager( 3157): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 1320): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3287): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3287): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/InputDispatcher(  907): channel '427437f0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '427437f0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '427437f0 com.example.hello.MainActivity (s)'
D/PMS     (  907): acquireWL(429dab50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/WindowState(  907): WIN DEATH: Window{427437f0 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  907): releaseWL(429dab50): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/SensorManager(  907): mEventCount = 300
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/WindowManager(  907): WINDOW DIED Window{427437f0 u0 com.example.hello/com.example.hello.MainActivity}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
W/AccTypeManager( 1320): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1320): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
W/AccTypeManager( 3157): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3157): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,I/FeedHostManager( 1251): [onResume]
,I/FeedProviderManager( 1251): onResume
I/SocialFeedProvider( 1251): +onResume
I/SocialFeedProvider( 1251): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1251): -onResume
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/ConnectivityHelper( 1251): [getCurrentConnectionType] no network connection
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1251/10076)
,D/Process (  907): killProcessQuiet, pid=2935
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Killing 2935:com.android.settings/1000 (adj 15): empty #17
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,E/ExternalAccountType( 1320): Unsupported attribute readOnly
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2935
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,E/ExternalAccountType( 3157): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 2720 uid 10396
I/InputMethodManagerService(  907): Enable input method client, pid=1251
,D/PMS     (  907): acquireWL(4272a298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1342/10029)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/PMS     (  907): releaseWL(4272a298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1960, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1960, uid=10029, userID:0
,E/MDM     ( 1199): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1960, uid=10029, userID:0
,D/LocationInitializer( 1960): Restart initialization of location
,D/GCM     ( 1342): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1342): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1342): Proximity feature is not enabled.
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1342/10029)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,D/PMS     (  907): acquireWL(4277dd80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,V/GmsCoreStatsServiceLauncher( 1960): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1199): No location to return for getLastLocation()
,W/FusedLocationProvider( 1342): location=null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(427a19d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1342 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1342/10029)
D/PMS     (  907): releaseWL(4277dd80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022583
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022835
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023142
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023329
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023356
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028904
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022583
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360022835
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023142
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023329
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023356
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028904
,D/PMS     (  907): releaseWL(427a19d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/SQLiteDBG( 1342): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/ns.db, handle = 0x65d27288
,W/dalvikvm( 1342): threadid=1: thread exiting with uncaught exception (group=0x417f7e30)
,D/MtpReceiver( 2170): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2170): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2170): [MTP][handleMessage][startService]
D/MtpReceiver( 2170): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2170): [MTP][handleMessage]-
E/AndroidRuntime( 1342): FATAL EXCEPTION: main
E/AndroidRuntime( 1342): Process: com.google.process.gapps, PID: 1342
E/AndroidRuntime( 1342): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.nts.SchedulerReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1342): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1342): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1342): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1342): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1342): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.nts.k.b(SourceFile:246)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:479)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:462)
E/AndroidRuntime( 1342): 	at com.google.android.gms.gcm.nts.SchedulerReceiver.onReceive(SourceFile:178)
E/AndroidRuntime( 1342): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1342): 	... 10 more
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3355 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
D/MtpService( 2170): [MTP] startForeground
D/MtpService( 2170): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2170): TotalSize=1918604,MediaCacheLimit=6000
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
W/PackageManager(  907): Unable to load service info ResolveInfo{42928f88 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/MtpService( 2170): [isMtpConnected] connected: true
D/PMS     (  907): acquireWL(42848c50): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1960 10029 null
,E/SQLiteDatabase( 3355): Failed to open database '/data/data/com.nero.android.htc.sync/databases/nccontentprovider.db'.
E/SQLiteDatabase( 3355): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3355): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3355): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3355): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3355): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/SQLiteDatabase( 3355): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/SQLiteDatabase( 3355): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 3355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3355): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3355): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 3355): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 3355): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 3355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 3355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 3355): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 3355): threadid=1: thread exiting with uncaught exception (group=0x417f7e30)
,E/ActivityManager(  907): App crashed! Process: com.nero.android.htc.sync
E/AndroidRuntime( 3355): FATAL EXCEPTION: main
E/AndroidRuntime( 3355): Process: com.nero.android.htc.sync, PID: 3355
E/AndroidRuntime( 3355): java.lang.RuntimeException: Unable to get provider com.nero.android.neroconnect.contentprovider.NCContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5397)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4965)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4902)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/AndroidRuntime( 3355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3355): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 3355): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 3355): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 3355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 3355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 3355): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 3355): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3355): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3355): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3355): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3355): 	at com.nero.android.neroconnect.contentprovider.NCContentProvider.onCreate(NCContentProvider.java:43)
E/AndroidRuntime( 3355): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1609)
E/AndroidRuntime( 3355): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1574)
E/AndroidRuntime( 3355): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5394)
E/AndroidRuntime( 3355): 	... 12 more
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
,I/iu.UploadsManager( 1960): End new media; added: 0, uploading: 0, time: 53 ms
D/PMS     (  907): releaseWL(42848c50): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448385979964.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/DotMatrix( 1526): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/RemoteViews( 1108): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1108): com.android.providers.media 0 1 10
,I/RemoteViews( 1108): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1108): com.android.providers.media 1 1 15
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
,I/Prism.ItemManager( 3287): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3287): loadItems() com.htc.launcher.pageview.WidgetManager@41ca06e0 +
,I/Prism.WidgetManager( 3287): onLoadItems() +

```
