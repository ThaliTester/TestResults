#### Test 50388019f33194e_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/HtcModeClient( 1544): handler message = 4011
E/HtcModeClient( 1544): Check connection and retry 3 times.
D/Process (  906): killProcessQuiet, pid=2661
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3007 uid=10098 gids={50098, 3003, 5012}
I/ActivityManager(  906): Killing 2661:com.htc.aurora:remote/u0a49 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2661
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3007): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3007 dbg=false s=true
I/DeviceManagement( 3007): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 3007): WorkflowService: Starting workflow service
I/DeviceManagement( 3007): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@425084f0] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3007): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3007): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 3007): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3007): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3024 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/DeviceManagement( 3007): BackgroundController: *** Update after boot...
I/DeviceManagement( 3007): SessionStateController: Checking invariants...
I/DeviceManagement( 3007): BackgroundController: Invariants are unchanged.
W/dalvikvm( 2171): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
I/DeviceManagement( 3007): SessionStateController: Checking invariants...
D/PMS     (  906): acquireWL(4313a3c8): PARTIAL_WAKE_LOCK  Icing 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 3024): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  906): releaseWL(4313a3c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 3007): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
E/cutils-trace( 3037): Error opening trace file: No such file or directory (2)
I/ActivityManager(  906): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
D/PMS     (  906): acquireWL(43293b38): PARTIAL_WAKE_LOCK  Icing 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=3024, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=3024, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=3024, uid=10107, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=3024, uid=10107, userID:0
I/DeviceManagement( 3007): Perf: *** Cache update - start...
I/Icing   ( 2171): Storage manager: low false usage 2.00MB avail 7.43GB capacity 7.85GB
I/DeviceManagement( 3007): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3007): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3007): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 3007): Perf: Scan enabled apps - start...
W/dalvikvm( 2171): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
I/DeviceManagement( 3007): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
D/CustomizationManager( 3037): ====startRecUseTime====
D/htc.customization.log.level( 3037):  is 
W/CustomizationLogLevel( 3037): Level value is invalid, use default level 2
I/Gmail   ( 3024): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
I/Gmail   ( 3024): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3024): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3024): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CustomizationManager( 3037):  Read ACC file spent 0.083 (s)
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3037): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3037): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3037): Parsing tag category name = system
I/CustomizationCIDLoader( 3037): Parsing tag category name = application
I/CustomizationCIDLoader( 3037): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3037): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3037): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3037): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3037): Parsing tag category name = Settings
D/CustomizationManager( 3037):  Read CID file spent 0.130 (s)
D/CustomizationManager( 3037):  All configurations done spent 0.130 (s)
W/HtcNativeFlag( 3037): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3037): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3037): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3037): Fail to get flag for type 'language', use default value: -1
W/asset   (  906): Copying FileAsset 0x62aa3d40 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1124275496
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3037
D/PMS     (  906): acquireHCC(43283d00): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(4327c1e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42648cf8
D/PMS     (  906): acquireWL(43277618): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3071 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
W/asset   ( 3071): Copying FileAsset 0x5c8ad420 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1270): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3071): Binding Chromium to main looper Looper (main, tid 1) {424dce68}
I/LibraryLoader( 3071): Expected native library version number "",actual native library version number ""
I/chromium( 3071): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3071): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(43135790): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(43135538): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f00fd0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3071): 1112483936: getState(). Returning 12
D/PMS     (  906): releaseWL(43135790): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3071): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3071): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3071): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3071): Local Branch: 
I/Adreno-EGL( 3071): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3071): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3071):                  aa63bbd948f41d15fc72f585e
I/Icing   ( 2171): updateResources: need to parse f{com.google.android.gms}
W/chromium( 3071): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3071): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3071): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3071): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3071): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3071): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3071): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3071): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3071): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3071): CordovaWebView is running on device made by: HTC
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
,I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
W/AwContents( 3071): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1270
W/ResourceType( 3071): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3071): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@42523cd0, mServedView=org.apache.cordova.engine.SystemWebView{424e9b80 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=3071
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +279ms
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
W/AwContents( 3071): nativeOnDraw failed; clearing to background color.
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
I/Icing   ( 2171): Internal init done: storage state 0
D/PMS     (  906): releaseWL(43277618): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/Icing   ( 2171): Post-init done
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
D/PMS     (  906): releaseWL(43293b38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  906): killProcessQuiet, pid=2677
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2677:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2677
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 3007): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
E/AndroidProtocolHandler( 3071): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3071): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/DeviceManagement( 3007): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
D/JsMessageQueue( 3071): Set native->JS mode to OnlineEventsBridgeMode
I/DeviceManagement( 3007): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 3007): Perf: Scan enabled apps - complete: 831 ms
I/DeviceManagement( 3007): Perf: *** Enabled app cache update - complete: 833 ms
I/DeviceManagement( 3007): Perf: *** Config cache update - start...
I/DeviceManagement( 3007): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3007): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 3007): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 3007): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 3007): AlarmController: Scheduling TTL alarm for: 2015.12.05 at 10:47:47.602 CET (due to: com.htc.aurora)
I/DeviceManagement( 3007): Perf: *** Config cache update - complete: 13 ms
I/DeviceManagement( 3007): Perf: *** Cache update - complete: 847 ms
I/DeviceManagement( 3007): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@425084f0]
I/DeviceManagement( 3007): WorkflowService: Stopping workflow service
D/Process (  906): killProcessQuiet, pid=2691
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3007, uid=10098, userID:0
I/ActivityManager(  906): Killing 2691:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ActivityManager(  906): Recipient 2691
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=3024, uid=10107, userID:0
I/ActivityManager(  906): Resuming delayed broadcast
D/jxcore_app_log( 3071): JniHelper::setJavaVM(0x42099010), pthread_self() = 1658298088
D/JX-Cordova( 3071): jxcore cordova android initializing
I/ActivityManager(  906): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3119 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/jxcore-log( 3071): Initializing JXcore engine
W/jxcore-log( 3071): JXcore engine is ready
W/jxcore-log( 3071): Starting JXcore engine
W/jxcore-log( 3071): Platform android
W/jxcore-log( 3071): 
W/jxcore-log( 3071): Process ARCH arm
W/jxcore-log( 3071): 
I/htcbackup-core( 3119): ModelRegistry: Loading model meta data from resources...
W/ContextImpl( 3119): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3119): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 3007): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 3007): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.CSDFunctionG, com.htc.home.personalize, com.htc.checkinprovider, com.android.inputdevices, com.android.settings, com.htc.backup, com.htc.mirrorlinkserver, com.htc.android.htcsetupwizard, com.android.providers.settings, com.htc.htcpowermanager, com.htc.smartdim, com.htc.usage, com.android.keychain, com.qualcomm.timeservice, com.htc.drive.activator, com.htc.lockscreen, com.htc.autobot.cargps.provider, com.htc.feedback, com.htc.android.htcloglevel, com.htc.guide, com.htc.backupreset, com.android.location.fused, android, com.htc.cirmodule, com.qualcomm.privinit]
I/DeviceManagement( 3007): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/DeviceManagement( 3007): WorkflowService: Starting workflow service
I/DeviceManagement( 3007): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42809610] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3007): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3007): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3007): SessionStateController: Checking invariants...
I/jxcore-log( 3071): JXcore Cordova bridge is ready!
I/jxcore-log( 3071): 
W/jxcore-log( 3071): JXcore engine is started
W/ContextImpl( 3119): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/ActivityManager(  906): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/RemoteViews( 1113): com.htc.backup (true,33751552)
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{425615a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1113): com.htc.backup 2 7 4 15
I/RemoteViews( 1113): com.htc.backup (true,33751552)
I/DeviceManagement( 3007): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{4256a8f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DeviceManagement( 3007): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42809610]
I/RemoteViews( 1113): com.htc.backup (true,33751552)
I/DeviceManagement( 3007): WorkflowService: Stopping workflow service
I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews.Performance( 1113): com.htc.backup 1 4 5 4
I/RemoteViews( 1113): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1113): com.htc.backup 1 1 1 4
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3140 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/RemoteViews( 1113): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1113): com.htc.backup 3 1 1 4
I/RemoteViews.Performance( 1113): com.htc.backup 0 9 20 21
E/jxcore-log( 3071): >> HTC-HTC Desire 820
E/jxcore-log( 3071): 
I/jxcore-log( 3071): Total memory 1964650496
I/jxcore-log( 3071): 
I/jxcore-log( 3071): Free memory 672940032
I/jxcore-log( 3071): 
I/jxcore-log( 3071): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3071): 
I/jxcore-log( 3071): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3071): 
I/jxcore-log( 3071): userPath [ 'www' ]
I/jxcore-log( 3071): 
I/jxcore-log( 3071): Size 720 1184
I/jxcore-log( 3071): 
I/jxcore-log( 3071): Screen Brightness 142
I/jxcore-log( 3071): 
E/jxcore-log( 3071): Dummy Error Log.
E/jxcore-log( 3071): 
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=5 [17][1][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:68, mTXpacketCount:47, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/htcbackup-core( 3119): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  906): sending alarm PendingIntent{42db3568: PendingIntentRecord{4267cb48 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=14, w=1440901414353, Int=604800000
,W/dalvikvm( 3119): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews( 1113): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1113): com.htc.backup 1 2 15
,I/RemoteViews( 1113): com.htc.backup (true,33751552)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1113): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1113): com.htc.backup 0 2 0 4
,I/RemoteViews( 1113): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1113): com.htc.backup 1 1 0 4
,I/RemoteViews( 1113): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1113): com.htc.backup 1 1 0 4
,I/RemoteViews.Performance( 1113): com.htc.backup 2 10 21
,D/UPolicy ( 3119): IUserBehaviorLoggingService reference is gotten !
,D/Process (  906): killProcessQuiet, pid=2711
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2711:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2711
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3140): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3140): MmsConfig.loadMmsSettings
,W/dalvikvm( 3140): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3140): VFY: unable to resolve instance field 46
,W/dalvikvm( 3140): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MmsCustomizationProvider( 2796): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2796): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3140): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3140): MmsConfig.loadFromDatabase
,E/Babel   ( 3140): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3140): MmsConfig.loadFromResources
,E/Babel   ( 3140): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3140): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3140, uid=10111, userID:0
W/Settings( 3140): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3140, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3140, uid=10111, userID:0
V/Babel   ( 3140): babel boot account: thalitester@gmail.com
V/Babel   ( 3140): babel boot account: SMS
,I/ActivityManager(  906): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3169 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2733
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2733:com.htc.video/u0a57 (adj 15): empty #17
,I/ProviderInstaller( 3140): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  906): Recipient 2733
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  906): sending alarm PendingIntent{42cd7e08: PendingIntentRecord{43162f58 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47925, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42cd10b8: PendingIntentRecord{43163d88 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47926, Int=0
,I/ActivityManager(  906): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3186 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  906): killProcessQuiet, pid=2765
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2765:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2765
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ResetNotifyBootCompleteReceiver( 1238): Receive bootcomplete intent
,W/ContextImpl( 1238): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/HtcCupdXmlParser( 3186): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3201 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/ActivityThread( 3186): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/dalvikvm-heap( 1238): Grow heap (frag case) to 12.418MB for 2097144-byte allocation
,I/jxcore-log( 3071): getBuffer is called!!!!
I/jxcore-log( 3071): 
,D/AppTag  ( 3201): getInstance(Context context)
,D/AppTag  ( 3201): getInstance(Context context)
,D/AppTag  ( 3201): onCreate()
,D/QXDM2SD:HtcNative( 1238): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3216 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=2845
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2845:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/HtcCupdXmlParser( 3186): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  906): Recipient 2845
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 3216): [3216/3216] onCreate()
W/ContextImpl( 3216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3229 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2750
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2750:com.android.defcontainer/u0a19 (adj 15): empty #17
I/AlarmManager(  906): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  906): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  906): [AlarmQueuing] init alarm queuing list
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2750
,I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3241 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  906): killProcessQuiet, pid=2863
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2863:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2863
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3229): -onCreate()
,V/Settings:HtcSettingsApplication( 3229): [3229/3229] onCreate()
W/ContextImpl( 3229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3229): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3229): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3229): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3229): Cust_ConnectToPC   : spcsc>false
D/        ( 3229): Cust_ConnectToPC   : IPT>true
,D/        ( 3229): Cust_ConnectToPC   : Singel_USB>false
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@43014528
,I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42f9cb00
W/Settings( 3229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3229): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3229): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3229): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3229): Cust_ConnectToPC   : spcsc>false
D/        ( 3229): Cust_ConnectToPC   : IPT>true
D/        ( 3229): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3229): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3229): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3229): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 3229): setISNotification
,D/SmartNS_Utility( 3229): usb_cable_connect = 1
,D/SmartNS_Utility( 3229): usb_denied = 0
I/SmartNS_PSService( 3229): usb notificaiton:true
D/Process (  906): killProcessQuiet, pid=2876
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  906): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42f4a470
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  906): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  906): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  906): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
I/ActivityManager(  906): Killing 2876:com.htc.showme/u0a83 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3229/1000)
V/Tethering(  906): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 3229): usb_cable_connect = 1
D/SmartNS_Utility( 3229): usb_denied = 0
I/SmartNS_PSService( 3229): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  906): bSetPropertyMultiRAB:false
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3229/1000)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 2876
D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  906): killProcessQuiet, pid=2890
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 2890:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2890
,I/RemoteViews( 1113): com.android.settings (true,33751552)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{4261c618 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.android.settings 2 7 0 10
,I/RemoteViews( 1113): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1113): com.android.settings 1 0 10
I/ActivityManager(  906): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3258 uid=9987 gids={49987}
,I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@430c8d70, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@430c8d70, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42dc3400
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@42b3de78
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@430c8d70
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@430c8d70, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42fb8668 u0 ReceiverList{42e877a0 906 system/1000/u0 local:42ac6138}}
,D/NfcUiccLockService( 3258): -- To check whether previous opened channel needed to be closed ...
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(43283d00): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(4327c1e8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/Process (  906): killProcessQuiet, pid=2919
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3272 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  906): Killing 2919:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 3
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@430c8d70, eanble = 1, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42dc3400
W/SensorService(  906): Listener[1] = com.android.server.power.DisplayPowerController$10@42b3de78
W/SensorService(  906): Listener[2] = com.htc.smartdim.sensor_eye@430c8d70
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  906): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3284 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=2957
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2957:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2957
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2919
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 3284): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 3284): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 3284): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 3284): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3284/10168)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3284): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3284): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3284): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3284): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 3284): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.youtube (pid 3284): Registered
,I/MediaRouter( 3284): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/YouTube ( 3284): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3284): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449275236&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.youtube (3284/10168)
D/libc    ( 3284): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3284): [NET] getaddrinfo-,err=8
D/libc    ( 3284): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3284): [NET] getaddrinfo-, 1
D/libc    ( 3284): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =781b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3284): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3284): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3284/10168)
D/YouTube ( 3284): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/MediaRouter( 3284): getSelectedRoute
D/YouTube ( 3284): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3284): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 3284): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3284/10168)
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=96
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3284): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3284/10168)
I/ActivityManager(  906): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/YouTube ( 3284): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3284): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3284): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
,D/YouTube ( 3284): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3284): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
,D/YouTube ( 3284): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service,
,I/GoogleConversionPing( 3284): Ping responded with response code 200
,D/YouTube ( 3284): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3284): apps.youtube.datalib.offline.b.run:86 Dispatching stored offline request immediately.
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3284/10168)
,W/dalvikvm( 3284): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3284): VFY: unable to resolve instance field 46
,W/dalvikvm( 3284): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3284): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ProviderInstaller( 3284): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 2171): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;,
D/libc    ( 3284): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 4
D/libc    ( 3284): [NET] getaddrinfo-,err=8
D/libc    ( 3284): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    ( 3284): [NET] getaddrinfo-, 1
D/libc    ( 3284): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e796f75),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ccbf +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/FileApkUtils( 2171): Spent 21ms computing apk sha1.
,D/FileApkUtils( 2171): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 2171): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/FileApkUtils( 2171): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/libc    (  363): [NET]res_nsend:resplen=83
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3284): [NET] getaddrinfo_proxy-, success
I/global  ( 3284): call createSocket() return a new socket.
D/libc    ( 3284): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3284): [NET] getaddrinfo-, SUCCESS
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,E/dalvikvm( 2171): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 2171): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/PMS     (  906): acquireWL(42a421d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
D/GmsModuleFndr( 2171): Beginning GMS chimera module scan
,W/asset   ( 2171): Copying FileAsset 0x665e6fa0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,E/dalvikvm( 2171): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 2171): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 2171): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 2171): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2171): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 2171): Beginning module configuration check
,D/ChimeraCfgMgr( 2171): Module APKs unchanged, check complete
,D/PMS     (  906): acquireWL(429a52f0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428f0310): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 2171): COMPAT: Multi user not supported
,D/GCM     ( 1358): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  906): releaseWL(42a421d0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2171): Checkin interval check for package: unspecified last checkin: 1449261991062 min interval config: 0 actual interval: 13245928
,I/GCoreUlr( 2171): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1222): DispatchingService.onCreate()
I/CheckinService( 2171): Disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 2171): onCreate
D/SystemUpdateService( 2171): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
W/dalvikvm( 2171): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,V/AuthZen ( 2171): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 2171): cancelUpdate (empty URL)
,I/SystemUpdateService( 2171): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
D/PMS     (  906): releaseWL(43135538): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  906): acquireWL(43196918): PARTIAL_WAKE_LOCK  Icing 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PMS     (  906): acquireWL(43197a30): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2171, uid=10029, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/CheckinService( 2171): Checking schedule, now: 1449275237065 next: 1449784928008
,I/CheckinService( 2171): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2171, uid=10029, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
D/PMS     (  906): releaseWL(43196918): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2171, uid=10029, userID:0
,D/AuthZenEventHandler( 2171): Handling event: android.intent.action.BOOT_COMPLETED
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2171, uid=10029, userID:0
,D/PMS     (  906): releaseWL(428f0310): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1222): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 2171): onDestroy
D/PMS     (  906): releaseWL(429a52f0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 2904): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 2171): Google Analytics 8.3.01 is starting up.
,W/BaseAppContext( 2171): Using Auth Proxy for data requests.
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2171): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2171): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1222, uid=10029, userID:0
,W/dalvikvm( 2171): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 2171): Fetching signing key...
,I/AuthZen ( 2171): Signing key fetched successfully!
,W/BaseAppContext( 2171): Using Auth Proxy for data requests.
,I/GCoreUlr( 1222): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  906): acquireWL(431b1fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(431b1fd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/AuthZenTransactionCache( 2171): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2171): Clearing transaction cache
,I/GCoreUlr( 1222): Unbound from all location providers
D/PMS     (  906): releaseWL(43197a30): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [17][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,I/ActivityManager(  906): Resuming delayed broadcast
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,I/GCoreUlr( 1222): DispatchingService.onDestroy()
,I/GCoreUlr( 1222): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1222): Unbound from all location providers,
D/PMS     (  906): acquireWL(431c0fb0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2171 10029 null
D/PMS     (  906): acquireWL(431c14d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(431c14d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(431c2c20): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2171 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,D/PMS     (  906): releaseWL(431c0fb0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  906): releaseWL(431c2c20): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1358): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
I/ActivityManager(  906): Resuming delayed broadcast
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,W/Auth    ( 1358): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(431c7a40): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1358 10029 null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  906): releaseWL(431c7a40): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,W/dalvikvm( 1358): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1358): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,V/GmsCoreStatsServiceLauncher( 2171): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1358): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3380 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/WIFI_ICON( 1113): WifiActivity: 3
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(431d1128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(431d7428): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,I/IntentController( 1113): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(431d1128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(431daf60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(431daf60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3380, uid=10074, userID:0
,D/PhoneStatusBar( 1113): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/Finsky  ( 3380): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3380/10074)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(431e9128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(431d7428): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1113): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(431e9128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3380/10074)
,D/Finsky  ( 3380): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3380): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3380): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PhoneStatusBar( 1113): removeIcon slot=sync_active index=7 viewIndex=0
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3380): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3380, uid=10074, userID:0
,D/Volley  ( 3380): [310] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3380): [303] DiskBasedCache.clear: Cache cleared.
,D/Process (  906): killProcessQuiet, pid=2977
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Ads     ( 3380): Skipping gmscore version check
I/ActivityManager(  906): Killing 2977:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2977
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3380): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3380): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3380): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1284): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1284): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
,D/TetherSettings( 3229): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3229): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3229): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3229): Cust_ConnectToPC   : spcsc>false
D/        ( 3229): Cust_ConnectToPC   : IPT>true
D/        ( 3229): Cust_ConnectToPC   : Singel_USB>false
D/Finsky  ( 3380): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/Settings( 3229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3229): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3229): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3229): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ActivityManager(  906): Resuming delayed broadcast
,I/PSReceiver( 3229): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3229): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3229): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3229):  defaultType:0
W/ContextImpl( 3229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3421 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1174): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/browser ( 3421): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3421): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3421): Loading: swewebviewchromium
,I/HtcModeClient( 1544): handler message = 4011
,E/HtcModeClient( 1544): Check connection and retry 4 times.
I/LibraryLoader( 3421): Time to load native libraries: 34 ms (timestamps 8078-8112)
,I/LibraryLoader( 3421): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3421): Initializing chromium process, renderers=9
,I/LibraryLoader( 3421): Expected native library version number "",actual native library version number ""
,I/chromium( 3421): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 3421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3421): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3421): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3421): Local Branch: 
I/Adreno-EGL( 3421): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3421): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3421):                  aa63bbd948f41d15fc72f585e
,I/GAV2    ( 3024): Thread[GAThread,5,main]: No campaign data found.,
,D/Process (  906): killProcessQuiet, pid=2990
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1316): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/SIMStateChangeReceiver( 1544): SIM state: ABSENT
I/SIMStateChangeReceiver( 1544): phoneType = 0
,I/SIMStateChangeReceiver( 1544): remove notification
I/ActivityManager(  906): Killing 2990:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2990
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3464 uid=10032 gids={50032, 3003, 5012}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3476 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3024
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3024:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2796): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2796): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2796): onReceive()
D/ExchangePolicystatus( 2796): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2796): onReceive(): else
,D/Process (  906): killProcessQuiet, pid=3007
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1238): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  906): Killing 3007:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/WeatherUtility( 1113): can't get weather sync account
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3492 uid=10041 gids={50041}
,W/WeatherRequest( 1113): request cur loc, but there is no sys cur
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3024
,I/ActivityManager(  906): Recipient 3007
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AccTypeManager( 3476): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  906): killProcessQuiet, pid=3140
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3507 uid=10078 gids={50078}
I/ActivityManager(  906): Killing 3140:com.google.android.talk/u0a111 (adj 15): empty #17
,W/AccTypeManager( 3476): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3476): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3507): Got a database change event
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3140
,E/ExternalAccountType( 3476): Unsupported attribute readOnly
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3521 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/Process (  906): killProcessQuiet, pid=3119
,I/ActivityManager(  906): Killing 3119:com.htc.backup/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AccTypeManager( 3476): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3476): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3476): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3476): Unsupported attribute readOnly
,D/CalendarApplication( 3521): onCreate
D/ProviderChangeReceiver( 3521): ---------------------------------------------------
,D/ProviderChangeReceiver( 3521): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3521): start to updateAlertNotification!
W/ContextImpl( 3216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3521): No fired or scheduled alerts
,D/HtcAlertUtils( 3521): -- cancelReminderNotification --
,D/HtcAlertUtils( 3521): broadcastExistReminder!
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3536 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  906): Recipient 3119
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3169
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3169:com.htc.backupreset/1000 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3169
,I/MusicStore( 3536): Database version: 95
,W/ContextImpl( 3536): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3536): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3536): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3536, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3536): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/MediaRouter( 3536): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3536/10154)
,I/NetworkMonitor( 3536): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1984/10021)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3557 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3536): getSelectedRoute
,I/NetworkMonitor( 3536): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3536/10154)
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3536, uid=10154, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42e675a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/Process (  906): killProcessQuiet, pid=3186
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42e675a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  906): Killing 3186:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Recipient 3186
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: survey data missing!
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1174): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3557): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3557): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3557): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3557): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3557): Preparing secondary program dexes.
V/DexLibLoader( 3557): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3557): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3557): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3557): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3557): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3557): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
,V/DexLibLoader( 3557): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3557): Dex already copied
D/OdexVerifier( 3557): Odex verification is skipped.
,V/DexLibLoader( 3557): Creating class loader
,V/DexLibLoader( 3557): Finished creating class loader
V/DexLibLoader( 3557): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3557): Dex already copied
D/OdexVerifier( 3557): Odex verification is skipped.
,V/DexLibLoader( 3557): Creating class loader
,V/DexLibLoader( 3557): Finished creating class loader
V/DexLibLoader( 3557): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 3557): Dex already copied
D/OdexVerifier( 3557): Odex verification is skipped.
,V/DexLibLoader( 3557): Creating class loader
,V/DexLibLoader( 3557): Finished creating class loader
,V/DexLibLoader( 3557): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3557): Dex already copied
D/OdexVerifier( 3557): Odex verification is skipped.
,V/DexLibLoader( 3557): Creating class loader
,V/DexLibLoader( 3557): Finished creating class loader
,V/DexLibLoader( 3557): Verifying classes from secondary dexes.
,D/DexLibLoader( 3557): DexLibLoader.ensureDexLoaded took 132 ms
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42cc2eb8 mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1823
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  906): Sending off request.
D/BluetoothAdapterState( 1662): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1662): Setting state to 13
I/BluetoothAdapterState( 1662): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1662): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1662): onBluetoothDisable()
I/bt-btm  ( 1662): BTM_SetDiscoverability
I/bt-btm  ( 1662): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1662): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1662): br_edr_supported=0x0
I/bt-btm  ( 1662): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1662): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1662): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1662): btm_ble_update_adv_flag old=0x0
I/BluetoothAdapterState( 1662): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btm  ( 1662): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1662): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1662): BTM_SetConnectability
I/bt-btm  ( 1662): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1662): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1662): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 1662): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1662): adapterPropertyChangedCallback with type:7 len:4
,D/WifiManager( 3071): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
D/BluetoothAdapterProperties( 1662): Scan Mode:20
E/BTIF_CORE( 1662): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1662): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothAdapterState( 1662): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/WifiService(  906): New client listening to asynchronous messages
,D/PMS     (  906): acquireWL(431f7628): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1662 1002 null
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btif ( 1662): BTA_JvDeleteRecord
I/bt-btif ( 1662): BTA_JvRfcommStopServer
D/bt-btm  ( 1662): BTM_FreeSCN 
V/BluetoothSapService( 1662): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 1662): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[15]: id 54
D/BluetoothRemoteDevices( 1662): Wake lock Aquired
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1662): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1662): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1662): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1662): Write Extended Inquiry Response to controller
I/bt-btm  ( 1662): Write Extended Inquiry Response to controller
I/bt-btm  ( 1662): Write Extended Inquiry Response to controller
I/bt-btm  ( 1662): Write Extended Inquiry Response to controller
I/bt-btm  ( 1662): BTM_SetDiscoverability
I/bt-btm  ( 1662): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1662): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1662): br_edr_supported=0x0
I/bt-btm  ( 1662): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1662): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1662): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1662): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1662): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1662): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1662): BTM_SetConnectability
I/bt-btm  ( 1662): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1662): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1662): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1662): BTM_IsInquiryActive
I/bt-btm  ( 1662): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1662): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btm  ( 1662): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1662): BTM_FreeSCN 
I/bt-btm  ( 1662): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1662): AVRC_Close handle:0
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1662): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1662): L2CAP - PSM: 0x0019 not f,ound for deregistration
W/bt-l2cap( 1662): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1662): GATT_Deregister gatt_if=3
I/bt-att  ( 1662): GATT_Deregister gatt_if=4
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 12 -> 13
D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 917
V/BluetoothPbapReceiver( 1662): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
D/WifiService(  906): setWifiEnabled: false pid=3071, uid=10396
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/IntentController( 1113): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 3(ms)
V/BluetoothPbapReceiver( 1662): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1781): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@42501270
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1781): onDeInitialized
D/BluetoothMasReceiver( 1662): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1662): SapReceiver onReceive 
V/BluetoothSapReceiver( 1662): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1662):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1662): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1781): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1781): getNotificationManager
V/BluetoothPbapService( 1662): Pbap Service closeService in
D/PMS     (  906): acquireWL(42e34fd0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1222 10029 null
D/PMS     (  906): acquireWL(42f55868): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3229 1000 null
W/ContextImpl( 3229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/BluetoothAdapter( 1222): 1115541040: getState(). Returning 13
D/BluetoothAdapter( 1222): 1115541040: getState(). Returning 13
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/PMS     (  906): releaseWL(42f55868): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  906): acquireWL(431816c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3229 1000 null
D/PMS     (  906): releaseWL(42e34fd0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4326ec70:true
I/jxcore-log( 3071): ****TEST TOOK:  5092  ms ****
I/jxcore-log( 3071): 
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
I/jxcore-log( 3071): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3071): 
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/WirelessDisplayService(  906): getMirrorDisplayStatus:falsecurState:1
I/LocationAgent( 3229): new LocationAgent instance!!
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/HtcTagManager( 3229): HtcTagManager construction complete
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42f68930): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 0
I/wpa_supplicant( 1174): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
,D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024930
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029472
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3577 uid=10040 gids={50040, 3002, 3001}
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothAdapter( 3229): 1112857416: getState(). Returning 13
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothInputDevice( 3229): BluetoothInputDevice()
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20989 mDataStallAlarmIntent=PendingIntent{42dbd020: PendingIntentRecord{42da90a0 android broadcastIntent}}
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothAdapter( 3229): 1112857416: getState(). Returning 13
D/BluetoothInputDevice( 3229): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3229): Bluetooth service connected
W/BluetoothInputDevice( 3229): Proxy not attached to service
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/BluetoothPan( 3229): BluetoothPan()
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BluetoothManagerService(  906): registerStateChangeCallback+
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
V/AlarmManager(  906): sending alarm PendingIntent{42d08f90: PendingIntentRecord{426ff1e8 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=47743, Int=259200000
V/AlarmManager(  906): sending alarm PendingIntent{427ede40: PendingIntentRecord{42e85fc8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51040, Int=0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  906):    returned null
D/BluetoothAdapter( 3229): 1112857416: getState(). Returning 13
D/BluetoothPan( 3229): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3229): Bluetooth service connected
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 8
V/BluetoothPbapService( 1662): successfully stopped pbap service
V/BluetoothPbapService( 1662): Pbap Service closeService out
D/BluetoothMap( 3229): Create BluetoothMap proxy object
V/BluetoothSapService( 1662): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1662): state: 13
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 1662): 1112484632: getState(). Returning 13
V/BluetoothSapService( 1662): Stopping SAP server process
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1781): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1781):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1781): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1781): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1781): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1781):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1781): deinit: 0
D/BluetoothManagerService(  906): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  906): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43226c20:true
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm
V/BluetoothSapService( 1662): Sap Service closeSapService in
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1781): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1781): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1781): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1781): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1781): setPendingRequestAlarm: false, mContext = null, null
V/BluetoothSapService( 1662): Close listen Socket : 
V/BluetoothSapService( 1662): Close rfcomm Socket : 
V/BluetoothSapService( 1662): Close sapd  Socket : 
V/BluetoothSapReceiver( 1662): BluetoothSapReceiver deinit
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  906): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1174): Power_Mode_Type mode = 0
I/wpa_supplicant( 1174): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 61
V/BluetoothSapService( 1662): successfully stopped Sap service
V/BluetoothSapService( 1662): Sap Service closeSapService out
I/BtOppRfcommListener( 1662): stopping Accept Thread
D/WifiNative-wlan0(  906):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1781): Exit IdleState
I/BtOppRfcommListener( 1662): BluetoothSocket listen thread finished
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1174): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1174): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
E/BluetoothMap( 3229): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiNative-wlan0(  906):    returned true
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  906): convertEffect before=902
D/HtcEffectManager(  906): convertEffect after=902
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 10
V/BluetoothPbapService( 1662): Pbap Service onDestroy
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  906): P2pDisablingState
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WifiP2pService(  906): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): p2p socket connection lost
D/WifiP2pService(  906): P2pDisabledState
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  906): set wifi.miracastlock to 0 for disconnect case
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  906): updateConnection
D/WifiP2pService(  906): P2pDisabledState{ when=-3ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-3ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  906): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  906): updateConnection enter step 4
D/WifiDisplayController(  906): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
V/BluetoothPbapService( 1662): Pbap Service closeService in
V/BluetoothPbapService( 1662): Pbap Service closeService out
D/BluetoothSap( 3229): BluetoothSap() call bindService
V/BluetoothSapService( 1662): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@4252b5c0
V/BluetoothSapService( 1662): Sap Service closeSapService in
V/BluetoothSapService( 1662): Close listen Socket : 
V/BluetoothSapService( 1662): Close rfcomm Socket : 
V/BluetoothSapService( 1662): Close sapd  Socket : 
V/BluetoothSapService( 1662): Sap Service closeSapService out
V/BluetoothSapService( 1662): ***onDestroyed***
V/NativeCrypto( 1358): Read error: ssl=0x62f8ae20: I/O error during system call, Connection timed out
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-p2p0(  906): doBoolean: TERMINATE
W/WifiHW  (  906): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1174): Supplicant Terminat @ wpa_supplicant_deinit function
I/QuickSettingBluetooth( 1113): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/libc    (  363): [NET] entry_id:5   entry:0xb8df3520  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb8df2d90  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8df3860  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8df3240  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8df3310  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8df3428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8df30e8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PhoneStatusBar( 1113): removeIcon slot=bluetooth index=12 viewIndex=0
D/WifiNative-p2p0(  906):    returned true
D/wpa_supplicant( 1174): TDLS: Tear down peers
I/wpa_supplicant( 1174): wpa_driver_nl80211_disconnect(reason_code=3)
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
W/ContextImpl( 3229): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
V/NativeCrypto( 1358): SSL shutdown failed: ssl=0x62f8ae20: I/O error during system call, Broken pipe
D/BluetoothPbap( 3229): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/HtcBtWidget_BTWidgetProvider( 3577): onBTStateChanged() for widget: 
D/BluetoothManagerService(  906): Registered receivers: 11
I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/HtcBtWidget_BTWidgetProvider( 3577): updateWidget(context) for widget: 
D/BluetoothAdapter( 3229): 1112857416: getState(). Returning 13
D/BluetoothPbap( 3229): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3229): Bluetooth service connected
D/LocalBluetoothProfileManager( 3229): LocalBluetoothProfileManager construction complete
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1113): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/PMS     (  906): acquireWL(430df290): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/DockEventReceiver( 3229): finishStartingService: stopping service
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024256
D/PMS     (  906): acquireWL(430e77f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024930
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029472
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1113): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3229): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1174): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1174): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1174): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1174): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7b72bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1174):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1174): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1174): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1174): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1174): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1358/10029)
D/PMS     (  906): releaseWL(431816c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WISPrService( 3229): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-3ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1662): Shutdown
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,D/WISPrService( 3229): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3229): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/PMS     (  906): releaseWL(430df290): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): mActiveDefaultNetwork: -1
,D/BluetoothMasReceiver( 1662): Bluetooth STATE CHANGED to 13
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1781): Received state change = 13
,I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:0
,D/Process (  906): killProcessQuiet, pid=3201
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1781): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@42501270
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): onDestroy() called...
,I/QuickSettingWifi( 1113): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1781): deinitLeServices: null
D/PMS     (  906): releaseWL(430e77f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/ActivityManager(  906): Killing 3201:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,D/WifiService(  906): New client listening to asynchronous messages
,D/Process (  906): killProcessQuiet, pid=3241
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1358): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  906): Killing 3241:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,W/bt-btif ( 1662): ag scb idx 1 not allocated
,W/bt-btif ( 1662): ag scb idx 2 not allocated
E/bt-btif ( 1662): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1662): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1662): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 1662): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1662): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1662): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1662): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt_userial_mct( 1662): userial_close userial_thread_created userial_running is 1 
,I/ActivityManager(  906): Recipient 3241
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3201
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1174): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1174): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1174): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,E/cutils-trace( 3595): Error opening trace file: No such file or directory (2)
,D/wpa_supplicant( 1174): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1174): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1174): nl80211: Unsubscribe mgmt frames handle 0xb7b73718 (mode change)
I/wpa_supplicant( 1174): htc_wext_command_deinit +
I/wpa_supplicant( 1174): htc_wext_command_deinit -
,E/wpa_supplicant( 1174): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1174): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1174): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1174): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1174): TDLS: Tear down peers
I/wpa_supplicant( 1174): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1174): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1174): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1174): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1174): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1174): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1174): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1174): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
,D/Tethering(  906): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,W/dalvikvm( 3557): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/CustomizationManager( 3595): ====startRecUseTime====
D/htc.customization.log.level( 3595):  is 
,W/CustomizationLogLevel( 3595): Level value is invalid, use default level 2
,E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x62dabca0
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x62dabdc0
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  906): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  906):    returned false
,D/WifiStateMachine(  906): Enter handleNetworkDisconnect
I/IntentController( 1113): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  906): WIFI Trun OFF
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,I/bt-btif ( 1662): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1662): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,W/Settings( 1222): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetService( 1662): Received stop request...Stopping profile...
D/WIFI_ICON( 1113): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 6 { when=-117ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1113): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/BluetoothAdapterState( 1662): Stopping profile services that were post enabled
,D/BluetoothHeadset(  906): Proxy object disconnected
D/PMS     (  906): acquireWL(431ff8e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WIFI_ICON( 1113): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/BluetoothHeadset( 1238): Proxy object disconnected
D/BluetoothHeadset( 1238): Proxy object disconnected
D/BluetoothPhoneService( 1238): BluetoothHeadset onServiceDisconnected
D/A2dpService( 1662): Received stop request...Stopping profile...
D/A2dpStateMachine( 1662): doQuit
D/BluetoothHeadset( 1113): Proxy object disconnected
D/A2dpStateMachine( 1662): Exit Disconnected: -1
I/QuickSettingMiniLite( 1113): btListener.disconnect:HEADSET
D/BluetoothA2dp(  906): Proxy object disconnected
D/WISPrService( 3229): >>>>>WISPrService start isConnected = false<<<<<
D/HidService( 1662): Received stop request...Stopping profile...
D/WISPrService( 3229): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HealthService( 1662): Received stop request...Stopping profile...
D/PanService( 1662): Received stop request...Stopping profile...
D/PanService( 1662): stop
D/PanService( 1662): stop: mTetherAc send disconnect
D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  906): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  906): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1662): Profile still running: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 1662): handleDebugAction() action=null
D/BtGatt.GattService( 1662): Received stop request...Stopping profile...
D/BtGatt.GattService( 1662): stop()
W/BluetoothHeadsetServiceJni( 1662): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1662): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1662): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 1662): cleanup
D/Avrcp   ( 1662): Unregistering previous receiver
D/BluetoothAdapterService( 1662): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1662): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1662): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1662): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1662): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1662): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1662): Cleaning up Bluetooth Health object
D/PanService( 1662): CMD_CHANNEL_DISCONNECTED
D/PanService( 1662): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1662): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1662): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1662): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1662): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1662): Setting state to 10
I/BluetoothAdapterState( 1662): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1662): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1113): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1662): Entering OffState
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
D/BluetoothSap( 3229): onBluetoothStateChange on: false
D/BluetoothInputDevice( 3229): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3229): 
E/BluetoothInputDevice( 3229): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@42559288
E/Blu,etoothInputDevice( 3229): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3229): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3229): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3229): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3229): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3229): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3229): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothPbap( 3229): onBluetoothStateChange: up=false
E/BluetoothPbap( 3229): 
E/BluetoothPbap( 3229): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@42562618
E/BluetoothPbap( 3229): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3229): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3229): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3229): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3229): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3229): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3229): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 1238): onBluetoothStateChange: up=false
E/BluetoothPan( 3229): 
E/BluetoothPan( 3229): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@4255a820
E/BluetoothPan( 3229): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3229): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3229): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3229): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3229): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3229): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3229): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothMap( 3229): onBluetoothStateChange: up=false
E/BluetoothMap( 3229): 
E/BluetoothMap( 3229): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@4255bba0
E/BluetoothMap( 3229): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3229): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3229): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3229): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3229): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3229): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3229): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset(  906): onBluetoothStateChange: up=false
D/BluetoothA2dp(  906): onBluetoothStateChange: up=false
I/QuickSettingWifi( 1113): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
D/BluetoothManagerService(  906): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1662): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@424f0f88
D/BluetoothDevice( 1662): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1662): onBluetoothServiceDown: done
D/BluetoothAdapter( 1781): onBluetoothServiceDown: android.bluetooth.IBlu,etooth$Stub$Proxy@42501b40
D/BluetoothAdapter( 1781): onBluetoothServiceDown: done
D/BluetoothAdapter( 1238): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@427889d8
D/BluetoothAdapter( 1238): onBluetoothServiceDown: done
D/BluetoothAdapter( 3071): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424f32c8
D/BluetoothAdapter( 3071): onBluetoothServiceDown: done
D/BluetoothAdapter( 1249): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425ad6e0
D/BluetoothAdapter( 1249): onBluetoothServiceDown: done
D/BluetoothAdapter( 1113): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@428cea38
D/BluetoothAdapter( 1113): onBluetoothServiceDown: done
D/BluetoothAdapter(  906): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42cc2eb8
D/BluetoothAdapter(  906): onBluetoothServiceDown: done
D/BluetoothAdapter( 1358): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4259e118
D/BluetoothAdapter( 1358): onBluetoothServiceDown: done
D/BluetoothAdapter( 1222): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@427dee28
D/BluetoothDevice( 1222): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1222): onBluetoothServiceDown: done
D/BluetoothAdapter( 3229): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4254e5b0
D/BluetoothAdapter( 3229): onBluetoothServiceDown: done
D/BluetoothManagerService(  906): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42cc2eb8 mBinding = false
D/BluetoothManagerService(  906): Sending unbind request.
D/BluetoothManagerService(  906): Bluetooth State Change Intent: 13 -> 10
D/CustomizationManager( 3595):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3595): Parsing tag item name = HTC__031
D/PMS     (  906): releaseWL(431f7628): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
V/CustomizationCIDLoader( 3595): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3595): Parsing tag category name = system
I/CustomizationCIDLoader( 3595): Parsing tag category name = application
I/CustomizationCIDLoader( 3595): Parsing tag category name = SettingsProvider
D/BluetoothAdapterService( 1662): Cleaning up adapter native....
I/CustomizationCIDLoader( 3595): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3595): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3595): Parsing tag category name = ACC
D/NfcHandover( 1249): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
I/IntentController( 1113): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
I/CustomizationCIDLoader( 3595): Parsing tag category name = Settings
D/CustomizationManager( 3595):  Read CID file spent 0.105 (s)
D/CustomizationManager( 3595):  All configurations done spent 0.106 (s)
D/LocalBluetoothProfileManager( 3229): setBluetoothStateOff
D/HtcTagManager( 3229): stopProxy
W/BluetoothEventManager( 3229): unregister mProfileBroadcastReceiver fail
I/bt-btif ( 1662): HAL bt_hal_cbacks->thread_evt_cb
I/QuickSettingWifi( 1113): receive.wifiConnect:false wifiAPname:null elapse:1
D/BluetoothAdapterService( 1662): Done cleaning up adapter native....
D/BluetoothAdapterService(1112466456)( 1662): ****onDestroy()********
W/HtcNativeFlag( 3595): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3595): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3595): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3595): Fail to get flag for type 'language', use default value: -1
D/BtGatt.GattService( 1662): cleanup()
W/bt-btif ( 1662): GATTC Module not enabled/already disabled
W/bt-btif ( 1662): GATTS Module not enabled/already disabled
D/BluetoothMasReceiver( 1662): Bluetooth STATE CHANGED to 10
D/PMS     (  906): acquireWL(4324e268): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1222 10029 null
D/BluetoothAdapter( 1222): 1115541040: getState() :  mService = null. Returning STATE_OFF
V/BluetoothMasService( 1662): onDestroy: mIsEmailEnabled: true
D/TetherPref( 3229): persistRestoreBluetoothState false
D/BluetoothAdapter( 1222): 1115541040: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  906): acquireWL(430286e8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3229 1000 null
W/ContextImpl( 3229): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/HtcBtWidget_BTWidgetProvider( 3577): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3577): updateWidget(context) for widget: 
D/BluetoothMasReceiver( 1662): Bluetooth STATE CHANGED to 10
D/DockEventReceiver( 3229): finishStartingService: stopping service
D/PMS     (  906): releaseWL(4324e268): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  906): releaseWL(430286e8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  906): acquireWL(43090608): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3229 1000 null
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1781): Received state change = 10
D/PMS     (  906): releaseWL(43090608): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ed8ff8:true
I/LocationAgent( 3216): new LocationAgent instance!!
D/HtcTagManager( 3216): HtcTagManager construction complete
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3216): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 12
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3216): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3216): Bluetooth service connected
W/BluetoothInputDevice( 3216): Proxy not attached to service
D/BluetoothAdapter( 1113): 1115193752: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3216): BluetoothPan()
I/QuickSettingBluetooth( 1113): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3216): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3216): Bluetooth service connected
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothMap( 3216): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 14
E/BluetoothMap( 3216): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothSap( 3216): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 15
W/BluetoothHeadset( 1113): Proxy not attached to service
I/QuickSettingMiniLite( 1113): updateLiteState:no connect device!
D/BluetoothPbap( 3216): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3216): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3216): Bluetooth service connected
D/LocalBluetoothProfileManager( 3216): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3216): 1112575040: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3216): setBluetoothStateOff
D/HtcTagManager( 3216): stopProxy
W/BluetoothEventManager( 3216): unregister mProfileBroadcastReceiver fail
D/Process (  906): killProcessQuiet, pid=3258
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3595, uid=2000 user=0
W/ContextImpl( 3216): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
I/ActivityManager(  906): Killing 3258:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/AuthorizationBluetoothService( 1358): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  906): Recipient 3258
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  906): killProcessQuiet, pid=3071
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  906): Copying FileAsset 0x6320ede8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  906): Killing 3071:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  906): Force removing ActivityRecord{42ae5460 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  906): Skipping PackageSetting{42c88e60 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  906): Force stopping com.example.hello appid=10396 user=0: pkg removed
,W/InputDispatcher(  906): channel '42d0a118 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42d0a118 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/WifiService(  906): Client connection lost with reason: 4
,W/dalvikvm( 3557): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.example.hello
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  906): WIN DEATH: Window{42d0a118 u0 com.example.hello/com.example.hello.MainActivity}
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42d0a118 com.example.hello.MainActivity (s)'
,I/FeedHostManager( 1270): [onResume]
,I/FeedProviderManager( 1270): onResume
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1270/10076)
W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/ConnectivityHelper( 1270): [getCurrentConnectionType] no network connection
,D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/WindowManager(  906): WINDOW DIED Window{42d0a118 u0 com.example.hello/com.example.hello.MainActivity}
,D/AccTypeManager( 3476): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/PMS     (  906): acquireWL(4327c1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1222 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4327c1e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
,W/dalvikvm( 3557): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 3476): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3476): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3071 uid 10396
,I/InputMethodManagerService(  906): Enable input method client, pid=1270
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 3476): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/FbInjectorInitializer( 3557): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
,I/Tethering(  906): No IPv4 upstream interface, giving up.
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
,I/NetworkMonitor( 3536): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.backuptransport (1606/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10076)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1222/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3536/10154)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2171/10029)
,W/fb4a(:<default>):StaticBindingVerifier( 3557): Verify
,W/PackageManager(  906): Unable to load service info ResolveInfo{43084b30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/WifiService(  906): New client listening to asynchronous messages
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3557/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3557): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3557): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): acquireWL(4304d2c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  906): releaseWL(4304d2c8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024140
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024256
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024923
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024930
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024933
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029472
,I/dalvikvm-heap( 3557): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  906): killProcessQuiet, pid=3272
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3272:com.android.smith/u0a163 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3272
,D/AutoSetting( 1284): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3624 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1284/10055)
,D/AutoSetting( 1284): Util - no network available!
,D/AutoSetting( 1284): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1284): service - mHandler: cancel location update
,D/AutoSetting( 1284): service -           changes count: 0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1284/10055)
,W/Netd    (  363): No subsystem found in netlink event
,V/Tethering(  906): remove iface:wlan0
,D/Tethering(  906): interfaceRemoved wlan0
,E/Tethering(  906): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,D/MobileConnectivityChangeReceiver( 3624): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3624): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 3624): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3624): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  906): killProcessQuiet, pid=3284
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3637 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3284:com.google.android.youtube/u0a168 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3624/10079)
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3624/10079)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3624/10079)
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,D/Process (  906): killProcessQuiet, pid=3380
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3650 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3380:com.android.vending/u0a74 (adj 15): empty #17
,D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false,
,I/ActivityManager(  906): Recipient 3284
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.youtube (pid 3284): Died!
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/GAV2    ( 3650): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 3650): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3650): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  906): remove iface:p2p0
D/Tethering(  906): interfaceRemoved p2p0
,E/Tethering(  906): attempting to remove unknown iface (p2p0), ignoring
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3650): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
I/ActivityManager(  906): Recipient 3380
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3650): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3650/10151)
,V/WebViewChromiumFactoryProvider( 3650): Binding Chromium to main looper Looper (main, tid 1) {424df000}
,I/LibraryLoader( 3650): Expected native library version number "",actual native library version number ""
,I/chromium( 3650): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3650): Initializing chromium process, renderers=0
,E/NSDepend( 3650): Could not load library: pdflib.dex.jar
E/NSDepend( 3650): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 3650): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/NSDepend( 3650): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/NSDepend( 3650): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:217)
E/NSDepend( 3650): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:205)
E/NSDepend( 3650): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:112)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:971)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:918)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.NSDepend$1.doInBackground(NSDepend.java:951)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 3650): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 3650): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 3650): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 3650): 	at com.google.apps.dots.android.newsstand.async.Queue$3$1.run(Queue.java:162)
E/NSDepend( 3650): 	at java.lang.Thread.run(Thread.java:864)
E/NSDepend( 3650): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 3650): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 3650): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/NSDepend( 3650): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/NSDepend( 3650): 	... 14 more
,E/AudioManagerAndroid( 3650): BLUETOOTH permission is missing!
,I/Adreno-EGL( 3650): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3650): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3650): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3650): Local Branch: 
I/Adreno-EGL( 3650): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3650): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3650):                  aa63bbd948f41d15fc72f585e
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,I/NSApplication( 3650): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3650/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3650/10151)
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3685 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3421
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Killing 3421:com.htc.sense.browser/u0a12 (adj 15): empty #17
E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.ru,n(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3557): Failed to open database '/data/data/com.facebook.katana/databases/prefs_db'.
E/SQLiteDatabase( 3557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/SQLiteDatabase( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/SQLiteDatabase( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/SQLiteDatabase( 3557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/SQLiteDatabase( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/SQLiteDatabase( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitializer.java:186)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executor,s$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.LoggingRunnable.run(LoggingRunnable.java:187)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3557): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3557): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/SQLiteDatabase( 3557): 	at java.lang.Thread.run(Thread.java:864)
,W/dalvikvm( 3557): threadid=12: thread exiting with uncaught exception (group=0x420aae30)
,E/ACRA    ( 3557): ACRA caught a RuntimeException exception for com.facebook.katana. Building report.
E/fb4a(:<default>):ACRA( 3557): Handling exception for crash
E/fb4a(:<default>):ACRA( 3557): java.lang.RuntimeException: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/fb4a(:<default>):ACRA( 3557): 	at com.google.common.base.Throwables.propagate(Throwables.java:156)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.appchoreographer.DefaultAppChoreographer.h(DefaultAppChoreographer.java:514)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.appchoreographer.DefaultAppChoreographer.b(DefaultAppChoreographer.java:61)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.appchoreographer.DefaultAppChoreographer$2.run(DefaultAppChoreographer.java:236)
E/fb4a(:<default>):ACRA( 3557): 	at java.lang.Thread.run(Thread.java:864)
E/fb4a(:<default>):ACRA( 3557): Caused by: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/fb4a(:<default>):ACRA( 3557): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/fb4a(:<default>):ACRA( 3557): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.appchoreographer.DefaultAppChoreographer.h(DefaultAppChoreographer.java:513)
E/fb4a(:<default>):ACRA( 3557): 	... 3 more
E/fb4a(:<default>):ACRA( 3557): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/fb4a(:<default>):ACRA( 3557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/fb4a(:<default>):ACRA( 3557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/fb4a(:<default>):ACRA( 3557): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.j(AbstractDatabaseSupplier.java:129)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.i(AbstractDatabaseSupplier.java:96)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.database.supplier.AbstractDatabaseSupplier.c(AbstractDatabaseSupplier.java:74)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:116)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:43)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.content.AbstractContentProvider.b(AbstractContentProvider.java:131)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.content.AbstractContentProvider.query(AbstractContentProvider.java:322)
E/fb4a(:<default>):ACRA( 3557),: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/fb4a(:<default>):ACRA( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/fb4a(:<default>):ACRA( 3557): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:278)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.g(FbSharedPreferencesImpl.java:245)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.b(FbSharedPreferencesImpl.java:214)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$FbSharedPreferenceInitializer.a(FbAppInitializer.java:81)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.InitializerProfilingUtil.a(InitializerProfilingUtil.java:55)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.b(FbAppInitializer.java:262)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:279)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:248)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.c(FbAppInitializer.java:233)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer.a(FbAppInitializer.java:69)
E/fb4a(:<default>):ACRA( 3557): 	at com.facebook.common.init.impl.FbAppInitializer$2.run(FbAppInitialize
,D/ACRA    ( 3557): Generating report file for crash
,E/ACRA    ( 3557): An error occurred while creating the report file ...
E/ACRA    ( 3557): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_acra-reports/1449275241964-SQLiteException-1698515.temp_stacktrace: open failed: EROFS (Read-only file system)
E/ACRA    ( 3557): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ACRA    ( 3557): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
E/ACRA    ( 3557): 	at org.acra.ErrorReporter.handleExceptionInternal(ErrorReporter.java:1249)
E/ACRA    ( 3557): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1167)
E/ACRA    ( 3557): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1152)
E/ACRA    ( 3557): 	at org.acra.ErrorReporter.uncaughtException(ErrorReporter.java:999)
E/ACRA    ( 3557): 	at com.facebook.common.errorreporting.memory.MemoryDumpHandler.uncaughtException(MemoryDumpHandler.java:113)
E/ACRA    ( 3557): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/ACRA    ( 3557): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/ACRA    ( 3557): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ACRA    ( 3557): 	at libcore.io.Posix.open(Native Method)
E/ACRA    ( 3557): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ACRA    ( 3557): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ACRA    ( 3557): 	... 8 more
,I/ActivityManager(  906): Recipient 3421
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 3685): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3685): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3685): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3685): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3685): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 3685): 	at del.a(PG:264)
E/SQLiteDatabase( 3685): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3685): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3685): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3685): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3685): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3685): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3685): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 3685): 	at del.a(PG:264)
E/SQLiteDatabase( 3685): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3685): 	at java.lang.Thread.run(Thread.java:864)
,E/EsApplication( 3685): Failed app initialization
E/EsApplication( 3685): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 3685): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 3685): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 3685): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 3685): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 3685): 	at del.a(PG:264)
E/EsApplication( 3685): 	at eeq.run(PG:187)
E/EsApplication( 3685): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  906): killProcessQuiet, pid=3464
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3685/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3685/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3685/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3685/10160)
I/ActivityManager(  906): Killing 3464:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3464
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2171, uid=10029, userID:0
I/iu.SyncManager( 2171): SYNC; picasa accounts
D/PMS     (  906): acquireWL(43207450): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
E/SQLiteDatabase( 2171): Failed to open database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite'.
E/SQLiteDatabase( 2171): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(SourceFile:204)
E/SQLiteDatabase( 2171): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 2171): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 2171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 2171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2171): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 2171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 2171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 2171): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 2171): threadid=1: thread exiting with uncaught exception (group=0x420aae30)
D/PMS     (  906): acquireWL(43286940): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AndroidRuntime( 2171): FATAL EXCEPTION: main
E/AndroidRuntime( 2171): Process: com.google.android.gms, PID: 2171
E/AndroidRuntime( 2171): java.lang.RuntimeException: Unable to start receiver com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2171): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2171): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2171): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2171): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2171): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2171): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2171): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 2171): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 2171): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2171): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2171): 	at com.google.android.lib,raries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2171): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(Source
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,W/Settings( 3557): Setting data_roaming_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
W/Settings( 3557): Setting data_roaming_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
W/Settings( 3557): Setting data_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
W/Settings( 3557): Setting data_roaming_guard_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting sms_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting voice_roaming_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting voice_roaming_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting voice_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting voice_roaming_guard_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting vzw_global_roaming_options has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3557): Setting boot_lock has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3557): Setting data_encryption has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3708 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  906): sending alarm PendingIntent{42bf4580: PendingIntentRecord{42be6c00 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54869, Int=0
,W/Settings( 3557): Setting sd_encryption has moved from android.provider.Settings.Secure to android.provider.Settings.Global.

```
