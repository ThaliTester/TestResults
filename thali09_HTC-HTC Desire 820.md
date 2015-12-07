#### Test 50242285e132180_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  903): Resuming delayed broadcast
--------- beginning of /dev/log/main
I/WorldClock.Global( 2651): isHtcDevice = true
I/ActivityManager(  903): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  903): Resuming delayed broadcast
D/Process (  903): killProcessQuiet, pid=2336
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2673 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  903): Killing 2336:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/OmaCPPushReceiverV2( 2673): initialCheck: sku=99, result=false
,D/Process (  903): killProcessQuiet, pid=2348
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2687 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  903): Killing 2348:com.htc.aurora/u0a49 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2336
I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  903): Resuming delayed broadcast
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2348
D/Process (  903): killProcessQuiet, pid=2362
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2704 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  903): Killing 2362:com.htc.aurora:remote/u0a49 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2362
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 2704): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=2704 dbg=false s=true
I/DeviceManagement( 2704): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/ActivityManager(  903): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 2704): WorkflowService: Starting workflow service
I/DeviceManagement( 2704): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41d9e438] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 2704): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2704): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 2704): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2704): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 2704): BackgroundController: *** Update after boot...
I/DeviceManagement( 2704): SessionStateController: Checking invariants...
I/DeviceManagement( 2704): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 2704): SessionStateController: Checking invariants...
E/cutils-trace( 2701): Error opening trace file: No such file or directory (2)
I/DeviceManagement( 2704): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/CustomizationManager( 2701): ====startRecUseTime====
D/htc.customization.log.level( 2701):  is 
W/CustomizationLogLevel( 2701): Level value is invalid, use default level 2
I/DeviceManagement( 2704): Perf: *** Cache update - start...
I/DeviceManagement( 2704): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 2704): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 2704): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 2704): Perf: Scan enabled apps - start...
I/DeviceManagement( 2704): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
D/CustomizationManager( 2701):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2701): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2701): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2701): Parsing tag category name = system
I/CustomizationCIDLoader( 2701): Parsing tag category name = application
I/CustomizationCIDLoader( 2701): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2701): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2701): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2701): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2701): Parsing tag category name = Settings
D/CustomizationManager( 2701):  Read CID file spent 0.105 (s)
D/CustomizationManager( 2701):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 2701): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2701): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2701): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2701): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  903): Waited long enough for: ServiceRecord{4289e870 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2728 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
W/CpuWake (  903): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  903): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  903): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2701
W/asset   (  903): Copying FileAsset 0x63bfb218 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  903): acquireHCC(42a45970): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 903 1000 null
I/Intent  (  903): @test_code: getHtcIntentFlag: 0 obj: 1118182464
I/FeedHostManager( 1242): [onPause]
I/FeedProviderManager( 1242): onPause
I/FeedHostManager( 1242): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42455148
I/SocialFeedProvider( 1242): +onPause
I/SocialFeedProvider( 1242): -onPause
D/PMS     (  903): acquireHCC(42a45148): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 903 1000 null
D/PMS     (  903): acquireWL(42a41f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 903 1000 null
I/ActivityManager(  903): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2742 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1242): [trimMemory] 20
W/asset   ( 2742): Copying FileAsset 0x5c769730 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 2742): Binding Chromium to main looper Looper (main, tid 1) {41d72da0}
I/LibraryLoader( 2742): Expected native library version number "",actual native library version number ""
I/chromium( 2742): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2742): Initializing chromium process, renderers=0
D/PMS     (  903): acquireWL(429b9900): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  903): acquireWL(429b9800): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  903): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  903): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426dc3c0:true
W/System.err(  903): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 2742): 1104709528: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  903): releaseWL(429b9900): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2742): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2742): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2742): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2742): Local Branch: 
I/Adreno-EGL( 2742): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2742): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2742):                  aa63bbd948f41d15fc72f585e
W/dalvikvm( 1961): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
I/HtcModeClient( 1477): handler message = 4011
E/HtcModeClient( 1477): Check connection and retry 3 times.
D/PMS     (  903): acquireWL(429aec70): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(429aec70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 2728): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/chromium( 2742): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  903): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
W/dalvikvm( 2742): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2742): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/PMS     (  903): acquireWL(428c78e8): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2742): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2742): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2742): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2742): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2742): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2742): CordovaWebView is running on device made by: HTC
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2728, uid=10107, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2728, uid=10107, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2728, uid=10107, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2728, uid=10107, userID:0
I/Icing   ( 1961): Storage manager: low false usage 1.99MB avail 7.43GB capacity 7.85GB
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
W/AwContents( 2742): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  903): Disable input method client, pid=1242
W/ResourceType( 2742): No package identifier when getting name for resource number 0x00000064
I/InputMethodManagerService(  903): Enable input method client, pid=2742
I/InputMethodManager( 2742): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41db9ae0, mServedView=org.apache.cordova.engine.SystemWebView{41d7fab8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1179): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1179): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1179): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 2742): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  903): Displayed com.example.hello/.MainActivity: +323ms
D/PMS     (  903): releaseWL(42a41f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
I/Gmail   ( 2728): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2728): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/AndroidProtocolHandler( 2742): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/Gmail   ( 2728): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2728): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/chromium( 2742): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
D/JsMessageQueue( 2742): Set native->JS mode to OnlineEventsBridgeMode
I/DeviceManagement( 2704): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/Icing   ( 1961): updateResources: need to parse f{com.google.android.gms}
D/jxcore_app_log( 2742): JniHelper::setJavaVM(0x4192c010), pthread_self() = 1657852336
D/JX-Cordova( 2742): jxcore cordova android initializing
I/DeviceManagement( 2704): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2704): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2704): Perf: Scan enabled apps - complete: 868 ms
I/DeviceManagement( 2704): Perf: *** Enabled app cache update - complete: 870 ms
I/DeviceManagement( 2704): Perf: *** Config cache update - start...
I/DeviceManagement( 2704): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2704): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2704): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2704): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2704): AlarmController: Scheduling TTL alarm for: 2015.12.08 at 07:48:50.991 CET (due to: com.htc.launcher)
I/DeviceManagement( 2704): Perf: *** Config cache update - complete: 19 ms
I/DeviceManagement( 2704): Perf: *** Cache update - complete: 890 ms
I/DeviceManagement( 2704): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41d9e438]
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2704, uid=10098, userID:0
I/DeviceManagement( 2704): WorkflowService: Stopping workflow service
D/Process (  903): killProcessQuiet, pid=2393
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2393:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 2742): Initializing JXcore engine
W/jxcore-log( 2742): JXcore engine is ready
I/ActivityManager(  903): Recipient 2393
W/jxcore-log( 2742): Starting JXcore engine
I/Icing   ( 1961): Internal init done: storage state 0
I/Icing   ( 1961): Post-init done
D/PMS     (  903): releaseWL(428c78e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  903): killProcessQuiet, pid=2407
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2407:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/ActivityManager(  903): Recipient 2407
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 2742): Platform android
W/jxcore-log( 2742): 
W/jxcore-log( 2742): Process ARCH arm
W/jxcore-log( 2742): 
I/jxcore-log( 2742): JXcore Cordova bridge is ready!
I/jxcore-log( 2742): 
W/jxcore-log( 2742): JXcore engine is started
E/jxcore-log( 2742): >> HTC-HTC Desire 820
E/jxcore-log( 2742): 
I/jxcore-log( 2742): Total memory 1964650496
I/jxcore-log( 2742): 
I/jxcore-log( 2742): Free memory 750772224
I/jxcore-log( 2742): 
I/jxcore-log( 2742): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2742): 
I/jxcore-log( 2742): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2742): 
I/jxcore-log( 2742): userPath [ 'www' ]
I/jxcore-log( 2742): 
I/jxcore-log( 2742): Size 720 1184
I/jxcore-log( 2742): 
I/jxcore-log( 2742): Screen Brightness 142
I/jxcore-log( 2742): 
E/jxcore-log( 2742): Dummy Error Log.
E/jxcore-log( 2742): 
,I/GAV2    ( 2598): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1961): Google Analytics 8.3.01 is starting up.
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2728, uid=10107, userID:0
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2818 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 2818): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 2818): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2818): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 2704): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 2704): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.cirmodule, com.android.CSDFunctionG, com.htc.drive.activator, com.htc.autobot.cargps.provider, com.htc.checkinprovider, com.htc.guide, android, com.android.keychain, com.htc.android.htcsetupwizard, com.android.location.fused, com.htc.backup, com.htc.mirrorlinkserver, com.htc.lockscreen, com.htc.smartdim, com.htc.usage, com.android.providers.settings, com.qualcomm.timeservice, com.htc.home.personalize, com.htc.feedback, com.htc.backupreset, com.android.settings, com.qualcomm.privinit, com.htc.android.htcloglevel, com.android.inputdevices, com.htc.htcpowermanager]
,I/DeviceManagement( 2704): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 2704): WorkflowService: Starting workflow service
,I/DeviceManagement( 2704): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4209f380] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2704): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 2704): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 2704): SessionStateController: Checking invariants...
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
W/ContextImpl( 2818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  903): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41df0c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1103): com.htc.backup 2 7 5 15
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
,I/DeviceManagement( 2704): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41df45a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DeviceManagement( 2704): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4209f380]
I/DeviceManagement( 2704): WorkflowService: Stopping workflow service
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2840 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/RemoteViews.Performance( 1103): com.htc.backup 1 3 7 4
I/RemoteViews( 1103): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1103): com.htc.backup 2 1 1 4
I/RemoteViews( 1103): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1103): com.htc.backup 1 1 1 4
I/RemoteViews.Performance( 1103): com.htc.backup 1 8 20 21
,I/htcbackup-core( 2818): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  903): sending alarm PendingIntent{427b3180: PendingIntentRecord{42747ca8 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=15, w=1440901414353, Int=604800000
,W/dalvikvm( 2818): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1103): com.htc.backup 2 2 15
D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1103): com.htc.backup 1 2 0 4
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1103): com.htc.backup 4 1 1 4
,I/RemoteViews( 1103): com.htc.backup (true,33751552)
I/jxcore-log( 2742): getBuffer is called!!!!
I/jxcore-log( 2742): 
,I/RemoteViews.Performance( 1103): com.htc.backup 2 1 0 4
,I/RemoteViews.Performance( 1103): com.htc.backup 1 17 21
,D/UPolicy ( 2818): IUserBehaviorLoggingService reference is gotten !
,W/dalvikvm( 2840): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2840): VFY: unable to resolve instance field 46
,W/dalvikvm( 2840): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 2840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/Babel   ( 2840): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 2840): MmsConfig.loadMmsSettings
,D/MmsCustomizationProvider( 2493): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2493): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 2840): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 2840): MmsConfig.loadFromDatabase
,E/Babel   ( 2840): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 2840): MmsConfig.loadFromResources
,E/Babel   ( 2840): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 2840): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2840, uid=10111, userID:0
,W/Settings( 2840): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2840, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2840, uid=10111, userID:0
V/Babel   ( 2840): babel boot account: thalitester@gmail.com
,V/Babel   ( 2840): babel boot account: SMS
,I/ActivityManager(  903): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2868 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=2420
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2420:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2420
,I/ProviderInstaller( 2840): Installed default security provider GmsCore_OpenSSL
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  903): sending alarm PendingIntent{42a18450: PendingIntentRecord{42689698 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46387, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{426fa3b0: PendingIntentRecord{428c32e0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46390, Int=0
,I/ActivityManager(  903): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2885 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=2444
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2444:com.htc.video/u0a57 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2444
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ResetNotifyBootCompleteReceiver( 1210): Receive bootcomplete intent
,W/ContextImpl( 1210): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/HtcCupdXmlParser( 2885): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2900 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 2885): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,D/AppTag  ( 2900): getInstance(Context context)
,D/AppTag  ( 2900): getInstance(Context context)
,D/AppTag  ( 2900): onCreate()
,D/QXDM2SD:HtcNative( 1210): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/HtcCupdXmlParser( 2885): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,W/CpuWake (  903): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  903): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  903): >>release mCpuPerf_Freq wakelock
W/CpuWake (  903): <<release mCpuPerf_Freq wakelock
,D/PMS     (  903): releaseHCC(42a45970): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  903): releaseHCC(42a45148): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2916 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=2461
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2461:com.htc.lmw/u0a60 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 2461
I/AlarmManager(  903): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  903): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  903): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  903): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2928 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  903): killProcessQuiet, pid=2511
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/Settings:HtcSettingsApplication( 2916): [2916/2916] onCreate()
I/ActivityManager(  903): Killing 2511:com.htc.reportagent/u0a66 (adj 15): empty #17
W/ContextImpl( 2916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Recipient 2511
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2940 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42323770
,D/HtcFingerPrintQuickLaunchProvider( 2940): -onCreate()
,I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42285248
,V/Settings:HtcSettingsApplication( 2940): [2940/2940] onCreate()
,D/Process (  903): killProcessQuiet, pid=2558
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/ContextImpl( 2940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  903): Killing 2558:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/AlarmManager(  903): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42122ab0
,D/Process (  903): killProcessQuiet, pid=2570
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  903): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  903): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  903): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  903): Killing 2570:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  903): Resuming delayed broadcast
D/TetherSettings( 2940): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2940): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2940): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2940): Cust_ConnectToPC   : spcsc>false
D/        ( 2940): Cust_ConnectToPC   : IPT>true
,D/        ( 2940): Cust_ConnectToPC   : Singel_USB>false
I/ActivityManager(  903): Recipient 2558
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2570
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Settings( 2940): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2940): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2940): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2940): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2940): Cust_ConnectToPC   : spcsc>false
D/        ( 2940): Cust_ConnectToPC   : IPT>true
D/        ( 2940): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2940): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2940): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2940): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2940): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2940): setISNotification
D/SmartNS_Utility( 2940): usb_cable_connect = 1
D/SmartNS_Utility( 2940): usb_denied = 0
I/SmartNS_PSService( 2940): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 2940): usb_cable_connect = 1
D/SmartNS_Utility( 2940): usb_denied = 0
,I/SmartNS_PSService( 2940): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (2940/1000)
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (2940/1000)
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false,
,D/Process (  903): killProcessQuiet, pid=2584
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  903): Killing 2584:com.htc.updater/u0a85 (adj 15): empty #17
,I/RemoteViews( 1103): com.android.settings (true,33751552)
,D/OnDemandProgressBar( 1103): release indeterminate drawable android.widget.OnDemandProgressBar{41dca9b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Recipient 2584
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1103): com.android.settings 2 9 0 10
,I/RemoteViews( 1103): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1103): com.android.settings 0 1 10
,I/ActivityManager(  903): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2957 uid=9987 gids={49987}
,I/SensorManager(  903): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@426210f8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426210f8, eanble = 1, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4245a978
W/SensorService(  903): Listener[1] = com.android.server.power.DisplayPowerController$10@42304210
W/SensorService(  903): Listener[2] = com.htc.smartdim.sensor_eye@426210f8
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  903): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@426210f8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  903): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{423569b0 u0 ReceiverList{4236df78 903 system/1000/u0 local:4240f338}}
,D/NfcUiccLockService( 2957): -- To check whether previous opened channel needed to be closed ...
,D/Process (  903): killProcessQuiet, pid=2613
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2971 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  903): Killing 2613:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 3
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426210f8, eanble = 1, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4245a978
W/SensorService(  903): Listener[1] = com.android.server.power.DisplayPowerController$10@42304210
W/SensorService(  903): Listener[2] = com.htc.smartdim.sensor_eye@426210f8
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2613
,I/ActivityManager(  903): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2983 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  903): killProcessQuiet, pid=2380
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2380:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2380
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 2983): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2983): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2983): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2983): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/PMS     (  903): releaseWL(429b9800): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (2983/10168)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2983): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2983): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2983): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2983): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2983): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
,D/MediaRouterService(  903): Client com.google.android.youtube (pid 2983): Registered
,I/MediaRouter( 2983): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  903): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  903):     Client/Owner: Client
D/WifiDisplayAdapter(  903):     GroupId: 
D/WifiDisplayAdapter(  903):     Passphrase: 
D/WifiDisplayAdapter(  903):     SessionId: 0
D/WifiDisplayAdapter(  903):     IP Address: }
D/YouTube ( 2983): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.google.android.youtube (2983/10168)
I/GoogleConversionPing( 2983): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449501084&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 2983): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2983): [NET] getaddrinfo-,err=8
D/libc    ( 2983): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2983): [NET] getaddrinfo-, 1
D/libc    ( 2983): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2983): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2983): Error sending ping
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2983): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2983): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 2983): getSelectedRoute
,D/YouTube ( 2983): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2983): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.youtube (2983/10168)
,D/YouTube ( 2983): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2983): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2983): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/Process (  903): killProcessQuiet, pid=2651
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2651:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 2651
,W/dalvikvm( 1961): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1961): Spent 21ms computing apk sha1.
,D/FileApkUtils( 1961): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1961): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1961): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1961): Beginning GMS chimera module scan
,W/asset   ( 1961): Copying FileAsset 0x64d4c450 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 1961): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1961): Beginning module configuration check
,D/ChimeraCfgMgr( 1961): Module APKs unchanged, check complete
I/ActivityManager(  903): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,E/dalvikvm( 1961): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1961): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(42886a48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42801870): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1961 10029 null
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,E/dalvikvm( 1961): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1961): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1961): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/GCM     ( 1961): COMPAT: Multi user not supported
,D/GCM     ( 1330): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  903): acquireWL(4280fb08): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
D/PMS     (  903): acquireWL(42a3c228): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42886a48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1449484213846 min interval config: 0 actual interval: 16871385
,I/GCoreUlr( 1961): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1193): DispatchingService.onCreate()
,I/CheckinService( 1961): Disabling old GoogleServicesFramework version
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
,D/SystemUpdateService( 1961): onCreate
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
D/PMS     (  903): acquireWL(42697a90): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
D/PMS     (  903): acquireWL(42a66c18): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1961, uid=10029, userID:0
,D/SystemUpdateService( 1961): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1961, uid=10029, userID:0
,V/AuthZen ( 1961): Handling intent: android.intent.action.BOOT_COMPLETED
D/PMS     (  903): releaseWL(42801870): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  903): releaseWL(42697a90): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/SystemUpdateService( 1961): cancelUpdate (empty URL)
,I/SystemUpdateService( 1961): active receiver: disabled
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/AuthZenEventHandler( 1961): Handling event: android.intent.action.BOOT_COMPLETED
I/CheckinService( 1961): Checking schedule, now: 1449501085320 next: 1450007150810
,I/CheckinService( 1961): active receiver: disabled
D/PMS     (  903): acquireWL(429cda00): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,I/GCoreUlr( 1193): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/PMS     (  903): releaseWL(429cda00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42a3c228): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 1961): onDestroy
D/PMS     (  903): releaseWL(4280fb08): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1961): Using Auth Proxy for data requests.
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1193, uid=10029, userID:0
,W/dalvikvm( 1961): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1961): Fetching signing key...
,I/GCoreUlr( 1193): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1193): Unbound from all location providers
D/PMS     (  903): acquireWL(428861f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(428861f0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42a66c18): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/AuthZen ( 1961): Signing key fetched successfully!
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/BaseAppContext( 1961): Using Auth Proxy for data requests.
,W/dalvikvm( 1330): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,I/GCoreUlr( 1193): DispatchingService.onDestroy()
,I/GCoreUlr( 1193): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1193): Unbound from all location providers
D/PMS     (  903): acquireWL(42977928): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42977928): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthZenTransactionCache( 1961): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1961): Clearing transaction cache
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,W/dalvikvm( 1330): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1330): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,W/Auth    ( 1330): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  903): acquireWL(42980508): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1330 10029 null
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  903): releaseWL(42980508): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1961): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1330): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  903): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3069 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
,D/PMS     (  903): acquireWL(42984a28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42984a28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3069, uid=10074, userID:0
,D/Finsky  ( 3069): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3069/10074)
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  903): getAllNetworkInfo called by com.android.vending (3069/10074)
,D/Finsky  ( 3069): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3069): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3069): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3069): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3069, uid=10074, userID:0
,D/Volley  ( 3069): [279] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3069): [286] DiskBasedCache.clear: Cache cleared.
,D/Process (  903): killProcessQuiet, pid=2673
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 2673:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/Ads     ( 3069): Skipping gmscore version check
,D/Finsky  ( 3069): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3069): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  903): Recipient 2673
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3069): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1312): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1312): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
D/TetherSettings( 2940): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2940): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2940): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2940): Cust_ConnectToPC   : spcsc>false
D/        ( 2940): Cust_ConnectToPC   : IPT>true
D/        ( 2940): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2940): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2940): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2940): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2940): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/Finsky  ( 3069): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PSReceiver( 2940): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 2940): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 2940): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 2940): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2940):  defaultType:0
,I/ActivityManager(  903): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3107 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3107): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3107): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3107): Loading: swewebviewchromium
,I/LibraryLoader( 3107): Time to load native libraries: 33 ms (timestamps 6354-6387)
,I/LibraryLoader( 3107): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3107): Initializing chromium process, renderers=9
I/LibraryLoader( 3107): Expected native library version number "",actual native library version number ""
,I/chromium( 3107): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/GAV2    ( 2728): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1477): handler message = 4011
,E/HtcModeClient( 1477): Check connection and retry 4 times.
,W/chromium( 3107): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3107): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3107): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3107): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3107): Local Branch: 
I/Adreno-EGL( 3107): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3107): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3107):                  aa63bbd948f41d15fc72f585e
,D/Process (  903): killProcessQuiet, pid=2687
,I/ActivityManager(  903): Killing 2687:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1269): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  903): Recipient 2687
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SIMStateChangeReceiver( 1477): SIM state: ABSENT
I/SIMStateChangeReceiver( 1477): phoneType = 0
I/SIMStateChangeReceiver( 1477): remove notification
,I/ActivityManager(  903): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3148 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  903): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3160 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=2728
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2728:com.google.android.gm/u0a107 (adj 15): empty #17
,I/SensorManager(  903): mEventCount = 300
,W/SystemReader( 2493): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2493): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2493): onReceive()
,D/ExchangePolicystatus( 2493): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2493): onReceive(): else
,D/Process (  903): killProcessQuiet, pid=2704
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1210): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  903): Killing 2704:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3175 uid=10041 gids={50041}
,I/ActivityManager(  903): Recipient 2728
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3160): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3191 uid=10078 gids={50078}
,D/Process (  903): killProcessQuiet, pid=2840
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 2840:com.google.android.talk/u0a111 (adj 15): empty #17
,W/AccTypeManager( 3160): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3160): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3191): Got a database change event
,D/Process (  903): killProcessQuiet, pid=2818
,I/ActivityManager(  903): Killing 2818:com.htc.backup/1000 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/WeatherUtility( 1103): can't get weather sync account
,I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3205 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
E/ExternalAccountType( 3160): Unsupported attribute readOnly
,W/WeatherRequest( 1103): request cur loc, but there is no sys cur
,I/ActivityManager(  903): Recipient 2704
,D/AccTypeManager( 3160): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3160): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3160): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/CalendarApplication( 3205): onCreate
D/ProviderChangeReceiver( 3205): ---------------------------------------------------
,D/ProviderChangeReceiver( 3205): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3205): start to updateAlertNotification!
W/ContextImpl( 2916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3205): No fired or scheduled alerts
,D/HtcAlertUtils( 3205): -- cancelReminderNotification --
,D/HtcAlertUtils( 3205): broadcastExistReminder!
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  903): Recipient 2818
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 2840
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ExternalAccountType( 3160): Unsupported attribute readOnly
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3220 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=2868
,I/ActivityManager(  903): Killing 2868:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3235 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherUtility( 3220): can't get weather sync account
,W/WeatherRequest( 3220): request cur loc, but there is no sys cur
,W/Settings( 3220): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3235): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3235): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3235): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  903): Recipient 2868
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=2885
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3249 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  903): Killing 2885:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2885
,D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1242): com.htc.widget.weatherclock (true,33751552)
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1242): com.htc.widget.weatherclock 2 14 17
,D/PMS     (  903): acquireWL(42862f40): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3249 10071 null
,D/PMS     (  903): acquireWL(42831e00): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3249 10071 null
,D/PMS     (  903): releaseWL(42862f40): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3249): update TASK shortcut>
,I/TodoTaskNotifyService( 3249): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  903): releaseWL(42831e00): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3249): stopSelfResult true
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3264 uid=10082 gids={50082, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=2900
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2900:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 2900
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3276 uid=10082 gids={50082, 3003, 5012}
,D/Process (  903): killProcessQuiet, pid=2928
,I/ActivityManager(  903): Killing 2928:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/SMSBackup( 3191): Got a database change event
I/ActivityManager(  903): Recipient 2928
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3288 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  903): killProcessQuiet, pid=2957
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  903): Killing 2957:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/BluetoothManagerService(  903): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  903): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1429
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  903): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  903): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
W/Settings:Agent(  903): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  903): Message: MESSAGE_DISABLE
I/ActivityManager(  903): Recipient 2957
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiManager( 2742): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  903): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  903): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  903): Settings:Agentvalue: 0
W/Settings:Agent(  903): >> traceCallingStack()
W/Settings:Agent(  903): Process.myPid(): 903
W/Settings:Agent(  903): Process.myTid(): 1255
W/Settings:Agent(  903): Process.myUid(): 1000
W/Settings:Agent(  903): 
W/Settings:Agent(  903): 
,W/System.err(  903): java.lang.Throwable: stack dump
W/System.err(  903): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  903): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  903): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  903): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  903): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  903): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  903): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  903): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  903): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  903): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  903): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  903): 
,W/Settings:Agent(  903): << traceCallingStack(): 1(ms)
D/WifiService(  903): New client listening to asynchronous messages
D/WifiService(  903): setWifiEnabled: false pid=2742, uid=10396
E/WifiService(  903): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  903): isSprintWifiRestricted(): false
I/WifiService(  903): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  903): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/jxcore-log( 2742): ****TEST TOOK:  5058  ms ****
I/jxcore-log( 2742): 
I/jxcore-log( 2742): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2742): 
,I/ImageRamCache( 3288): create image Cache, size: 31457280.
I/ImageRamCache( 3288): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3288): create image Cache, size: 12582912.
,I/FeedSettings( 3288): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3288): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3288): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3288): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3288): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3288): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3288): [custom highlight] onReceive
,D/CustomHighlightService( 3288): [custom highlight] onHandleIntent
,D/NewsDB  ( 3288): set custom highlight []
I/ActivityManager(  903): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3288): [custom highlight] set tags 
,I/ActivityManager(  903): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2493): keep hiding shortcut bubble
D/MessagingShortcut( 2493): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2493): After query: 0
D/MessagingShortcut( 2493): mPresentUnreadCount: -1
D/MessagingShortcut( 2493): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2493): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1525): [EventService] reorderNotification, total:0
D/DotMatrix( 1525): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1525): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3249): update TASK shortcut>
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1210): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  903): killProcessQuiet, pid=2971
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Killing 2971:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3307 uid=10091 gids={50091, 3003, 5012}
,D/MessagingNotification( 2493): New incoming message, can't cancel notification now
,D/MessagingNotification( 2493): newMsgCnt: 0, false
I/ActivityManager(  903): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023677
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024227
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024231
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024237
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028562
,V/AlarmManager(  903): sending alarm PendingIntent{421e15d0: PendingIntentRecord{4281d5f8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21150, Int=1800000
,V/AlarmManager(  903): sending alarm PendingIntent{42714db0: PendingIntentRecord{42a46358 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=46294, Int=259200000
,V/AlarmManager(  903): sending alarm PendingIntent{4200b458: PendingIntentRecord{426e0258 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50253, Int=0
,I/ActivityManager(  903): Recipient 2971
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3322 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  903): sending alarm PendingIntent{42784b90: PendingIntentRecord{42749db0 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1449486000000, Int=86400000
,D/MdScBoot( 3307): [8c8.1.] 30@-161100 -> 40@-161127
I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=2983
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  903): killProcessQuiet, pid=3069
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 2983:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  903): Killing 3069:com.android.vending/u0a74 (adj 15): empty #17
,D/WearableService( 1193): callingUid 10029, callindPid: 1193
,E/MDM     ( 1193): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,D/LocationInitializer( 1961): Restart initialization of location
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1193): No location to return for getLastLocation()
,W/FusedLocationProvider( 1330): location=null
D/PMS     (  903): acquireWL(42a43aa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42a43aa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024231
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024237
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028562
I/ActivityManager(  903): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1330): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1330): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/AuthorizationBluetoothService( 1330): Proximity feature is not enabled.
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  903): Recipient 3069
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  903): Recipient 2983
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  903): Client com.google.android.youtube (pid 2983): Died!
,E/cutils-trace( 3303): Error opening trace file: No such file or directory (2)
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1961): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42a11d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1330 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
,D/PMS     (  903): releaseWL(42a11d40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1961, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1961, uid=10029, userID:0
,E/MDM     ( 1193): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
,D/LocationInitializer( 1961): Restart initialization of location
I/ActivityManager(  903): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1193): No location to return for getLastLocation()
,W/FusedLocationProvider( 1330): location=null
D/PMS     (  903): acquireWL(428d73c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(428d73c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024231
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024237
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028562
,I/ActivityManager(  903): Resuming delayed broadcast
,D/GCM     ( 1330): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1330): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1330): Proximity feature is not enabled.
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
,V/GLSActivity( 1330): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  903): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1961): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(429ca6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1330 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3353 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/CustomizationManager( 3303): ====startRecUseTime====
D/htc.customization.log.level( 3303):  is 
,W/CustomizationLogLevel( 3303): Level value is invalid, use default level 2
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024231
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024237
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028562
,D/PMS     (  903): releaseWL(429ca6e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 3353): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3353): MmsConfig.loadMmsSettings
,D/CustomizationManager( 3303):  Read ACC file spent 0.061 (s)
,D/CIDMapFileReader( 3303): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__A07
W/dalvikvm( 3353): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3303): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3303): Parsing tag item name = HTC__031
,W/dalvikvm( 3353): VFY: unable to resolve instance field 46
V/CustomizationCIDLoader( 3303): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3303): Parsing tag category name = system
,W/dalvikvm( 3353): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/CustomizationCIDLoader( 3303): Parsing tag category name = application
,I/CustomizationCIDLoader( 3303): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3303): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3303): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3303): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3303): Parsing tag category name = Settings,
D/CustomizationManager( 3303):  Read CID file spent 0.109 (s)
,D/CustomizationManager( 3303):  All configurations done spent 0.109 (s)
,V/JNIHelp ( 3353): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/HtcNativeFlag( 3303): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3303): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3303): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3303): Fail to get flag for type 'language', use default value: -1
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3353, uid=10111, userID:0
D/MmsCustomizationProvider( 2493): query uri: content://htc-mms-customization/mms-ua/ua_string
W/Settings( 3353): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MmsCustomizationProvider( 2493): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3353, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3353, uid=10111, userID:0
I/Babel   ( 3353): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3353): MmsConfig.loadFromDatabase
D/Process (  903): killProcessQuiet, pid=2940
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3353, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3353, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3353, uid=10111, userID:0
I/ActivityManager(  903): Killing 2940:com.android.settings/1000 (adj 15): empty #17
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Babel   ( 3353): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3353): MmsConfig.loadFromResources
,E/Babel   ( 3353): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3353): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  903): Recipient 2940
,D/PackageManager(  903): deletePackageAsUser: pkg=com.example.hello, pid=3303, uid=2000 user=0
,D/Process (  903): killProcessQuiet, pid=3107
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/MtpReceiver( 2171): [MTP][MtpReceiver][onReceive]+
,D/MtpReceiver( 2171): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2171): [MTP][handleMessage][startService]
,D/MtpReceiver( 2171): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2171): [MTP][handleMessage]-
I/ActivityManager(  903): Killing 3107:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/PMS     (  903): acquireWL(4293f3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1330 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1330/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023677
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024093
I/ActivityManager(  903): Recipient 3107
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3381 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2171): [MTP] startForeground
,D/MtpService( 2171): updating state; isCurrentUser=true, mMtpLocked=false
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024227
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024231
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360024237
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360028562
I/RemoteViews( 1103): com.android.providers.media (false,0)
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1103): com.android.providers.media 3 1 10
D/MtpDatabase( 2171): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews( 1103): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1103): com.android.providers.media 1 1 15
,D/Process (  903): killProcessQuiet, pid=2742
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  903): Copying FileAsset 0x63bf5a98 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  903): acquireWL(42a6b6b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1961 10029 null
I/ActivityManager(  903): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
I/ActivityManager(  903): Killing 2742:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  903): Force removing ActivityRecord{422f30c0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  903): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ProviderInstaller( 3353): Installed default security provider GmsCore_OpenSSL
,W/PackageSettings(  903): Skipping PackageSetting{4255c208 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  903): Force stopping com.example.hello appid=10396 user=0: pkg removed
,D/PMS     (  903): releaseWL(4293f3a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpService( 2171): [isMtpConnected] connected: true
,W/InputDispatcher(  903): channel '41fe5040 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  903): channel '41fe5040 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/WifiService(  903): Client connection lost with reason: 4
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1103): ApplicationsIntentReceiver replacing:false
,W/InputDispatcher(  903): Attempted to unregister already unregistered input channel '41fe5040 com.example.hello.MainActivity (s)'
I/WindowState(  903): WIN DEATH: Window{41fe5040 u0 com.example.hello/com.example.hello.MainActivity}
,D/AccTypeManager( 1294): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/WindowManager(  903): WINDOW DIED Window{41fe5040 u0 com.example.hello/com.example.hello.MainActivity}
,D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,D/DotMatrix( 1525): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1525): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1193): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
,D/AccTypeManager( 3160): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3288): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3288): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1294): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1294): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  903): acquireWL(42a49788): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42a49788): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
I/FeedHostManager( 1242): [onResume]
I/FeedProviderManager( 1242): onResume
I/SocialFeedProvider( 1242): +onResume
I/SocialFeedProvider( 1242): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1242): -onResume
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/ConnectivityHelper( 1242): [getCurrentConnectionType] no network connection
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.launcher (1242/10076)
,D/SyncApplication( 3381): Loading default preferences
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,W/Resources( 3381): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,W/AccTypeManager( 3160): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3160): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1242): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1221): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/WifiService(  903): New client listening to asynchronous messages
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,D/SyncApplication( 3381): Overriding preferences with custom values
,D/SyncApplication( 3381): Updating preferences succeeded
,E/ExternalAccountType( 1294): Unsupported attribute readOnly
,E/SyncApplication( 3381): Application created.
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
D/VolumeInfo( 3381): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3381): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3381): Found 0 mount point(s)
,V/VolumeInfo( 3381): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3381): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
E/ExternalAccountType( 3160): Unsupported attribute readOnly
,I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
D/VolumeInfo( 3381): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3381): Can not create volume ID for unmounted volume null
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/CalendarDefines( 3381): getNewCalendarAuthority()...
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3381, uid=10008, userID:0
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,W/InputMethodManagerService(  903): Got RemoteException sending setActive(false) notification to pid 2742 uid 10396
,I/InputMethodManagerService(  903): Enable input method client, pid=1242
,I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1210 :
,I/iu.UploadsManager( 1961): End new media; added: 0, uploading: 0, time: 420 ms
,D/PhoneApp( 1210): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/SyncApplication( 3381): enableAppOperation()+
,D/SyncApplication( 3381): enableAppOperation()-
,D/HTCUtilities( 3381): isNeorSinged() + 
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3381, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/PMS     (  903): releaseWL(42a6b6b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/HTCUtilities( 3381): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3381): isNeorSinged() return false
D/CDMountReceiver( 3381): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3381): USB connected to PC
,D/FOTAReceiver( 3381): onReceive() enter 
,D/FOTAReceiver( 3381): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  903): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3403 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  903): killProcessQuiet, pid=3148
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Killing 3148:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3148
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3403): -onCreate()
,V/Settings:HtcSettingsApplication( 3403): [3403/3403] onCreate()
,D/TetherSettings( 3403): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3403): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3403): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3403): Cust_ConnectToPC   : spcsc>false
D/        ( 3403): Cust_ConnectToPC   : IPT>true
,D/        ( 3403): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3403): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3403): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3403): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3403): Cust_ConnectToPC   : spcsc>false
D/        ( 3403): Cust_ConnectToPC   : IPT>true
D/        ( 3403): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3403): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3403): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3403): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3403): usb_cable_connect = 1
,D/SmartNS_Utility( 3403): usb_denied = 0
,W/PackageManager(  903): Unable to load service info ResolveInfo{429e1ca8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
I/SmartNS_NSReceiver( 3403): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3403): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3403): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3403): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3403): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3403): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3403):  defaultType:0
I/SmartNS_PSService( 3403): fail notificaiton:false
D/SmartNS_Utility( 3403): usb_cable_connect = 1
D/SmartNS_Utility( 3403): usb_denied = 0
I/SmartNS_PSService( 3403): usb notificaiton:true
V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3403/1000)
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/SmartNS_Utility( 3403): usb_cable_connect = 1
D/SmartNS_Utility( 3403): usb_denied = 0
I/SmartNS_PSService( 3403): usb notificaiton:true
,V/Tethering(  903): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  903): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  903): bSetPropertyMultiRAB:false
I/ActivityManager(  903): Resuming delayed broadcast
D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.settings (3403/1000)
,D/SmartNS_Utility( 3403): usb_cable_connect = 1
,D/SmartNS_Utility( 3403): usb_denied = 0
I/ActivityManager(  903): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/SmartNS_PSService( 3403): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3403): USB Plugged, Set USBPlugged=  truePSenabled:false
,W/WeatherUtility( 3220): can't get weather sync account
I/ActivityManager(  903): Resuming delayed broadcast
,D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1242): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1242): com.google.android.googlequicksearchbox 1 1 5
,D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/WeatherRequest( 3220): request cur loc, but there is no sys cur
,W/Settings( 3220): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/RemoteDisplayProvider(  903): start
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3422 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1525): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1242): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews( 1103): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1103): com.android.settings 1 1 10
,I/RemoteViews( 1103): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1103): com.android.settings 1 1 10
,I/RemoteViews.Performance( 1242): com.htc.widget.weatherclock 1 10 17
,W/ContextImpl( 3422): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3422): call getInstance()
I/ActivityManager(  903): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3422): MY_DEBUG = false
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,E/SQLiteLog(  903): (3850) statement aborts at 46: [INSERT INTO secure(value,name) VALUES (?,?)] disk I/O error
,E/SQLiteDBG(  903): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.settings/databases/settings.db, handle = 0x62ce6438
,E/SQLiteDatabase(  903): Error inserting ...
E/SQLiteDatabase(  903): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase(  903): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase(  903): 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1408)
E/SQLiteDatabase(  903): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:692)
E/SQLiteDatabase(  903): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase(  903): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:312)
E/SQLiteDatabase(  903): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase(  903): 	at dalvik.system.NativeStart.run(Native Method)
,E/SQLiteDatabase( 3422): Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
E/SQLiteDatabase( 3422): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3422): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3422): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:328)
E/SQLiteDatabase( 3422): 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:245)
E/SQLiteDatabase( 3422): 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1274)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:2954)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:169)
E/SQLiteDatabase( 3422): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3422): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PowerUsageList:PowerUsageHelper( 3422): bulkInsertData(), Exception: 
E/PowerUsageList:PowerUsageHelper( 3422): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PowerUsageList:PowerUsageHelper( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:328)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:245)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1274)
E/PowerUsageList:PowerUsageHelper( 3422): 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:2954)
E/PowerUsageList:PowerUsageHelper( 3422): 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:169)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.os.Looper.loop(Looper.java:157)
E/PowerUsageList:PowerUsageHelper( 3422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PowerUsageService( 3422): bulk insert error
D/Process (  903): killProcessQuiet, pid=3160
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Killing 3160:com.htc.contacts/u0a44 (adj 15): empty #17
D/WeatherUtility( 1312): Weather sync is On
D/WSP     ( 1312): [Receiver] auto sync agent, auto sync is enabled, reset schedule
E/SQLiteDatabase( 3422): Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
E/SQLiteDatabase( 3422): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3422): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3422): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3422): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.query(SmartSyncProvider.java:161)
E/SQLiteDatabase( 3422): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3422): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3422): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3422): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2019)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3422): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3422): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3422): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3422): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3422): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3422): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3422): 	at java.lang.Thread.run(Thread.java:864)
W/WeatherUtility( 1103): can't get weather sync account
D/PMS     (  903): acquireWL(429bc780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3422 1000 null
D/PMS     (  903): releaseWL(429bc780): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/WeatherUtility( 3220): can't get weather sync account
I/ActivityManager(  903): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3439 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3220): request cur loc, but there is no sys cur
,W/Settings( 3220): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1242): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1242): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  903): Recipient 3160
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1242): com.htc.widget.weatherclock 1 8 17
,D/ContactMessageStore( 1210): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1210): MSG_NOTIFY_CS_TO_SYNC <<,
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/SQLiteDatabase( 3439): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 3439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 3439): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3439): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3439): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteDatabase( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteDatabase( 3439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3439): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteDatabase( 3439): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 3439): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 3439): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3439): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3439): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 3439): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3439): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3439): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteOpenHelper( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteOpenHelper( 3439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3439): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteOpenHelper( 3439): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3439): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 3439): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 3439): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 3439): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5ca45db8
,W/System.err( 3439): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 3439): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 3439): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 3439): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 3439): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
,W/System.err( 3439): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 3439): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 3439): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 3439): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 3439): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 3439): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3439): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:476)
W/System.err( 3439): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 3439): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
W/System.err( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
W/System.err( 3439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3439): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3439): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
,W/System.err( 3439): 	at java.lang.Thread.run(Thread.java:864)

```
