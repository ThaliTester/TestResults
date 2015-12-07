#### Test 502422852e23b2c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  937): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4596 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=4237, uid=10024, userID:0
W/ResourcesManager( 4596): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4596): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/TelephUtils( 1451): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1451): sku_id=118
I/WebViewFactory( 4493): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/MultiDex( 4596): VM with version 2.1.0 has multidex support
I/MultiDex( 4596): install
I/MultiDex( 4596): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  937): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=4623 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
D/LocationInitializer( 4237): Restart initialization of location
D/TelephUtils( 1451): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 93
D/AccFlag ( 1451): sku_id=118
V/JNIHelp ( 4596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/TelephUtils( 1451): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 96
D/AccFlag ( 1451): sku_id=118
I/LibraryLoader( 4493): Time to load native libraries: 25 ms (timestamps 8619-8644)
I/LibraryLoader( 4493): Expected native library version number "",actual native library version number ""
D/TelephUtils( 1451): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 50
D/AccFlag ( 1451): sku_id=118
W/ActivityThread( 4596): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4596): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32e52226: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4596): Installed default security provider GmsCore_OpenSSL
W/art     ( 4493): Attempt to remove local handle scope entry from IRT, ignoring
D/WearableService( 4596): callingUid 10024, callindPid: 4596
E/MDM     ( 1790): [135] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/ImageRamCache( 4623): create image Cache, size: 31457280.
I/ImageRamCache( 4623): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 4623): create image Cache, size: 31457280.
I/FeedSettings( 4623): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 4623): GroupBudget 0.500000 0.380000
I/FeedSettings( 4623): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4623): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 4623): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4623): loadGridSize() with Alternative
W/art     ( 4493): Attempt to remove local handle scope entry from IRT, ignoring
D/CustomHighlightReceiver( 4623): [custom highlight] onReceive
D/CustomHighlightService( 4623): [custom highlight] onHandleIntent
D/NewsDB  ( 4623): set custom highlight []
I/ActivityManager(  937): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4667 uid=10035 gids={50035, 9997} abi=arm64-v8a
I/ActivityManager(  937): Killing 3084:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=3084
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/CustomHighlightService( 4623): [custom highlight] set tags 
E/cutils-trace( 4647): Error opening trace file: Permission denied (13)
I/ActivityManager(  937): Recipient 3084
D/Process (  937): killProcessQuiet, pid=3982
I/ActivityManager(  937): Killing 3982:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/CustomizationManager( 4647): ====startRecUseTime====
D/htc.customization.log.level( 4647):  is 
W/CustomizationLogLevel( 4647): Level value is invalid, use default level 2
D/CustomizationManager( 4647):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__001
I/ActivityManager(  937): Recipient 3982
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4647): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4647): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 4647): Parsing tag category name = system
I/CustomizationCIDLoader( 4647): Parsing tag category name = application
I/CustomizationCIDLoader( 4647): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4647): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4647): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4647): Parsing tag category name = Settings
I/CustomizationCIDLoader( 4647): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4647): add string-array item, value = 42507
I/CustomizationCIDLoader( 4647): add string-array item, value = 21902
I/CustomizationCIDLoader( 4647): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 4647): add string-array item, value = 23420
I/CustomizationCIDLoader( 4647): add string-array item, value = 22299
I/CustomizationCIDLoader( 4647): add string-array item, value = 24002
I/CustomizationCIDLoader( 4647): add string-array item, value = 23210
I/CustomizationCIDLoader( 4647): add string-array item, value = 23205
I/CustomizationCIDLoader( 4647): add string-array item, value = 23806
I/CustomizationCIDLoader( 4647): add string-array item, value = 23430
I/CustomizationCIDLoader( 4647): add string-array item, value = 23408
I/CustomizationCIDLoader( 4647): add string-array item, value = 27205
I/CustomizationCIDLoader( 4647): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 4647): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 4647):  Read CID file spent 0.097 (s)
D/CustomizationManager( 4647):  All configurations done spent 0.097 (s)
I/ActivityManager(  937): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=4704 uid=10076 gids={50076, 9997} abi=arm64-v8a
D/Process (  937): killProcessQuiet, pid=4010
I/ActivityManager(  937): Killing 4010:com.htc.htccupd/u0a13 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  937): Recipient 4010
I/ActivityManager(  937): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 pid 4647 on display 0
D/PMS     (  937): acquireHCC(21560260): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 937 1000 null
D/PMS     (  937): acquireHCC(1c987319): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 937 1000 null
W/asset   (  937): Copying FileAsset 0x55a71d0180 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  937): acquireWL(688e48c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 937 1000 null
I/FeedHostManager( 1516): [onPause]
I/FeedProviderManager( 1516): onPause
I/FeedHostManager( 1516): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@14e7cfca
I/SocialFeedProvider( 1516): +onPause
I/SocialFeedProvider( 1516): -onPause
D/ContactMessageStore( 1451): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1451): MSG_NOTIFY_CS_TO_SYNC <<
I/AnimationUtil(  937): isHTCRecent(HelloWorld/Recent screens.)/15
W/HtcSystemUPManager(  937): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
I/ActivityManager(  937): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4727 uid=10373 gids={50373, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/SMSBackup( 4704): Got a database change event
I/art     (  442): Explicit concurrent mark sweep GC freed 8670(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 248us total 21.796ms
D/Process (  937): killProcessQuiet, pid=4055
I/ActivityManager(  937): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=4744 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  937): Killing 4055:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
I/art     (  442): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 563us total 20.163ms
I/art     (  439): Explicit concurrent mark sweep GC freed 8647(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 163us total 22.244ms
I/art     (  442): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 820us total 19.919ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 130us total 19.949ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 121us total 15.548ms
I/ActivityManager(  937): Recipient 4055
,D/StatusBarManagerService(  937): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
W/asset   ( 4727): Copying FileAsset 0xac47e080 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/MessagingShortcutReceiver( 3728): keep hiding shortcut bubble
D/MessagingShortcut( 3728): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 3728): After query: 0
D/MessagingShortcut( 3728): mPresentUnreadCount: -1
D/MessageUtils( 3728): [getShortcut] com.htc.sense.mms.ui.ConversationList, false
D/MessagingShortcut( 3728): setMsgShortcutDrawable> 0, false
D/MessagingShortcut( 3728): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/TrimMemoryManager( 1516): [trimMemory] 20
I/ActivityManager(  937): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4770 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  937): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=4792 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
W/ResourcesManager( 4770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/TodoTaskshortcut( 4770): update TASK shortcut>
I/WebViewFactory( 4727): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
D/PMS     (  937): releaseWL(28a62f82): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
D/MdScBoot( 4744): [c0.1.] 30@-140743 -> 40
D/MdScBootUi( 4744): [c0.1.2.] boot 118
D/PMS     (  937): acquireWL(3c9ec390): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4770 10069 null
I/ActivityManager(  937): Killing 4100:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=4100
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/MdScSimSt( 4744): [c0.1.2.] qry 118: 0+1 running 0
D/PMS     (  937): acquireWL(8f5489): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4770 10069 null
I/LibraryLoader( 4727): Time to load native libraries: 10 ms (timestamps 9694-9704)
I/LibraryLoader( 4727): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4727): Binding Chromium to main looper Looper (main, tid 1) {14d154b5}
I/LibraryLoader( 4727): Expected native library version number "",actual native library version number ""
I/chromium( 4727): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4727): Initializing chromium process, singleProcess=true
W/art     ( 4727): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4727): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  937): Recipient 4100
W/chromium( 4727): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/Atfwd_Sendcmd(  464): AtCmdFwd service not published, waiting... retryCnt : 4
W/chromium( 4727): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/PMS     (  937): releaseWL(3c9ec390): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/Process (  937): killProcessQuiet, pid=4125
I/ActivityManager(  937): Killing 4125:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/TodoTaskNotifyService( 4770): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4770): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
W/System.err( 4770): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4770): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4770): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4770): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 4770): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/libEGL  ( 4727): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/PMS     (  937): releaseWL(8f5489): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
E/libEGL  ( 4727): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4727): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 4727): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 4727): Build Date: 03/09/15 Mon
I/Adreno-EGL( 4727): Local Branch: 
I/Adreno-EGL( 4727): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 4727): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 4727):                  d74aa161a12b9c6fc6332151
W/System.err(  937): java.lang.Throwable: stack dump
W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  937): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  937): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@140fb045:true
D/BluetoothAdapter( 4727): 899348440: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  937): Recipient 4125
W/NotifyReceiver( 4770): stopSelfResult true
D/Process (  937): killProcessQuiet, pid=4149
I/ActivityManager(  937): Killing 4149:com.android.smith/1000 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  937): acquireWL(3e6b3354): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1888 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  937): Recipient 4149
D/MtpReceiver( 3689): [MTP][handleUsbStateAsync]+
D/MtpReceiver( 3689): [MTP][handleUsbStateAsync]1:1-
D/MtpReceiver( 3689): [MTP][handleUsbState]+
D/PMS     (  937): releaseWL(3e6b3354): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  937): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4839 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
D/MtpReceiver( 3689): [MTP][scanExternalVolumeIfNeed] scan external volume
D/MtpReceiver( 3689): [MTP][handleUsbState]-
D/MtpReceiver( 3689): [MTP][handleMessage]-
D/MtpService( 3689): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 3689): TotalSize=1886532,MediaCacheLimit=6000
D/MtpService( 3689): [isMtpConnected] connected: true
W/art     ( 4727): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4727): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 4727): CordovaWebView is running on device made by: HTC
W/art     ( 4727): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4727): Attempt to remove local handle scope entry from IRT, ignoring
D/SyncApplication( 4839): Loading default preferences
E/MediaScannerService( 3689): [onStartCommand] --- Should not be here, redirect request. ----
E/MediaScannerService( 3689): [handleMessage] --- Should not be here, ignore request. ----
W/Resources( 4839): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
W/chromium( 4727): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/WifiTrafficPoller(  937): ADD_CLIENT: 7
D/WifiService(  937): New client listening to asynchronous messages
D/SyncApplication( 4839): Overriding preferences with custom values
D/FindExtension( 4727): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
E/MediaScannerServiceEx( 3689): [getStorageMaskIdFromPath] path is null
D/MediaScannerServiceEx( 3689): [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
D/SyncApplication( 4839): Updating preferences succeeded
D/MediaScannerServiceEx( 3689): [handleExternalVolume] ext storage
E/SyncApplication( 4839): Application created.
D/MediaProviderUtils( 3689): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3689): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3689): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3689): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
D/MediaScannerServiceEx( 3689): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 3689): [update][4]#0#
D/MediaProvider( 3689): [update][1]#0#
W/VolumeInfo( 4839): Unable to read mount points
W/VolumeInfo( 4839): java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4839): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/VolumeInfo( 4839): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/VolumeInfo( 4839): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/VolumeInfo( 4839): 	at java.io.FileReader.<init>(FileReader.java:66)
W/VolumeInfo( 4839): 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
W/VolumeInfo( 4839): 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153)
W/VolumeInfo( 4839): 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
W/VolumeInfo( 4839): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
W/VolumeInfo( 4839): 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
W/VolumeInfo( 4839): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/VolumeInfo( 4839): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/VolumeInfo( 4839): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/VolumeInfo( 4839): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/VolumeInfo( 4839): 	at java.lang.Thread.run(Thread.java:818)
W/VolumeInfo( 4839): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/VolumeInfo( 4839): 	at libcore.io.Posix.open(Native Method)
W/VolumeInfo( 4839): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/VolumeInfo( 4839): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/VolumeInfo( 4839): 	... 13 more
V/VolumeInfo( 4839): Found 0 mount point(s)
V/VolumeInfo( 4839): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4839): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 4839): Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
W/VolumeInfo( 4839): Can not create volume ID for unmounted volume null
I/InputMethodManager( 4727): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@c91c8c6, mServedView=org.apache.cordova.engine.SystemWebView{14630087 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@7ba8bb4
I/InputMethodManagerService(  937): Disable input method client, pid=1516
D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=4727
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/MediaProvider( 3689): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 3689): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 3689): [update][28]#1#
D/MediaScannerServiceEx( 3689): [AliveExtStorageRows]-0, 0
D/PMS     (  937): acquireWL(36f6a4ab): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3689 10017 null
I/ActivityManager(  937): Displayed com.example.hello/.MainActivity: +1s252ms
D/PMS     (  937): releaseWL(688e48c): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/MediaScanner( 3689): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
W/XT9_C   ( 1353): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1353): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1353): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/CalendarDefines( 4839): getNewCalendarAuthority()...
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4839, uid=10005, userID:0
W/PackageManager(  937): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
W/BindingManager( 4727): Cannot call determinedVisibility() - never saw a connection for the pid: 4727
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4839, uid=10005, userID:0
D/SyncApplication( 4839): enableAppOperation()+
W/PackageManager(  937): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 4839): enableAppOperation()-
I/chromium( 4727): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/HTCUtilities( 4839): isNeorSinged() + 
D/HTCUtilities( 4839): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 4839): isNeorSinged() return false
D/CDMountReceiver( 4839): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 4839): USB connected to PC
D/JsMessageQueue( 4727): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4727): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/art     (  937): Explicit concurrent mark sweep GC freed 10477(518KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 1.460ms total 158.695ms
D/FOTAReceiver( 4839): onReceive() enter 
D/FOTAReceiver( 4839): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/TetherSettings( 4079): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4079): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4079): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4079): Cust_ConnectToPC   : spcsc>false
D/        ( 4079): Cust_ConnectToPC   : IPT>true
D/        ( 4079): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4079): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4079): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4079): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4079): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4079): usb_cable_connect = 1
D/SmartNS_Utility( 4079): usb_denied = 0
I/SmartNS_NSReceiver( 4079): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 4079): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 4079): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 4079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_PSService( 4079): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 4079): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 4079):  defaultType:0
I/SmartNS_PSService( 4079): fail notificaiton:false
D/SmartNS_Utility( 4079): usb_cable_connect = 1
D/SmartNS_Utility( 4079): usb_denied = 0
I/SmartNS_PSService( 4079): usb notificaiton:true
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
I/ActivityManager(  937): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=4883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/SmartNS_Utility( 4079): usb_cable_connect = 1
D/SmartNS_Utility( 4079): usb_denied = 0
I/SmartNS_PSService( 4079): usb notificaiton:true
E/WifiStateMachine(  937): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_Utility( 4079): usb_cable_connect = 1
D/SmartNS_Utility( 4079): usb_denied = 0
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/SmartNS_PSService( 4079): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 4079): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  937): killProcessQuiet, pid=4211
I/ActivityManager(  937): Killing 4211:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  937): Recipient 4211
D/jxcore_app_log( 4727): JniHelper::setJavaVM(0xab30f8f8), pthread_self() = -1402800312
D/JX-Cordova( 4727): jxcore cordova android initializing
W/ContextImpl( 4883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
D/Process (  937): killProcessQuiet, pid=4174
I/ActivityManager(  937): Killing 4174:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/jxcore-log( 4727): Initializing JXcore engine
W/jxcore-log( 4727): JXcore engine is ready
W/jxcore-log( 4727): Starting JXcore engine
I/art     ( 1888): Explicit concurrent mark sweep GC freed 10052(540KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 949us total 49.886ms
D/PMS     (  937): acquireWL(1850f20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1888 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1888): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1888): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1888): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1888): [NET] android_getaddrinfo_proxy+
D/libc    ( 1888): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1888): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  937): releaseWL(1850f20): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  937): Recipient 4174
W/jxcore-log( 4727): Platform android
W/jxcore-log( 4727): 
W/jxcore-log( 4727): Process ARCH arm
W/jxcore-log( 4727): 
,I/ActivityManager(  937): Waited long enough for: ServiceRecord{1d703780 u0 com.htc.HTCSpeaker/.NGFService}
,D/PMS     (  937): releaseHCC(21560260): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  937): releaseHCC(1c987319): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 4727): JXcore Cordova bridge is ready!,
I/jxcore-log( 4727): 
W/jxcore-log( 4727): JXcore engine is started
,I/ActivityManager(  937): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=4912 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a,
,W/ResourcesManager( 4912): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,E/jxcore-log( 4727): >> HTC-HTC One M8s
E/jxcore-log( 4727): 
I/jxcore-log( 4727): Total memory 1931808768
I/jxcore-log( 4727): 
I/jxcore-log( 4727): Free memory 87683072
I/jxcore-log( 4727): 
I/jxcore-log( 4727): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4727): 
I/jxcore-log( 4727): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4727): 
I/jxcore-log( 4727): userPath [ 'www' ]
I/jxcore-log( 4727): 
I/jxcore-log( 4727): Size 1080 1776
I/jxcore-log( 4727): 
,I/jxcore-log( 4727): Screen Brightness 142
I/jxcore-log( 4727): 
,E/jxcore-log( 4727): Dummy Error Log.
E/jxcore-log( 4727): 
,I/CalendarProvider2( 4912): Created com.android.providers.calendar.CalendarAlarmManager@189d38ec(com.htc.providers.calendar.HtcCalendarProvider@14d154b5),
,D/CalendarProvider2( 4912): wait start:true,
,D/FlexNetS( 4912): updateSvcAllowedInSettings:false
D/CalendarProvider2( 4912): wait end:false
I/HtcModeClient( 3156): handler message = 4011
E/HtcModeClient( 3156): Check connection and retry 4 times.
,I/ActivityManager(  937): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4937 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a,
,W/ContextImpl( 4937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  937): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=4960 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/PowerUsageList:PowerUsageHelper( 4937): MY_DEBUG = false
,D/PowerUsageService( 4937): repeat time = 1449498193995
,D/WeatherUtility( 1411): Weather sync is On
,D/WSP     ( 1411): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,D/PMS     (  937): acquireWL(32b5fe4d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4937 1000 null
,D/WeatherUtility( 4960): Weather sync is On
,I/[PluginManager]RegisterService( 1411): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
I/[PluginManager]RegisterService( 1411): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1516): action: android.intent.action.PACKAGE_ADDED
,I/PowerUsageList:PowerUsageHelper( 4937): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/ActivityManager(  937): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4990 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,D/PowerUsageList:BatterySipperExt( 4937): gen(), null == sipper.uidObj, userId = 0
,W/WeatherRequest( 4960): request cur loc, but there is no sys cur
,W/Settings( 4960): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActionCombine( 4960): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/jxcore-log( 4727): getBuffer is called!!!!
I/jxcore-log( 4727): 
,I/RemoteViews( 1516): reapply : com.htc.widget.weatherclock 8 17
,I/DeviceManagement( 4990): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=4990 dbg=false s=true
,I/DeviceManagement( 4990): PackageUpdateReceiver: vvv Package added: [com.example.hello],
,D/Process (  937): killProcessQuiet, pid=3265
I/ActivityManager(  937): Killing 3265:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/MediaProvider( 3689): [update][10]#1#
,D/MediaScanner( 3689):  prescan time: 641ms
,D/MediaScanner( 3689):     scan time: 827ms
D/MediaScanner( 3689): postscan time: 3ms
D/MediaScanner( 3689):    total time: 1471ms,
D/MediaScanner( 3689): -----------------------------------------------------------------
D/MediaScanner( 3689): firstscan(media) time: 280ms
D/MediaScanner( 3689): secondscan(non-media) time: 547ms
D/MediaScanner( 3689):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 1
D/MediaScanner( 3689):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3689):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 3689):  [Total]    File(Image+Video+Audio+Others) in database : 1546,
,D/MediaProvider( 3689): [delete][5],
D/MediaProvider( 3689): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
,D/MediaProvider( 3689): [recoverParentNodes] - 0,
D/MediaProvider( 3689): [update][3]
D/MediaScannerServiceEx( 3689): [scan] Recover Parent Node is finished!
D/MediaScannerServiceEx( 3689): [updateImage]+
,I/ActivityManager(  937): Recipient 3265,
,D/MediaScannerServiceEx( 3689): [updateImage]-0
,D/MediaScannerServiceEx( 3689): [1] scan finished
D/PMS     (  937): releaseWL(36f6a4ab): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaProviderUtils( 3689): calcVolumeId: /storage/emulated/0
D/MediaProviderUtils( 3689): calcVolumeId: /storage/ext_sd
D/MediaProviderUtils( 3689): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3689): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #1
W/MediaScannerServiceEx( 3689): Process mounted intent for unmounted storage: /storage/ext_sd
,I/ActivityManager(  937): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=5013 uid=10013 gids={50013, 9997, 3003, 1028, 1015, 1023, 5011} abi=arm64-v8a
D/MediaScannerServiceEx( 3689): [disAliveExtStorageRows]+131073
I/ActivityManager(  937): Killing 4370:com.google.android.youtube/u0a176 (adj 15): empty #17,
D/Process (  937): killProcessQuiet, pid=4370
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/MediaProvider( 3689): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
D/MediaProvider( 3689): [update][22]#1#
,D/MediaProvider( 3689): [update][19]#0#
,D/MediaScannerServiceEx( 3689): [disAliveExtStorageRows]--1, 0
,I/ActivityManager(  937): Recipient 4370
,D/MediaProviderUtils( 3689): calcVolumeId: /storage/emulated/0
,D/MediaProviderUtils( 3689): calcVolumeId: /storage/ext_sd
,D/MediaProviderUtils( 3689): calcVolumeId: /storage/usb
D/MediaScannerServiceEx( 3689): [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] -1 : #2
W/MediaScannerServiceEx( 3689): Process mounted intent for unmounted storage: /storage/usb
,D/MediaScannerServiceEx( 3689): [disAliveExtStorageRows]+196609
,I/GAV2    ( 4448): Thread[GAThread,5,main]: No campaign data found.
,D/HtcCupdReceiver(Provider)( 5013):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED,
,I/GAv4-SVC( 4237): Google Analytics 7.8.99 is starting up.
,I/ActivityManager(  937): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5038 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a,
D/Process (  937): killProcessQuiet, pid=4448
I/ActivityManager(  937): Killing 4448:com.google.android.gm/u0a106 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/MediaProvider( 3689): [sendStorageAddedIfNeed]: /storage/usb : unmounted,
,D/MediaProvider( 3689): [update][100]#1#
,I/CalendarProvider2( 4912): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: },
W/ContentResolver( 4912): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/MediaProvider( 3689): [update][39]#0#
,D/MediaScannerServiceEx( 3689): [disAliveExtStorageRows]--1, 0
,D/Settings:HtcWirelessFeatureFlags( 4079): id/is att sku: 118/false,
,E/Settings:HtcWrapHeaderInfo( 4079): no such activity!
,I/ActivityManager(  937): Recipient 4448,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4079): The wrap header doesn't exist in header list.,
,E/Settings:HtcWrapHeaderInfo( 4079): updateDevelopment, bPrefShow = true,
,E/Settings:HtcUmcWidgetEnabler( 4079): isSupportMusicChannel(): false,
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]support         :false
,D/Process (  937): killProcessQuiet, pid=4493
I/ActivityManager(  937): Killing 4493:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]support         :false
,I/ActivityManager(  937): Recipient 4493
,D/WifiService(  937): Client connection lost with reason: 4
,V/AlarmManager(  937): sending alarm PendingIntent{29f517c: PendingIntentRecord{2a91aa05 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449497295007, Int=0,
,E/Settings:HtcVoWifiWidgetEnabler( 4079): isSupportVoWifi: null,
I/ActivityManager(  937): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4079): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4079): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 4079): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4079): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4079): [supportHomeButton]support         :false
,I/ActivityManager(  937): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4079): isSupportVoWifi: null
E/ActivityThread( 4079): Failed to find provider info for com.htc.vowifi
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5038, uid=10072, userID:0,
I/ActivityManager(  937): Killing 4623:com.htc.sense.news/u0a74 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=4623
W/global  ( 5038): [apache-http] Connection GC has been deprecated!
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 4623,
,D/Finsky  ( 5038): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,W/global  ( 5038): [apache-http] Connection GC has been deprecated!
,W/global  ( 5038): [apache-http] Connection GC has been deprecated!,
,D/Finsky  ( 5038): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,I/ActivityManager(  937): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5080 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,W/Settings( 5038): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5038): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     (  439): Explicit concurrent mark sweep GC freed 8683(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 401us total 34.816ms
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5038, uid=10072, userID:0
,W/ResourcesManager( 5080): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5080): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 276us total 27.389ms
,I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 193us total 22.466ms
,I/MultiDex( 5080): VM with version 2.1.0 has multidex support
,I/MultiDex( 5080): install
I/MultiDex( 5080): VM has multidex support, MultiDex support library is disabled.
,I/SocialFeedProvider( 1516): +disConnect socialManager
,I/SocialFeedProvider( 1516): disconnect socialManager
I/SocialFeedProvider( 1516): -disConnect socialManager
,D/Process (  937): killProcessQuiet, pid=4667
I/ActivityManager(  937): Killing 4667:com.htc.widget.hmsproc1/u0a35 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  937): Recipient 4667
,D/PMS     (  937): releaseWL(32b5fe4d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Finsky  ( 5038): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5038): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  937): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=5107 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
V/AlarmManager(  937): sending alarm PendingIntent{25269d80: PendingIntentRecord{266e3fb9 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449497295661, Int=0
,D/Finsky  ( 5038): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
D/ChimeraCfgMgr( 4237): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4237): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 4237): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,V/JNIHelp ( 5080): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/PMS     (  937): acquireWL(11aa1e75): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4237 10024 null,
,D/Finsky  ( 5038): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/System  ( 5080): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32e52226: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 5080): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 5080): Installed default security provider GmsCore_OpenSSL
,I/ImageRamCache( 5107): create image Cache, size: 31457280.,
I/ImageRamCache( 5107): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 5107): create image Cache, size: 31457280.
,I/FeedSettings( 5107): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 5107): GroupBudget 0.500000 0.380000
I/FeedSettings( 5107): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 5107): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 5107): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 5107): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 5107): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 5107): last commit ulog time 1449470898364
I/SocialManager[SocialBiLogHelper]( 5107): skip commit this time
,D/Process (  937): killProcessQuiet, pid=4704
I/ActivityManager(  937): Killing 4704:com.htc.mms.backupagent/u0a76 (adj 15): empty #17,
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 4704
,I/ConfigFetchService( 4237): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,D/PMS     (  937): acquireWL(33a4cdba): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4237 10024 WorkSource{10373 com.example.hello}
,I/ConfigFetchService( 4237): launchTask
,D/Process (  937): killProcessQuiet, pid=4744
I/ActivityManager(  937): Killing 4744:com.htc.mobiledata:remote/u0a46 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  937): releaseWL(11aa1e75): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,V/ConfigFetchTask( 4237): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U_Vm09PQXBI7xeLsfvfugZgnIAEbBTTpvkI3KjWuig-spo3EAIzBX-fZFzmoTBSLe7ZzKcOCsAAsBube7CCKMIFKSdclADtl1IDDiYZC8MT96uWYunyqVRLTS2xeQG1aJacWQOBIhL2Ki5nV7QYwqzK5ATJa1sNlc3YzJio_eCUjCsgTIxcYyS8AQgd4VdEVQ4eT-t
,I/GoogleURLConnFactory( 4237): Using platform SSLCertificateSocketFactory,
,I/ActivityManager(  937): Recipient 4744
,D/PMS     (  937): acquireWL(4c20b86): PARTIAL_WAKE_LOCK  Icing 0x1 4237 10024 WorkSource{10024 com.google.android.gms}
,D/ChimeraCfgMgr( 4237): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4237): Module APK com.google.android.play.games already loaded,
,I/PeopleContactsSync( 4237): CP2 sync disabled
,D/ChimeraCfgMgr( 4237): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4237, uid=10024, userID:0
,D/Vision  ( 4237): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package: flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 4237): Failed to find package metadata for com.example.hello
,D/Vision  ( 4237): No vision deps,
,I/ActivityManager(  937): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5147 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a,
,I/Icing   ( 4237): Storage manager: low false usage 1.98MB avail 5.80GB capacity 7.95GB,
,D/libc    ( 4237): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
D/libc    ( 4237): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 4237): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    ( 4237): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 4237): [NET] android_getaddrinfo_proxy+
,D/libc    ( 4237): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 4237): [NET] android_getaddrinfo_proxy-, NODATA
,W/ConfigFetchTask( 4237): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 4237): fetch service done; releasing wakelock,
D/PMS     (  937): releaseWL(33a4cdba): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 WorkSource{10373 com.example.hello},
I/ConfigFetchService( 4237): stopping self
W/Icing   ( 4237): Received bad json for section weights override -- ignoring.
,W/Icing   ( 4237): Received bad json for corpus context scoring override -- ignoring.,
W/Icing   ( 4237): Received bad json for section weights override -- ignoring.
W/Icing   ( 4237): Received bad json for corpus context scoring override -- ignoring.,
,V/AlarmManager(  937): sending alarm PendingIntent{46b05e3: PendingIntentRecord{2deedbe0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449497296468, Int=0
,D/Finsky  ( 5038): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 5038): [1] GearheadStateMonitor.onReady: sIsProjecting:false,
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5038): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=4237, uid=10024, userID:0,
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=4237, uid=10024, userID:0
,I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=4237, uid=10024, userID:0
I/PackageManager(  937):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=4237, uid=10024, userID:0
,I/art     (  937): Explicit concurrent mark sweep GC freed 24494(1162KB) AllocSpace objects, 3(380KB) LOS objects, 33% free, 15MB/23MB, paused 1.468ms total 155.823ms
,E/Icing   ( 4237): Loading extension by file descriptor -1 failed
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.,
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.,
,W/ResourcesManager( 1451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AccTypeManager( 1691): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1691): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/Prism.AllAppsManager( 1516): AllAppsMgr addApps, already exist: ApplicationInfo(id=33, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,W/BaseAppContext( 4237): Using Auth Proxy for data requests.
I/Launcher( 1516): Deferring update until onResume
D/Launcher( 1516): waitUntilResume // bindAppsUpdated
,D/AccTypeManager( 1691): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/PhoneApp( 1451): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1691): Unsupported attribute readOnly,
,W/PackageManager(  937): Unable to load service info ResolveInfo{3f5368a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/Icing   ( 4237): updateResources: need to parse f{com.google.android.gms}
,I/BackupManagerService(  937): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1790): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Icing   ( 4237): Internal init done: storage state 0
,I/Icing   ( 4237): Post-init done
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GAv4    ( 5147): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5147):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5147):   adb logcat -s GAv4
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  937): releaseWL(4c20b86): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 5147): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/Finsky  ( 5038): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/LocationProviderProxy(  937): applying state to connected service
V/GmsNetworkLocationProvi( 1790): DISABLE
,D/PMS     (  937): acquireWL(12645bb5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1790 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(12645bb5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
W/GAv4    ( 5147): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5147): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/LocationProviderProxy(  937): applying state to connected service,
,D/PMS     (  937): acquireWL(baa624a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1790 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): acquireWL(30ba95bb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1790 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(baa624a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): acquireWL(22b2ead8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1790 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  937): releaseWL(30ba95bb): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  937): releaseWL(22b2ead8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,W/AnalyticsTrackerProxyImpl( 5147): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
,E/AndroidHttpClient( 5038): Leak found
E/AndroidHttpClient( 5038): java.lang.IllegalStateException: AndroidHttpClient created and never closed
,E/AndroidHttpClient( 5038): 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:202)
E/AndroidHttpClient( 5038): 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:170)
E/AndroidHttpClient( 5038): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:146)
E/AndroidHttpClient( 5038): 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:113),
E/AndroidHttpClient( 5038): 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:367)
E/AndroidHttpClient( 5038): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidHttpClient( 5038): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidHttpClient( 5038): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidHttpClient( 5038): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidHttpClient( 5038): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidHttpClient( 5038): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidHttpClient( 5038): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidHttpClient( 5038): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidHttpClient( 5038): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidHttpClient( 5038): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidHttpClient( 5038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/VoldConnector(  937): SND -> {16 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
,E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 5147): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
,I/ActivityManager(  937): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5195 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 5147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 4237): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4237): Module APK com.google.android.play.games already loaded
,V/JNIHelp ( 5147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/ResourcesManager( 5195): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PMS     (  937): acquireWL(37d7dc84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 937 1000 null
,I/BatteryService(  937): n_update end
D/PMS     (  937): releaseWL(37d7dc84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/NotificationService(  937): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  937): battery changed pluggedType: 2
D/UsbnetService(  937): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  937): updateBatteryInfo
D/UsbnetService(  937): onReceive BATTERY_CHANGED
D/PMS     (  937): runPSCheck
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  937): Checking...
,D/UsbnetService(  937):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  937): >> updateStatus
D/UsbnetService(  937): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  937): handleMessage: E msg.what=155652
D/WifiController(  937): processMsg: ApStaDisabledState
D/WifiController(  937): processMsg: DefaultState
D/WifiController(  937): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  937): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  937): << updateStatus
,W/System  ( 5147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5147): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1888): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1888): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1888): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1888): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1888): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1888): Explicit concurrent mark sweep GC freed 12760(704KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 777us total 43.883ms
,W/Finsky  ( 5038): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5038): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5038): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5038): [1] DailyHygiene.reschedule: Scheduling new run in 797 minutes (failures=5)
,I/ActivityManager(  937): Killing 4792:com.htc.mobiledata/u0a46 (adj 15): empty #17,
,D/Process (  937): killProcessQuiet, pid=4792
D/DeviceConnectionService( 1790): client connected with version: 7571000
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 4792
,D/Process (  937): killProcessQuiet, pid=3728
I/ActivityManager(  937): Killing 3728:com.htc.sense.mms/u0a64 (adj 15): empty #18
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  937): Recipient 3728
,D/PMS     (  937): acquireWL(321ef59e): PARTIAL_WAKE_LOCK  AsyncService 0x1 5195 10167 null,
,D/PMS     (  937): acquireWL(2c4be04c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 5195 10167 null
,D/PMS     (  937): releaseWL(321ef59e): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  937): releaseWL(2c4be04c): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
,I/ActivityManager(  937): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5230 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a,
D/Process (  937): killProcessQuiet, pid=4338
I/ActivityManager(  937): Killing 4338:com.google.android.talk/u0a112 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1516): loadItems() com.htc.launcher.pageview.WidgetManager@14cde28e +
I/Prism.WidgetManager( 1516): onLoadItems() +
,I/ActivityManager(  937): Recipient 4338
,I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
I/Prism.ItemManager( 5107): loadItems() com.htc.launcher.pageview.WidgetManager@1024656d +
I/Prism.WidgetManager( 5107): onLoadItems() +
,W/ResourcesManager( 1516): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 5107): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PMS     (  937): acquireWL(367d8d9b): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4912 10011 null
,E/SQLiteLog( 4912): (284) automatic index on view_events(_id)
,I/ActivityManager(  937): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5254 uid=10028 gids={50028, 9997, 1028, 1015, 1023, 3003, 2001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  937): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=5276 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 1516): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,W/ResourcesManager( 5107): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
D/PMS     (  937): releaseWL(367d8d9b): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/LocationManagerService(  937): getProviders()=[passive],
,D/BluetoothManagerService(  937): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  937): disable(): mBluetooth = null mBinding = false
,W/Settings:Agent(  937): MONITOR_LOG
W/Settings:Agent(  937): name: bluetooth_on
W/Settings:Agent(  937): value: 0
W/Settings:Agent(  937): >> traceCallingStack()
W/Settings:Agent(  937): Process.myPid(): 937
W/Settings:Agent(  937): Process.myTid(): 1467
W/Settings:Agent(  937): Process.myUid(): 1000
W/Settings:Agent(  937): 
W/Settings:Agent(  937): 
W/System.err(  937): java.lang.Throwable: stack dump
,W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  937): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  937): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  937): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  937): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  937): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:624)
W/System.err(  937): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  937): 
W/Settings:Agent(  937): << traceCallingStack(): 21(ms)
D/BluetoothManagerService(  937): Message: MESSAGE_DISABLE
,D/WifiManager( 4727): setWifiEnabled: Base Package Name=com.example.hello, uid=10373
,D/WifiService(  937): New client listening to asynchronous messages
E/WifiTrafficPoller(  937): ADD_CLIENT: 7
,D/WifiService(  937): setWifiEnabled: false pid=4727, uid=10373
E/WifiService(  937): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  937): isSprintWifiRestricted(): false
W/Settings:Agent(  937): MONITOR_LOG
I/WifiService(  937): isMdmWifiRestricted(): false
W/Settings:Agent(  937): name: wifi_on
W/Settings:Agent(  937): value: 0
W/Settings:Agent(  937): >> traceCallingStack()
W/Settings:Agent(  937): Process.myPid(): 937
W/Settings:Agent(  937): Process.myTid(): 1162
W/Settings:Agent(  937): Process.myUid(): 1000
W/Settings:Agent(  937): 
W/Settings:Agent(  937): 
W/System.err(  937): java.lang.Throwable: stack dump
,W/System.err(  937): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  937): 	,at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  937): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  937): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  937): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  937): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  937): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  937): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  937): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  937): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  937): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  937): 
W/Settings:Agent(  937): << traceCallingStack(): 7(ms)
,D/WifiController(  937): handleMessage: E msg.what=155656
,D/WifiController(  937): processMsg: ApStaDisabledState
D/WifiController(  937): handleMessage: X
I/jxcore-log( 4727): ****TEST TOOK:  5123  ms ****
I/jxcore-log( 4727): 
I/jxcore-log( 4727): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4727): 
,W/asset   ( 1516): Copying FileAsset 0x55a7378ea0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/UpdateIcingCorporaServi( 5230): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/asset   ( 5107): Copying FileAsset 0x55a6eb1ca0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
,I/HtcModeClient( 3156): handler message = 4011
,E/HtcModeClient( 3156): Check connection and retry 5 times.
,E/Prism.WidgetManager( 1516): The same lists. No need to update. skip it.,
I/Prism.WidgetManager( 1516): onLoadItems() -
I/Prism.ItemManager( 1516): loadItems() com.htc.launcher.pageview.WidgetManager@14cde28e -
,D/PhoneApp( 1451): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1451): -- N1 =0
D/PhoneApp( 1451): -- N2 =0
I/EASAppSvc( 5276): [ NA ]onCreate
D/PhoneApp( 1451): -- N3 =0
I/VersionUtil( 5276): [ NA ]setIsFOTAing: true
,I/Prism.WidgetManager( 5107): onLoadItems() -
,I/Prism.ItemManager( 5107): loadItems() com.htc.launcher.pageview.WidgetManager@1024656d -
,I/VersionUtil( 5276): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5276): [ NA ]setIsFOTAing: false
,D/HtcAdjCursorFactory( 5276): Set CursorWindow size to: 4194304 KB, Tid: 5308
,D/ORMLib  ( 4770): put()
,W/asset   ( 5230): Copying FileAsset 0x55a6d61ef0 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/UpdateIcingCorporaServi( 5230): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
,I/ActivityManager(  937): Killing 4839:com.nero.android.htc.sync/u0a5 (adj 15): empty #17
D/Process (  937): killProcessQuiet, pid=4839
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,E/cutils-trace( 5306): Error opening trace file: Permission denied (13),
,I/ActivityManager(  937): Recipient 4839
,D/WifiService(  937): Client connection lost with reason: 4
,D/CustomizationManager( 5306): ====startRecUseTime====
I/ActivityManager(  937): Killing 4883:com.htc.backupreset/1000 (adj 15): empty #17
D/htc.customization.log.level( 5306):  is 
W/CustomizationLogLevel( 5306): Level value is invalid, use default level 2
D/Process (  937): killProcessQuiet, pid=4883
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/CustomizationManager( 5306):  Read ACC file spent 0.039 (s),
,D/CIDMapFileReader( 5306): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5306): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 5306): full path : /system/customize/CID/HTC__102.xml
,I/CustomizationCIDLoader( 5306): Parsing tag category name = system
,I/CustomizationCIDLoader( 5306): Parsing tag category name = application
I/CustomizationCIDLoader( 5306): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5306): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5306): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5306): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5306): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 5306): add string-array item, value = 42507
I/CustomizationCIDLoader( 5306): add string-array item, value = 21902
I/CustomizationCIDLoader( 5306): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5306): add string-array item, value = 23420
I/CustomizationCIDLoader( 5306): add string-array item, value = 22299
I/CustomizationCIDLoader( 5306): add string-array item, value = 24002
I/CustomizationCIDLoader( 5306): add string-array item, value = 23210
I/CustomizationCIDLoader( 5306): add string-array item, value = 23205
I/CustomizationCIDLoader( 5306): add string-array item, value = 23806
I/CustomizationCIDLoader( 5306): add string-array item, value = 23430
I/CustomizationCIDLoader( 5306): add string-array item, value = 23408
I/CustomizationCIDLoader( 5306): add string-array item, value = 27205
,I/CustomizationCIDLoader( 5306): add string-array item, value = 42507:C:1:0
,I/ActivityManager(  937): Recipient 4883
I/CustomizationCIDLoader( 5306): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 23210:D:2:0
,I/CustomizationCIDLoader( 5306): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5306): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5306):  Read CID file spent 0.078 (s)
D/CustomizationManager( 5306):  All configurations done spent 0.079 (s)
,I/art     (  937): Explicit concurrent mark sweep GC freed 24282(1305KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 1.298ms total 134.070ms
,D/WifiService(  937): New client listening to asynchronous messages
E/WifiTrafficPoller(  937): ADD_CLIENT: 7
,W/EAS_NetworkUtil( 5276): [ NA ]getNetworkInfo: NetworkInfo is null,
,I/ActivityManager(  937): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5332 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=arm64-v8a
,D/PackageManager(  937): deletePackageAsUser: pkg=com.example.hello, pid=5306, uid=2000 userid=0
,I/EASAppSvc( 5276): [ NA ]onDestroy
,I/EASAppSvc( 5276): [ NA ]> uninitEASService
I/EASAppSvc( 5276): [ NA ]onCreate
I/EASRequestController( 5276): [ NA ]release
,I/VersionUtil( 5276): [ NA ]setIsFOTAing: true
,I/VersionUtil( 5276): [ NA ]onUpgrade: current version=100, latest version=100
,I/VersionUtil( 5276): [ NA ]setIsFOTAing: false
W/EAS_NetworkUtil( 5276): [ NA ]getNetworkInfo: NetworkInfo is null
,I/ActivityManager(  937): Force stopping com.example.hello appid=10373 user=-1: uninstall pkg
,D/EASPublicBinder( 5276): [ NA ]release
D/TaskBinder( 5276): [ NA ]release
,D/TaskBinder( 5276): [ NA ]release
I/EASAppSvc( 5276): [ NA ]< uninitEASService
,D/Process (  937): killProcessQuiet, pid=4727
I/ActivityManager(  937): Killing 4727:com.example.hello/u0a373 (adj 0): stop com.example.hello
,D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
,W/PackageSettings(  937): Skipping PackageSetting{6ddfd87 com.test.thalitest/10366} due to missing metadata
,D/ORMLib  ( 4770): put()
,I/ActivityManager(  937): Recipient 4727
,E/InputEventReceiver( 1353): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{e8296fa uid 10373 pid 4727} (c)'
I/WindowState(  937): WIN DEATH: Window{1d5fc9ee u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  937): Client connection lost with reason: 4
,W/ActivityManager(  937): Force removing ActivityRecord{3e50cfde u0 com.example.hello/.MainActivity t8}: app died, no saved state
,I/ActivityManager(  937): Force stopping com.example.hello appid=10373 user=0: pkg removed
,W/ActivityManager(  937): Spurious death for ProcessRecord{359574ac 4727:com.example.hello/u0a373}, curProc for 4727: null
,E/SQLiteLog( 5254): (283) recovered 15 frames from WAL file /data/data/com.htc.album/databases/MMexternal.db-wal,
,D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  937): acquireWL(2330690a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1790 10024 WorkSource{10024 com.google.android.gms}
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PMS     (  937): releaseWL(2330690a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1790): Ignoring removeGeofence because network location is disabled.
I/FeedHostManager( 1516): [onResume]
I/FeedProviderManager( 1516): onResume
I/SocialFeedProvider( 1516): +onResume
I/SocialFeedProvider( 1516): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1516): -onResume
D/AccTypeManager( 1691): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/ConnectivityHelper( 1516): [getCurrentConnectionType] no network connection
,I/EASAppSvc( 5276): [ NA ]onDestroy
,I/EASAppSvc( 5276): [ NA ]> uninitEASService
,W/SystemReader(  937): Cannot find grip_rejection_width, use default value instead
,D/AccTypeManager( 1691): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  937): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=5365 uid=10066 gids={50066, 9997, 3003} abi=arm64-v8a
,I/EASRequestController( 5276): [ NA ]release
I/InputMethodManagerService(  937): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/StatusBarManagerService(  937): setSystemUiVisibility(0x700)
D/AccTypeManager( 1691): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin,
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,D/EASPublicBinder( 5276): [ NA ]release
D/TaskBinder( 5276): [ NA ]release
D/TaskBinder( 5276): [ NA ]release
I/EASAppSvc( 5276): [ NA ]< uninitEASService
,D/FindExtension( 1516): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1516): Defer allocateBuffers to drawing time
I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/PhoneApp( 1451): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  937): Got RemoteException sending setActive(false) notification to pid 4727 uid 10373
,D/StatusBarManagerService(  937): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  937): Enable input method client, pid=1516
,E/ExternalAccountType( 1691): Unsupported attribute readOnly,
,W/ResourcesManager(  937): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusBarManagerService(  937): setSystemUiVisibility(0xc0000700)
,D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,W/PackageManager(  937): Unable to load service info ResolveInfo{1422c709 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  937): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  937): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  937): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  937): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  937): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  937): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  937): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  937): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  937): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  937): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/art     (  937): Explicit concurrent mark sweep GC freed 15147(1196KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 2.575ms total 185.085ms
D/Process (  937): killProcessQuiet, pid=4960
I/ActivityManager(  937): Killing 4960:com.htc.widget.hmsproc2/u0a40 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/ORMLib  ( 4770): put()
,D/JobSchedulerService(  937): Receieved: android.intent.action.PACKAGE_REMOVED
,I/MusicStore( 5332): Database version: 120,
,I/ActivityManager(  937): Recipient 4960
,I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,D/TaskPersister(  937): removeObsoleteFile: deleting file=8_task.xml
,D/VoldConnector(  937): SND -> {17 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5332): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  937): SND -> {18 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
,W/ContextImpl( 5332): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,D/VoldConnector(  937): SND -> {19 volume mkdirs /storage/ext_sd/Android/data/com.google.android.music/files/},
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.music/files/
W/ContextImpl( 5332): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files,
,W/ResourcesManager( 5332): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 5332): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5332): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/OpenGLRenderer( 1516): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...,
,D/Process (  937): killProcessQuiet, pid=4937,
I/ActivityManager(  937): Killing 4937:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  937): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,W/art     ( 5332): Suspending all threads took: 11.821ms
,W/ActivityThread( 5332): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5332): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22587be0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5332): Installed default security provider GmsCore_OpenSSL,
D/AndroidMusic( 5332): GMSCore installation verified
,I/ActivityManager(  937): Recipient 4937
,I/ConfigStore( 5332): Config Database version: 1
,E/SQLiteDatabase( 5332): Failed to open database '/data/data/com.google.android.music/databases/config.db'.,
E/SQLiteDatabase( 5332): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854),
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5332): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 5332): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5332): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5332): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/SQLiteDatabase( 5332): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 5332): 	,at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/SQLiteDatabase( 5332): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5332): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5332): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/SQLiteDatabase( 5332): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/SQLiteDatabase( 5332): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/SQLiteDatabase( 5332): 	at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/SQLiteDatabase( 5332): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/SQLiteDatabase( 5332): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/SQLiteDatabase( 5332): 	,at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/SQLiteDatabase( 5332): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/SQLiteDatabase( 5332): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
E/SQLiteDatabase( 5332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/SQLiteDatabase( 5332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/SQLiteDatabase( 5332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 5332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 5332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5332): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5332): 	,at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 5332): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 5332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,E/AndroidRuntime( 5332): FATAL EXCEPTION: main,
E/AndroidRuntime( 5332): Process: com.google.android.music:main, PID: 5332
E/AndroidRuntime( 5332): java.lang.RuntimeException: Unable to create application com.google.android.music.MusicApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4954)
E/AndroidRuntime( 5332): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 5332): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 5332): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5332): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5332): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 5332): ,	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5332): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5332): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 5332): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 5332): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
,E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5332): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 5332): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5332): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5332): 	at com.google.android.music.store.ConfigStore.getDatabase(ConfigStore.java:64)
E/AndroidRuntime( 5332): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 5332): ,	at com.google.android.music.store.ConfigContentProvider.query(ConfigContentProvider.java:129)
E/AndroidRuntime( 5332): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/AndroidRuntime( 5332): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/AndroidRuntime( 5332): 	at android.content.ContentResolver.query(ContentResolver.java:491)
E/AndroidRuntime( 5332): 	at android.content.ContentResolver.query(ContentResolver.java:435)
E/AndroidRuntime( 5332): 	at com.google.android.music.utils.ConfigCache.get(ConfigCache.java:136)
E/AndroidRuntime( 5332): 	,at com.google.android.music.utils.ConfigUtils.getString(ConfigUtils.java:673)
E/AndroidRuntime( 5332): 	at com.google.android.music.utils.ConfigUtils.getBoolean(ConfigUtils.java:709)
E/AndroidRuntime( 5332): 	at com.google.android.music.utils.ConfigUtils.isPlayLoggingEnabled(ConfigUtils.java:399)
E/AndroidRuntime( 5332): 	at com.google.android.music.eventlog.MusicEventLogger.<init>(MusicEventLogger.java:152)
E/AndroidRuntime( 5332): 	at com.google.android.music.eventlog.MusicEventLogger.getInstance(MusicEventLogger.java:270)
E/AndroidRuntime( 5332): 	at com.google.android.music.MusicApplication.onCreate(MusicApplication.java:87)
,E/AndroidRuntime( 5332): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1024)
E/AndroidRuntime( 5332): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4951)
E/AndroidRuntime( 5332): 	... 9 more
,E/ActivityManager(  937): App crashed! Process: com.google.android.music:main
,E/DropBoxManagerService(  937): Can't write: system_app_crash
E/DropBoxManagerService(  937): java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  937): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  937): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  937): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  937): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  937): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  937): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  937): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  937): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  937): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  937): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  937): 	... 5 more
,D/StatusBarManagerService(  937): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  937): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  937): hiding MENU key
,V/AlarmManager(  937): sending alarm PendingIntent{1917f463: PendingIntentRecord{233b6860 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1449497300964, Int=0
,I/Prism.ItemManager( 5107): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 5107): loadItems() com.htc.launcher.pageview.WidgetManager@1024656d +
I/Prism.WidgetManager( 5107): onLoadItems() +
,D/TelephonyReceiver( 1451): bind: true
,I/ActivityManager(  937): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=5406 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=arm64-v8a
,I/ActivityManager(  937): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=5419 uid=10064 gids={50064, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a,
,W/ResourcesManager( 5107): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
,I/Prism.ItemManager( 1516): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1516): loadItems() com.htc.launcher.pageview.WidgetManager@14cde28e +
I/Prism.WidgetManager( 1516): onLoadItems() +
,D/DFPI.PIReciver( 5406): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 5406): onHandleIntent,
I/DFPI.ApkInstallService( 5406): Media Scan Finished Case 
,W/HtcWrapAdjustableCursorFactory( 5419): HtcWrapAdjustableCursorFactory is deprecated. Use HtcWrapSQLite in HDK Lib3 instead.
,D/DFPI.ApkInstallService( 5406): check CID = HTC__102,
I/DFPI.ApkInstallService( 5406): There is no Demo.apk in sd card or phone storage
,D/MessageFrequencyProvider( 5419): onCreate
I/ActivityManager(  937): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=5453 uid=10049 gids={50049, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/GetPrviateResource( 5419): GetPrviateResource
V/GetPrviateResource( 5419): GetPrviateResource
D/GenericMessagesProvider( 5419): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 5419): (14) cannot open file at line 30058 of [9491ba7d73]
E/SQLiteLog( 5419): (14) os_unix.c:30058: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 5419): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 5419): DB info: errno = 2, errno message = No such file or directory
,D/MessageCustFlag( 5419): sense_version=6.0,
,D/BTAccessoryUtil( 5419): createReceiver
,D/BTAccessoryUtil( 5419): registerReceiver return intent = null
E/SQLiteDatabase( 5419): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 5419): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
E/SQLiteDatabase( 5419): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 5419): 	at android.content.ContentProvider.query(ContentProvider.java:960)
E/SQLiteDatabase( 5419): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
E/SQLiteDatabase( 5419): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)
E/SQLiteDatabase( 5419): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err( 5419): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
,W/System.err( 5419): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
W/System.err( 5419): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
W/System.err( 5419): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 5419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 5419): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 5419): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
W/System.err( 5419): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
W/System.err( 5419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
W/System.err( 5419): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:712)
I/ActivityManager(  937): Killing 4526:com.google.android.partnersetup/u0a27 (adj 15): empty #17
W/System.err( 5419): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 5419): 	at android.content.ContentProvider.query(ContentProvider.java:960)
W/System.err( 5419): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:220)
W/System.err( 5419): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:142)

```
