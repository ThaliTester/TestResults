#### Test 503880196b4ec73_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/ContactMessageStore( 1453): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1453): MSG_NOTIFY_CS_TO_SYNC <<
D/SmsReceiver( 3707): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 3707): onReceive()
D/ExchangePolicystatus( 3707): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 3707): onReceive(): else
D/Process (  940): killProcessQuiet, pid=4136
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
--------- beginning of system
I/ActivityManager(  940): Killing 4136:com.android.settings:remote/1000 (adj 15): empty #17
I/ActivityManager(  940): Recipient 4136
V/IccIntentReceiver( 1638): IccIntent: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED icc state: null icc slot: 0
D/GCM     ( 1892): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1892): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 4268): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/AccTypeManager( 4735): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 4735): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  940): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4769 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4268, uid=10024, userID:0
W/ResourcesManager( 4769): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4769): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TelephUtils( 1453): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1453): sku_id=118
I/MultiDex( 4769): VM with version 2.1.0 has multidex support
I/MultiDex( 4769): install
I/MultiDex( 4769): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  940): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4794 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/LocationInitializer( 4268): Restart initialization of location
V/JNIHelp ( 4769): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/AccTypeManager( 4735): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 4735): Unsupported attribute readOnly
W/ActivityThread( 4769): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4769): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@203e72b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4769): Installed default security provider GmsCore_OpenSSL
D/AccTypeManager( 4735): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/WearableService( 4769): callingUid 10024, callindPid: 4769
D/AccTypeManager( 4735): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 4735): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/MDM     ( 1786): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/ExternalAccountType( 4735): Unsupported attribute readOnly
I/art     (  940): Explicit concurrent mark sweep GC freed 11446(601KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.481ms total 161.650ms
D/TelephUtils( 1453): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1453): sku_id=118
I/ImageRamCache( 4794): create image Cache, size: 31457280.
I/ImageRamCache( 4794): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4794): create image Cache, size: 31457280.
D/TelephUtils( 1453): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 65
D/AccFlag ( 1453): sku_id=118
I/FeedSettings( 4794): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4794): GroupBudget 0.500000 0.380000
I/FeedSettings( 4794): GroupBudget 60 45 15
D/TelephUtils( 1453): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 64
D/AccFlag ( 1453): sku_id=118
I/Prism.ExternalStringMa_( 4794): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 4794): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4794): loadGridSize() with Alternative
D/CustomHighlightReceiver( 4794): [custom highlight] onReceive
D/CustomHighlightService( 4794): [custom highlight] onHandleIntent
D/NewsDB  ( 4794): set custom highlight []
I/ActivityManager(  940): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4825 uid=10035 gids={50035, 9997} abi=arm64-v8a
D/CustomHighlightService( 4794): [custom highlight] set tags 
D/Process (  940): killProcessQuiet, pid=4161
I/ActivityManager(  940): Killing 4161:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/Atfwd_Sendcmd(  448): AtCmdFwd service not published, waiting... retryCnt : 4
I/ActivityManager(  940): Recipient 4161
,I/ActivityManager(  940): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4849 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  940): killProcessQuiet, pid=4184
I/ActivityManager(  940): Killing 4184:com.android.smith/1000 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  940): Recipient 4184
E/cutils-trace( 4847): Error opening trace file: Permission denied (13)
D/SMSBackup( 4849): Got a database change event
D/CustomizationManager( 4847): ====startRecUseTime====
I/ActivityManager(  940): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4884 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/htc.customization.log.level( 4847):  is 
I/ActivityManager(  940): Killing 4092:com.android.settings/1000 (adj 15): empty #17
W/CustomizationLogLevel( 4847): Level value is invalid, use default level 2
D/Process (  940): killProcessQuiet, pid=4092
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/CustomizationManager( 4847):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4847): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4847): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4847): Parsing tag category name = system
I/CustomizationCIDLoader( 4847): Parsing tag category name = application
I/CustomizationCIDLoader( 4847): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4847): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4847): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4847): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4847): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4847): add string-array item, value = 42507
I/CustomizationCIDLoader( 4847): add string-array item, value = 21902
I/CustomizationCIDLoader( 4847): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4847): add string-array item, value = 23420
I/CustomizationCIDLoader( 4847): add string-array item, value = 22299
I/CustomizationCIDLoader( 4847): add string-array item, value = 24002
I/CustomizationCIDLoader( 4847): add string-array item, value = 23210
I/CustomizationCIDLoader( 4847): add string-array item, value = 23205
I/CustomizationCIDLoader( 4847): add string-array item, value = 23806
I/CustomizationCIDLoader( 4847): add string-array item, value = 23430
I/CustomizationCIDLoader( 4847): add string-array item, value = 23408
I/CustomizationCIDLoader( 4847): add string-array item, value = 27205
I/CustomizationCIDLoader( 4847): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4847): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4847):  Read CID file spent 0.091 (s)
D/CustomizationManager( 4847):  All configurations done spent 0.092 (s)
I/ActivityManager(  940): Recipient 4092
I/ActivityManager(  940): Waited long enough for: ServiceRecord{298e3a34 u0 com.htc.HTCSpeaker/.NGFService}
I/ActivityManager(  940): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4847 on display 0
D/PMS     (  940): acquireHCC(97cba8c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 940 1000 null
W/asset   (  940): Copying FileAsset 0x55901ea560 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  940): acquireHCC(1f3a45d5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 940 1000 null
D/PMS     (  940): acquireWL(1f80f378): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 940 1000 null
I/AnimationUtil(  940): isHTCRecent(HelloWorld/Recent screens.)/10
I/FeedHostManager( 1521): [onPause]
I/FeedProviderManager( 1521): onPause
I/FeedHostManager( 1521): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@b9ec6f3
I/SocialFeedProvider( 1521): +onPause
I/SocialFeedProvider( 1521): -onPause
W/HtcSystemUPManager(  940): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  940): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4907 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/MessagingShortcutReceiver( 3707): keep hiding shortcut bubble
D/MessagingShortcut( 3707): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3707): After query: 0
D/MessagingShortcut( 3707): mPresentUnreadCount: -1
D/MessageUtils( 3707): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3707): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 3707): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderNotification, total:0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcModeClient( 3152): handler message = 4011
E/HtcModeClient( 3152): Check connection and retry 4 times.
W/asset   ( 4907): Copying FileAsset 0xac5498a0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  940): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4930 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
V/AlarmManager(  940): sending alarm PendingIntent{1c69b442: PendingIntentRecord{3afa0c53 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=59914, Int=0
D/StatusBarManagerService(  940): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  940): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  940): hiding MENU key
I/TrimMemoryManager( 1521): [trimMemory] 20
I/ActivityManager(  940): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4952 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
W/ResourcesManager( 4930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/TodoTaskshortcut( 4930): update TASK shortcut>
I/WebViewFactory( 4907): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/Process (  940): killProcessQuiet, pid=4242
I/ActivityManager(  940): Killing 4242:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/MdScBoot( 4884): [5d7.1.] 30@-192045 -> 40
D/MdScBootUi( 4884): [5d7.1.2.] boot 118
D/MdScSimSt( 4884): [5d7.1.2.] qry 118: 0+1 running 0
D/PMS     (  940): acquireWL(5bd899a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
I/LibraryLoader( 4907): Time to load native libraries: 11 ms (timestamps 95-106)
I/LibraryLoader( 4907): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4907): Binding Chromium to main looper Looper (main, tid 1) {1c6f8330}
I/LibraryLoader( 4907): Expected native library version number "",actual native library version number ""
I/chromium( 4907): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4907): Initializing chromium process, singleProcess=true
W/art     ( 4907): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4907): ApplicationContext is null in ApplicationStatus
W/chromium( 4907): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/ActivityManager(  940): Recipient 4242
W/chromium( 4907): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4907): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4907): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4907): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4907): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4907): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4907): Local Branch: 
I/Adreno-EGL( 4907): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4907): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4907):                  d74aa161a12b9c6fc6332151
W/System.err(  940): java.lang.Throwable: stack dump
D/BluetoothManagerService(  940): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  940): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@174589c1:true
W/System.err(  940): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  940): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  940): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  940): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 4907): 883108047: getState() :  mService = null. Returning STATE_OFF
D/Process (  940): killProcessQuiet, pid=4205
I/ActivityManager(  940): Killing 4205:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/PMS     (  940): releaseWL(5bd899a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  940): Recipient 4205
D/PMS     (  940): acquireWL(2f47af84): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4930 10069 null
D/Process (  940): killProcessQuiet, pid=3383
D/PMS     (  940): acquireWL(3d18236d): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4930 10069 null
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  940): Killing 3383:com.android.defcontainer/u0a15 (adj 15): empty #17
W/art     ( 4907): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4907): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4907): CordovaWebView is running on device made by: HTC
I/ActivityManager(  940): Recipient 3383
D/MtpReceiver( 3651): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3651): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3651): [MTP][handleUsbState]+
D/PMS     (  940): releaseWL(2f47af84): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/art     ( 4907): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4907): Attempt to remove local handle scope entry from IRT, ignoring
E/TodoTaskNotifyService( 4930): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4930): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4930): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4930): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
D/PMS     (  940): releaseWL(3d18236d): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/System.err( 4930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4930): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4930): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  940): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5002 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
W/NotifyReceiver( 4930): stopSelfResult true
D/MtpReceiver( 3651): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpService( 3651): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpReceiver( 3651): [MTP][handleUsbState]-
D/MtpReceiver( 3651): [MTP][handleMessage]-
D/MtpDatabase( 3651): TotalSize=1886532,MediaCacheLimit=6000
D/MtpService( 3651): [isMtpConnected] connected: true
W/chromium( 4907): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/GAV2    ( 4483): Thread[GAThread,5,main]: No campaign data found.
D/FindExtension( 4907): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/MediaScannerService( 3651): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3651): [handleMessage] --- Should not be here, ignore request. ----
I/GAv4-SVC( 4268): Google Analytics 7.8.99 is starting up.
D/SyncApplication( 5002): Loading default preferences
W/Resources( 5002): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  940): New client listening to asynchronous messages
E/WifiTrafficPoller(  940): ADD_CLIENT: 7
I/InputMethodManager( 4907): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@a2565d5, mServedView=org.apache.cordova.engine.SystemWebView{eb171ea VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@173efcdb
I/InputMethodManagerService(  940): Disable input method client, pid=1521
D/StatusBarManagerService(  940): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/InputMethodManagerService(  940): Enable input method client, pid=4907
E/MediaScannerServiceEx( 3651): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3651): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 3651): [handleExternalVolume] ext storage
I/ActivityManager(  940): Displayed com.example.hello/.MainActivity: +1s145ms
D/MediaProviderUtils( 3651): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3651): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3651): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3651): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3651): [AliveExtStorageRows]+65537, 11223344
D/SyncApplication( 5002): Overriding preferences with custom values
D/PMS     (  940): releaseWL(1f80f378): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/MediaProvider( 3651): [update][5]#0#
D/MediaProvider( 3651): [update][1]#0#
I/art     ( 1892): Explicit concurrent mark sweep GC freed 10054(541KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 621us total 38.253ms
W/XT9_C   ( 1356): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1356): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1356): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/MediaProvider( 3651): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3651): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3651): [update][53]#1#
D/MediaScannerServiceEx( 3651): [AliveExtStorageRows]-0, 0
D/PMS     (  940): acquireWL(262d8520): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3651 10017 null
D/SyncApplication( 5002): Updating preferences succeeded
D/MediaScanner( 3651): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
E/SyncApplication( 5002): Application created.
W/BindingManager( 4907): Cannot call determinedVisibility() - never saw a connection for the pid: 4907
I/CalendarDefines( 5002): getNewCalendarAuthority()...
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5002, uid=10005, userID:0
W/PackageManager(  940): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5002, uid=10005, userID:0
W/PackageManager(  940): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 5002): enableAppOperation()+
W/VolumeInfo( 5002): Unable to read mount points
W/VolumeInfo( 5002): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5002): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 5002): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 5002): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 5002): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 5002): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 5002): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 5002): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 5002): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 5002): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 5002): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 5002): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 5002): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 5002): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 5002): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 5002): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 5002): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 5002): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 5002): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 5002): 	... 13 more
V/VolumeInfo( 5002): Found 0 mount point(s)
V/VolumeInfo( 5002): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/SyncApplication( 5002): enableAppOperation()-
D/VolumeInfo( 5002): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/chromium( 4907): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/HTCUtilities( 5002): isNeorSinged() + 
D/VolumeInfo( 5002): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 5002): Can not create volume ID for unmounted volume null
D/HTCUtilities( 5002): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 5002): isNeorSinged() return false
D/CDMountReceiver( 5002): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 5002): USB connected to PC
,D/FOTAReceiver( 5002): onReceive() enter 
,D/FOTAReceiver( 5002): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  940): Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,D/Process (  940): killProcessQuiet, pid=4404,
I/ActivityManager(  940): Killing 4404:com.google.android.youtube/u0a176 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/JsMessageQueue( 4907): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4907): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  940): Recipient 4404,
,D/jxcore_app_log( 4907): JniHelper::setJavaVM(0xab3ee8f8), pthread_self() = -1401800744
,D/JX-Cordova( 4907): jxcore cordova android initializing
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 5051): -onCreate()
,V/Settings:HtcSettingsApplication( 5051): [5051/5051] onCreate()
,D/TetherSettings( 5051): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5051): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5051): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5051): Cust_ConnectToPC   : spcsc>false
D/        ( 5051): Cust_ConnectToPC   : IPT>true
D/        ( 5051): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5051): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5051): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5051): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5051): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 5051): usb_cable_connect = 1
,D/SmartNS_Utility( 5051): usb_denied = 0
,I/SmartNS_NSReceiver( 5051): locked:falsesecurity:falseisLocked:false,
D/SmartNS_NSReceiver( 5051): USB = true hasTethered = false isNSOpening: false
W/jxcore-log( 4907): Initializing JXcore engine
W/jxcore-log( 4907): JXcore engine is ready
,W/jxcore-log( 4907): Starting JXcore engine,
,I/PSReceiver( 5051): onReceive:com.htc.intent.action.USB_CONNECT2PC,
,W/ContextImpl( 5051): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_PSService( 5051): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 5051): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 5051):  defaultType:0
I/SmartNS_PSService( 5051): fail notificaiton:false
,D/SmartNS_Utility( 5051): usb_cable_connect = 1
,D/SmartNS_Utility( 5051): usb_denied = 0
,I/SmartNS_PSService( 5051): usb notificaiton:true
E/WifiStateMachine(  940): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  940): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/ActionCombine( 5051): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/SmartNS_Utility( 5051): usb_cable_connect = 1
,D/SmartNS_Utility( 5051): usb_denied = 0
I/SmartNS_PSService( 5051): usb notificaiton:true
E/WifiStateMachine(  940): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1221): reapply : com.android.settings 1 36,
,D/SmartNS_Utility( 5051): usb_cable_connect = 1
D/SmartNS_Utility( 5051): usb_denied = 0
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
I/SmartNS_PSService( 5051): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 5051): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  940): killProcessQuiet, pid=4483,
I/ActivityManager(  940): Killing 4483:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/jxcore-log( 4907): Platform android
W/jxcore-log( 4907): 
W/jxcore-log( 4907): Process ARCH arm
W/jxcore-log( 4907): 
,I/jxcore-log( 4907): JXcore Cordova bridge is ready!,
I/jxcore-log( 4907): 
W/jxcore-log( 4907): JXcore engine is started
I/ActivityManager(  940): Recipient 4483
,W/ContextImpl( 5074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
,D/FlexNetS( 4626): updateSvcAllowedInSettings:false
,D/PMS     (  940): acquireWL(2bb75011): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1892 10024 WorkSource{10024 com.google.android.gms}
,D/Process (  940): killProcessQuiet, pid=4528
,I/ActivityManager(  940): Killing 4528:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1892): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1892): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1892): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1892): [NET] android_getaddrinfo_proxy+
D/libc    ( 1892): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1892): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  940): releaseWL(2bb75011): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,E/jxcore-log( 4907): >> HTC-HTC One M8s
E/jxcore-log( 4907): 
,I/jxcore-log( 4907): Total memory 1931808768
I/jxcore-log( 4907): 
,I/jxcore-log( 4907): Free memory 98295808
I/jxcore-log( 4907): 
I/jxcore-log( 4907): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4907): 
I/jxcore-log( 4907): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4907): 
,I/jxcore-log( 4907): userPath [ 'www' ]
I/jxcore-log( 4907): 
,I/jxcore-log( 4907): Size 1080 1776
I/jxcore-log( 4907): 
,I/jxcore-log( 4907): Screen Brightness 142
I/jxcore-log( 4907): 
,E/jxcore-log( 4907): Dummy Error Log.
E/jxcore-log( 4907): 
,I/ActivityManager(  940): Recipient 4528
,D/WifiService(  940): Client connection lost with reason: 4
,D/PMS     (  940): releaseHCC(97cba8c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  940): releaseHCC(1f3a45d5): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null,
,I/ActivityManager(  940): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5099 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,I/art     (  431): Explicit concurrent mark sweep GC freed 8673(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 154us total 20.901ms
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 130us total 15.453ms,
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 127us total 15.793ms
,W/ContextImpl( 5099): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5099): MY_DEBUG = false
,D/PowerUsageService( 5099): repeat time = 1448307378103,
,D/PMS     (  940): acquireWL(14f82777): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5099 1000 null
,I/ActivityManager(  940): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5125 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/WeatherUtility( 1419): Weather sync is On
,D/WSP     ( 1419): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PMS     (  940): acquireWL(3c8e7302): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4626 10011 null,
,E/SQLiteLog( 4626): (284) automatic index on view_events(_id),
,I/ActivityManager(  940): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5151 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,D/WeatherUtility( 5125): Weather sync is On
,I/PowerUsageList:PowerUsageHelper( 5099): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/jxcore-log( 4907): getBuffer is called!!!!
I/jxcore-log( 4907): 
,W/WeatherRequest( 5125): request cur loc, but there is no sys cur,
W/Settings( 5125): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  940): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5172 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
I/ActionCombine( 5125): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/PowerUsageList:BatterySipperExt( 5099): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 5099): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5099): gen(), null == sipper.uidObj, userId = 0
,I/RemoteViews( 1521): reapply : com.htc.widget.weatherclock 10 17
,D/PMS     (  940): releaseWL(3c8e7302): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null,
,D/PowerUsageService( 5099): calcPower(), no data
D/Process (  940): killProcessQuiet, pid=4654
I/ActivityManager(  940): Killing 4654:com.htc.showme/u0a81 (adj 15): empty #17
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/art     (  940): Explicit concurrent mark sweep GC freed 13711(713KB) AllocSpace objects, 2(584KB) LOS objects, 33% free, 16MB/24MB, paused 2.477ms total 176.925ms
,W/ResourcesManager( 5151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  940): Recipient 4654
,I/SocialFeedProvider( 1521): +disConnect socialManager
I/SocialFeedProvider( 1521): disconnect socialManager
,I/SocialFeedProvider( 1521): -disConnect socialManager
,V/AlarmManager(  940): sending alarm PendingIntent{22294805: PendingIntentRecord{1863605a com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448306478602, Int=0
,I/SocialManager[SocialBiLogHelper]( 4794): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4794): last commit ulog time 1448258067684
I/SocialManager[SocialBiLogHelper]( 4794): skip commit this time
,I/EASAppSvc( 5172): [ NA ]onCreate,
,D/MediaProvider( 3651): [update][157]#1#
,D/MediaScanner( 3651):  prescan time: 537ms
D/MediaScanner( 3651):     scan time: 1048ms
D/MediaScanner( 3651): postscan time: 5ms
,D/MediaScanner( 3651):    total time: 1590ms
D/MediaScanner( 3651): -----------------------------------------------------------------
D/MediaScanner( 3651): firstscan(media) time: 390ms
D/MediaScanner( 3651): secondscan(non-media) time: 658ms
D/MediaScanner( 3651):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3651):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0,
D/MediaScanner( 3651):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3651):  [Total]    File(Image+Video+Audio+Others) in database : 1546
,I/VersionUtil( 5172): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5172): [ NA ]onUpgrade: current version=100, latest version=100,
I/VersionUtil( 5172): [ NA ]setIsFOTAing: false
,D/MediaProvider( 3651): [delete][26]
,D/MediaProvider( 3651): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/HtcAdjCursorFactory( 5172): Set CursorWindow size to: 4194304 KB, Tid: 5198
,D/ORMLib  ( 4930): put(),
,D/MediaProvider( 3651): [recoverParentNodes] - 0,
D/MediaProvider( 3651): [update][16]
D/MediaScannerServiceEx( 3651): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3651): [updateImage]+
,D/MediaScannerServiceEx( 3651): [updateImage]-0
,D/PMS     (  940): releaseWL(262d8520): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaScannerServiceEx( 3651): [1] scan finished
,D/MediaProviderUtils( 3651): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3651): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3651): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3651): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3651): Process mounted intent for unmounted storage: /storage/ext_sd
D/MediaScannerServiceEx( 3651): [disAliveExtStorageRows]+131073
,D/Process (  940): killProcessQuiet, pid=4680,
I/ActivityManager(  940): Killing 4680:com.htc.sense.browser/u0a9 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3651): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted,
,D/MediaProvider( 3651): [update][41]#1#
,D/MediaProvider( 3651): [update][23]#0#
,D/MediaScannerServiceEx( 3651): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  940): Recipient 4680,
,D/MediaProviderUtils( 3651): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3651): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3651): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3651): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3651): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3651): [disAliveExtStorageRows]+196609,
D/WifiService(  940): New client listening to asynchronous messages
E/WifiTrafficPoller(  940): ADD_CLIENT: 7
,I/EASAppSvc( 5172): [ NA ]onDestroy
,D/MediaProvider( 3651): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,W/EAS_NetworkUtil( 5172): [ NA ]getNetworkInfo: NetworkInfo is null
I/EASAppSvc( 5172): [ NA ]> uninitEASService
D/MediaProvider( 3651): [update][11]#1#
,I/ActivityManager(  940): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5207 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/EASAppSvc( 5172): [ NA ]onCreate,
I/EASRequestController( 5172): [ NA ]release
D/MediaProvider( 3651): [update][28]#0#
D/MediaScannerServiceEx( 3651): [disAliveExtStorageRows]--1, 0
I/VersionUtil( 5172): [ NA ]setIsFOTAing: true
I/VersionUtil( 5172): [ NA ]onUpgrade: current version=100, latest version=100
I/VersionUtil( 5172): [ NA ]setIsFOTAing: false
,W/EAS_NetworkUtil( 5172): [ NA ]getNetworkInfo: NetworkInfo is null
,D/EASPublicBinder( 5172): [ NA ]release,
D/TaskBinder( 5172): [ NA ]release
D/TaskBinder( 5172): [ NA ]release
I/EASAppSvc( 5172): [ NA ]< uninitEASService
,D/ORMLib  ( 4930): put()
,E/SQLiteLog( 5151): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal
,I/EASAppSvc( 5172): [ NA ]onDestroy,
I/EASAppSvc( 5172): [ NA ]> uninitEASService
,I/ActivityManager(  940): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5239 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a,
,I/EASRequestController( 5172): [ NA ]release
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4268, uid=10024, userID:0
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4268, uid=10024, userID:0
,D/EASPublicBinder( 5172): [ NA ]release
D/TaskBinder( 5172): [ NA ]release
D/TaskBinder( 5172): [ NA ]release
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4268, uid=10024, userID:0
I/EASAppSvc( 5172): [ NA ]< uninitEASService
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4268, uid=10024, userID:0
,D/Process (  940): killProcessQuiet, pid=4560
I/ActivityManager(  940): Killing 4560:com.google.android.partnersetup/u0a27 (adj 15): empty #17
,D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/ORMLib  ( 4930): put(),
,I/MusicStore( 5207): Database version: 120,
,I/ActivityManager(  940): Recipient 4560,
,V/AlarmManager(  940): sending alarm PendingIntent{caead57: PendingIntentRecord{77a8044 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448306479166, Int=0
,W/SystemReader(  940): Cannot find grip_rejection_width, use default value instead
,I/ActivityManager(  940): Killing 4735:com.htc.contacts/u0a38 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=4735
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/AccTypeManager( 1680): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AccTypeManager( 1680): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1521): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/ResourcesManager(  940): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1521): Deferring update until onResume
D/Launcher( 1521): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1680): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1453): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,E/ExternalAccountType( 1680): Unsupported attribute readOnly
,I/ActivityManager(  940): Recipient 4735,
,W/PackageManager(  940): Unable to load service info ResolveInfo{3cf680e com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  940): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  940): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  940): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  940): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  940): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  940): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  940): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  940): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  940): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/BackupManagerService(  940): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService},
,D/Process (  940): killProcessQuiet, pid=4825
I/ActivityManager(  940): Killing 4825:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 4825
,I/GCoreNlp( 1786): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/VoldConnector(  940): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5207): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/PMS     (  940): releaseWL(14f82777): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,V/GmsNetworkLocationProvi( 1786): DISABLE
D/LocationProviderProxy(  940): applying state to connected service
D/PMS     (  940): acquireWL(13ce2065): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(13ce2065): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/LocationProviderProxy(  940): applying state to connected service,
,D/PMS     (  940): acquireWL(2fc0c13a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): acquireWL(3cce21eb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(2fc0c13a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): acquireWL(18dc3b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  940): releaseWL(3cce21eb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  940): releaseWL(18dc3b48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/VoldConnector(  940): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5207): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  940): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5207): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 5207): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5207): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,V/JNIHelp ( 5207): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ActivityThread( 5207): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5207): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2aaa4777: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5207): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5207): GMSCore installation verified
,W/art     ( 5207): Suspending all threads took: 8.719ms,
,I/ConfigStore( 5207): Config Database version: 1,
,D/Process (  940): killProcessQuiet, pid=4849
I/ActivityManager(  940): Killing 4849:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 4849
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=5207, uid=10159, userID:0,
,D/WifiDisplayAdapter(  940): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  940):     Client/Owner: Client
D/WifiDisplayAdapter(  940):     GroupId: 
D/WifiDisplayAdapter(  940):     Passphrase: 
D/WifiDisplayAdapter(  940):     SessionId: 0
D/WifiDisplayAdapter(  940):     IP Address: }
,D/MediaRouterService(  940): Client com.google.android.music (pid 5207): Registered,
,D/WifiDisplayAdapter(  940): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  940):     Client/Owner: Client
D/WifiDisplayAdapter(  940):     GroupId: 
D/WifiDisplayAdapter(  940):     Passphrase: 
D/WifiDisplayAdapter(  940):     SessionId: 0
D/WifiDisplayAdapter(  940):     IP Address: }
,I/MediaRouter( 5207): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android },
,D/TelephonyReceiver( 1453): bind: true
,D/GenericMessagesProvider( 3707): query uri: content://htc-messages/wappush/count,
,E/SQLiteLog( 3707): (14) cannot open file at line 30058 of [9491ba7d73]
,E/SQLiteLog( 3707): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3707): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3707): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 3707): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3707): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 3707): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3707): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 3707): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 3707): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 3707): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 3707): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 3707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
W/System.err( 3707): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3707): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 3707): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 3707): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
W/System.err( 3707): 	at android.os.Binder.execTransact(Binder.java:454)
,I/ActivityManager(  940): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5282 uid=10027 gids={50027, 9997, 3003} abi=arm64-v8a
D/TelephonyReceiver( 1453): switchBindHtcMsgCursor: null
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=5207, uid=10159, userID:0
,I/GHttpClientFactory( 5207): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5207): Using platform SSLCertificateSocketFactory,
,D/Prism.PackageStateRece_( 1521): action: android.intent.action.PACKAGE_ADDED
,I/[PluginManager]RegisterService( 1419): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1419): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  940): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5309 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
I/ActivityManager(  940): Killing 4884:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=4884
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  940): Recipient 4884
,D/Process (  940): killProcessQuiet, pid=4952
I/ActivityManager(  940): Killing 4952:com.htc.mobiledata/u0a46 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/PMS     (  940): acquireWL(59266f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 940 1000 null,
I/BatteryService(  940): n_update end
D/PMS     (  940): releaseWL(59266f9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  940): Recipient 4952,
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  940): updateBatteryInfo
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NotificationService(  940): plugged=true pluggin=true,
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  940): runPSCheck
D/UsbnetService(  940): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  940): Checking...
D/UsbnetService(  940): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  940): >> updateStatus
D/UsbnetService(  940):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  940): battery changed pluggedType: 2
D/UsbnetService(  940): BroadcastReceiver::onReceive-
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  940): handleMessage: E msg.what=155652
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): processMsg: DefaultState
D/WifiController(  940): handleMessage: X
I/HtcPowerSaver(  940): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  940): << updateStatus
,I/DeviceManagement( 5309): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=5309 dbg=false s=true
,I/DeviceManagement( 5309): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  940): killProcessQuiet, pid=4365
I/ActivityManager(  940): Killing 4365:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  940): Recipient 4365
,I/ActivityManager(  940): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5331 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
,I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 1521): loadItems() com.htc.launcher.pageview.WidgetManager@1e6a8e94 +
I/Prism.WidgetManager( 1521): onLoadItems() +
,I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 4794): loadItems() com.htc.launcher.pageview.WidgetManager@262de0f4 +
I/Prism.WidgetManager( 4794): onLoadItems() +
,W/ResourcesManager( 4794): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/HtcCupdReceiver(Provider)( 5331):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/HtcModeClient( 3152): handler message = 4011,
,E/HtcModeClient( 3152): Check connection and retry 5 times.
,I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5354 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  940): killProcessQuiet, pid=5002
I/ActivityManager(  940): Killing 5002:com.nero.android.htc.sync/u0a5 (adj 15): empty #17,
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,W/ResourcesManager( 1521): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Settings:HtcWirelessFeatureFlags( 5051): id/is att sku: 118/false
,I/ActivityManager(  940): Recipient 5002
D/WifiService(  940): Client connection lost with reason: 4
,E/Settings:HtcWrapHeaderInfo( 5051): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5051): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 5051): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 5051): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasMenuKey      :false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]support         :false
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5354, uid=10072, userID:0
,W/global  ( 5354): [apache-http] Connection GC has been deprecated!,
,W/ResourcesManager( 4794): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  940): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5051): isSupportVoWifi: null
E/ActivityThread( 5051): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5051): The wrap header doesn't exist in header list.,
E/Settings:HtcWrapHeaderInfo( 5051): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5051): isSupportMusicChannel(): false
,D/Finsky  ( 5354): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5051): [supportHomeButton]support         :false
,E/Settings:HtcVoWifiWidgetEnabler( 5051): isSupportVoWifi: null,
I/ActivityManager(  940): Cannot resolve ContentProvider=com.htc.vowifi
W/global  ( 5354): [apache-http] Connection GC has been deprecated!
E/ActivityThread( 5051): Failed to find provider info for com.htc.vowifi
,W/ResourcesManager( 1521): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/global  ( 5354): [apache-http] Connection GC has been deprecated!
,W/asset   ( 4794): Copying FileAsset 0x558ff6f890 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,D/Finsky  ( 5354): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,W/asset   ( 1521): Copying FileAsset 0x55902a6410 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/Prism.WidgetManager( 4794): onLoadItems() -,
I/Prism.ItemManager( 4794): loadItems() com.htc.launcher.pageview.WidgetManager@262de0f4 -
I/ActivityManager(  940): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5395 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5354): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5354): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PhoneApp( 1453): EVENT_QUERY_MO_PACKAGES
E/Prism.WidgetManager( 1521): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1521): onLoadItems() -
I/PackageManager(  940):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5354, uid=10072, userID:0
I/Prism.ItemManager( 1521): loadItems() com.htc.launcher.pageview.WidgetManager@1e6a8e94 -
D/PhoneApp( 1453): -- N1 =0
D/PhoneApp( 1453): -- N2 =0
D/PhoneApp( 1453): -- N3 =0
,I/art     (  940): Explicit concurrent mark sweep GC freed 29087(1565KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.394ms total 128.801ms
,W/ResourcesManager( 5395): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5395): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5395): VM with version 2.1.0 has multidex support,
I/MultiDex( 5395): install
I/MultiDex( 5395): VM has multidex support, MultiDex support library is disabled.
,D/Process (  940): killProcessQuiet, pid=5074
I/ActivityManager(  940): Killing 5074:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  940): Recipient 5074
,D/Finsky  ( 5354): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5354): [1] 2.run: Finished loading 1 libraries.,
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4268): Loading module APK com.google.android.play.games
,D/Finsky  ( 5354): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4268): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,V/JNIHelp ( 5395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PMS     (  940): acquireWL(2a1b6b8f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4268 10024 null
,D/Finsky  ( 5354): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ActivityThread( 5395): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5395): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@203e72b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5395): Installed default security provider GmsCore_OpenSSL
,I/ConfigFetchService( 4268): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 4268): launchTask
,D/PMS     (  940): acquireWL(eb0d9c6): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4268 10024 WorkSource{10373 com.example.hello}
,D/PMS     (  940): releaseWL(2a1b6b8f): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,D/PMS     (  940): acquireWL(18cb3d87): PARTIAL_WAKE_LOCK  Icing 0x1 4268 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4268): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 4268): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Xna6Zn8O8ZM2DGUMUqat69UOsJXBLyTpHUD033sc4Z0-v6dcJVQDhqmwgbjZGIo9ANiEm234lINoThzo7YmcLU4h38vTg7Skh2QtEGNVvj7z5EvmaI-3xLwNGlYvTrXTw_U1OEo7Ta1VN7FXyl1DH56vW60OWTW07jmvtFPM8vAg9Y1yHr2q_tYvar_-fkHxn7Kcpo
,I/PeopleContactsSync( 4268): CP2 sync disabled,
,I/PackageManager(  940):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4268, uid=10024, userID:0,
,I/GoogleURLConnFactory( 4268): Using platform SSLCertificateSocketFactory
,D/Vision  ( 4268): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 4268): Failed to find package metadata for com.example.hello
,D/Vision  ( 4268): No vision deps
,I/ActivityManager(  940): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5436 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
,I/Icing   ( 4268): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB
,D/Process (  940): killProcessQuiet, pid=5099
I/ActivityManager(  940): Killing 5099:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/libc    ( 4268): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 4268): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4268): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4268): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 4268): [NET] android_getaddrinfo_proxy+
W/Icing   ( 4268): Received bad json for section weights override -- ignoring.
D/libc    ( 4268): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4268): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4268): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname,
,I/ConfigFetchService( 4268): fetch service done; releasing wakelock,
D/PMS     (  940): releaseWL(eb0d9c6): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello}
I/ConfigFetchService( 4268): stopping self
,I/ActivityManager(  940): Recipient 5099
,W/Icing   ( 4268): Received bad json for corpus context scoring override -- ignoring.
,W/Icing   ( 4268): Received bad json for section weights override -- ignoring.
W/Icing   ( 4268): Received bad json for corpus context scoring override -- ignoring.
,V/Finsky  ( 5354): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     ( 4268): Background sticky concurrent mark sweep GC freed 18473(1533KB) AllocSpace objects, 21(420KB) LOS objects, 24% free, 6MB/7MB, paused 7.093ms total 76.894ms
I/art     ( 4268): WaitForGcToComplete blocked for 24.048ms for cause Explicit
,I/art     ( 4268): Explicit concurrent mark sweep GC freed 13337(765KB) AllocSpace objects, 0(0B) LOS objects, 42% free, 5MB/9MB, paused 902us total 49.435ms
,V/AlarmManager(  940): sending alarm PendingIntent{198b5b9e: PendingIntentRecord{1074567f com.android.vending startService}}, i=null, t=0, cnt=1, w=1448306482363, Int=0,
D/Finsky  ( 5354): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,I/GLSUser ( 1892): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1892): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1892): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1892): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4268): Using Auth Proxy for data requests.
,W/Finsky  ( 5354): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Icing   ( 4268): Loading extension by file descriptor -1 failed,
,I/GLSUser ( 1892): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1892): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1892): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1892): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1892): Explicit concurrent mark sweep GC freed 9985(530KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 662us total 34.228ms
,I/GLSUser ( 1892): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1892): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1892): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1892): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5354): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,I/Icing   ( 4268): updateResources: need to parse f{com.google.android.gms}
,E/AndroidHttpClient( 5354): Leak found,
E/AndroidHttpClient( 5354): java.lang.IllegalStateException: AndroidHttpClient created and never closed
E/AndroidHttpClient( 5354): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5354): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5354): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5354): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113)
E/AndroidHttpClient( 5354): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5354): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5354): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5354): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5354): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5354): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5354): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5354): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Icing   ( 4268): Internal init done: storage state 0
,D/BluetoothManagerService(  940): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  940): disable(): mBluetooth = null mBinding = false
W/Settings:Agent(  940): MONITOR_LOG
W/Settings:Agent(  940): name: bluetooth_on
W/Settings:Agent(  940): value: 0
W/Settings:Agent(  940): >> traceCallingStack()
W/Settings:Agent(  940): Process.myPid(): 940
W/Settings:Agent(  940): Process.myTid(): 1715
W/Settings:Agent(  940): Process.myUid(): 1000
W/Settings:Agent(  940): 
W/Settings:Agent(  940): 
W/System.err(  940): java.lang.Throwable: stack dump
,W/System.err(  940): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  940): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  940): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  940): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  940): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  940): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  940): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  940): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  940): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  940): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  940): 
W/Settings:Agent(  940): << traceCallingStack(): 6(ms)
D/BluetoothManagerService(  940): Message: MESSAGE_DISABLE
I/Icing   ( 4268): Post-init done
D/WifiManager( 4907): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
D/WifiService(  940): New client listening to asynchronous messages
E/WifiTrafficPoller(  940): ADD_CLIENT: 7
,D/PMS     (  940): releaseWL(18cb3d87): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,D/WifiService(  940): setWifiEnabled: false pid=4907, uid=10373,
E/WifiService(  940): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  940): isSprintWifiRestricted(): false
I/WifiService(  940): isMdmWifiRestricted(): false,
,W/Settings:Agent(  940): MONITOR_LOG
W/Settings:Agent(  940): name: wifi_on
W/Settings:Agent(  940): value: 0
W/Settings:Agent(  940): >> traceCallingStack()
W/Settings:Agent(  940): Process.myPid(): 940
W/Settings:Agent(  940): Process.myTid(): 1715
W/Settings:Agent(  940): Process.myUid(): 1000
W/Settings:Agent(  940): 
W/Settings:Agent(  940): 
W/System.err(  940): java.lang.Throwable: stack dump
,W/System.err(  940): 	at java.lang.Thread.dumpStack(Thread.java:490),
W/System.err(  940): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  940): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  940): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  940): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  940): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  940): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  940): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  940): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  940): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  940): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  940): 
W/Settings:Agent(  940): << traceCallingStack(): 5(ms)
D/WifiController(  940): handleMessage: E msg.what=155656
I/jxcore-log( 4907): ****TEST TOOK:  5075  ms ****
I/jxcore-log( 4907): 
D/WifiController(  940): processMsg: ApStaDisabledState
D/WifiController(  940): handleMessage: X
I/jxcore-log( 4907): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4907): 
,I/GAv4    ( 5436): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5436):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5436):   adb logcat -s GAv4
,W/GAv4    ( 5436): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5436): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 5436): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5436): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,D/ChimeraCfgMgr( 4268): Loading module com.google.android.gms.games from APK com.google.android.play.games,
D/ChimeraModuleLdr( 4268): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1892): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1892): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1892): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1892): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5354): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 5354): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 5354): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5354): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/VoldConnector(  940): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
,W/ContextImpl( 5436): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache,
,D/DeviceConnectionService( 1786): client connected with version: 7571000
,I/ActivityManager(  940): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5487 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager(  940): Killing 5125:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=5125
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,E/cutils-trace( 5473): Error opening trace file: Permission denied (13),
W/ResourcesManager( 5436): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5436): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CustomizationManager( 5473): ====startRecUseTime====,
D/htc.customization.log.level( 5473):  is 
W/CustomizationLogLevel( 5473): Level value is invalid, use default level 2
,I/ActivityManager(  940): Recipient 5125,
,W/ResourcesManager( 5487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,D/CustomizationManager( 5473):  Read ACC file spent 0.031 (s),
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5473): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5473): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5473): Parsing tag category name = system
I/CustomizationCIDLoader( 5473): Parsing tag category name = application
I/CustomizationCIDLoader( 5473): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5473): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5473): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5473): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5473): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5473): add string-array item, value = 42507
I/CustomizationCIDLoader( 5473): add string-array item, value = 21902
I/CustomizationCIDLoader( 5473): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5473): add string-array item, value = 23420
I/CustomizationCIDLoader( 5473): add string-array item, value = 22299
I/CustomizationCIDLoader( 5473): add string-array item, value = 24002
I/CustomizationCIDLoader( 5473): add string-array item, value = 23210
I/CustomizationCIDLoader( 5473): add string-array item, value = 23205
I/CustomizationCIDLoader( 5473): add string-array item, value = 23806
I/CustomizationCIDLoader( 5473): add string-array item, value = 23430
I/CustomizationCIDLoader( 5473): add string-array item, value = 23408
I/CustomizationCIDLoader( 5473): add string-array item, value = 27205
I/CustomizationCIDLoader( 5473): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5473): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5473):  Read CID file spent 0.092 (s),
D/CustomizationManager( 5473):  All configurations done spent 0.093 (s)
,V/JNIHelp ( 5436): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PackageManager(  940): deletePackageAsUser: pkg=com.example.hello, pid=5473, uid=2000 userid=0,
,W/System  ( 5436): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5436): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  940): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,I/ActivityManager(  940): Killing 4907:com.example.hello/u0a373 (adj 0): stop com.example.hello
D/Process (  940): killProcessQuiet, pid=4907
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  940): Skipping PackageSetting{382c72ea com.test.thalitest/10366} due to missing metadata
,I/ActivityManager(  940): Recipient 4907
I/WindowState(  940): WIN DEATH: Window{2f19dcfa u0 com.example.hello/com.example.hello.MainActivity}
E/InputEventReceiver( 1356): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{113801b4 uid 10373 pid 4907} (c)'
D/WifiService(  940): Client connection lost with reason: 4
,W/ActivityManager(  940): Force removing ActivityRecord{24d4d1ea u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  940): Force stopping com.example.hello appid=10373 user=0: pkg removed,
,V/GLSActivity( 1892): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager(  940): Spurious death for ProcessRecord{22560574 4907:com.example.hello/u0a373}, curProc for 4907: null
,D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello,
D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/PMS     (  940): acquireWL(1da9d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1786 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1786): Ignoring removeGeofence because network location is disabled.
D/PMS     (  940): releaseWL(1da9d): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/FeedHostManager( 1521): [onResume]
I/FeedProviderManager( 1521): onResume
,I/SocialFeedProvider( 1521): +onResume
I/SocialFeedProvider( 1521): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1521): -onResume
,I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/ConnectivityHelper( 1521): [getCurrentConnectionType] no network connection
,W/SystemReader(  940): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1680): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,D/StatusBarManagerService(  940): setSystemUiVisibility(0x700)
,D/StatusBarManagerService(  940): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  940): hiding MENU key
,D/FindExtension( 1521): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,D/AccTypeManager( 1680): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ThreadedRenderer( 1521): Defer allocateBuffers to drawing time
,I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/InputMethodManagerService(  940): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  940): Got RemoteException sending setActive(false) notification to pid 4907 uid 10373,
D/StatusBarManagerService(  940): swetImeWindowStatus vis=0 backDisposition=0
D/AccTypeManager( 1680): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/InputMethodManagerService(  940): Enable input method client, pid=1521
,D/PhoneApp( 1453): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,E/ExternalAccountType( 1680): Unsupported attribute readOnly,
,W/PackageManager(  940): Unable to load service info ResolveInfo{2d8edbbe com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  940): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  940): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  940): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  940): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  940): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  940): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  940): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  940): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  940): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  940): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  940): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/StatusBarManagerService(  940): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  940): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ResourcesManager(  940): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/StatusBarManagerService(  940): hiding MENU key
,I/art     (  940): Explicit concurrent mark sweep GC freed 24650(1642KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 8.396ms total 213.788ms
,D/PMS     (  940): acquireWL(18c37291): PARTIAL_WAKE_LOCK  AsyncService 0x1 5487 10167 null
,D/PMS     (  940): releaseWL(18c37291): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  940): acquireWL(3bc4d293): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5487 10167 null
,D/PMS     (  940): releaseWL(3bc4d293): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  940): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5535 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
,D/Process (  940): killProcessQuiet, pid=4930
I/ActivityManager(  940): Killing 4930:com.htc.task/u0a69 (adj 15): empty #17
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/JobSchedulerService(  940): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  940): Recipient 4930,
,D/TaskPersister(  940): removeObsoleteFile: deleting file=8_task.xml
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/OpenGLRenderer( 1521): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,I/ActivityManager(  940): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5559 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a,
,I/art     (  431): Explicit concurrent mark sweep GC freed 8653(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 198us total 23.423ms,
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 180us total 23.103ms
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 21.572ms
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5559): onHandleIntent,
I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
,D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  940): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5583 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  940): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=5609 uid=10079 gids={50079, 9997, 5001, 1028, 1015} abi=arm64-v8a,
,D/LocationManagerService(  940): getProviders()=[passive]
,D/VoldConnector(  940): SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/},
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.htc.musicenhancer/cache/
W/ContextImpl( 5583): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED,
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5609): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5609): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5609): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
,W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/ActivityManager(  940): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=5640 uid=10084 gids={50084, 9997, 3003, 1028, 1015, 1023, 2001, 5006, 5001} abi=arm64-v8a,
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  940): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5660 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/SharedPreferencesImpl( 5535): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
E/AndroidRuntime( 5535): FATAL EXCEPTION: IntentService[UpdateCorporaService],
E/AndroidRuntime( 5535): Process: com.google.android.googlequicksearchbox:search, PID: 5535
E/AndroidRuntime( 5535): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 5535): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 5535): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 5535): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5535): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5535): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5535): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 5535): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 5535): ,	... 7 more
E/AndroidRuntime( 5535): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5535): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5535): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5535): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5535): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5535): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5535): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5535): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5535): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 5535): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 5535): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 5535): 	... 9 more
E/AndroidRuntime( 5535): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5535): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 5535): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 5535): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 5535): 	... 11 more
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
E/ActivityManager(  940): App crashed! Process: com.google.android.googlequicksearchbox:search
,E/DropBoxManagerService(  940): Can't write: system_app_crash,
E/DropBoxManagerService(  940): java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  940): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  940): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  940): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  940): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  940): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  940): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  940): 	... 5 more
,D/StatusBarManagerService(  940): setSystemUiVisibility(0xc0000000)
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
D/StatusBarManagerService(  940): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  940): hiding MENU key
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,I/ActivityManager(  940): Killing 4626:com.htc.bgp/u0a11 (adj 15): empty #17
D/Process (  940): killProcessQuiet, pid=4626
D/Process (  940): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,E/SQLiteDatabase( 5640): Failed to open database '/data/data/com.htc.updater/databases/fota.db'.
E/SQLiteDatabase( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5640): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteDatabase( 5640): 	at android.content.ContentProvider.query(ContentProvider.java:960)
,E/SQLiteDatabase( 5640): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5640): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5640): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteDatabase( 5640): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteDatabase( 5640): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteDatabase( 5640): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
E/SQLiteOpenHelper( 5640): Couldn't open fota.db for writing (will try read-only):
E/SQLiteOpenHelper( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper( 5640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper( 5640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5640): 	at com.htc.updater.db.UpdaterProvider.query(UpdaterProvider.java:473)
E/SQLiteOpenHelper( 5640): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper( 5640): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper( 5640): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteOpenHelper( 5640): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteOpenHelper( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.getString(FOTASettings.java:310)
E/SQLiteOpenHelper( 5640): 	at com.htc.updater.db.FOTASettings.getString(FOTASettings.java:185)
E/SQLiteOpenHelper( 5640): 	at com.htc.updater.db.FOTASettings.getBoolean(FOTASettings.java:257)
E/SQLiteOpenHelper( 5640): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:183)
,W/SQLiteOpenHelper( 5640): Opened fota.db in read-only mode,
,E/UpdaterAPK | COTASettings( 5640): Can't set key cota_notify_download,
E/UpdaterAPK | COTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | COTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | COTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | COTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.db.COTASettings$NameValueCache.putString(COTASettings.java:91)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.db.COTASettings.putString(COTASettings.java:146)
,E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.db.COTASettings.putBoolean(COTASettings.java:160)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.UpdaterReceiver.checkConfirmStatus(UpdaterReceiver.java:687)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.UpdaterReceiver.access$200(UpdaterReceiver.java:53)
E/UpdaterAPK | COTASettings( 5640): 	at com.htc.updater.UpdaterReceiver$CheckActionThread.run(UpdaterReceiver.java:192)
,I/ActivityManager(  940): Recipient 4626,
,D/TelephonyReceiver( 1453): bind: false
,D/TelephonyReceiver( 1453): switchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,I/DFPI.ApkInstallService( 5559): onHandleIntent
I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  940): Resuming delayed broadcast
,E/SQLiteDatabase(  940): Failed to open database '/data/data/com.htc.checkinprovider/databases/htcCheckin.db'.
E/SQLiteDatabase(  940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase(  940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(  940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(  940): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteDatabase(  940): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase(  940): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase(  940): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase(  940): 	at android.os.Binder.execTransact(Binder.java:454)
E/SQLiteOpenHelper(  940): Couldn't open htcCheckin.db for writing (will try read-only):
E/SQLiteOpenHelper(  940): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteOpenHelper(  940): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(  940): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(  940): 	at com.htc.checkinprovider.htcCheckinProvider.query(htcCheckinProvider.java:335)
E/SQLiteOpenHelper(  940): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteOpenHelper(  940): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteOpenHelper(  940): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteOpenHelper(  940): 	at android.os.Binder.execTransact(Binder.java:454)
W/SQ,LiteOpenHelper(  940): Opened htcCheckin.db in read-only mode
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
E/SharedPreferencesImpl( 5207): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/ActivityManager(  940): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,E/SQLiteDatabase( 5207): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 5207): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5207): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5207): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 5207): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 5207): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5207): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5207): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 5207): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5207): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 5207): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 5207): Process: com.google.android.music:main, PID: 5207
E/AndroidRuntime( 5207): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5207): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5207): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5207): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.Store.getDatabase(Store.java:287)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.Store.createDatabase(Store.java:262)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.Store.importMediaStore(Store.java:10438)
,E/AndroidRuntime( 5207): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 5207): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 5207): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5207): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5207): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 5207): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5207): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  940): App crashed! Process: com.google.android.music:main
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,E/DropBoxManagerService(  940): Can't write: system_app_crash
E/DropBoxManagerService(  940): java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	,at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  940): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  940): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  940): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  940): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  940): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  940): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  940): 	... 5 more
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,E/UpdaterAPK | FOTASettings( 5640): Can't set key backup_uri_string
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:180)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/UpdaterAPK | FOTASettings( 5640): Can't set key download_sdcard
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	,at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:181),
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
,E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_prompt_version
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): ,	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
,E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:182)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_prompt_feature
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:183)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_prompt_size
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:184)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandle,r.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_force_update
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:185)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5609): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5609): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5609): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_notify_download
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:186)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_need_token
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:189)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_reserve_data_size
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putInt(FOTASettings.java:239)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:194)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/GFEEDBACK_SendErrorReportOperation( 4268): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4268): Error saving report: java.io.IOException: failed to create reports directory
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_package_download_via_wifi
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putBoolean(FOTASettings.java:280)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:200)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_prompt_message
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:202)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
I/ActionCombine( 5640): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
E/UpdaterAPK | FOTASettings( 5640): Can't set key fota_optional
E/UpdaterAPK | FOTASettings( 5640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:823)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:212)
E/UpdaterAPK | FOTASettings( 5640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.UpdaterProvider.update(UpdaterProvider.java:480)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:335)
E/UpdaterAPK | FOTASettings( 5640): 	at android.content.ContentResolver.update(ContentResolver.java:1354)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings$NameValueCache.putString(FOTASettings.java:296)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.db.FOTASettings.putString(FOTASettings.java:199)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.doCheckConfirmStatus(UpdaterCheckIntranetService.java:282)
E/UpdaterAPK | FOTASettings( 5640): 	at com.htc.updater.service.UpdaterCheckIntranetService.onHandleIntent(UpdaterCheckIntranetService.java:70)
E/UpdaterAPK | FOTASettings( 5640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.Looper.loop(Looper.java:155)
E/UpdaterAPK | FOTASettings( 5640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/ActivityManager(  940): Resuming delayed broadcast
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/RemoteViews( 1221): setHTCTheme(com.htc.updater,true,33751145)
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/RemoteViews( 1221): apply : com.htc.updater 1 17 3 36,
I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 5559): onHandleIntent
I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  940): Resuming delayed broadcast
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5609): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 5609): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/DFPI.ApkInstallService( 5559): onHandleIntent
,I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  940): Resuming delayed broadcast
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
,I/Prism.ItemManager( 4794): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4794): loadItems() com.htc.launcher.pageview.WidgetManager@262de0f4 +
I/Prism.WidgetManager( 4794): onLoadItems() +
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,V/AlarmManager(  940): sending alarm PendingIntent{111907b4: PendingIntentRecord{11394fdd com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1448306485152, Int=0
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac,
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/Prism.ItemManager( 1521): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1521): loadItems() com.htc.launcher.pageview.WidgetManager@1e6a8e94 +
I/Prism.WidgetManager( 1521): onLoadItems() +
I/DFPI.ApkInstallService( 5559): onHandleIntent
I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/ActivityManager(  940): Resuming delayed broadcast
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 5609): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5609): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
,W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
,D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/FindExtension( 1221): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1221): Defer allocateBuffers to drawing time
,I/DFPI.ApkInstallService( 5559): onHandleIntent
I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
D/DFPI.ApkInstallService( 5559): check CID = HTC__102
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  940): Resuming delayed broadcast
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/30
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/96
D/DFPI.PIReciver( 5559): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/ActivityManager(  940): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/102
I/DFPI.ApkInstallService( 5559): onHandleIntent
,I/DFPI.ApkInstallService( 5559): Media Scan Finished Case 
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/104
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac,
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/98
,D/DFPI.ApkInstallService( 5559): check CID = HTC__102,
I/DFPI.ApkInstallService( 5559): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  940): Resuming delayed broadcast
I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 5609): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService cmp=com.htc.sdm/.service.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 5609): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 5609): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/122
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=4
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/30 type=5
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/30
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/96 type=6
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/96
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/102 type=7
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/102
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/104 type=8
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/104
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/98 type=9
W/SoundPicker( 5609): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/98
I/SoundPicker( 5609): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_gsm)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=1
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/SoundPicker( 5609): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=2
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,D/GCM     ( 1892): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/SoundPicker( 5609): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/AuthorizationBluetoothService( 1892): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 5609): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 5609): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/122 type=3
I/SoundPicker( 5609): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/122
,V/GmsCoreStatsServiceLauncher( 4268): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }

```
