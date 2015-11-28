#### Test 50388019809f971_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/DeviceManagement( 2714): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 2714): SessionStateController: Checking invariants...
W/GAV2    ( 2729): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
--------- beginning of /dev/log/system
I/ActivityManager(  905): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/DeviceManagement( 2714): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/PMS     (  905): acquireWL(41df13d0): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41df13d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2729, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2729, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2729, uid=10107, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2729, uid=10107, userID:0
D/Process (  905): killProcessQuiet, pid=2350
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2350:com.htc.aurora:remote/u0a49 (adj 15): empty #17
D/PMS     (  905): acquireWL(427125a0): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 2714): Perf: *** Cache update - start...
D/PMS     (  905): releaseWL(427125a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/DeviceManagement( 2714): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 2714): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 2714): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 2714): Perf: Scan enabled apps - start...
I/ActivityManager(  905): Recipient 2350
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 2714): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
I/Gmail   ( 2729): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2729): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 2729): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 2729): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
E/cutils-trace( 2752): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 2752): ====startRecUseTime====
D/htc.customization.log.level( 2752):  is 
W/CustomizationLogLevel( 2752): Level value is invalid, use default level 2
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
D/CustomizationManager( 2752):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2752): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2752): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2752): Parsing tag category name = system
I/ActivityManager(  905): Resuming delayed broadcast
I/CustomizationCIDLoader( 2752): Parsing tag category name = application
I/CustomizationCIDLoader( 2752): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2752): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2752): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2752): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2752): Parsing tag category name = Settings
D/CustomizationManager( 2752):  Read CID file spent 0.096 (s)
D/CustomizationManager( 2752):  All configurations done spent 0.096 (s)
W/HtcNativeFlag( 2752): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2752): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2752): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2752): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2729, uid=10107, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
I/ActivityManager(  905): Resuming delayed broadcast
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2779 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2752
W/asset   (  905): Copying FileAsset 0x6bf06510 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1105653224
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
D/PMS     (  905): acquireHCC(4242ac08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(42386bf8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
D/PMS     (  905): acquireWL(420b0148): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41dd8150
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2791 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
W/asset   ( 2791): Copying FileAsset 0x5c8be428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1247): [trimMemory] 20
E/ActivityThread( 1247): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1247): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1247): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3590)
E/ActivityThread( 1247): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3684)
E/ActivityThread( 1247): 	at android.app.ActivityThread.access$1100(ActivityThread.java:153)
E/ActivityThread( 1247): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1376)
E/ActivityThread( 1247): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1247): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread( 1247): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/ActivityThread( 1247): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1247): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1247): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread( 1247): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread( 1247): 	at dalvik.system.NativeStart.main(Native Method)
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
V/WebViewChromiumFactoryProvider( 2791): Binding Chromium to main looper Looper (main, tid 1) {41b95e28}
I/LibraryLoader( 2791): Expected native library version number "",actual native library version number ""
I/chromium( 2791): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2791): Initializing chromium process, renderers=0
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
D/PMS     (  905): acquireWL(426988a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): acquireWL(425dfec8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  905): releaseWL(426988a8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Activity reported stop, but no longer stopping: ActivityRecord{42421a90 u0 com.htc.launcher/.Launcher t1}
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4238e0e8:true
D/BluetoothAdapter( 2791): 1102755872: getState() :  mService = null. Returning STATE_OFF
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
I/Adreno-EGL( 2791): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2791): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2791): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2791): Local Branch: 
I/Adreno-EGL( 2791): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2791): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2791):                  aa63bbd948f41d15fc72f585e
I/htcbackup-core( 2779): ModelRegistry: Loading model meta data from resources...
W/chromium( 2791): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/ContextImpl( 2779): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2779): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 2714): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 2714): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.autobot.cargps.provider, com.htc.android.htcloglevel, com.qualcomm.privinit, android, com.android.keychain, com.htc.home.personalize, com.qualcomm.timeservice, com.htc.android.htcsetupwizard, com.htc.drive.activator, com.android.CSDFunctionG, com.htc.cirmodule, com.htc.smartdim, com.htc.lockscreen, com.android.location.fused, com.android.providers.settings, com.htc.feedback, com.htc.backupreset, com.android.settings, com.htc.guide, com.htc.checkinprovider, com.htc.backup, com.htc.mirrorlinkserver, com.htc.htcpowermanager, com.htc.usage, com.android.inputdevices]
W/dalvikvm( 2791): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
I/DeviceManagement( 2714): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
W/dalvikvm( 2791): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2791): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2791): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2791): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2791): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2791): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2791): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2791): CordovaWebView is running on device made by: HTC
I/DeviceManagement( 2714): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
W/ContextImpl( 2779): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews( 1106): com.htc.backup (true,33751552)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41c12c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  905): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/RemoteViews.Performance( 1106): com.htc.backup 3 8 5 15
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/DeviceManagement( 2714): EnabledAppBuilder: Found 9 DM enabled apps.
D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41c165a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/RemoteViews.Performance( 1106): com.htc.backup 2 3 3 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/RemoteViews.Performance( 1106): com.htc.backup 1 1 1 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/RemoteViews.Performance( 1106): com.htc.backup 0 2 1 4
I/RemoteViews.Performance( 1106): com.htc.backup 0 8 16 21
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2714): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/DeviceManagement( 2714): Perf: Scan enabled apps - complete: 885 ms
I/DeviceManagement( 2714): Perf: *** Enabled app cache update - complete: 885 ms
I/DeviceManagement( 2714): Perf: *** Config cache update - start...
I/DeviceManagement( 2714): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2714): ConfigCacheController: *** Updating stale config cache entries...
W/AwContents( 2791): nativeOnDraw failed; clearing to background color.
W/dalvikvm( 2714): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
W/dalvikvm( 2714): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
W/dalvikvm( 2714): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
I/InputMethodManagerService(  905): Disable input method client, pid=1247
W/ResourceType( 2791): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2791): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bdcb68, mServedView=org.apache.cordova.engine.SystemWebView{41ba2b40 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1184): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1184): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 2791): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Enable input method client, pid=2791
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +408ms
D/PMS     (  905): releaseWL(420b0148): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/System.err( 2714): Starting the internal HTTP client
I/DeviceManagement( 2714): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEwLTE0VDEwOjI4OjM4LjU4Mlo
I/DeviceManagement( 2714): DeviceClientResource: Active network...
I/DeviceManagement( 2714):   No active network
I/DeviceManagement( 2714): DeviceClientResourceController: Network is unavailable: code=1010 description=There is no active network.
I/DeviceManagement( 2714): BackgroundController: *** Network unavailable!
I/DeviceManagement( 2714): Perf: *** Config cache update - complete: 129 ms
I/DeviceManagement( 2714): Perf: *** Cache update - complete: 1016 ms
I/DeviceManagement( 2714): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41bc03e0]
I/DeviceManagement( 2714): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41f8cf68] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2714): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2714): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2714): SessionStateController: Checking invariants...
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (2714/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (2714/10098)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.cs.dm (2714/10098)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=1, flag=1, pid=2714, uid=10098, userID:0
I/DeviceManagement( 2714): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2714): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41f8cf68]
I/DeviceManagement( 2714): WorkflowService: Stopping workflow service
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2843 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
D/Process (  905): killProcessQuiet, pid=2373
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2373:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
E/AndroidProtocolHandler( 2791): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2791): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2791): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  905): Recipient 2373
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/jxcore_app_log( 2791): JniHelper::setJavaVM(0x4174e010), pthread_self() = 1658383312
D/JX-Cordova( 2791): jxcore cordova android initializing
I/Babel   ( 2843): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 2843): MmsConfig.loadMmsSettings
W/dalvikvm( 2843): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2843): VFY: unable to resolve instance field 46
W/dalvikvm( 2843): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 2843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2843, uid=10111, userID:0
D/MmsCustomizationProvider( 2486): query uri: content://htc-mms-customization/mms-ua/ua_string
W/Settings( 2843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/jxcore-log( 2791): Initializing JXcore engine
W/jxcore-log( 2791): JXcore engine is ready
D/MmsCustomizationProvider( 2486): query uri: content://htc-mms-customization/mms-ua/ua_profile
W/jxcore-log( 2791): Starting JXcore engine
I/Babel   ( 2843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 2843): MmsConfig.loadFromDatabase
E/Babel   ( 2843): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 2843): MmsConfig.loadFromResources
E/Babel   ( 2843): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 2843): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/htcbackup-core( 2779): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  905): sending alarm PendingIntent{428a45f8: PendingIntentRecord{426fa960 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=13, w=1440901414353, Int=604800000
I/RemoteViews( 1106): com.htc.backup (true,33751552)
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews.Performance( 1106): com.htc.backup 2 2 15
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews( 1106): com.htc.backup (true,33751552)
W/dalvikvm( 2779): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
I/RemoteViews.Performance( 1106): com.htc.backup 1 1 0 4
I/ProviderInstaller( 2843): Installed default security provider GmsCore_OpenSSL
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 1 1 0 4
I/RemoteViews( 1106): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1106): com.htc.backup 1 1 1 4
I/RemoteViews.Performance( 1106): com.htc.backup 1 12 21
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
D/UPolicy ( 2779): IUserBehaviorLoggingService reference is gotten !
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2843, uid=10111, userID:0
V/Babel   ( 2843): babel boot account: thalitester@gmail.com
V/Babel   ( 2843): babel boot account: SMS
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2843, uid=10111, userID:0
I/ActivityManager(  905): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2875 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  905): killProcessQuiet, pid=2400
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  905): killProcessQuiet, pid=2387
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2400:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  905): Killing 2387:com.htc.musicenhancer/u0a53 (adj 15): empty #18
V/AlarmManager(  905): sending alarm PendingIntent{42760430: PendingIntentRecord{426cf988 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47645, Int=0
I/ActivityManager(  905): Recipient 2387
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  905): sending alarm PendingIntent{42751d18: PendingIntentRecord{4269e130 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=47651, Int=0
I/ActivityManager(  905): Recipient 2400
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 2791): Platform android
W/jxcore-log( 2791): 
W/jxcore-log( 2791): Process ARCH arm
W/jxcore-log( 2791): 
I/jxcore-log( 2791): JXcore Cordova bridge is ready!
I/jxcore-log( 2791): 
W/jxcore-log( 2791): JXcore engine is started
E/jxcore-log( 2791): >> HTC-HTC Desire 820
E/jxcore-log( 2791): 
I/jxcore-log( 2791): Total memory 1964650496
I/jxcore-log( 2791): 
I/jxcore-log( 2791): Free memory 718077952
I/jxcore-log( 2791): 
I/jxcore-log( 2791): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2791): 
I/jxcore-log( 2791): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2791): 
I/jxcore-log( 2791): userPath [ 'www' ]
I/jxcore-log( 2791): 
,I/jxcore-log( 2791): Size 720 1184
I/jxcore-log( 2791): 
,I/jxcore-log( 2791): Screen Brightness 142
I/jxcore-log( 2791): 
,E/jxcore-log( 2791): Dummy Error Log.
E/jxcore-log( 2791): 
,I/ActivityManager(  905): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2890 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  905): killProcessQuiet, pid=2424
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2424:com.htc.video/u0a57 (adj 15): empty #17
,D/ResetNotifyBootCompleteReceiver( 1214): Receive bootcomplete intent
,W/ContextImpl( 1214): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/HtcCupdXmlParser( 2890): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2905 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ActivityThread( 2890): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/dalvikvm-heap( 1214): Grow heap (frag case) to 12.396MB for 2097144-byte allocation
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2424
,D/AppTag  ( 2905): getInstance(Context context)
,D/AppTag  ( 2905): getInstance(Context context)
,D/AppTag  ( 2905): onCreate()
,D/QXDM2SD:HtcNative( 1214): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2919 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2455
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2455:com.htc.lmw/u0a60 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcCupdXmlParser( 2890): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  905): Recipient 2455
,V/Settings:HtcSettingsApplication( 2919): [2919/2919] onCreate()
W/ContextImpl( 2919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/AlarmManager(  905): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  905): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  905): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2933 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2945 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2535
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2535:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2535
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 2945): -onCreate()
,V/Settings:HtcSettingsApplication( 2945): [2945/2945] onCreate()
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41eea390
W/ContextImpl( 2945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=2438
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  905): Killing 2438:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41c03d68
I/ActivityManager(  905): Recipient 2438
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 2791): getBuffer is called!!!!
I/jxcore-log( 2791): 
I/ActivityManager(  905): Resuming delayed broadcast
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@41bba650
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  905): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  905): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  905): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,D/Process (  905): killProcessQuiet, pid=2553
D/TetherSettings( 2945): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2945): Cust_ConnectToPC   : Internet_Sharing>true
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/        ( 2945): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2945): Cust_ConnectToPC   : spcsc>false
D/        ( 2945): Cust_ConnectToPC   : IPT>true
,D/        ( 2945): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2945): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2945): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2945): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2945): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2945): Cust_ConnectToPC   : spcsc>false
D/        ( 2945): Cust_ConnectToPC   : IPT>true
D/        ( 2945): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2945): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2945): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2945): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2945): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 2945): setISNotification
I/ActivityManager(  905): Killing 2553:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2553
D/SmartNS_Utility( 2945): usb_cable_connect = 1
D/SmartNS_Utility( 2945): usb_denied = 0
I/SmartNS_PSService( 2945): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 2945): usb_cable_connect = 1
D/SmartNS_Utility( 2945): usb_denied = 0
I/SmartNS_PSService( 2945): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2945/1000)
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2945/1000),
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  905): killProcessQuiet, pid=2565
,I/ActivityManager(  905): Killing 2565:com.htc.showme/u0a83 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/RemoteViews( 1106): com.android.settings (true,33751552)
,D/OnDemandProgressBar( 1106): release indeterminate drawable android.widget.OnDemandProgressBar{41ba0488 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1106): com.android.settings 1 6 1 10
I/ActivityManager(  905): Recipient 2565
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1106): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1106): com.android.settings 1 0 10
,I/ActivityManager(  905): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2960 uid=9987 gids={49987}
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42568cc0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42568cc0, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42439d50
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42210090
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42568cc0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42568cc0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42422998 u0 ReceiverList{425ddee8 905 system/1000/u0 local:424a1380}}
,D/NfcUiccLockService( 2960): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  905): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2974 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
D/Process (  905): killProcessQuiet, pid=2579
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2579:com.htc.updater/u0a85 (adj 15): empty #17
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 3
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42568cc0, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42439d50
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@42210090
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42568cc0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  905): Recipient 2579
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2987 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2608
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2608:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2608
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 2987): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
,D/PMS     (  905): releaseHCC(4242ac08): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  905): releaseHCC(42386bf8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/libc    ( 2987): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2987): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2987): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,I/GAV2    ( 2593): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1956): Google Analytics 8.3.01 is starting up.
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2987/10168)
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2987): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2987): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2987): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2987): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2987): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 2987): Registered
,I/MediaRouter( 2987): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/YouTube ( 2987): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 2987): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448709340&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (2987/10168)
D/libc    ( 2987): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 2987): [NET] getaddrinfo-,err=8
D/libc    ( 2987): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2987): [NET] getaddrinfo-, 1
,D/libc    ( 2987): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET] get_iface_protocol fail: 
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  364): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  364): [NET] getaddrinfo-,err=7
D/libc    ( 2987): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 2987): Error sending ping
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2987): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2987): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 2987): getSelectedRoute
,D/YouTube ( 2987): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2987): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2987/10168)
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2668
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2668:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/YouTube ( 2987): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2987): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2987): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  905): Recipient 2668
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1956): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1956): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1956): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1956): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1956): Beginning GMS chimera module scan
,W/asset   ( 1956): Copying FileAsset 0x64d975c0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1956): Beginning module configuration check
,D/ChimeraCfgMgr( 1956): Module APKs unchanged, check complete
,E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
D/PMS     (  905): acquireWL(4272fe28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1956): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  905): acquireWL(42875518): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42641268): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1956): COMPAT: Multi user not supported
,D/GCM     ( 1337): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  905): releaseWL(4272fe28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1448627602455 min interval config: 0 actual interval: 81738627
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
,I/GCoreUlr( 1956): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1197): DispatchingService.onCreate()
,I/CheckinService( 1956): Disabling old GoogleServicesFramework version
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 1956): onCreate
,D/SystemUpdateService( 1956): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,V/AuthZen ( 1956): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 1956): cancelUpdate (empty URL)
,I/SystemUpdateService( 1956): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  905): acquireWL(42a09320): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  905): acquireWL(4274e2b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/CheckinService( 1956): Checking schedule, now: 1448709341169 next: 1449150539405
,I/CheckinService( 1956): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  905): releaseWL(42a09320): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
D/AuthZenEventHandler( 1956): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/GCoreUlr( 1197): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 1956): onDestroy
D/PMS     (  905): releaseWL(42875518): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42641268): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1197, uid=10029, userID:0
,W/dalvikvm( 1956): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1956): Fetching signing key...
,I/AuthZen ( 1956): Signing key fetched successfully!
,I/GCoreUlr( 1197): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/BaseAppContext( 1956): Using Auth Proxy for data requests.
D/PMS     (  905): acquireWL(427200e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1197): Unbound from all location providers
D/PMS     (  905): releaseWL(427200e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4274e2b0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/AuthZenTransactionCache( 1956): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1956): Clearing transaction cache
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42849218): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1956 10029 null
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,D/PMS     (  905): acquireWL(42757d50): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42849218): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  905): releaseWL(42757d50): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Auth    ( 1337): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/PMS     (  905): acquireWL(42a11780): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1337 10029 null
V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PMS     (  905): releaseWL(42a11780): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1337): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/PMS     (  905): releaseWL(425dfec8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3078 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,I/GCoreUlr( 1197): DispatchingService.onDestroy()
I/GCoreUlr( 1197): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1197): Unbound from all location providers
D/PMS     (  905): acquireWL(42a18250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42a18250): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(428d4f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(428d4f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3078, uid=10074, userID:0
,I/HtcModeClient( 1495): handler message = 4011
,E/HtcModeClient( 1495): Check connection and retry 4 times.
,D/Finsky  ( 3078): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3078/10074)
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3078/10074)
,D/Finsky  ( 3078): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z,
,W/Settings( 3078): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3078): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3078): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3078, uid=10074, userID:0
,D/Volley  ( 3078): [279] DiskBasedCache.clear: Cache cleared.
,D/Process (  905): killProcessQuiet, pid=2687
D/Ads     ( 3078): Skipping gmscore version check
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Volley  ( 3078): [286] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  905): Killing 2687:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/Finsky  ( 3078): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3078): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  905): Recipient 2687
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3078): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  905): Delay finish: com.htc.dotmatrix/.CoverStateReceiver
,D/AutoSetting( 1296): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2945): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2945): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2945): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2945): Cust_ConnectToPC   : spcsc>false
D/        ( 2945): Cust_ConnectToPC   : IPT>true
D/        ( 2945): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2945): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Finsky  ( 3078): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/SmartNS_Utility( 2945): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2945): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2945): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/ActivityManager(  905): Resuming delayed broadcast
D/AutoSetting( 1296): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 2945): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 2945): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 2945): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2945):  defaultType:0
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3116 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3116): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3116): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3116): Loading: swewebviewchromium
,I/LibraryLoader( 3116): Time to load native libraries: 39 ms (timestamps 2034-2073)
,I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3116): Initializing chromium process, renderers=9
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
,I/chromium( 3116): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3116): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3116): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3116): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3116): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3116): Local Branch: 
I/Adreno-EGL( 3116): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3116): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3116):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=2700
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1261): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/ActivityManager(  905): Killing 2700:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1495): SIM state: ABSENT
I/SIMStateChangeReceiver( 1495): phoneType = 0
,I/SIMStateChangeReceiver( 1495): remove notification
I/ActivityManager(  905): Recipient 2700
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3155 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3167 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2729
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2729:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2486): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2486): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2486): onReceive()
,D/ExchangePolicystatus( 2486): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2486): onReceive(): else
,D/Process (  905): killProcessQuiet, pid=2779
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1214): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  905): Killing 2779:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2729
,W/WeatherUtility( 1106): can't get weather sync account
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3183 uid=10041 gids={50041}
,W/WeatherRequest( 1106): request cur loc, but there is no sys cur
,D/AccTypeManager( 3167): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3199 uid=10078 gids={50078}
,I/ActivityManager(  905): Killing 2714:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=2714
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Recipient 2779
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3167): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3167): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3199): Got a database change event
,D/Process (  905): killProcessQuiet, pid=2843
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3211 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  905): Killing 2843:com.google.android.talk/u0a111 (adj 15): empty #17
,E/ExternalAccountType( 3167): Unsupported attribute readOnly
,D/AccTypeManager( 3167): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  905): Recipient 2714
,W/AccTypeManager( 3167): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3167): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/CalendarApplication( 3211): onCreate
D/ProviderChangeReceiver( 3211): ---------------------------------------------------
,D/ProviderChangeReceiver( 3211): ProviderChangeReceiver onReceive, start to update notification!
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 3211): start to updateAlertNotification!
W/ContextImpl( 2919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,E/ExternalAccountType( 3167): Unsupported attribute readOnly
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3226 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
D/AlertService( 3211): No fired or scheduled alerts
D/HtcAlertUtils( 3211): -- cancelReminderNotification --
D/HtcAlertUtils( 3211): broadcastExistReminder!
D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/Process (  905): killProcessQuiet, pid=2875
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2875:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2875
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2843
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3226): can't get weather sync account
I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3241 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3241): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3241): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,W/WeatherRequest( 3226): request cur loc, but there is no sys cur
,W/Settings( 3226): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3241): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3255 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=2890
,I/ActivityManager(  905): Killing 2890:com.htc.htccupd/u0a17 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 0 16 17
,D/PMS     (  905): acquireWL(428e13e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3255 10071 null
,D/PMS     (  905): acquireWL(4265a820): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3255 10071 null
,D/PMS     (  905): releaseWL(428e13e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3255): update TASK shortcut>
I/ActivityManager(  905): Recipient 2890
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/TodoTaskNotifyService( 3255): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  905): releaseWL(4265a820): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3255): stopSelfResult true
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3270 uid=10082 gids={50082, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2905
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2905:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  905): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3282 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  905): Recipient 2905
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3294 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  905): killProcessQuiet, pid=2960
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  905): killProcessQuiet, pid=2933
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2960:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  905): Killing 2933:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
,I/ActivityManager(  905): Recipient 2933
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2960
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3294): create image Cache, size: 31457280.
I/ImageRamCache( 3294): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3294): create image Cache, size: 12582912.
,I/FeedSettings( 3294): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3294): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3294): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3294): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3294): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3294): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3294): [custom highlight] onReceive
,I/ActivityManager(  905): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3294): [custom highlight] onHandleIntent
D/NewsDB  ( 3294): set custom highlight []
,D/CustomHighlightService( 3294): [custom highlight] set tags 
I/ActivityManager(  905): Resuming delayed broadcast
,D/SMSBackup( 3199): Got a database change event
,D/MessagingShortcutReceiver( 2486): keep hiding shortcut bubble
D/MessagingShortcut( 2486): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2486): After query: 0
D/MessagingShortcut( 2486): mPresentUnreadCount: -1
,D/MessagingShortcut( 2486): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2486): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] reorderNotification, total:0
D/DotMatrix( 1530): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1530): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3255): update TASK shortcut>
I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1214): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  905): killProcessQuiet, pid=2974
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Killing 2974:com.android.smith/u0a163 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 2974
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3310 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  905): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024272
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025040
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025049
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028924
,D/MessagingNotification( 2486): New incoming message, can't cancel notification now
,D/MessagingNotification( 2486): newMsgCnt: 0, false
V/AlarmManager(  905): sending alarm PendingIntent{4209d0e8: PendingIntentRecord{4267d5d8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=22090, Int=1800000
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3325 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  905): sending alarm PendingIntent{427a0f18: PendingIntentRecord{4278fa10 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=47620, Int=259200000
V/AlarmManager(  905): sending alarm PendingIntent{41e75288: PendingIntentRecord{4253ae88 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51177, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42446810: PendingIntentRecord{423ea980 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448708400000, Int=86400000
,D/MdScBoot( 3310): [920.1.] 30@-121516 -> 40@-121543
I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=2987
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  905): killProcessQuiet, pid=3078
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 2987:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  905): Killing 3078:com.android.vending/u0a74 (adj 15): empty #17
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
,D/WearableService( 1197): callingUid 10029, callindPid: 1197
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,E/MDM     ( 1197): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1197): No location to return for getLastLocation()
,W/FusedLocationProvider( 1337): location=null
D/PMS     (  905): acquireWL(426c3308): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(426c3308): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024272
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025040
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025049
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028924
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 2987
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.youtube (pid 2987): Died!
,D/GCM     ( 1337): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1337): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1337): Proximity feature is not enabled.
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3078
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/PMS     (  905): acquireWL(426b9bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
,E/MDM     ( 1197): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  905): releaseWL(426b9bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1197): No location to return for getLastLocation()
,W/FusedLocationProvider( 1337): location=null
D/PMS     (  905): acquireWL(4270e260): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4270e260): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024272
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025040
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025049
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028924
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1337): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1337): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1337): Proximity feature is not enabled.
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(4283ed78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024272
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024867
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025040
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025049
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028924
,D/PMS     (  905): releaseWL(4283ed78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4266f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1337 10029 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2154): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2154): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2154): [MTP][handleMessage][startService]
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1337/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024272
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024867
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025040
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025045
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025049
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028924
,D/MtpReceiver( 2154): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2154): [MTP][handleMessage]-
I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3350 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  905): releaseWL(4266f210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/MtpService( 2154): [MTP] startForeground
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1106): com.android.providers.media (false,0)
D/MtpService( 2154): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews.Performance( 1106): com.android.providers.media 2 1 10
D/MtpDatabase( 2154): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews( 1106): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1106): com.android.providers.media 1 1 15
,D/MtpService( 2154): [isMtpConnected] connected: true
D/PMS     (  905): acquireWL(427bb7f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1956 10029 null
,D/SyncApplication( 3350): Loading default preferences
,W/Resources( 3350): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/Process (  905): killProcessQuiet, pid=2945
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2945:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 3350): Overriding preferences with custom values
,D/SyncApplication( 3350): Updating preferences succeeded
,E/SyncApplication( 3350): Application created.
D/VolumeInfo( 3350): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3350): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3350): Found 0 mount point(s)
,V/VolumeInfo( 3350): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3350): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3350): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3350): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3350): getNewCalendarAuthority()...
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2945
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3350, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3350, uid=10008, userID:0
,W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3350): enableAppOperation()+
,D/SyncApplication( 3350): enableAppOperation()-
,D/HTCUtilities( 3350): isNeorSinged() + 
,D/HTCUtilities( 3350): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3350): isNeorSinged() return false
D/CDMountReceiver( 3350): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3350): USB connected to PC
,D/FOTAReceiver( 3350): onReceive() enter 
,D/FOTAReceiver( 3350): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/iu.UploadsManager( 1956): End new media; added: 0, uploading: 0, time: 172 ms
D/PMS     (  905): releaseWL(427bb7f8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3370 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3116
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3116:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/SensorManager(  905): mEventCount = 300
,I/ActivityManager(  905): Recipient 3116
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3370): -onCreate()
,V/Settings:HtcSettingsApplication( 3370): [3370/3370] onCreate()
,D/TetherSettings( 3370): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3370): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 3370): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3370): Cust_ConnectToPC   : spcsc>false
,D/        ( 3370): Cust_ConnectToPC   : IPT>true
,D/        ( 3370): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3370): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3370): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3370): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 3370): Cust_ConnectToPC   : spcsc>false
D/        ( 3370): Cust_ConnectToPC   : IPT>true
,D/        ( 3370): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3370): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3370): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3370): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3370): usb_cable_connect = 1
,D/SmartNS_Utility( 3370): usb_denied = 0
,I/SmartNS_NSReceiver( 3370): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3370): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3370): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3370): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3370): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 3370): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3370):  defaultType:0
,I/SmartNS_PSService( 3370): fail notificaiton:false
,D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
,I/SmartNS_PSService( 3370): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3370/1000)
I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/SmartNS_Utility( 3370): usb_denied = 0
,I/SmartNS_PSService( 3370): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  905): Resuming delayed broadcast
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,I/RemoteViews( 1106): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1106): com.android.settings 2 0 10
,D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 3370): usb_cable_connect = 1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3370/1000)
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3370): usb_denied = 0
W/WeatherUtility( 3226): can't get weather sync account
D/DotMatrix( 1530): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3370): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3370): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/ActivityManager(  905): Resuming delayed broadcast
I/RemoteViews( 1106): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1106): com.android.settings 3 0 10
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1247): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1247): com.google.android.googlequicksearchbox 0 0 5
,W/WeatherRequest( 3226): request cur loc, but there is no sys cur
,W/Settings( 3226): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3387 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 11 17
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  905): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
,W/Settings:Agent(  905): >> traceCallingStack()
,W/Settings:Agent(  905): Process.myPid(): 905
,W/Settings:Agent(  905): Process.myTid(): 1344
,W/Settings:Agent(  905): Process.myUid(): 1000
,W/Settings:Agent(  905): 
,W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 8(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,D/WifiManager( 2791): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: false pid=2791, uid=10396
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1259
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 4(ms)
I/jxcore-log( 2791): ****TEST TOOK:  5150  ms ****
I/jxcore-log( 2791): 
,I/jxcore-log( 2791): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2791): 
,D/PowerUsageService( 3387): call getInstance()
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageList:PowerUsageHelper( 3387): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3155
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3155:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  905): acquireWL(424b5ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3387 1000 null
,W/WeatherUtility( 1106): can't get weather sync account
,D/WeatherUtility( 1296): Weather sync is On
,D/WSP     ( 1296): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,E/cutils-trace( 3401): Error opening trace file: No such file or directory (2)
,W/WeatherUtility( 3226): can't get weather sync account
I/ActivityManager(  905): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3413 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherRequest( 3226): request cur loc, but there is no sys cur
,W/Settings( 3226): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  905): Recipient 3155
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 7 17
,D/CustomizationManager( 3401): ====startRecUseTime====
D/htc.customization.log.level( 3401):  is 
,W/CustomizationLogLevel( 3401): Level value is invalid, use default level 2
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/CustomizationManager( 3401):  Read ACC file spent 0.057 (s)
,D/CIDMapFileReader( 3401): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__J15
,D/CIDMapFileReader( 3401): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3401): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3401): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3401): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3401): Parsing tag category name = system
,I/CustomizationCIDLoader( 3401): Parsing tag category name = application
,I/CustomizationCIDLoader( 3401): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3401): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3401): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3401): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3401): Parsing tag category name = Settings
D/CustomizationManager( 3401):  Read CID file spent 0.100 (s),
,D/CustomizationManager( 3401):  All configurations done spent 0.100 (s),
W/HtcNativeFlag( 3401): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3401): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3401): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3401): Fail to get flag for type 'language', use default value: -1,
,D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=3401, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=2791
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  905): Copying FileAsset 0x63fd6638 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  905): Killing 2791:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  905): Force removing ActivityRecord{41d16658 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  905): Skipping PackageSetting{422bd498 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=0: pkg removed
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{42392970 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  905): Client connection lost with reason: 4
,I/FeedHostManager( 1247): [onResume]
I/FeedProviderManager( 1247): onResume
I/SocialFeedProvider( 1247): +onResume
I/SocialFeedProvider( 1247): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1247): -onResume
,D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1530): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1530): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 1197): Ignoring removeGeofence because network location is disabled.
I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 3167): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(42a1c058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42a1c058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ConnectivityHelper( 1247): [getCurrentConnectionType] no network connection
,D/AccTypeManager( 1317): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3294): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3294): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1247/10076)
,W/SystemReader( 1226): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 3167): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3167): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
W/AccTypeManager( 1317): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1317): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
,E/ExternalAccountType( 3167): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,E/ExternalAccountType( 1317): Unsupported attribute readOnly
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,I/ActivityManager(  905): Resuming delayed broadcast
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
,D/Process (  905): killProcessQuiet, pid=3167
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3436 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3167:com.htc.contacts/u0a44 (adj 15): empty #17
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1214 :
,D/PhoneApp( 1214): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  905): Recipient 3167
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1214): MSG_NOTIFY_CS_TO_SYNC <<
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/MusicStore( 3436): Database version: 95
,W/ContextImpl( 3436): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3436): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 2791 uid 10396
,W/Binder  ( 1184): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1184): java.lang.NullPointerException
W/Binder  ( 1184): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1184): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1184): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1184): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  905): Enable input method client, pid=1247
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3436): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/SQLiteLog( 3387): (778) statement aborts at 13: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] 
,E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
,E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
V/AlarmManager(  905): sending alarm PendingIntent{4248bbc0: PendingIntentRecord{424eeb88 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448709345841, Int=0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213),
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
W/ContextImpl( 3436): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
W/ContextImpl( 3436): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3436, uid=10154, userID:0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
W/PackageManager(  905): Unable to load service info ResolveInfo{42706b38 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  905): killProcessQuiet, pid=3211
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
D/MediaRouterService(  905): Client com.google.android.music (pid 3436): Registered
I/ActivityManager(  905): Killing 3211:com.htc.calendar/u0a13 (adj 15): empty #17
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): ,	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
I/ActivityManager(  905): Recipient 3211
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
I/MediaRouter( 3436): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDataba,se.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	a,t com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.,sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.C,heckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
D/DFPI.PIReciver( 3241): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
,E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
I/DFPI.ApkInstallService( 3241): onHandleIntent
I/DFPI.ApkInstallService( 3241): Media Scan Finished Case 
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): ,	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (3436/10154)
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	,at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
D/DFPI.ApkInstallService( 3241): check CID = HTC__032
I/DFPI.ApkInstallService( 3241): There is no Demo.apk in sd card or phone storage
,E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
I/ActivityManager(  905): Resuming delayed broadcast
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
,E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
,E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): ,	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
,E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E,/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
D/MediaRouter( 3436): getSelectedRoute
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3436, uid=10154, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202,)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 3387): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_sat(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 3387): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5caf67a0
E/SQLiteDatabase( 3387): Error inserting ...
E/SQLiteDatabase( 3387): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 3387): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 3387): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 3387): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 3387): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3387): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3387): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3387): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  905): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3460 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,D/PMS     (  905): releaseWL(424b5ca0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  905): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3460/10053)
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3460): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(4284cd08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/PMS     (  905): releaseWL(4284cd08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/HtcModeClient( 1495): handler message = 4011
,E/HtcModeClient( 1495): Check connection and retry 5 times.

```
