#### Test 50242285e707819_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/DeviceManagement( 2692): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
I/DeviceManagement( 2692): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
I/DeviceManagement( 2692): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
I/GAV2    ( 2585): Thread[GAThread,5,main]: No campaign data found.
I/DeviceManagement( 2692): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
I/GAv4-SVC( 1958): Google Analytics 8.3.01 is starting up.
I/DeviceManagement( 2692): EnabledAppBuilder: Found 9 DM enabled apps.
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
I/Icing   ( 1958): Internal init done: storage state 0
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
I/DeviceManagement( 2692): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
I/Icing   ( 1958): Post-init done
I/DeviceManagement( 2692): Perf: Scan enabled apps - complete: 1052 ms
I/DeviceManagement( 2692): Perf: *** Enabled app cache update - complete: 1054 ms
I/DeviceManagement( 2692): Perf: *** Config cache update - start...
I/DeviceManagement( 2692): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 2692): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 2692): ConfigCacheController: *** Update config cache: updating 0 entries...
I/DeviceManagement( 2692): ConfigCacheController: No changes need to be broadcasted.
I/DeviceManagement( 2692): AlarmController: Scheduling TTL alarm for: 2015.12.08 at 07:48:50.991 CET (due to: com.htc.launcher)
--------- beginning of /dev/log/system
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=2692, uid=10098, userID:0
I/DeviceManagement( 2692): Perf: *** Config cache update - complete: 20 ms
I/DeviceManagement( 2692): Perf: *** Cache update - complete: 1078 ms
I/DeviceManagement( 2692): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@421bd420]
I/DeviceManagement( 2692): WorkflowService: Stopping workflow service
D/Process (  905): killProcessQuiet, pid=2367
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2367:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
D/PMS     (  905): releaseWL(42d083b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Recipient 2367
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 2747): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 2747): ====startRecUseTime====
D/htc.customization.log.level( 2747):  is 
W/CustomizationLogLevel( 2747): Level value is invalid, use default level 2
D/CustomizationManager( 2747):  Read ACC file spent 0.064 (s)
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2747): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2747): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2747): Parsing tag category name = system
I/CustomizationCIDLoader( 2747): Parsing tag category name = application
I/CustomizationCIDLoader( 2747): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2747): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2747): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2747): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2747): Parsing tag category name = Settings
D/CustomizationManager( 2747):  Read CID file spent 0.105 (s)
D/CustomizationManager( 2747):  All configurations done spent 0.105 (s)
W/HtcNativeFlag( 2747): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2747): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2747): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2747): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/asset   (  905): Copying FileAsset 0x623d0e60 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1115808544
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2747
D/PMS     (  905): acquireHCC(42750080): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
D/PMS     (  905): acquireHCC(424fb4b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
D/PMS     (  905): acquireWL(42891200): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/FeedHostManager( 1252): [onPause]
I/FeedProviderManager( 1252): onPause
I/FeedHostManager( 1252): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@422ce978
I/SocialFeedProvider( 1252): +onPause
I/SocialFeedProvider( 1252): -onPause
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2767 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1252): [trimMemory] 20
I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
W/asset   ( 2767): Copying FileAsset 0x5c799428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2709, uid=10107, userID:0
I/ActivityManager(  905): Resuming delayed broadcast
V/WebViewChromiumFactoryProvider( 2767): Binding Chromium to main looper Looper (main, tid 1) {42191d88}
I/LibraryLoader( 2767): Expected native library version number "",actual native library version number ""
I/chromium( 2767): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2767): Initializing chromium process, renderers=0
I/ActivityManager(  905): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42b899f8:true
D/BluetoothAdapter( 2767): 1109030784: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  905): acquireWL(429849e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(42233080): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(42233080): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2767): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2767): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2767): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2767): Local Branch: 
I/Adreno-EGL( 2767): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2767): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2767):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=2791 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/chromium( 2767): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 2767): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2767): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 2767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2767): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 2767): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2767): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2767): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2767): CordovaWebView is running on device made by: HTC
I/htcbackup-core( 2791): ModelRegistry: Loading model meta data from resources...
W/ContextImpl( 2791): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 2791): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 2692): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 2692): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.providers.settings, com.htc.lockscreen, com.htc.android.htcloglevel, com.qualcomm.privinit, com.android.keychain, com.htc.drive.activator, android, com.htc.mirrorlinkserver, com.htc.android.htcsetupwizard, com.android.settings, com.android.location.fused, com.android.CSDFunctionG, com.android.inputdevices, com.htc.cirmodule, com.htc.home.personalize, com.htc.backupreset, com.htc.smartdim, com.qualcomm.timeservice, com.htc.feedback, com.htc.guide, com.htc.usage, com.htc.autobot.cargps.provider, com.htc.backup, com.htc.htcpowermanager, com.htc.checkinprovider]
I/DeviceManagement( 2692): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/DeviceManagement( 2692): WorkflowService: Starting workflow service
I/DeviceManagement( 2692): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@424be3a0] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 2692): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 2692): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 2692): SessionStateController: Checking invariants...
W/AwContents( 2767): nativeOnDraw failed; clearing to background color.
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews( 1112): com.htc.backup (true,33751552)
W/ContextImpl( 2791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42210c48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/ResourceType( 2767): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2767): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@421d8ac8, mServedView=org.apache.cordova.engine.SystemWebView{4219eaa0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +455ms
W/AwContents( 2767): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  905): Disable input method client, pid=1252
I/InputMethodManagerService(  905): Enable input method client, pid=2767
I/RemoteViews.Performance( 1112): com.htc.backup 6 9 8 15
W/XT9_C   ( 1188): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1188): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1188): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/DeviceManagement( 2692): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
D/PMS     (  905): releaseWL(42891200): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{422145a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DeviceManagement( 2692): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@424be3a0]
I/DeviceManagement( 2692): WorkflowService: Stopping workflow service
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/ActivityManager(  905): Resuming delayed broadcast
I/RemoteViews.Performance( 1112): com.htc.backup 1 3 3 4
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1112): com.htc.backup 1 1 1 4
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1112): com.htc.backup 1 1 1 4
I/RemoteViews.Performance( 1112): com.htc.backup 1 8 16 21
I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=2833 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/htcbackup-core( 2791): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
V/AlarmManager(  905): sending alarm PendingIntent{42ba9a68: PendingIntentRecord{42d075d8 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=15, w=1440901414353, Int=604800000
W/dalvikvm( 2791): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
I/RemoteViews( 1112): com.htc.backup (true,33751552)
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews.Performance( 1112): com.htc.backup 5 2 15
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1112): com.htc.backup 1 1 1 4
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1112): com.htc.backup 1 1 0 4
I/RemoteViews( 1112): com.htc.backup (true,33751552)
I/RemoteViews.Performance( 1112): com.htc.backup 1 1 0 4
I/RemoteViews.Performance( 1112): com.htc.backup 1 11 21
D/UPolicy ( 2791): IUserBehaviorLoggingService reference is gotten !
D/Process (  905): killProcessQuiet, pid=2381
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2381:com.htc.musicenhancer/u0a53 (adj 15): empty #17
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2381
W/dalvikvm( 2833): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2833): VFY: unable to resolve instance field 46
W/dalvikvm( 2833): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
I/Babel   ( 2833): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 2833): MmsConfig.loadMmsSettings
V/JNIHelp ( 2833): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_string
E/AndroidProtocolHandler( 2767): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/chromium( 2767): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/Babel   ( 2833): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 2833): MmsConfig.loadFromDatabase
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=2833, uid=10111, userID:0
W/Settings( 2833): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Babel   ( 2833): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 2833): MmsConfig.loadFromResources
E/Babel   ( 2833): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 2833): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=2833, uid=10111, userID:0
D/JsMessageQueue( 2767): Set native->JS mode to OnlineEventsBridgeMode
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=2833, uid=10111, userID:0
V/Babel   ( 2833): babel boot account: thalitester@gmail.com
V/Babel   ( 2833): babel boot account: SMS
D/Process (  905): killProcessQuiet, pid=2125
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=2863 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 2125:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ProviderInstaller( 2833): Installed default security provider GmsCore_OpenSSL
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2125
V/AlarmManager(  905): sending alarm PendingIntent{42e5f180: PendingIntentRecord{42cabf28 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46138, Int=0
V/AlarmManager(  905): sending alarm PendingIntent{42d4a508: PendingIntentRecord{42e56440 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=46140, Int=0
D/jxcore_app_log( 2767): JniHelper::setJavaVM(0x41d4c010), pthread_self() = 1658838048
D/JX-Cordova( 2767): jxcore cordova android initializing
I/ActivityManager(  905): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=2880 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
D/Process (  905): killProcessQuiet, pid=2408
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2408:com.htc.video/u0a57 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2408
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ResetNotifyBootCompleteReceiver( 1219): Receive bootcomplete intent
W/ContextImpl( 1219): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=2895 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
I/HtcCupdXmlParser( 2880): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 2880): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
W/jxcore-log( 2767): Initializing JXcore engine
W/jxcore-log( 2767): JXcore engine is ready
W/jxcore-log( 2767): Starting JXcore engine
D/AppTag  ( 2895): getInstance(Context context)
D/AppTag  ( 2895): getInstance(Context context)
D/AppTag  ( 2895): onCreate()
D/QXDM2SD:HtcNative( 1219): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=2909 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/HtcCupdXmlParser( 2880): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,W/jxcore-log( 2767): Platform android
W/jxcore-log( 2767): 
,W/jxcore-log( 2767): Process ARCH arm
W/jxcore-log( 2767): 
,I/jxcore-log( 2767): JXcore Cordova bridge is ready!
I/jxcore-log( 2767): 
,W/jxcore-log( 2767): JXcore engine is started
,E/jxcore-log( 2767): >> HTC-HTC Desire 820
E/jxcore-log( 2767): 
,I/jxcore-log( 2767): Total memory 1964650496
I/jxcore-log( 2767): 
I/jxcore-log( 2767): Free memory 709234688
I/jxcore-log( 2767): 
,I/jxcore-log( 2767): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2767): 
,I/jxcore-log( 2767): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2767): 
,I/jxcore-log( 2767): userPath [ 'www' ]
I/jxcore-log( 2767): 
,I/jxcore-log( 2767): Size 720 1184
I/jxcore-log( 2767): 
,D/Process (  905): killProcessQuiet, pid=2424
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 2424:com.htc.lmw/u0a60 (adj 15): empty #17
I/jxcore-log( 2767): Screen Brightness 142
I/jxcore-log( 2767): 
E/jxcore-log( 2767): Dummy Error Log.
E/jxcore-log( 2767): 
,I/ActivityManager(  905): Recipient 2424
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 2909): [2909/2909] onCreate()
W/ContextImpl( 2909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/AlarmManager(  905): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  905): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  905): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  905): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=2925 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=2937 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2495
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2495:com.htc.reportagent/u0a66 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2495
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@429ab1a0
,D/HtcFingerPrintQuickLaunchProvider( 2937): -onCreate()
,V/Settings:HtcSettingsApplication( 2937): [2937/2937] onCreate()
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@429801c8
I/AlarmManager(  905): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@429179d8
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
W/ContextImpl( 2937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  905): killProcessQuiet, pid=2544
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  905): killProcessQuiet, pid=2556
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2544:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  905): Killing 2556:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Recipient 2544
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 2937): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2937): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2937): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2937): Cust_ConnectToPC   : spcsc>false
D/        ( 2937): Cust_ConnectToPC   : IPT>true
,D/        ( 2937): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 2937): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  905): Recipient 2556
D/TetherSettings( 2937): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2937): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2937): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2937): Cust_ConnectToPC   : spcsc>false
D/        ( 2937): Cust_ConnectToPC   : IPT>true
D/        ( 2937): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2937): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2937): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2937): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2937): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2937): setISNotification
D/SmartNS_Utility( 2937): usb_cable_connect = 1
D/SmartNS_Utility( 2937): usb_denied = 0
I/SmartNS_PSService( 2937): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2937/1000)
D/SmartNS_Utility( 2937): usb_cable_connect = 1
D/SmartNS_Utility( 2937): usb_denied = 0
I/SmartNS_PSService( 2937): usb notificaiton:true
V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  905): killProcessQuiet, pid=2571
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (2937/1000)
I/ActivityManager(  905): Killing 2571:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2571
,I/RemoteViews( 1112): com.android.settings (true,33751552)
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{421e7648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1112): com.android.settings 1 7 0 10
,I/RemoteViews( 1112): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1112): com.android.settings 0 1 10
,I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42a0a2f8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a0a2f8, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421c2768
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@4284ccb0
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42a0a2f8
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  905): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42a0a2f8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): enable: get sensor name = CM36282 Proximity sensor
I/ActivityManager(  905): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2952 uid=9987 gids={49987}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42aca710 u0 ReceiverList{42a65e38 905 system/1000/u0 local:42304e48}}
,D/NfcUiccLockService( 2952): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  905): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2966 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,D/Process (  905): killProcessQuiet, pid=2600
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2600:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 3
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a0a2f8, eanble = 1, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@421c2768
W/SensorService(  905): Listener[1] = com.android.server.power.DisplayPowerController$10@4284ccb0
W/SensorService(  905): Listener[2] = com.htc.smartdim.sensor_eye@42a0a2f8
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2978 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=2449
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2449:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2449
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2600
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 2978): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/jxcore-log( 2767): getBuffer is called!!!!
I/jxcore-log( 2767): 
,D/libc    ( 2978): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 2978): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 2978): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2978/10168)
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
D/PMS     (  905): releaseHCC(42750080): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock,
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/PMS     (  905): releaseHCC(424fb4b0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2978): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2978): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 2978): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,D/YouTube ( 2978): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 2978): Registered
,I/MediaRouter( 2978): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/YouTube ( 2978): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 2978): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449498939&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (2978/10168)
D/libc    ( 2978): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2978): [NET] getaddrinfo-,err=8
D/libc    ( 2978): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2978): [NET] getaddrinfo-, 1
D/libc    ( 2978): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2978): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2978): Error sending ping
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 2978): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 2978): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 2978): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,D/MediaRouter( 2978): getSelectedRoute
,D/YouTube ( 2978): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2978/10168)
,D/YouTube ( 2978): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
D/YouTube ( 2978): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 2978): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
,I/ActivityManager(  905): Resuming delayed broadcast
D/YouTube ( 2978): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2978): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
,D/Process (  905): killProcessQuiet, pid=2645
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2645:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2645
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/YouTube ( 2978): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
,D/YouTube ( 2978): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
,D/YouTube ( 2978): apps.youtube.datalib.offline.b.run:89 Queuing stored offline request.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (2978/10168)
,W/dalvikvm( 1958): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 1958): Spent 20ms computing apk sha1.
,D/FileApkUtils( 1958): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 1958): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1958): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 1958): Beginning GMS chimera module scan
,W/asset   ( 1958): Copying FileAsset 0x65259c70 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
,W/dalvikvm( 1958): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ChimeraCfgMgr( 1958): Beginning module configuration check
,D/ChimeraCfgMgr( 1958): Module APKs unchanged, check complete
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,E/dalvikvm( 1958): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1958): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1958/10029)
D/PMS     (  905): acquireWL(42d33018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1958): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1958): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1958): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1958): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  905): acquireWL(42c97bb0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42f75338): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1958): COMPAT: Multi user not supported
,D/GCM     ( 1358): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/PMS     (  905): releaseWL(42d33018): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1449484213846 min interval config: 0 actual interval: 14725909
,I/GCoreUlr( 1958): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1202): DispatchingService.onCreate()
,I/CheckinService( 1958): Disabling old GoogleServicesFramework version
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 1958): onCreate
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1958, uid=10029, userID:0
,D/SystemUpdateService( 1958): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
,W/dalvikvm( 1958): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,V/AuthZen ( 1958): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
D/PMS     (  905): acquireWL(42d12c90): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1958, uid=10029, userID:0
D/PMS     (  905): acquireWL(42d1c258): PARTIAL_WAKE_LOCK  Icing 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
I/CheckinService( 1958): Checking schedule, now: 1449498939832 next: 1450007150810
,I/CheckinService( 1958): active receiver: disabled
I/SystemUpdateService( 1958): cancelUpdate (empty URL)
I/SystemUpdateService( 1958): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1958, uid=10029, userID:0
D/PMS     (  905): releaseWL(42d1c258): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/AuthZenEventHandler( 1958): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1958, uid=10029, userID:0
D/PMS     (  905): releaseWL(42f75338): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 1958): onDestroy
,D/PMS     (  905): releaseWL(42c97bb0): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1202): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1958): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1958): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,W/dalvikvm( 1958): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1958): Fetching signing key...
,I/AuthZen ( 1958): Signing key fetched successfully!
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1202, uid=10029, userID:0
,W/BaseAppContext( 1958): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 1958): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1958): Clearing transaction cache
,I/ActivityManager(  905): Resuming delayed broadcast
,I/GCoreUlr( 1202): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  905): acquireWL(42c4fcd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1202): Unbound from all location providers
D/PMS     (  905): releaseWL(42c4fcd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42d12c90): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/PMS     (  905): acquireWL(42d30e58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1958 10029 null
D/PMS     (  905): acquireWL(42d26648): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1958 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,D/PMS     (  905): releaseWL(42d30e58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  905): releaseWL(42d26648): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1202): DispatchingService.onDestroy()
,I/GCoreUlr( 1202): Stopping handler for UlrDispSvcFast
I/ActivityManager(  905): Resuming delayed broadcast
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1202): Unbound from all location providers
D/PMS     (  905): acquireWL(42fa3098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42fa3098): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,W/Auth    ( 1358): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(42d10dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1358 10029 null
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  905): releaseWL(42d10dc8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1958): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1358): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3065 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42ea3020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42ea3020): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): releaseWL(429849e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3065, uid=10074, userID:0
,D/Finsky  ( 3065): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3065/10074)
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3065/10074)
,D/Finsky  ( 3065): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3065): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3065): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3065): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3065, uid=10074, userID:0
,D/Volley  ( 3065): [283] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3065): [276] DiskBasedCache.clear: Cache cleared.
,D/Process (  905): killProcessQuiet, pid=2665
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2665:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/Ads     ( 3065): Skipping gmscore version check
,D/Finsky  ( 3065): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3065): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  905): Recipient 2665
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1302): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2937): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2937): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2937): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2937): Cust_ConnectToPC   : spcsc>false
D/        ( 2937): Cust_ConnectToPC   : IPT>true
D/        ( 2937): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2937): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2937): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2937): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2937): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1302): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/Finsky  ( 3065): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/PSReceiver( 2937): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 2937): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2937): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2937):  defaultType:0
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/Finsky  ( 3065): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3105 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3105): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3105): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3105): Loading: swewebviewchromium
,I/LibraryLoader( 3105): Time to load native libraries: 40 ms (timestamps 812-852)
,I/LibraryLoader( 3105): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3105): Initializing chromium process, renderers=9
I/LibraryLoader( 3105): Expected native library version number "",actual native library version number ""
,I/chromium( 3105): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 4 times.
,I/GAV2    ( 2709): Thread[GAThread,5,main]: No campaign data found.
,W/chromium( 3105): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3105): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3105): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3105): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3105): Local Branch: 
I/Adreno-EGL( 3105): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3105): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3105):                  aa63bbd948f41d15fc72f585e
,D/Process (  905): killProcessQuiet, pid=2677
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1277): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  905): Killing 2677:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/SIMStateChangeReceiver( 1488): SIM state: ABSENT
I/SIMStateChangeReceiver( 1488): phoneType = 0
,I/SIMStateChangeReceiver( 1488): remove notification
I/ActivityManager(  905): Recipient 2677
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3146 uid=10032 gids={50032, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2709
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3158 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 2709:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2477): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2477): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2477): onReceive()
,D/ExchangePolicystatus( 2477): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2477): onReceive(): else
,D/Process (  905): killProcessQuiet, pid=2791
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  905): Killing 2791:com.htc.backup/1000 (adj 15): empty #17
D/HtcBroadcastReceiver( 1219): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/ActivityManager(  905): Recipient 2791
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1112): can't get weather sync account
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3174 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  905): Recipient 2709
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherRequest( 1112): request cur loc, but there is no sys cur
,D/AccTypeManager( 3158): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3174): onCreate
D/ProviderChangeReceiver( 3174): ---------------------------------------------------
,D/ProviderChangeReceiver( 3174): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3174): start to updateAlertNotification!
W/ContextImpl( 2909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3192 uid=10041 gids={50041}
,D/AlertService( 3174): No fired or scheduled alerts
,W/AccTypeManager( 3158): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/HtcAlertUtils( 3174): -- cancelReminderNotification --
,D/AccTypeManager( 3158): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/HtcAlertUtils( 3174): broadcastExistReminder!
,D/Process (  905): killProcessQuiet, pid=2692
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  905): Killing 2692:com.htc.cs.dm/u0a98 (adj 15): empty #17
,E/ExternalAccountType( 3158): Unsupported attribute readOnly
,D/Process (  905): killProcessQuiet, pid=2833
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3205 uid=10078 gids={50078}
I/ActivityManager(  905): Killing 2833:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2692
,D/AccTypeManager( 3158): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3158): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3158): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3205): Got a database change event
,E/ExternalAccountType( 3158): Unsupported attribute readOnly
,D/Process (  905): killProcessQuiet, pid=2863
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3217 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  905): Killing 2863:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2833
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 2863
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3232 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3217): can't get weather sync account
,W/WeatherRequest( 3217): request cur loc, but there is no sys cur
,W/Settings( 3217): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3232): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3232): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3232): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 2 10 17
,D/Process (  905): killProcessQuiet, pid=2880
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3246 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 2880:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2880
,D/PMS     (  905): acquireWL(42674128): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3246 10071 null
,D/PMS     (  905): acquireWL(4250aa88): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3246 10071 null
,D/PMS     (  905): releaseWL(42674128): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3246): update TASK shortcut>
,I/TodoTaskNotifyService( 3246): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3246): stopSelfResult true
D/PMS     (  905): releaseWL(4250aa88): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3262 uid=10082 gids={50082, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2895
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2895:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 2895
,I/ActivityManager(  905): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3275 uid=10082 gids={50082, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=2925
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 2925:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/SMSBackup( 3205): Got a database change event
I/ActivityManager(  905): Recipient 2925
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3287 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  905): killProcessQuiet, pid=2952
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2952:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2952
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
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
,I/ActivityManager(  905): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/NewsDB  ( 3287): set custom highlight []
,D/CustomHighlightService( 3287): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2477): keep hiding shortcut bubble
D/MessagingShortcut( 2477): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2477): After query: 0
D/MessagingShortcut( 2477): mPresentUnreadCount: -1
,D/MessagingShortcut( 2477): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2477): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,I/ActivityManager(  905): Resuming delayed broadcast
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderNotification, total:0
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3246): update TASK shortcut>
I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1219): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  905): killProcessQuiet, pid=2966
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2966:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3303 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  905): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,D/MessagingNotification( 2477): New incoming message, can't cancel notification now
,D/MessagingNotification( 2477): newMsgCnt: 0, false
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022933
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023520
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023525
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023530
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027664
,V/AlarmManager(  905): sending alarm PendingIntent{42704778: PendingIntentRecord{42c43418 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20669, Int=1800000
I/ActivityManager(  905): Recipient 2966
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  905): sending alarm PendingIntent{42d3fcc0: PendingIntentRecord{42c4c8c0 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=45992, Int=259200000,
,V/AlarmManager(  905): sending alarm PendingIntent{42452cf0: PendingIntentRecord{42b08300 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49778, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{427dc210: PendingIntentRecord{4271fe98 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1449486000000, Int=86400000
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3317 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3303): [1a8.1.] 30@-153515 -> 40@-153542
,D/Process (  905): killProcessQuiet, pid=2978
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Killing 2978:com.google.android.youtube/u0a168 (adj 15): empty #17
,D/Process (  905): killProcessQuiet, pid=3065
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3065:com.android.vending/u0a74 (adj 15): empty #17
,D/WearableService( 1202): callingUid 10029, callindPid: 1202
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1958, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
E/MDM     ( 1202): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1958): Restart initialization of location
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  905): Recipient 2978
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  905): Client com.google.android.youtube (pid 2978): Died!
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1358): location=null
D/PMS     (  905): acquireWL(42acf960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42acf960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023520
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023530
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027664
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
,D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  905): Recipient 3065
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  905): Resuming delayed broadcast
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1958): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42c9c478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
,E/MDM     ( 1202): [65] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/PMS     (  905): releaseWL(42c9c478): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1958, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1958, uid=10029, userID:0
,D/LocationInitializer( 1958): Restart initialization of location
I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1358): location=null
D/PMS     (  905): acquireWL(42f39488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42f39488): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023520
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023530
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027664
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1958): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42d47bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3341 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023411
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023520
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023530
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027664
,D/PMS     (  905): releaseWL(42d47bc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  905): killProcessQuiet, pid=2937
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2937:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2937
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3341): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3341): MmsConfig.loadMmsSettings
,W/dalvikvm( 3341): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3341): VFY: unable to resolve instance field 46
,W/dalvikvm( 3341): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3341): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2477): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3341): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3341): MmsConfig.loadFromDatabase
,E/Babel   ( 3341): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3341): MmsConfig.loadFromResources
,E/Babel   ( 3341): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3341): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3341, uid=10111, userID:0
,W/Settings( 3341): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3341, uid=10111, userID:0
,D/Process (  905): killProcessQuiet, pid=3105
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3341, uid=10111, userID:0
I/ActivityManager(  905): Killing 3105:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/MtpReceiver( 2168): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2168): [MTP][handleMessage][startService]
,D/MtpReceiver( 2168): [MTP][MtpReceiver][onReceive]1-
D/PMS     (  905): acquireWL(42b89f60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1358/10029)
D/MtpReceiver( 2168): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2168): [MTP][handleMessage]-
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360022933
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023411
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023520
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023525
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023530
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027664
D/PMS     (  905): releaseWL(42b89f60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpService( 2168): [MTP] startForeground
I/RemoteViews( 1112): com.android.providers.media (false,0)
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3367 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1112): com.android.providers.media 2 2 10
D/MtpService( 2168): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2168): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews( 1112): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1112): com.android.providers.media 3 1 15
,D/MtpService( 2168): [isMtpConnected] connected: true
D/PMS     (  905): acquireWL(42d20868): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1958 10029 null
,I/ProviderInstaller( 3341): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  905): Recipient 3105
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3367): Loading default preferences
,I/iu.UploadsManager( 1958): End new media; added: 0, uploading: 0, time: 159 ms
D/PMS     (  905): releaseWL(42d20868): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/Resources( 3367): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 3367): Overriding preferences with custom values
,D/SyncApplication( 3367): Updating preferences succeeded
,E/SyncApplication( 3367): Application created.
D/VolumeInfo( 3367): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3367): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3367): Found 0 mount point(s)
,V/VolumeInfo( 3367): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3367): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3367): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3367): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3367): getNewCalendarAuthority()...
,D/SyncApplication( 3367): enableAppOperation()+
,D/SyncApplication( 3367): enableAppOperation()-
,D/HTCUtilities( 3367): isNeorSinged() + 
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3367, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3367, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3367): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3367): isNeorSinged() return false
,D/CDMountReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3367): USB connected to PC
,D/FOTAReceiver( 3367): onReceive() enter 
,D/FOTAReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3387 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=3146
,I/ActivityManager(  905): Killing 3146:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  905): Recipient 3146
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3387): -onCreate()
,V/Settings:HtcSettingsApplication( 3387): [3387/3387] onCreate()
,D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
D/        ( 3387): Cust_ConnectToPC   : IPT>true
,D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
D/        ( 3387): Cust_ConnectToPC   : IPT>true
D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3387): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3387): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3387): usb_cable_connect = 1
,D/SmartNS_Utility( 3387): usb_denied = 0
I/SmartNS_NSReceiver( 3387): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3387): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3387): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3387): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3387):  defaultType:0
,I/SmartNS_PSService( 3387): fail notificaiton:false
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
D/SmartNS_Utility( 3387): usb_denied = 0
,I/SmartNS_PSService( 3387): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3387/1000)
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
D/SmartNS_Utility( 3387): usb_denied = 0
,I/SmartNS_PSService( 3387): usb notificaiton:true
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  905): bSetPropertyMultiRAB:false
I/ActivityManager(  905): Resuming delayed broadcast
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.settings (3387/1000)
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1112): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1112): com.android.settings 1 1 10
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
,D/SmartNS_Utility( 3387): usb_denied = 0
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3387): KeyGuard locked:falseKeyGuard is secured:false
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/SmartNS_PSService( 3387): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews( 1112): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1112): com.android.settings 2 0 10
,W/WeatherUtility( 3217): can't get weather sync account
I/ActivityManager(  905): Resuming delayed broadcast
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1252): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1252): com.google.android.googlequicksearchbox 1 0 5
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3404 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/WeatherRequest( 3217): request cur loc, but there is no sys cur
,W/Settings( 3217): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  905): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1344
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
,W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): ,	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): ,	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): ,	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183),
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): ,	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 2(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,D/WifiManager( 2767): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1259
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,W/System.err(  905): java.lang.Throwable: stack dump
I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
,W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
D/WifiService(  905): New client listening to asynchronous messages
D/WifiService(  905): setWifiEnabled: false pid=2767, uid=10396
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
W/Settings:Agent(  905): << traceCallingStack(): 7(ms)
I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 0 8 17
,I/jxcore-log( 2767): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 2767): 
,I/jxcore-log( 2767): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2767): 
,D/PowerUsageService( 3404): call getInstance()
W/ContextImpl( 3404): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
D/PowerUsageList:PowerUsageHelper( 3404): MY_DEBUG = false
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(4274f458): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3404 1000 null
,D/Process (  905): killProcessQuiet, pid=3158
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3158:com.htc.contacts/u0a44 (adj 15): empty #17
,W/WeatherUtility( 1112): can't get weather sync account
,D/WeatherUtility( 1302): Weather sync is On
,D/WSP     ( 1302): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  905): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3426 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherUtility( 3217): can't get weather sync account
D/PMS     (  905): releaseWL(4274f458): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/WeatherRequest( 3217): request cur loc, but there is no sys cur
,W/Settings( 3217): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 1 5 17
,E/cutils-trace( 3420): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  905): Recipient 3158
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/CustomizationManager( 3420): ====startRecUseTime====
D/htc.customization.log.level( 3420):  is 
,W/CustomizationLogLevel( 3420): Level value is invalid, use default level 2
,D/CustomizationManager( 3420):  Read ACC file spent 0.058 (s)
,D/CIDMapFileReader( 3420): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 3420): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3420): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3420): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3420): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3420): Parsing tag category name = system
,I/CustomizationCIDLoader( 3420): Parsing tag category name = application
,I/CustomizationCIDLoader( 3420): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3420): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3420): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3420): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3420): Parsing tag category name = Settings
,D/CustomizationManager( 3420):  Read CID file spent 0.106 (s)
,D/CustomizationManager( 3420):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 3420): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3420): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3420): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3420): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=3420, uid=2000 user=0
,I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=2767
,W/asset   (  905): Copying FileAsset 0x6a21e1e8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 2767:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  905): Force removing ActivityRecord{42983d78 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  905): Skipping PackageSetting{42863ab0 com.test.thalitest/10389} due to missing metadata
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowState(  905): WIN DEATH: Window{429ad1a8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  905): Client connection lost with reason: 4
,I/ActivityManager(  905): Force stopping com.example.hello appid=10396 user=0: pkg removed
,I/SensorManager(  905): mEventCount = 300
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/Prism.ItemManager( 3287): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3287): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/AccTypeManager( 1322): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(42e6c428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,I/FeedHostManager( 1252): [onResume]
,I/FeedProviderManager( 1252): onResume
I/SocialFeedProvider( 1252): +onResume
I/SocialFeedProvider( 1252): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1252): -onResume
I/ConnectivityHelper( 1252): [getCurrentConnectionType] no network connection
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1252/10076)
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/AccTypeManager( 1322): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1322): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
,W/SystemReader( 1235): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  905): releaseWL(42e6c428): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1219): MSG_NOTIFY_CS_TO_SYNC <<
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,E/ExternalAccountType( 1322): Unsupported attribute readOnly
,W/Binder  ( 1188): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1188): java.lang.NullPointerException
W/Binder  ( 1188): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1188): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1188): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1188): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  905): Resuming delayed broadcast
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 2767 uid 10396
I/InputMethodManagerService(  905): Enable input method client, pid=1252
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/PackageManager(  905):   Scheme: "sms"
,D/Process (  905): killProcessQuiet, pid=3174
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3455 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  905): Killing 3174:com.htc.calendar/u0a13 (adj 15): empty #17
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/ActivityManager(  905): Recipient 3174
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1219 :
,D/PhoneApp( 1219): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/MusicStore( 3455): Database version: 95
,W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
V/AlarmManager(  905): sending alarm PendingIntent{42aff6b8: PendingIntentRecord{42b03998 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449498944906, Int=0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3455): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/Process (  905): killProcessQuiet, pid=2909
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2909:com.android.settings:remote/1000 (adj 15): empty #17
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/PackageManager(  905): Unable to load service info ResolveInfo{42d084c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,W/ContextImpl( 3455): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3455): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3455, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 3455): Registered
,I/MediaRouter( 3455): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/DFPI.PIReciver( 3232): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (3455/10154)
I/DFPI.ApkInstallService( 3232): onHandleIntent
,I/DFPI.ApkInstallService( 3232): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3232): check CID = HTC__032
,I/DFPI.ApkInstallService( 3232): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,D/MediaRouter( 3455): getSelectedRoute
I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/ActivityManager(  905): Recipient 2909
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3455, uid=10154, userID:0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3479 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  905): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.musicenhancer (3479/10053)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3479): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42f92bf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42f92bf0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  905): start
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 5 times.

```
