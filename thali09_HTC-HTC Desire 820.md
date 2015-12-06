#### Test 502422853393492_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
W/WorldClock.AlarmService( 2633): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
I/WorldClock.AlarmUtils( 2633): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmUtils( 2633): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 2633): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1110): receive(android.intent.action.ALARM_CHANGED,1,false)
--------- beginning of /dev/log/system
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(430e40c0): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
I/WorldClock.Global( 2633): isHtcDevice = true
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2657 uid=10091 gids={50091, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2351
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2351:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2351
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/OmaCPPushReceiverV2( 2657): initialCheck: sku=99, result=false
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2669 uid=10091 gids={50091, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2363
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2363:com.htc.aurora/u0a49 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/ActivityManager(  906): Recipient 2363
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=2686 uid=10098 gids={50098, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2377
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2377:com.htc.aurora:remote/u0a49 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2377
I/DeviceManagement( 2686): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=2686 dbg=false s=true
I/DeviceManagement( 2686): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 2686): WorkflowService: Starting workflow service
I/DeviceManagement( 2686): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@423db428] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 2686): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2686): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 2686): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 2686): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 2686): BackgroundController: *** Update after boot...
I/DeviceManagement( 2686): SessionStateController: Checking invariants...
I/DeviceManagement( 2686): BackgroundController: Invariants are unchanged.
E/cutils-trace( 2675): Error opening trace file: No such file or directory (2)
I/DeviceManagement( 2686): SessionStateController: Checking invariants...
I/DeviceManagement( 2686): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
I/DeviceManagement( 2686): Perf: *** Cache update - start...
I/DeviceManagement( 2686): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 2686): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 2686): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 2686): Perf: Scan enabled apps - start...
D/CustomizationManager( 2675): ====startRecUseTime====
D/htc.customization.log.level( 2675):  is 
W/CustomizationLogLevel( 2675): Level value is invalid, use default level 2
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42ee8ec8 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2710 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/DeviceManagement( 2686): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
D/CustomizationManager( 2675):  Read ACC file spent 0.069 (s)
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2675): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2675): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2675): Parsing tag category name = system
I/CustomizationCIDLoader( 2675): Parsing tag category name = application
I/CustomizationCIDLoader( 2675): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2675): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2675): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2675): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2675): Parsing tag category name = Settings
D/CustomizationManager( 2675):  Read CID file spent 0.115 (s)
D/CustomizationManager( 2675):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 2675): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2675): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2675): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2675): Fail to get flag for type 'language', use default value: -1
I/HtcModeClient( 1490): handler message = 4011
E/HtcModeClient( 1490): Check connection and retry 3 times.
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  906): acquireHCC(4310c8c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2675
D/PMS     (  906): acquireHCC(4310c670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6a34bea8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1125012080
I/FeedHostManager( 1251): [onPause]
I/FeedProviderManager( 1251): onPause
I/FeedHostManager( 1251): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42492930
I/SocialFeedProvider( 1251): +onPause
I/SocialFeedProvider( 1251): -onPause
D/PMS     (  906): acquireWL(430e3018): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2724 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
W/asset   ( 2724): Copying FileAsset 0x5c8f5c90 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1251): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 2724): Binding Chromium to main looper Looper (main, tid 1) {423afe40}
I/LibraryLoader( 2724): Expected native library version number "",actual native library version number ""
I/chromium( 2724): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2724): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(43015a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  906): acquireWL(43014300): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d94ff0:true
D/PMS     (  906): releaseWL(43014300): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 2724): 1111251000: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2724): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2724): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2724): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2724): Local Branch: 
I/Adreno-EGL( 2724): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2724): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2724):                  aa63bbd948f41d15fc72f585e
W/dalvikvm( 1962): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
W/GAV2    ( 2710): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  906): acquireWL(42f2e040): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
W/chromium( 2724): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/PMS     (  906): releaseWL(42f2e040): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2724): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2724): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2724): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2724): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2724): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
I/ActivityManager(  906): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
W/dalvikvm( 2724): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2724): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2724): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2724): CordovaWebView is running on device made by: HTC
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2710, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2710, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2710, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2710, uid=10107, userID:0
D/PMS     (  906): acquireWL(42f1db30): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1962): Storage manager: low false usage 1.78MB avail 7.43GB capacity 7.85GB
W/dalvikvm( 1962): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
W/AwContents( 2724): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1251
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +308ms
W/ResourceType( 2724): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2724): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@423f6b80, mServedView=org.apache.cordova.engine.SystemWebView{423bcb58 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  906): Enable input method client, pid=2724
W/AwContents( 2724): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/Gmail   ( 2710): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  906): releaseWL(430e3018): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/Gmail   ( 2710): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2710): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2710): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
E/AndroidProtocolHandler( 2724): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2724): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/DeviceManagement( 2686): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
D/JsMessageQueue( 2724): Set native->JS mode to OnlineEventsBridgeMode
I/Icing   ( 1962): updateResources: need to parse f{com.google.android.gms}
I/DeviceManagement( 2686): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2686): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2686): Perf: Scan enabled apps - complete: 862 ms
I/DeviceManagement( 2686): Perf: *** Enabled app cache update - complete: 863 ms
I/DeviceManagement( 2686): Perf: *** Config cache update - start...
I/DeviceManagement( 2686): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2686): ConfigCacheController: *** Updating stale config cache entries...
D/jxcore_app_log( 2724): JniHelper::setJavaVM(0x41f6a010), pthread_self() = 1659075952
D/JX-Cordova( 2724): jxcore cordova android initializing
W/dalvikvm( 2686): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 2686): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
W/dalvikvm( 2686): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
W/System.err( 2686): Starting the internal HTTP client
I/Icing   ( 1962): Internal init done: storage state 0
I/DeviceManagement( 2686): ConfigCacheController: Getting config update from server: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.aurora/versions/ddcde851-94d3-4ce2-896c-ddafd2987e4a/cid/MDozOjIwMTUtMDgtMjFUMDk6MTU6MTcuMTg4Wg
I/Icing   ( 1962): Post-init done
W/jxcore-log( 2724): Initializing JXcore engine
W/jxcore-log( 2724): JXcore engine is ready
W/jxcore-log( 2724): Starting JXcore engine
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (2686/10098)
I/DeviceManagement( 2686): DeviceClientResource: Active network...
I/DeviceManagement( 2686):   No active network
I/DeviceManagement( 2686): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
I/DeviceManagement( 2686): BackgroundController: *** Network unavailable!
I/DeviceManagement( 2686): Perf: *** Config cache update - complete: 175 ms
I/DeviceManagement( 2686): Perf: *** Cache update - complete: 1040 ms
I/DeviceManagement( 2686): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@423db428]
I/DeviceManagement( 2686): WorkflowService: Stopping workflow service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (2686/10098)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.cs.dm (2686/10098)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=2686, uid=10098, userID:0
I/ActivityManager(  906): Killing 2394:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=2394
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(42f1db30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 2394
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=2408
I/ActivityManager(  906): Killing 2408:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Recipient 2408
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 2724): Platform android
W/jxcore-log( 2724): 
W/jxcore-log( 2724): Process ARCH arm
W/jxcore-log( 2724): 
I/jxcore-log( 2724): JXcore Cordova bridge is ready!
I/jxcore-log( 2724): 
W/jxcore-log( 2724): JXcore engine is started
E/jxcore-log( 2724): >> HTC-HTC Desire 820
E/jxcore-log( 2724): 
I/jxcore-log( 2724): Total memory 1964650496
I/jxcore-log( 2724): 
I/jxcore-log( 2724): Free memory 749793280
I/jxcore-log( 2724): 
I/jxcore-log( 2724): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2724): 
I/jxcore-log( 2724): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2724): 
I/jxcore-log( 2724): userPath [ 'www' ]
I/jxcore-log( 2724): 
I/jxcore-log( 2724): Size 720 1184
I/jxcore-log( 2724): 
I/jxcore-log( 2724): Screen Brightness 142
I/jxcore-log( 2724): 
E/jxcore-log( 2724): Dummy Error Log.
E/jxcore-log( 2724): 
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2710, uid=10107, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2795 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 2795): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 2795): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2795): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 2686): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 2686): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.mirrorlinkserver, android, com.qualcomm.timeservice, com.htc.usage, com.htc.backupreset, com.android.keychain, com.android.settings, com.htc.feedback, com.htc.lockscreen, com.htc.android.htcsetupwizard, com.qualcomm.privinit, com.htc.autobot.cargps.provider, com.htc.home.personalize, com.htc.backup, com.android.CSDFunctionG, com.htc.checkinprovider, com.htc.cirmodule, com.android.location.fused, com.htc.guide, com.htc.smartdim, com.htc.drive.activator, com.android.inputdevices, com.android.providers.settings, com.htc.htcpowermanager, com.htc.android.htcloglevel]
,I/DeviceManagement( 2686): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 2686): WorkflowService: Starting workflow service
I/DeviceManagement( 2686): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@427a9800] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 2686): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 2686): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 2686): SessionStateController: Checking invariants...
,W/ContextImpl( 2795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
I/ActivityManager(  906): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{42404400 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1110): com.htc.backup 1 10 5 15
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,I/DeviceManagement( 2686): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{4242ec48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DeviceManagement( 2686): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@427a9800]
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
,I/DeviceManagement( 2686): WorkflowService: Stopping workflow service
,I/RemoteViews.Performance( 1110): com.htc.backup 1 2 8 4
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2818 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/RemoteViews.Performance( 1110): com.htc.backup 2 1 3 4
I/RemoteViews( 1110): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1110): com.htc.backup 1 1 1 4
I/RemoteViews.Performance( 1110): com.htc.backup 0 10 23 21
,I/jxcore-log( 2724): getBuffer is called!!!!
I/jxcore-log( 2724): 
,I/htcbackup-core( 2795): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  906): sending alarm PendingIntent{42e7cb28: PendingIntentRecord{42e7fa30 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=15, w=1440901414353, Int=604800000
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,W/dalvikvm( 2795): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews.Performance( 1110): com.htc.backup 1 2 15
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1110): com.htc.backup 1 1 0 4
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1110): com.htc.backup 1 1 0 4
,I/RemoteViews( 1110): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1110): com.htc.backup 1 1 0 4
,I/RemoteViews.Performance( 1110): com.htc.backup 1 12 21
,D/UPolicy ( 2795): IUserBehaviorLoggingService reference is gotten !
,D/Process (  906): killProcessQuiet, pid=2113
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 2113:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
W/dalvikvm( 2818): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2818): VFY: unable to resolve instance field 46
I/Babel   ( 2818): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 2818): MmsConfig.loadMmsSettings
W/dalvikvm( 2818): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 2818): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MmsCustomizationProvider( 2480): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2480): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 2818): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 2818): MmsConfig.loadFromDatabase
,E/Babel   ( 2818): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 2818): MmsConfig.loadFromResources
,E/Babel   ( 2818): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 2818): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2818, uid=10111, userID:0
,W/Settings( 2818): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2818, uid=10111, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2818, uid=10111, userID:0
V/Babel   ( 2818): babel boot account: thalitester@gmail.com
V/Babel   ( 2818): babel boot account: SMS
,I/ActivityManager(  906): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2845 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2435
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2435:com.htc.video/u0a57 (adj 15): empty #17
,I/ProviderInstaller( 2818): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  906): Recipient 2435
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2113
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  906): sending alarm PendingIntent{42ccafa8: PendingIntentRecord{42cdc9e0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47161, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42f0f898: PendingIntentRecord{42d40868 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47164, Int=0
,I/ActivityManager(  906): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2863 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  906): killProcessQuiet, pid=2450
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2450:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2450
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ResetNotifyBootCompleteReceiver( 1218): Receive bootcomplete intent
,W/ContextImpl( 1218): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(4310c8c8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(4310c670): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/HtcCupdXmlParser( 2863): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2878 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 2863): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,D/AppTag  ( 2878): getInstance(Context context)
,D/AppTag  ( 2878): getInstance(Context context)
,D/AppTag  ( 2878): onCreate()
,D/QXDM2SD:HtcNative( 1218): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/HtcCupdXmlParser( 2863): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,D/Process (  906): killProcessQuiet, pid=2530
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2893 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 2530:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2530
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 2893): [2893/2893] onCreate()
W/ContextImpl( 2893): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/AlarmManager(  906): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  906): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  906): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2906 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2917 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2337
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2337:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2337
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42e37330
,D/HtcFingerPrintQuickLaunchProvider( 2917): -onCreate()
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42f39188
,V/Settings:HtcSettingsApplication( 2917): [2917/2917] onCreate()
,D/Process (  906): killProcessQuiet, pid=2548
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42e9ecb8
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  906): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.tencent.mm
W/ContextImpl( 2917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  906): Killing 2548:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=2560
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  906): Killing 2560:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2548
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
,D/TetherSettings( 2917): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 2917): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2917): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2917): Cust_ConnectToPC   : spcsc>false
D/        ( 2917): Cust_ConnectToPC   : IPT>true
,D/        ( 2917): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2917): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2917): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2917): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2917): Cust_ConnectToPC   : spcsc>false
D/        ( 2917): Cust_ConnectToPC   : IPT>true
D/        ( 2917): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2917): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2917): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2917): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 2917): setISNotification
,D/SmartNS_Utility( 2917): usb_cable_connect = 1
D/SmartNS_Utility( 2917): usb_denied = 0
,I/SmartNS_PSService( 2917): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 2917): usb_cable_connect = 1
D/SmartNS_Utility( 2917): usb_denied = 0
I/SmartNS_PSService( 2917): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (2917/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (2917/1000)
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  906): killProcessQuiet, pid=2575
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2575:com.htc.updater/u0a85 (adj 15): empty #17
,I/RemoteViews( 1110): com.android.settings (true,33751552)
,D/OnDemandProgressBar( 1110): release indeterminate drawable android.widget.OnDemandProgressBar{42405668 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews.Performance( 1110): com.android.settings 1 7 0 10
I/RemoteViews( 1110): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1110): com.android.settings 1 0 10
,I/ActivityManager(  906): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2935 uid=9987 gids={49987}
,I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42911c00, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42911c00, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ccf6d8
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@42a493f0
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@42911c00
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42911c00, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42d49318 u0 ReceiverList{42c96210 906 system/1000/u0 local:423c5ce0}}
,D/NfcUiccLockService( 2935): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  906): Recipient 2560
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 3
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42911c00, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42ccf6d8
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@42a493f0
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@42911c00
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  906): killProcessQuiet, pid=2604
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2949 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 2604:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2604
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2575
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=2633
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2961 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 2633:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2633
,E/YouTube ( 2961): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 2961): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2961): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2961): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (2961/10168)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2961): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2961): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2961): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2961): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/PMS     (  906): releaseWL(43015a18): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/YouTube ( 2961): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.youtube (pid 2961): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/MediaRouter( 2961): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/YouTube ( 2961): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.youtube (2961/10168)
I/GoogleConversionPing( 2961): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449413967&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/libc    ( 2961): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 2961): [NET] getaddrinfo-,err=8
D/libc    ( 2961): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2961): [NET] getaddrinfo-, 1
,D/libc    ( 2961): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2961): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 2961): Error sending ping
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2961): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2961): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 2961): getSelectedRoute
,D/YouTube ( 2961): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (2961/10168)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/YouTube ( 2961): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2961): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2961): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2961): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,W/dalvikvm( 1962): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1962): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1962): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1962): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1962): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1962): Beginning GMS chimera module scan
,W/asset   ( 1962): Copying FileAsset 0x65ab67f0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,W/dalvikvm( 1962): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1962): Beginning module configuration check
,D/ChimeraCfgMgr( 1962): Module APKs unchanged, check complete
I/ActivityManager(  906): Resuming delayed broadcast
,E/dalvikvm( 1962): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1962): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1962/10029)
D/PMS     (  906): acquireWL(42e75520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1962): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1962): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1962): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  906): acquireWL(42c997b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1962): COMPAT: Multi user not supported
,D/GCM     ( 1343): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  906): acquireWL(42d74350): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
D/PMS     (  906): releaseWL(42e75520): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1962): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1201): DispatchingService.onCreate()
,I/CheckinService( 1962): Checkin interval check for package: unspecified last checkin: 1449261991062 min interval config: 0 actual interval: 151977238
,I/CheckinService( 1962): Disabling old GoogleServicesFramework version
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/SystemUpdateService( 1962): onCreate
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
,D/SystemUpdateService( 1962): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1962, uid=10029, userID:0
D/PMS     (  906): acquireWL(42ff8d30): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1962, uid=10029, userID:0
,V/AuthZen ( 1962): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1962, uid=10029, userID:0
,D/PMS     (  906): acquireWL(42fc37e0): PARTIAL_WAKE_LOCK  Icing 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,I/CheckinService( 1962): Checking schedule, now: 1449413968383 next: 1449784928008
,I/CheckinService( 1962): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,I/SystemUpdateService( 1962): cancelUpdate (empty URL)
,I/SystemUpdateService( 1962): active receiver: disabled
,I/GAV2    ( 2589): Thread[GAThread,5,main]: No campaign data found.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,D/AuthZenEventHandler( 1962): Handling event: android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1201): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PMS     (  906): releaseWL(42fc37e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42d74350): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/GAv4-SVC( 1962): Google Analytics 8.3.01 is starting up.
,W/BaseAppContext( 1962): Using Auth Proxy for data requests.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1201, uid=10029, userID:0
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1962): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 1962): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1962): Fetching signing key...
,I/AuthZen ( 1962): Signing key fetched successfully!
,I/GCoreUlr( 1201): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/BaseAppContext( 1962): Using Auth Proxy for data requests.
,I/GCoreUlr( 1201): Unbound from all location providers
D/PMS     (  906): acquireWL(43032fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(43032fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42ff8d30): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/AuthZenTransactionCache( 1962): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1962): Clearing transaction cache
,D/SystemUpdateService( 1962): onDestroy
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42c997b8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1201): DispatchingService.onDestroy()
,I/GCoreUlr( 1201): Stopping handler for UlrDispSvcFast
D/PMS     (  906): acquireWL(4303a5c0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1962 10029 null
,I/GCoreUlr( 1201): Unbound from all location providers
D/PMS     (  906): acquireWL(42e72a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42e72a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42e83ea8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1962 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/dalvikvm( 1343): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/PMS     (  906): releaseWL(4303a5c0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  906): releaseWL(42e83ea8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,W/Auth    ( 1343): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  906): acquireWL(4300a508): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1343 10029 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  906): releaseWL(4300a508): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1962): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,W/dalvikvm( 1343): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1343): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/PersistentNotificationBroadcastReceiver( 1343): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3054 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(430965f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(430965f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3054, uid=10074, userID:0
,D/Finsky  ( 3054): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3054/10074)
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3054/10074)
,D/Finsky  ( 3054): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3054): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3054): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3054): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3054, uid=10074, userID:0
,D/Volley  ( 3054): [283] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3054): [276] DiskBasedCache.clear: Cache cleared.
,D/Process (  906): killProcessQuiet, pid=2657
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2657:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2657
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
D/Ads     ( 3054): Skipping gmscore version check
D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
D/Finsky  ( 3054): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3054): [1] Libraries$2.run: Finished loading 1 libraries.
D/TetherSettings( 2917): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2917): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2917): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2917): Cust_ConnectToPC   : spcsc>false
D/        ( 2917): Cust_ConnectToPC   : IPT>true
D/        ( 2917): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2917): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2917): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2917): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/Finsky  ( 3054): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 2917): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 2917): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 2917): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2917): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2917):  defaultType:0
I/ActivityManager(  906): Delay finish: com.android.settings/.PSReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/Finsky  ( 3054): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3092 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3092): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3092): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3092): Loading: swewebviewchromium
,I/LibraryLoader( 3092): Time to load native libraries: 43 ms (timestamps 9262-9305)
,I/LibraryLoader( 3092): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3092): Initializing chromium process, renderers=9
I/LibraryLoader( 3092): Expected native library version number "",actual native library version number ""
,I/chromium( 3092): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3092): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3092): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3092): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3092): Local Branch: 
I/Adreno-EGL( 3092): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3092): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3092):                  aa63bbd948f41d15fc72f585e
,I/HtcModeClient( 1490): handler message = 4011
,E/HtcModeClient( 1490): Check connection and retry 4 times.
,D/Process (  906): killProcessQuiet, pid=2669
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 2669:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1277): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1490): SIM state: ABSENT
I/SIMStateChangeReceiver( 1490): phoneType = 0
,I/SIMStateChangeReceiver( 1490): remove notification
I/ActivityManager(  906): Recipient 2669
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3131 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3143 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2710
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2710:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2480): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2480): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2480): onReceive()
D/ExchangePolicystatus( 2480): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2480): onReceive(): else
,D/Process (  906): killProcessQuiet, pid=2795
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 2795:com.htc.backup/1000 (adj 15): empty #17
D/HtcBroadcastReceiver( 1218): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2710
,I/ActivityManager(  906): Recipient 2795
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3158 uid=10041 gids={50041}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3173 uid=10078 gids={50078}
,D/Process (  906): killProcessQuiet, pid=2686
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2686:com.htc.cs.dm/u0a98 (adj 15): empty #17
,D/AccTypeManager( 3143): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/SMSBackup( 3173): Got a database change event
,D/Process (  906): killProcessQuiet, pid=2818
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2818:com.google.android.talk/u0a111 (adj 15): empty #17
,W/WeatherUtility( 1110): can't get weather sync account
W/AccTypeManager( 3143): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3143): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3187 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2686
,W/WeatherRequest( 1110): request cur loc, but there is no sys cur
,E/ExternalAccountType( 3143): Unsupported attribute readOnly
,I/ActivityManager(  906): Recipient 2818
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3143): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3187): onCreate
D/ProviderChangeReceiver( 3187): ---------------------------------------------------
,D/ProviderChangeReceiver( 3187): ProviderChangeReceiver onReceive, start to update notification!
W/AccTypeManager( 3143): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3143): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/AlertService( 3187): start to updateAlertNotification!
W/ContextImpl( 2893): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/ExternalAccountType( 3143): Unsupported attribute readOnly
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3202 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
D/AlertService( 3187): No fired or scheduled alerts
D/HtcAlertUtils( 3187): -- cancelReminderNotification --
D/HtcAlertUtils( 3187): broadcastExistReminder!
D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  906): killProcessQuiet, pid=2845
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2845:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2845
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3217 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3202): can't get weather sync account
,W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3217): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3217): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3217): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3231 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2863
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2863:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 3 22 17
I/ActivityManager(  906): Recipient 2863
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42cdede8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3231 10071 null
,D/PMS     (  906): acquireWL(42cd5380): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3231 10071 null
,D/PMS     (  906): releaseWL(42cdede8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3231): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3231): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42cd5380): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,W/NotifyReceiver( 3231): stopSelfResult true
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3246 uid=10082 gids={50082, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=2878
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2878:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2878
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3258 uid=10082 gids={50082, 3003, 5012}
,V/AlarmManager(  906): sending alarm PendingIntent{428a71b8: PendingIntentRecord{42e511c0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=22007, Int=1800000
,V/AlarmManager(  906): sending alarm PendingIntent{42e8e1e8: PendingIntentRecord{42efa620 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=47036, Int=259200000
,V/AlarmManager(  906): sending alarm PendingIntent{425ee538: PendingIntentRecord{42c3a450 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51111, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42cf7a98: PendingIntentRecord{42dd4df8 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1449399600000, Int=86400000
,D/Process (  906): killProcessQuiet, pid=2935
I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3270 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  906): Killing 2935:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  906): killProcessQuiet, pid=2906
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2906:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  906): Recipient 2906
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2935
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3270): create image Cache, size: 31457280.
I/ImageRamCache( 3270): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3270): create image Cache, size: 12582912.
,I/FeedSettings( 3270): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3270): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3270): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3270): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3270): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3270): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3270): [custom highlight] onReceive
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3270): [custom highlight] onHandleIntent
D/NewsDB  ( 3270): set custom highlight []
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1359
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/WifiManager( 2724): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
D/WifiService(  906): New client listening to asynchronous messages
D/WifiService(  906): setWifiEnabled: false pid=2724, uid=10396
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1250
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
D/CustomHighlightService( 3270): [custom highlight] set tags 
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
,W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
,I/ActivityManager(  906): Resuming delayed broadcast
D/SMSBackup( 3173): Got a database change event
I/jxcore-log( 2724): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 2724): 
I/jxcore-log( 2724): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2724): 
D/MessagingShortcutReceiver( 2480): keep hiding shortcut bubble
D/MessagingShortcut( 2480): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2480): After query: 0
D/MessagingShortcut( 2480): mPresentUnreadCount: -1
D/MessagingShortcut( 2480): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2480): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1534): [EventService] reorderNotification, total:0
D/DotMatrix( 1534): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1534): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3231): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1218): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  906): killProcessQuiet, pid=2949
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2949:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2949
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3287 uid=10091 gids={50091, 3003, 5012}
,D/MessagingNotification( 2480): New incoming message, can't cancel notification now
,D/MessagingNotification( 2480): newMsgCnt: 0, false
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3303 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3287): [2a8.1.] 30@-155904 -> 40@-155930
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=2961
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  906): killProcessQuiet, pid=3054
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2961:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  906): Killing 3054:com.android.vending/u0a74 (adj 15): empty #17
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1962, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
,D/WearableService( 1201): callingUid 10029, callindPid: 1201
,E/MDM     ( 1201): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1962): Restart initialization of location
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Recipient 3054
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1343): location=null
D/PMS     (  906): acquireWL(42c1c400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/PMS     (  906): releaseWL(42c1c400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Recipient 2961
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 2961): Died!
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1962): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4310c7c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1962, uid=10029, userID:0
,E/MDM     ( 1201): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1962, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1962, uid=10029, userID:0
D/PMS     (  906): releaseWL(4310c7c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1962): Restart initialization of location
,E/cutils-trace( 3301): Error opening trace file: No such file or directory (2)
,W/GCoreFlp( 1201): No location to return for getLastLocation()
,W/FusedLocationProvider( 1343): location=null
D/PMS     (  906): acquireWL(42911f38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42911f38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1962): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42ddb158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
,D/PMS     (  906): releaseWL(42ddb158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42e2fed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2173): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2173): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2173): [MTP][handleMessage][startService]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1343/10029)
D/MtpReceiver( 2173): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2173): [MTP][handleMessage]-
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024253
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024859
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024871
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024882
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028988
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3335 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2173): [MTP] startForeground
,D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/PMS     (  906): releaseWL(42e2fed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/RemoteViews( 1110): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1110): com.android.providers.media 0 1 10
I/RemoteViews( 1110): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1110): com.android.providers.media 1 1 15
D/MtpService( 2173): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2173): TotalSize=1918604,MediaCacheLimit=6000
,D/MtpService( 2173): [isMtpConnected] connected: true
D/PMS     (  906): acquireWL(42d60c88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1962 10029 null
,D/CustomizationManager( 3301): ====startRecUseTime====
D/htc.customization.log.level( 3301):  is 
,W/CustomizationLogLevel( 3301): Level value is invalid, use default level 2
,D/SyncApplication( 3335): Loading default preferences
,W/Resources( 3335): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/iu.UploadsManager( 1962): End new media; added: 0, uploading: 0, time: 47 ms
D/PMS     (  906): releaseWL(42d60c88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/Process (  906): killProcessQuiet, pid=2917
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2917:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2917
,I/SensorManager(  906): mEventCount = 300
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 3335): Overriding preferences with custom values
,D/SyncApplication( 3335): Updating preferences succeeded
,E/SyncApplication( 3335): Application created.
D/VolumeInfo( 3335): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3335): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3335): Found 0 mount point(s)
,V/VolumeInfo( 3335): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3335): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3335): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3335): Can not create volume ID for unmounted volume null
,D/CustomizationManager( 3301):  Read ACC file spent 0.057 (s)
,I/CalendarDefines( 3335): getNewCalendarAuthority()...
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__Y13
,D/CIDMapFileReader( 3301): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3301): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3301): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3301): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3301): Parsing tag category name = system
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3335, uid=10008, userID:0
,I/CustomizationCIDLoader( 3301): Parsing tag category name = application
,I/CustomizationCIDLoader( 3301): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3301): Parsing tag category name = AutomotiveHome
D/SyncApplication( 3335): enableAppOperation()+
I/CustomizationCIDLoader( 3301): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3301): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3301): Parsing tag category name = Settings
D/CustomizationManager( 3301):  Read CID file spent 0.099 (s)
,D/CustomizationManager( 3301):  All configurations done spent 0.099 (s)
,D/SyncApplication( 3335): enableAppOperation()-
,D/HTCUtilities( 3335): isNeorSinged() + 
W/HtcNativeFlag( 3301): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3301): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3301): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3301): Fail to get flag for type 'language', use default value: -1
,D/HTCUtilities( 3335): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3335): isNeorSinged() return false
D/CDMountReceiver( 3335): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3335): USB connected to PC
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3335, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/FOTAReceiver( 3335): onReceive() enter 
,D/FOTAReceiver( 3335): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3355 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3092
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3092:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3301, uid=2000 user=0
I/ActivityManager(  906): Recipient 3092
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=2724
,W/asset   (  906): Copying FileAsset 0x69fd8f30 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,D/HtcFingerPrintQuickLaunchProvider( 3355): -onCreate()
I/ActivityManager(  906): Killing 2724:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{42886668 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  906): Skipping PackageSetting{42afce40 com.test.thalitest/10389} due to missing metadata
,V/Settings:HtcSettingsApplication( 3355): [3355/3355] onCreate()
I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,D/TetherSettings( 3355): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3355): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3355): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3355): Cust_ConnectToPC   : spcsc>false
D/        ( 3355): Cust_ConnectToPC   : IPT>true
,D/        ( 3355): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3355): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/InputDispatcher(  906): channel '42d44ba8 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42d44ba8 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1110): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1534): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1534): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
I/Prism.ItemManager( 3270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
D/PMS     (  906): acquireWL(430aa080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1201 10029 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 3270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 3143): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 1302): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/TetherSettings( 3355): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3355): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3355): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3355): Cust_ConnectToPC   : spcsc>false
,D/        ( 3355): Cust_ConnectToPC   : IPT>true
D/        ( 3355): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3355): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3355): hasRemovableStorageSlot: true
,D/PMS     (  906): releaseWL(430aa080): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/SmartNS_Utility( 3355): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3355): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3355): usb_cable_connect = 1
,D/SmartNS_Utility( 3355): usb_denied = 0
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42d44ba8 com.example.hello.MainActivity (s)'
I/FeedHostManager( 1251): [onResume]
,I/FeedProviderManager( 1251): onResume
I/SocialFeedProvider( 1251): +onResume
I/SocialFeedProvider( 1251): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1251): -onResume
,I/ConnectivityHelper( 1251): [getCurrentConnectionType] no network connection
I/WindowState(  906): WIN DEATH: Window{42d44ba8 u0 com.example.hello/com.example.hello.MainActivity}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1251/10076)
,I/WindowManager(  906): WINDOW DIED Window{42d44ba8 u0 com.example.hello/com.example.hello.MainActivity}
W/AccTypeManager( 1302): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1302): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1251): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SmartNS_NSReceiver( 3355): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3355): USB = true hasTethered = false isNSOpening: false
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/PSReceiver( 3355): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/ContextImpl( 3355): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
W/AccTypeManager( 3143): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3143): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 1302): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/SmartNS_PSService( 3355): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3355): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3355):  defaultType:0
I/SmartNS_PSService( 3355): fail notificaiton:false
D/SmartNS_Utility( 3355): usb_cable_connect = 1
D/SmartNS_Utility( 3355): usb_denied = 0
I/SmartNS_PSService( 3355): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3355/1000)
,E/ExternalAccountType( 3143): Unsupported attribute readOnly
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/SmartNS_Utility( 3355): usb_cable_connect = 1
D/SmartNS_Utility( 3355): usb_denied = 0
,I/SmartNS_PSService( 3355): usb notificaiton:true
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3355/1000)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3355): usb_cable_connect = 1
D/SmartNS_Utility( 3355): usb_denied = 0
D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/WeatherUtility( 3202): can't get weather sync account
I/SmartNS_PSService( 3355): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3355): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  906): Resuming delayed broadcast
,W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3376 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 2724 uid 10396
,I/InputMethodManagerService(  906): Enable input method client, pid=1251
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1251): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1251): com.google.android.googlequicksearchbox 1 1 5
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
W/ContextImpl( 3376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageService( 3376): call getInstance()
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 10 17
,D/PowerUsageList:PowerUsageHelper( 3376): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/PackageManager(  906): Unable to load service info ResolveInfo{42e76a78 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,E/SQLiteLog(  906): (3850) statement aborts at 46: [INSERT INTO secure(value,name) VALUES (?,?)] disk I/O error
,E/SQLiteDBG(  906): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.settings/databases/settings.db, handle = 0x5c91d008
,E/SQLiteDatabase(  906): Error inserting ...
E/SQLiteDatabase(  906): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase(  906): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase(  906): 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1408)
E/SQLiteDatabase(  906): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:692)
E/SQLiteDatabase(  906): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase(  906): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:312)
E/SQLiteDatabase(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase(  906): 	at dalvik.system.NativeStart.run(Native Method)
,E/SQLiteDatabase( 3376): Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
E/SQLiteDatabase( 3376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:328)
E/SQLiteDatabase( 3376): 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:245)
E/SQLiteDatabase( 3376): 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1274)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:2954)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:169)
E/SQLiteDatabase( 3376): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3376): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/PowerUsageList:PowerUsageHelper( 3376): bulkInsertData(), Exception: 
E/PowerUsageList:PowerUsageHelper( 3376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PowerUsageList:PowerUsageHelper( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.bulkInsert(SmartSyncProvider.java:328)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.content.ContentProvider$Transport.bulkInsert(ContentProvider.java:245)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.content.ContentResolver.bulkInsert(ContentResolver.java:1274)
E/PowerUsageList:PowerUsageHelper( 3376): 	at com.htc.htcpowermanager.battery.PowerUsageHelper.bulkInsertData(PowerUsageHelper.java:2954)
E/PowerUsageList:PowerUsageHelper( 3376): 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:169)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.os.Looper.loop(Looper.java:157)
E/PowerUsageList:PowerUsageHelper( 3376): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PowerUsageService( 3376): bulk insert error
I/RemoteViews( 1110): com.android.settings (true,33751552)
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/RemoteViews.Performance( 1110): com.android.settings 3 1 10
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1534): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews( 1110): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1110): com.android.settings 2 0 10
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42de6d20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3376 1000 null
D/Process (  906): killProcessQuiet, pid=3131
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3131:com.google.android.partnersetup/u0a32 (adj 15): empty #17
E/SQLiteDatabase( 3376): Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
E/SQLiteDatabase( 3376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.query(SmartSyncProvider.java:161)
E/SQLiteDatabase( 3376): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3376): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3376): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3376): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2019)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3376): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3376): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3376): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3376): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3376): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3376): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3376): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  906): releaseWL(42de6d20): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  906): Recipient 3131
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1110): can't get weather sync account
D/WeatherUtility( 1318): Weather sync is On
D/WSP     ( 1318): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3395 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3202): can't get weather sync account
,W/WeatherRequest( 3202): request cur loc, but there is no sys cur
,W/Settings( 3202): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1251): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1251): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1251): com.htc.widget.weatherclock 1 11 17
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/SQLiteDatabase( 3395): Failed to open database '/data/data/com.htc.album/databases/MMexternal.db'.
E/SQLiteDatabase( 3395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteDatabase( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteDatabase( 3395): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3395): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3395): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteDatabase( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteDatabase( 3395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3395): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteDatabase( 3395): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 3395): Couldn't open MMexternal.db for writing (will try read-only):
E/SQLiteOpenHelper( 3395): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3395): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3395): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
E/SQLiteOpenHelper( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
E/SQLiteOpenHelper( 3395): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3395): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3395): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
E/SQLiteOpenHelper( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
E/SQLiteOpenHelper( 3395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3395): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
E/SQLiteOpenHelper( 3395): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3395): (14) cannot open file at line 28969 of [00bb9c9ce4]
E/SQLiteLog( 3395): (14) os_unix.c:28969: (30) open(/data/data/com.htc.album/databases/MMexternal.db-shm) - 
E/SQLiteLog( 3395): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
,E/SQLiteDBG( 3395): func: executeOneRowQuery errno = 30, error message = Read-only file system, path = /data/data/com.htc.album/databases/MMexternal.db, handle = 0x5caa9458
,W/System.err( 3395): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
W/System.err( 3395): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
W/System.err( 3395): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:634)
W/System.err( 3395): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
W/System.err( 3395): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
W/System.err( 3395): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
W/System.err( 3395): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
W/System.err( 3395): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:918)
W/System.err( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
W/System.err( 3395): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
W/System.err( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProviderImpl.query(MediaManagerProviderImpl.java:773)
W/System.err( 3395): 	at com.htc.mediamanager.providers.media.MediaManagerProvider.query(MediaManagerProvider.java:605)
W/System.err( 3395): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3395): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:476)
W/System.err( 3395): 	at android.content.ContentResolver.query(ContentResolver.java:419)
W/System.err( 3395): 	at com.htc.mediamanager.providers.media.MMPScanner.syncMP2MMP(MMPScanner.java:206)
W/System.err( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService$ServiceHandler.handleMessage(MMPScanService.java:426)
W/System.err( 3395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3395): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3395): 	at com.htc.mediamanager.providers.media.MMPScanService.run(MMPScanService.java:352)
,W/System.err( 3395): 	at java.lang.Thread.run(Thread.java:864)
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<

```
