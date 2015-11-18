#### Test 50388019f4ce509_thali05_HTC-HTC One_M8 Logs


```
--------- beginning of main
I/HtcModeClient( 3177): handler message = 4011
E/HtcModeClient( 3177): Check connection and retry 5 times.
I/ConfigService( 1758): onDestroy
,I/SocialFeedProvider( 1490): +disConnect socialManager
I/SocialFeedProvider( 1490): disconnect socialManager
I/SocialFeedProvider( 1490): -disConnect socialManager
D/Process (  975): killProcessQuiet, pid=5347
--------- beginning of system
I/ActivityManager(  975): Killing 5347:com.google.android.apps.docs/u0a107 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
I/ActivityManager(  975): Recipient 5347
D/Process (  975): killProcessQuiet, pid=5347
W/libprocessgroup(  975): failed to open /acct/uid_10107/pid_5347/cgroup.procs: No such file or directory
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
I/SocialFeedProvider( 1490): syncData - m_GetDataType=REPLACE
I/SocialFeedAdapter( 1490): prepareHighlightItems - Original dataList (size=0)
I/SocialFeedAdapter( 1490): prepareHighlightItems - DataList for highlight (size=0), SKIP - NoPictureNews:0
I/SocialFeedAdapter( 1490): updateFeedItemsList:REPLACE - Adapter:News, m_nNewAddCount=0, m_HighLightItemsList size=0, m_FilterItemsList size=0
I/SocialFeedAdapter( 1490): prepareHighlightItems - Original dataList (size=0)
I/SocialFeedAdapter( 1490): prepareHighlightItems - DataList for highlight (size=0), SKIP - NoPictureNews:0
I/SocialFeedAdapter( 1490): updateFeedItemsList:REPLACE - Adapter:RSS Reader for HTC Sense, m_nNewAddCount=0, m_HighLightItemsList size=0, m_FilterItemsList size=0
I/SocialFeedProvider( 1490): getSyncUri - HostType=PRISM
I/SocialFeedProvider( 1490): getFeedDataFromUrl - uri=content://com.htc.sense.hsp.opensense.social/stream/topstory
W/SocialFeedProvider( 1490): Customize Highlight array is null
D/a       ( 1411): get htcisdemo: false
I/SocialFeedProvider( 1490): cur size=0
I/SocialFeedAdapter( 1490): prepareHighlightItems - Original dataList (size=0)
I/SocialFeedAdapter( 1490): prepareHighlightItems - DataList for highlight (size=0), SKIP - NoPictureNews:0
I/SocialFeedAdapter( 1490): updateFeedItemsList:REPLACE - Adapter:News, m_nNewAddCount=0, m_HighLightItemsList size=0, m_FilterItemsList size=0
I/SocialFeedAdapter( 1490): prepareHighlightItems - Original dataList (size=0)
I/SocialFeedAdapter( 1490): prepareHighlightItems - DataList for highlight (size=0), SKIP - NoPictureNews:0
I/SocialFeedAdapter( 1490): updateFeedItemsList:REPLACE - Adapter:RSS Reader for HTC Sense, m_nNewAddCount=0, m_HighLightItemsList size=0, m_FilterItemsList size=0
I/SocialFeedProvider( 1490): -sync
I/FeedProviderManager( 1490): onSyncCompleted: com.htc.feed.socialfeedprovider.SocialFeedProvider@24163a73
I/SocialFeedProvider( 1490): onHostCommand - COMMAND_CHECK_BLINKFEED_COMMITMENT (false)
I/FeedHostManager( 1490): >>host.performSync.onSyncCompleted: [com.htc.feed.local.getstarted.GetStartedFeedProvider@b4b2c92, com.htc.feed.local.showme.ShowMeFeedProvider@3e5c7edb, com.htc.feed.local.calendar.CalendarFeedProvider@1b2fe319, com.htc.videohub.ui.feedservice.VideoCenterFeedService @ com.htc.libfeedframework.HtcFeedProvider@36d297d5, com.htc.feed.local.memory.MemoryFeedProvider@25735af4, com.htc.feed.socialfeedprovider.SocialFeedProvider@24163a73], filter:Highlights
I/ConnectivityHelper( 1490): [dumpCurrentState] can not get networkInfo
I/FeedViewEntryStack( 1490): clearAllNewsInStack()
I/FeedHostManager( 1490): adapter SocialFeedAdapter/com.htc.opensense.htcnews 309a2db7 num:0
I/FeedHostManager( 1490): adapter SocialFeedAdapter/com.htc.socialnetwork.rss.octopus 3e1d6924 num:0
I/FeedHostManager( 1490): adapter com.htc.feed.local.memory.MemoryFeedAdapter@1e66ec8d num:0
I/FeedHostManager( 1490): adapter com.htc.feed.local.getstarted.GetStartedFeedAdapter@ff3de42 num:2
I/FeedHostManager( 1490): adapter com.htc.feed.local.calendar.CalendarFeedAdapter@199ee53 num:0
I/FeedHostManager( 1490): adapter com.htc.feed.local.showme.ShowMeFeedAdapter@3c59f390 num:0
I/FeedHostManager( 1490): adapter com.htc.libfeedframework.HtcFeedAdapter@be2c489@com.htc.videohub.ui/.feedservice.VideoCenterFeedService num:0
I/FeedProviderManager( 1490): callProviderCommand [6001]com.htc.videohub.ui.feedservice.VideoCenterFeedService @ com.htc.libfeedframework.HtcFeedProvider@36d297d5:null
I/FeedAdapterData( 1490): adatpter SocialFeedAdapter/com.htc.opensense.htcnews 309a2db7 has no items, boundary:0
I/FeedAdapterData( 1490): adatpter SocialFeedAdapter/com.htc.socialnetwork.rss.octopus 3e1d6924 has no items, boundary:0
I/FeedAdapterData( 1490): adatpter com.htc.feed.local.memory.MemoryFeedAdapter@1e66ec8d has no items, boundary:0
I/FeedAdapterData( 1490): adatpter com.htc.feed.local.getstarted.GetStartedFeedAdapter@ff3de42 has 2 items but no one match boundary:0
I/FeedAdapterData( 1490): adatpter com.htc.feed.local.calendar.CalendarFeedAdapter@199ee53 has no items, boundary:0
I/FeedAdapterData( 1490): adatpter com.htc.feed.local.showme.ShowMeFeedAdapter@3c59f390 has no items, boundary:0
I/FeedAdapterData( 1490): adatpter com.htc.libfeedframework.HtcFeedAdapter@be2c489@com.htc.videohub.ui/.feedservice.VideoCenterFeedService has no items, boundary:0
I/HighlightFeedCellPool( 1490): getNewFeedList news: FeedAdapterData:SocialFeedAdapter/com.htc.opensense.htcnews 309a2db7, social: [FeedAdapterData:SocialFeedAdapter/com.htc.socialnetwork.rss.octopus 3e1d6924], local: [FeedAdapterData:com.htc.feed.local.memory.MemoryFeedAdapter@1e66ec8d, FeedAdapterData:com.htc.feed.local.getstarted.GetStartedFeedAdapter@ff3de42, FeedAdapterData:com.htc.feed.local.calendar.CalendarFeedAdapter@199ee53, FeedAdapterData:com.htc.feed.local.showme.ShowMeFeedAdapter@3c59f390, FeedAdapterData:com.htc.libfeedframework.HtcFeedAdapter@be2c489@com.htc.videohub.ui/.feedservice.VideoCenterFeedService]
I/FeedViewEntryStack( 1490): clearAllNewsInStack()
I/FeedViewEntryStack( 1490): newItemList isEmpty
I/HighlightFeedCellPool( 1490): selectHighglihtSocialFeeds +
I/HighlightFeedCellPool( 1490): nMaxBudget: 45, socialFeedViewEntryList: []
I/FeedViewEntryStack( 1490): pop 0 items, 0
I/HighlightFeedCellPool( 1490): getNewFeedList newsFeed 0, socialFeed 0, localfeed 0
I/FeedGridAdapter( 1490): setData() - dataList 2
I/FeedGridAdapter( 1490): generateRows() - genrated rows:2
I/FeedGridAdapter( 1490): generateRowsLand() - genrated rows:1
I/FeedGridAdapter( 1490): setData() - rows:(2 1), total:(2 1)
I/FeedAdapterData( 1490): [load more]m_nRecentNextIndex:2
I/FeedScrollView( 1490): onRefreshFinished() - bSetLastUpdateTime? true, bHideActionBar? true
I/FeedHostManager( 1490): nNewPages: 2, forceRefreshPages: true, runnableIsNull: true, pager is no data: false
I/FeedHostManager( 1490): <<host.performSync.onSyncCompleted: [com.htc.feed.local.getstarted.GetStartedFeedProvider@b4b2c92, com.htc.feed.local.showme.ShowMeFeedProvider@3e5c7edb, com.htc.feed.local.calendar.CalendarFeedProvider@1b2fe319, com.htc.videohub.ui.feedservice.VideoCenterFeedService @ com.htc.libfeedframework.HtcFeedProvider@36d297d5, com.htc.feed.local.memory.MemoryFeedProvider@25735af4, com.htc.feed.socialfeedprovider.SocialFeedProvider@24163a73]
I/FeedProviderManager( 1490): <<sync
I/FeedHostManager( 1490): <<performSync: REMOVE_FILTER_SOURCE_AT_HIGHLIGHT
I/FeedSyncExecutorService( 1490): complete task: T:FeedHostSync #1, R:SyncTask #1447834337202
I/PriorityFeedCacheHelper( 1490): updatePriorityFeeds cv:row=0 feedid=101 rowland=0 adapter=GetStartedFeedAdapter
W/View    ( 1490): requestLayout() improperly called by android.widget.ImageView{97f21c3 V.ED.... ......ID 0,2-40,42 #7f0e0195 app:id/footer_icon} during layout: running second layout pass
W/View    ( 1490): requestLayout() improperly called by android.widget.ImageView{273cfa40 V.ED.... ......ID 0,2-40,42 #7f0e0195 app:id/footer_icon} during layout: running second layout pass
I/FeedScrollView( 1490): setRefreshing false
I/FeedActionBar( 1490): updateLastUpdatedTime(in String) LAST UPDATED 9:12
I/FeedScrollView( 1490): [load more]cancel return
I/PriorityFeedCacheHelper( 1490): updatePriorityFeeds cv:row=1 feedid=100 rowland=0 adapter=GetStartedFeedAdapter
I/SensorManager( 1695): unregisterListenerImpl++: listener = com.google.android.location.collectionlib.cm@2fe1c8b8
W/SensorService(  975): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  975): disable: get sensor name = Accelerometer Sensor
W/SensorService(  975): pid=1695, uid=10025
W/SensorService(  975): Active sensors: size = 3
W/SensorService(  975): Accelerometer Sensor (handle=0x00000000, connections=2)
W/SensorService(  975): CM36282 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  975): CM36282 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  975): SensorService::listenerSensor++: mName = com.google.android.location.collectionlib.cm@2fe1c8b8, eanble = 0, strlen(mName) = 53
W/SensorService(  975): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  975): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@3b0f60db
W/SensorService(  975): Listener[1] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4eb9e41
W/SensorService(  975): Listener[2] = com.htc.smartdim.sensor_eye@11b271ef
W/SensorService(  975): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  975): acquireWL(74b5170): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1695 10025 null
D/PMS     (  975): releaseWL(1568d1f): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
D/PMS     (  975): releaseWL(74b5170): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  975): acquireWL(3a81fce9): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1695 10025 null
D/PMS     (  975): releaseWL(48fc8be): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
D/PMS     (  975): releaseWL(3a81fce9): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/CustomizationManager( 5643): ====startRecUseTime====
D/htc.customization.log.level( 5643):  is 
W/CustomizationLogLevel( 5643): Level value is invalid, use default level 2
D/PMS     (  975): acquireWL(99ddd6e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1695 10025 null
D/PMS     (  975): releaseWL(3bc64379): PARTIAL_WAKE_LOCK  NlpCollectorWakeLock 0x1 null
D/PMS     (  975): acquireWL(22c2fc0f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1695 10025 null
D/PMS     (  975): releaseWL(22c2fc0f): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  975): acquireWL(386c149c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1695 10025 WorkSource{10025 com.google.android.gms}
D/PMS     (  975): releaseWL(386c149c): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10025 com.google.android.gms}
D/PMS     (  975): acquireWL(f47ea5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1695 10025 null
D/PMS     (  975): releaseWL(f47ea5): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  975): releaseWL(99ddd6e): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/CustomizationManager( 5643):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__203
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__405
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__304
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 5643): Parsing tag item name = HTC__002
V/CustomizationCIDLoader( 5643): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 5643): Parsing tag category name = system
I/CustomizationCIDLoader( 5643): Parsing tag category name = application
I/CustomizationCIDLoader( 5643): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5643): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5643): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5643): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5643): Parsing tag category name = ACC
D/CustomizationManager( 5643):  Read CID file spent 0.097 (s)
D/CustomizationManager( 5643):  All configurations done spent 0.098 (s)
E/ActTriggerJNI( 5643): open library fail.
E/MP-Decision( 2207): Update arg 2
I/ActivityManager(  975): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PMS     (  975): acquireHCC(3f4e627a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 975 1000 null
D/PMS     (  975): acquireHCC(3abd4a2b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 975 1000 null
E/MP-Decision( 2207): Update arg 4
W/asset   (  975): Copying FileAsset 0xb83bf5a8 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
E/MP-Decision( 2207): Update arg "0 190 240 240".
E/MP-Decision( 2207): Update arg "0 75 400 400".
I/AnimationUtil(  975): isHTCRecent(HelloWorld/Recent screens.)/1
D/PMS     (  975): acquireWL(28502c46): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 975 1000 null
I/FeedHostManager( 1490): [onPause]
I/FeedProviderManager( 1490): onPause
I/FeedHostManager( 1490): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@9964e15
I/SocialFeedProvider( 1490): +onPause
I/SocialFeedProvider( 1490): -onPause
E/cutils-trace( 5643): Error opening trace file: No such file or directory (2)
D/HtcSystemUPManager(  975): HtcSystemUPolicy [canLog (default)] category: launch, enable: true
I/ActivityManager(  975): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5677 uid=10380 gids={50380, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/StatusBarManagerService(  975): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  975): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  975): hiding MENU key
W/asset   ( 5677): Copying FileAsset 0xb8355a98 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1490): [trimMemory] 20
I/WebViewFactory( 5677): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5677): Time to load native libraries: 2 ms (timestamps 8785-8787)
I/LibraryLoader( 5677): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5677): Binding Chromium to main looper Looper (main, tid 1) {1001a702}
I/LibraryLoader( 5677): Expected native library version number "",actual native library version number ""
I/chromium( 5677): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5677): Initializing chromium process, singleProcess=true
W/art     ( 5677): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5677): ApplicationContext is null in ApplicationStatus
W/chromium( 5677): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5677): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5677): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5677): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5677): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030_msm8974_refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030__release_AU ()
I/Adreno-EGL( 5677): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5677): Build Date: 12/11/14 Thu
I/Adreno-EGL( 5677): Local Branch: 
I/Adreno-EGL( 5677): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.030
I/Adreno-EGL( 5677): Local Patches: NONE
I/Adreno-EGL( 5677): Reconstruct Branch: NOTHING
W/System.err(  975): java.lang.Throwable: stack dump
D/BluetoothManagerService(  975): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  975): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  975): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:449)
W/System.err(  975): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  975): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  975): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1db6f964:true
D/BluetoothAdapter( 5677): 1046950222: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5677): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5677): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5677): CordovaWebView is running on device made by: HTC
W/art     ( 5677): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5677): Attempt to remove local handle scope entry from IRT, ignoring
D/Atlas   ( 5677): Validating map...
W/chromium( 5677): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/InputMethodManager( 5677): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@342555f, mServedView=org.apache.cordova.engine.SystemWebView{3fbb7bac VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@158a4075
I/ActivityManager(  975): Displayed com.example.hello/.MainActivity: +506ms
I/art     (  975): Explicit concurrent mark sweep GC freed 13123(656KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 851us total 78.469ms
I/InputMethodManagerService(  975): Disable input method client, pid=1490
D/StatusBarManagerService(  975): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  975): Enable input method client, pid=5677
D/PMS     (  975): releaseWL(28502c46): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/XT9_C   ( 1276): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1276): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1276): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1276): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/BindingManager( 5677): Cannot call determinedVisibility() - never saw a connection for the pid: 5677
I/chromium( 5677): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 5677): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5677): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/c*.h*.c*.u*.m*.ModelAs*( 2257): ModelAsyncTask: Caught exception running async model handler: com.htc.cs.dm.config.TimeoutException
D/c*.h*.c*.u*.m*.ModelAs*( 2257): ModelAsyncTask: The future has completed
E/ServerCorridor( 2257): DMHelper: DM Exception => com.htc.cs.dm.config.TimeoutException
E/ServerCorridor( 2257): BaseException: DMErrorException java.lang.Throwable: com.htc.cs.dm.config.TimeoutException
D/NewsPlugin( 2257): DMHelper exception
D/NewsPlugin( 2257): com.htc.prism.feed.corridor.exceptions.DMErrorException: java.lang.Throwable: com.htc.cs.dm.config.TimeoutException
D/NewsPlugin( 2257): 	at com.htc.prism.feed.corridor.util.DMHelper.fetchData(DMHelper.java:57)
D/NewsPlugin( 2257): 	at com.htc.prism.feed.corridor.util.DMHelper.init(DMHelper.java:63)
D/NewsPlugin( 2257): 	at com.htc.prism.feed.corridor.util.DMHelper.getDMHelper(DMHelper.java:76)
D/NewsPlugin( 2257): 	at com.htc.plugin.news.NewsUtils.getBooleanSettingFromDm(NewsUtils.java:621)
D/NewsPlugin( 2257): 	at com.htc.plugin.news.NewsSocialPluginService.shouldFetchOobeNews(NewsSocialPluginService.java:863)
D/NewsPlugin( 2257): 	at com.htc.plugin.news.NewsSocialPluginService.access$300(NewsSocialPluginService.java:64)
D/NewsPlugin( 2257): 	at com.htc.plugin.news.NewsSocialPluginService$SocialPluginStub.syncActivityStreams(NewsSocialPluginService.java:200)
D/NewsPlugin( 2257): 	at com.htc.lib2.opensense.social.AbstractSocialPlugin$Transport$1.run(AbstractSocialPlugin.java:58)
D/NewsPlugin( 2257): 	at java.lang.Thread.run(Thread.java:818)
D/NewsPlugin( 2257): Caused by: java.lang.Throwable: com.htc.cs.dm.config.TimeoutException
D/NewsPlugin( 2257): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
D/NewsPlugin( 2257): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
D/NewsPlugin( 2257): 	at com.htc.cs.util.model.ModelAsyncTask.get(ModelAsyncTask.java:195)
D/NewsPlugin( 2257): 	at com.htc.cs.util.model.ModelAsyncTask.get(ModelAsyncTask.java:31)
D/NewsPlugin( 2257): 	at com.htc.prism.feed.corridor.util.DMHelper.fetchData(DMHelper.java:46)
D/NewsPlugin( 2257): 	... 8 more
I/NewsPlugin( 2257): customize flag enable oobe news? true, dm enable oobe news? false, oobe news fetched? true
I/NewsPlugin( 2257): set user profile
I/NewsPlugin( 2257): host sync highlights
D/NewsDB  ( 2257): set custom highlight []
D/ProfileService( 2257): onHandleIntent
E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
E/ServerCorridor( 2257): DMHelper: com.htc.cs.util.model.BaseModel.checkAvailable(BaseModel.java:312)com.htc.cs.dm.config.model.DataBindingConfigModel.getConfig(DataBindingConfigModel.java:518)com.htc.prism.feed.corridor.util.DMHelper.getOrElse(DMHelper.java:83)com.htc.prism.feed.corridor.util.DMHelper.getConfigString(DMHelper.java:100)com.htc.prism.feed.corridor.util.DMHelper.getNewsConfigLong(DMHelper.java:145)com.htc.prism.feed.corridor.event.PromotionService.getUserProfileTTL(PromotionService.java:374)com.htc.plugin.news.ProfileService.onHandleIntent(ProfileService.java:385)android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)android.os.Handler.dispatchMessage(Handler.java:102)android.os.Looper.loop(Looper.java:155)android.os.HandlerThread.run(HandlerThread.java:61)
D/ProfileService( 2257): installed component: 58
D/NewsPlugin( 2257): syncResult true
W/MessageQueue( 1411): Handler (com.htc.sense.hsp.opensense.social.b) {5d47192} sending message to a Handler on a dead thread
W/MessageQueue( 1411): java.lang.IllegalStateException: Handler (com.htc.sense.hsp.opensense.social.b) {5d47192} sending message to a Handler on a dead thread
W/MessageQueue( 1411): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:335)
W/MessageQueue( 1411): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 1411): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 1411): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 1411): 	at android.os.Handler.sendMessage(Handler.java:507)
W/MessageQueue( 1411): 	at android.os.Message.sendToTarget(Message.java:416)
W/MessageQueue( 1411): 	at com.htc.sense.hsp.opensense.social.SocialManagerService$a$a.b(Unknown Source)
W/MessageQueue( 1411): 	at com.htc.sense.hsp.opensense.social.SocialManagerService$a$a.a(Unknown Source)
W/MessageQueue( 1411): 	at com.htc.lib2.opensense.social.e$a.onTransact(Unknown Source)
W/MessageQueue( 1411): 	at android.os.Binder.execTransact(Binder.java:454)
I/ActivityManager(  975): Start proc com.htc.videocenter for content provider com.htc.videohub.ui/com.htc.videohub.engine.contentprovider.VideoHubContentProvider: pid=5730 uid=10091 gids={50091, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     (  471): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 172us total 11.085ms
I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 156us total 10.144ms
D/jxcore_app_log( 5677): JniHelper::setJavaVM(0xb7298b98), pthread_self() = -1202469976
D/JX-Cordova( 5677): jxcore cordova android initializing
I/art     (  471): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 157KB/4MB, paused 157us total 10.222ms
W/ResourceType( 5730): ResTable_typeSpec entry count inconsistent: given 1, previously 1426
W/ResourcesManager( 5730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ProfileService( 2257): TV favorate = 0,
,D/ProfileService( 2257): TV Reminder = 0
,W/jxcore-log( 5677): Initializing JXcore engine
W/jxcore-log( 5677): JXcore engine is ready
D/ProfileService( 2257): TV Share = 0
,W/jxcore-log( 5677): Starting JXcore engine
,I/ActivityManager(  975): Start proc com.htc.sense.socialplugins for content provider com.htc.sense.socialnetwork.facebook/com.htc.socialnetwork.facebook.FacebookDB: pid=5749 uid=10021 gids={50021, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 5423:com.htc.demoflopackageinstaller/u0a16 (adj 15): empty #17,
D/Process (  975): killProcessQuiet, pid=5423
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 5423
,D/LinkedIn( 5749): contentprovider oncreate getReadableDatabase
,D/Process (  975): killProcessQuiet, pid=5423
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  975): failed to open /acct/uid_10016/pid_5423/cgroup.procs: No such file or directory
,D/Process (  975): killProcessQuiet, pid=5441,
I/ActivityManager(  975): Killing 5441:com.htc.sdm/u0a82 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,W/jxcore-log( 5677): Platform android
W/jxcore-log( 5677): 
,W/jxcore-log( 5677): Process ARCH arm
W/jxcore-log( 5677): 
I/ActivityManager(  975): Recipient 5441
,I/jxcore-log( 5677): JXcore Cordova bridge is ready!
I/jxcore-log( 5677): 
,W/jxcore-log( 5677): JXcore engine is started
,D/Process (  975): killProcessQuiet, pid=5441
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  975): failed to open /acct/uid_10082/pid_5441/cgroup.procs: No such file or directory
,E/jxcore-log( 5677): >> HTC-HTC One_M8,
E/jxcore-log( 5677): 
,I/jxcore-log( 5677): Total memory 1912020992
I/jxcore-log( 5677): 
,I/jxcore-log( 5677): Free memory 143728640
I/jxcore-log( 5677): 
I/jxcore-log( 5677): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5677): 
I/jxcore-log( 5677): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5677): 
,I/jxcore-log( 5677): userPath [ 'www' ]
I/jxcore-log( 5677): 
,I/jxcore-log( 5677): Size 1080 1776
I/jxcore-log( 5677): 
,I/jxcore-log( 5677): Screen Brightness 142
I/jxcore-log( 5677): 
E/jxcore-log( 5677): Dummy Error Log.
E/jxcore-log( 5677): 
D/FacebookDB( 5749): You are not login Facebook
D/ProfileService( 2257): no access token
I/ActivityManager(  975): Killing 5465:com.htc.task/u0a72 (adj 15): empty #17
D/Process (  975): killProcessQuiet, pid=5465
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.removeContentProvider:10118 
E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
E/ServerCorridor( 2257): DMHelper: com.htc.cs.util.model.BaseModel.checkAvailable(BaseModel.java:312)com.htc.cs.dm.config.model.DataBindingConfigModel.getConfig(DataBindingConfigModel.java:518)com.htc.prism.feed.corridor.util.DMHelper.getOrElse(DMHelper.java:83)com.htc.prism.feed.corridor.util.DMHelper.getConfigString(DMHelper.java:100)com.htc.prism.feed.corridor.util.UtilHelper.getPromotionBaseUri(UtilHelper.java:720)com.htc.prism.feed.corridor.event.PromotionService.putUserProfile(PromotionService.java:65)com.htc.plugin.news.ProfileService.onHandleIntent(ProfileService.java:401)android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)android.os.Handler.dispatchMessage(Handler.java:102)android.os.Looper.loop(Looper.java:155)android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  975): Recipient 5465
,D/Process (  975): killProcessQuiet, pid=5465,
W/libprocessgroup(  975): failed to open /acct/uid_10072/pid_5465/cgroup.procs: No such file or directory
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/HtcTelephonyManager( 2257): wrong phone slot in non-dual projects,
,E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.,
,D/HtcTelephonyManager( 2257): wrong phone slot in non-dual projects,
,E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
,E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
E/ServerCorridor( 2257): DMHelper: com.htc.cs.util.model.BaseModel.checkAvailable(BaseModel.java:312)com.htc.cs.dm.config.model.DataBindingConfigModel.getConfig(DataBindingConfigModel.java:518)com.htc.prism.feed.corridor.util.DMHelper.getOrElse(DMHelper.java:83)com.htc.prism.feed.corridor.util.DMHelper.getConfigString(DMHelper.java:100)com.htc.prism.feed.corridor.util.UtilHelper.getHttpContentEncoding(UtilHelper.java:415)com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:111)com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:94)com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:240)com.htc.prism.feed.corridor.event.PromotionService.putUserProfile(PromotionService.java:74)com.htc.plugin.news.ProfileService.onHandleIntent(ProfileService.java:401)android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)android.os.Handler.dispatchMessage(Handler.java:102)android.os.Looper.loop(Looper.java:155)android.os.HandlerThread.run(HandlerThread.java:61)
E/ServerCorridor( 2257): DMHelper: java.lang.IllegalStateException: Model [app:prism_corridor] is not available.
,D/HtcTelephonyManager( 2257): wrong phone slot in non-dual projects
,D/libc    ( 2257): [NET] android_getaddrinfofornet+,hn 22(0x67656f2d707269),sn(),hints(known),family 0,flags 4,
D/libc    ( 2257): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 2257): [NET] android_getaddrinfofornet+,hn 22(0x67656f2d707269),sn(),hints(known),family 0,flags 1024
D/libc    ( 2257): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 2257): [NET] android_getaddrinfo_proxy+
,D/libc    ( 2257): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  460): [NET] android_getaddrinfofornet+,hn 22(0x67656f2d707269),sn(),hints(known),family 0,flags 1024
D/libc    (  460): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  460): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  460): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 2257): [NET] android_getaddrinfo_proxy-, NODATA
,E/ServerCorridor( 2257): BaseException: ServiceUnavailableException java.lang.Throwable: Unable to resolve host "geo-prism.htcsense.com": No address associated with hostname
W/System.err( 2257): com.htc.prism.feed.corridor.exceptions.ServiceUnavailableException: java.lang.Throwable: Unable to resolve host "geo-prism.htcsense.com": No address associated with hostname
W/System.err( 2257): 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:184)
W/System.err( 2257): 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:94)
W/System.err( 2257): 	at com.htc.prism.feed.corridor.RestClient.getString(RestClient.java:240)
W/System.err( 2257): 	at com.htc.prism.feed.corridor.event.PromotionService.putUserProfile(PromotionService.java:74)
,W/System.err( 2257): 	at com.htc.plugin.news.ProfileService.onHandleIntent(ProfileService.java:401)
W/System.err( 2257): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2257): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2257): 	at android.os.Looper.loop(Looper.java:155)
W/System.err( 2257): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2257): Caused by: java.lang.Throwable: Unable to resolve host "geo-prism.htcsense.com": No address associated with hostname
,W/System.err( 2257): 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
W/System.err( 2257): 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
W/System.err( 2257): 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
W/System.err( 2257): 	at com.android.okhttp.HostResolver$1.getAllByName(HostResolver.java:29)
W/System.err( 2257): 	at com.android.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:232)
W/System.err( 2257): 	at com.android.okhttp.internal.http.RouteSelector.next(RouteSelector.java:124)
,W/System.err( 2257): 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:272)
W/System.err( 2257): 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:211)
W/System.err( 2257): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:373)
W/System.err( 2257): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:106)
W/System.err( 2257): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.connect(DelegatingHttpsURLConnection.java:89)
W/System.err( 2257): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.connect(HttpsURLConnectionImpl.java:25)
,W/System.err( 2257): 	at com.htc.prism.feed.corridor.RestClient.sendHTTPRequest(RestClient.java:130)
W/System.err( 2257): 	... 8 more
,D/Process (  975): killProcessQuiet, pid=5283,
I/ActivityManager(  975): Killing 5283:com.google.android.gms:car/u0a25 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 5283
,D/Process (  975): killProcessQuiet, pid=5283
,W/libprocessgroup(  975): failed to open /acct/uid_10025/pid_5283/cgroup.procs: No such file or directory
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,I/jxcore-log( 5677): getBuffer is called!!!!
I/jxcore-log( 5677): 
,D/PMS     (  975): releaseHCC(3f4e627a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  975): releaseHCC(3abd4a2b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/MP-Decision( 2207): Update arg 1
,W/Atfwd_Sendcmd(  480): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/PackageManager(  975):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=4119, uid=10025, userID:0,
,I/PackageManager(  975):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=4119, uid=10025, userID:0
I/PackageManager(  975):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=4119, uid=10025, userID:0,
I/CheckinService( 4119): Done disabling old GoogleServicesFramework version,
,I/HtcModeClient( 3177): handler message = 4011,
,E/HtcModeClient( 3177): Check connection and retry 6 times.,
,I/ActivityManager(  975): Waited long enough for: ServiceRecord{178a5035 u0 com.htc.album/com.htc.mediamanager.providers.media.MMPScanService}
,D/UsbnetService(  975): BroadcastReceiver::onReceive+,
D/PMS     (  975): acquireWL(12f807f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 975 1000 null
D/UsbnetService(  975): onReceive BATTERY_CHANGED
I/BatteryService(  975): n_update end
,D/UsbnetService(  975):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/NotificationService(  975): plugged=true pluggin=true
D/UsbnetService(  975): BroadcastReceiver::onReceive-
,D/WifiController(  975): battery changed pluggedType: 2,
D/DotMatrix( 1196): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1120): closing low battery warning: level=100
D/DotMatrix( 1196): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1196): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  975): updateBatteryInfo
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  975): runPSCheck,
D/HtcPowerSaver(  975): Checking...,
,D/UsbnetService(  975): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  975): >> updateStatus
D/UsbnetService(  975): onReceive BATTERY_CHANGED
D/PMS     (  975): releaseWL(12f807f5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  975):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  975): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  975): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  975): << updateStatus
I/IntentController( 1120): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  975): acquireWL(286398a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 975 1000 null
,D/DotMatrix( 1196): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  975): n_update end
D/DotMatrix( 1196): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1196): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  975): releaseWL(286398a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  975): plugged=true pluggin=true
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true,
,D/WifiController(  975): battery changed pluggedType: 2
I/BatteryController( 1120): status:5 level:100 unsupport:false plugged:true
D/PowerUI ( 1120): closing low battery warning: level=100,
,D/PowerUI ( 1120): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  975): updateBatteryInfo
D/PMS     (  975): runPSCheck
D/HtcPowerSaver(  975): Checking...
I/HtcPowerSaver(  975): >> updateStatus
I/HtcPowerSaver(  975): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  975): << updateStatus
,I/ActivityManager(  975): Waited long enough for: ServiceRecord{1e82a183 u0 com.htc.musicenhancer/.EnhancerService}
,D/Process (  975): killProcessQuiet, pid=5100,
I/ActivityManager(  975): Killing 5100:com.google.android.talk/u0a120 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 5100,
,D/Process (  975): killProcessQuiet, pid=5100,
W/libprocessgroup(  975): failed to open /acct/uid_10120/pid_5100/cgroup.procs: No such file or directory
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,W/MediaManager( 4795): [DualLensScanUtil],	mmpCursor count is 0
,D/Process (  975): killProcessQuiet, pid=5223,
I/ActivityManager(  975): Killing 5223:com.android.settings/1000 (adj 15): empty #17,
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 5223,
,D/Process (  975): killProcessQuiet, pid=5223
W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_5223/cgroup.procs: No such file or directory,
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,D/PMS     (  975): releaseWL(28839b96): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null,
,D/BluetoothManagerService(  975): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  975): disable(): mBluetooth = null mBinding = false
D/WifiService(  975): New client listening to asynchronous messages
W/Settings:Agent(  975): MONITOR_LOG
W/Settings:Agent(  975): name: bluetooth_on,
,W/Settings:Agent(  975): value: 0
D/WifiService(  975): setWifiEnabled: false pid=5677, uid=10380
W/Settings:Agent(  975): >> traceCallingStack()
E/WifiService(  975): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  975): Process.myPid(): 975
I/WifiService(  975): isSprintWifiRestricted(): false
W/Settings:Agent(  975): Process.myTid(): 2093
I/WifiService(  975): isMdmWifiRestricted(): false
W/Settings:Agent(  975): Process.myUid(): 1000
W/Settings:Agent(  975): 
W/Settings:Agent(  975): 
W/System.err(  975): java.lang.Throwable: stack dump
W/System.err(  975): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  975): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56),
W/System.err(  975): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  975): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  975): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  975): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  975): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:379)
W/System.err(  975): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:625)
W/System.err(  975): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  975): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  975): 
W/Settings:Agent(  975): << traceCallingStack(): 2(ms)
D/BluetoothManagerService(  975): Message: MESSAGE_DISABLE
E/WifiTrafficPoller(  975): ADD_CLIENT: 7
D/WifiManager( 5677): setWifiEnabled: Base Package Name=com.example.hello, uid=10380
,W/Settings:Agent(  975): MONITOR_LOG,
W/Settings:Agent(  975): name: wifi_on
W/Settings:Agent(  975): value: 0
W/Settings:Agent(  975): >> traceCallingStack()
W/Settings:Agent(  975): Process.myPid(): 975
W/Settings:Agent(  975): Process.myTid(): 1301
W/Settings:Agent(  975): Process.myUid(): 1000
W/Settings:Agent(  975): 
W/Settings:Agent(  975): 
W/System.err(  975): java.lang.Throwable: stack dump
W/System.err(  975): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  975): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  975): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  975): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  975): ,	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  975): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  975): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:151)
W/System.err(  975): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:112)
W/System.err(  975): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1134)
W/System.err(  975): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  975): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  975): 
W/Settings:Agent(  975): << traceCallingStack(): 2(ms)
I/jxcore-log( 5677): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 5677): 
I/jxcore-log( 5677): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5677): 
,E/cutils-trace( 5816): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 5816): ====startRecUseTime====
,D/htc.customization.log.level( 5816):  is 
W/CustomizationLogLevel( 5816): Level value is invalid, use default level 2
,D/CustomizationManager( 5816):  Read ACC file spent 0.071 (s),
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__E11
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__203
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__405
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__304
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__016
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__A48
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__K18
D/CIDMapFileReader( 5816): Parsing tag item name = HTC__002
,V/CustomizationCIDLoader( 5816): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 5816): Parsing tag category name = system
I/CustomizationCIDLoader( 5816): Parsing tag category name = application
,I/CustomizationCIDLoader( 5816): Parsing tag category name = SettingsProvider
,I/CustomizationCIDLoader( 5816): Parsing tag category name = Settings
,I/CustomizationCIDLoader( 5816): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5816): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 5816): Parsing tag category name = ACC
,D/CustomizationManager( 5816):  Read CID file spent 0.130 (s)
,D/CustomizationManager( 5816):  All configurations done spent 0.131 (s)
,E/ActTriggerJNI( 5816): open library fail.
,D/PackageManager(  975): deletePackageAsUser: pkg=com.example.hello, pid=5816, uid=2000 userid=0
,I/ActivityManager(  975): Force stopping com.example.hello appid=10380 user=-1: uninstall pkg
D/Process (  975): killProcessQuiet, pid=5677
I/ActivityManager(  975): Killing 5677:com.example.hello/u0a380 (adj 0): stop com.example.hello
,D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6340 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6138 
,I/ActivityManager(  975): Recipient 5677,
I/WindowState(  975): WIN DEATH: Window{387d8394 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  975): Client connection lost with reason: 4
,W/PackageSettings(  975): Skipping PackageSetting{2d9ccf7f com.test.thalitest/10373} due to missing metadata
,W/ActivityManager(  975): Force removing ActivityRecord{3773de88 u0 com.example.hello/.MainActivity t27}: app died, no saved state
,E/MP-Decision( 2207): Update arg "0 380 380 380".,
E/MP-Decision( 2207): Update arg "0 400 400 400".
,W/ActivityManager(  975): Spurious death for ProcessRecord{18dab418 5677:com.example.hello/u0a380}, curProc for 5677: null,
,I/ActivityManager(  975): Force stopping com.example.hello appid=10380 user=0: pkg removed
,I/art     ( 5318): Explicit concurrent mark sweep GC freed 474(30KB) AllocSpace objects, 0(0B) LOS objects, 44% free, 2MB/4MB, paused 261us total 27.054ms
,D/DotMatrix( 1196): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/PMS     (  975): acquireWL(3d166456): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1695 10025 WorkSource{10025 com.google.android.gms}
D/DotMatrix( 1196): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/PMS     (  975): releaseWL(3d166456): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10025 com.google.android.gms}
D/DotMatrix( 1196): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/StatusBarManagerService(  975): setSystemUiVisibility(0x700)
I/Prism.ItemManager( 2257): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/StatusBarManagerService(  975): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/FeedHostManager( 1490): [onResume]
D/StatusBarManagerService(  975): hiding MENU key
I/FeedProviderManager( 1490): onResume
I/SocialFeedProvider( 1490): +onResume
I/SocialFeedProvider( 1490): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1490): -onResume
I/ConnectivityHelper( 1490): [getCurrentConnectionType] no network connection
D/PhoneApp( 1448): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1490): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1490): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 2257): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/[PluginManager]RegisterService( 1411): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
D/AccTypeManager( 1570): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/VoicemailCleanupService( 1546): Cleaning up data for package: com.example.hello
I/[PluginManager]RegisterService( 1411): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1570): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/art     (  975): Explicit concurrent mark sweep GC freed 17810(1260KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 16MB/25MB, paused 898us total 124.487ms,
I/art     (  975): WaitForGcToComplete blocked for 44.848ms for cause Explicit
,E/ExternalAccountType( 1570): Unsupported attribute readOnly
,I/InputMethodManagerService(  975): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  975): Got RemoteException sending setActive(false) notification to pid 5677 uid 10380
,D/StatusBarManagerService(  975): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  975): Enable input method client, pid=1490
,W/PackageManager(  975): Unable to load service info ResolveInfo{14bfb951 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
W/PackageManager(  975): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  975): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:470)
W/PackageManager(  975): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:326)
W/PackageManager(  975): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  975): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  975): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  975): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  975): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  975): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  975): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  975): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  975): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  975): 	,at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  975): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  975): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
W/PackageManager(  975): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
,D/Prism.PackageStateRece_( 1490): action: android.intent.action.PACKAGE_REMOVED
,D/StatusBarManagerService(  975): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  975): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  975): hiding MENU key
,I/ActivityManager(  975): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5846 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a,
,W/ResourcesManager(  975): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  975): Explicit concurrent mark sweep GC freed 8681(513KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 1.070ms total 133.489ms
,W/asset   (  975): Copying FileAsset 0xb8582008 (zip:/data/app/com.example.hello-1/base.apk:/resources.arsc) to buffer size 2472 to make it aligned.,
,D/JobSchedulerService(  975): Receieved: android.intent.action.PACKAGE_REMOVED,
,D/TaskPersister(  975): removeObsoleteFile: deleting file=27_task.xml,
,W/ContextImpl( 5846): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
,I/ActivityManager(  975): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=5866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=armeabi-v7a
,D/Process (  975): killProcessQuiet, pid=5244
I/ActivityManager(  975): Killing 5244:com.android.vending/u0a75 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 5244
,D/Process (  975): killProcessQuiet, pid=5244
,D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  975): failed to open /acct/uid_10075/pid_5244/cgroup.procs: No such file or directory
,D/HtcFingerPrintQuickLaunchProvider( 5866): -onCreate()
,V/Settings:HtcSettingsApplication( 5866): [5866/5866] onCreate(),
,I/ActivityManager(  975): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5889 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/Process (  975): killProcessQuiet, pid=5318,
I/ActivityManager(  975): Killing 5318:com.google.android.googlequicksearchbox:search/u0a89 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
,I/ActivityManager(  975): Recipient 5318,
,E/Settings:HtcWrapHeaderInfo( 5866): no such activity!,
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5866): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5866): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5866): isSupportMusicChannel(): false
,D/Process (  975): killProcessQuiet, pid=5318
,D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  975): failed to open /acct/uid_10089/pid_5318/cgroup.procs: No such file or directory
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]support         :false
,I/ActivityManager(  975): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 5866): isSupportVoWifi: null
E/ActivityThread( 5866): Failed to find provider info for com.htc.vowifi
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 5866): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 5866): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 5866): isSupportMusicChannel(): false,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]hasNavigationBar:true,
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 5866): [supportHomeButton]support         :false
,I/ActivityManager(  975): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5866): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 5866): isSupportVoWifi: null
,I/PackageManager(  975):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=5889, uid=10075, userID:0
,D/Finsky  ( 5889): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5889): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,W/OpenGLRenderer( 1490): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,I/ActivityManager(  975): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5929 uid=10025 gids={50025, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 5889): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5889): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteDatabase( 5889): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 5889): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 5889): ,	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 5889): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5889): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5889): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 5889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5889): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 5889): Process: com.android.vending, PID: 5889
E/AndroidRuntime( 5889): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5889): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 5889): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 5889): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 5889): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5889): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5889): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 5889): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  975): App crashed! Process: com.android.vending
I/PackageManager(  975):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=5889, uid=10075, userID:0
E/DropBoxManagerService(  975): Can't write: system_app_crash
E/DropBoxManagerService(  975): java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  975): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  975): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  975): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  975): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  975): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  975): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  975): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  975): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  975): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  975): 	... 5 more
W/ResourcesManager( 5929): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5929): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteDatabase( 5889): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 5889): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 5889): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5889): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5889): 	at java.lang.Thread.run(Thread.java:818)
D/StatusBarManagerService(  975): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  975): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  975): hiding MENU key
E/AndroidRuntime_2_crash( 5889): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 5889): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 5889): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 5889): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 5889): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 5889): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime_2_crash( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 5889): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 5889): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 5889): 	... 4 more
,E/SQLiteDatabase( 5889): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 5889): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 5889): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 5889): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5889): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5889): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 5889): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 5889): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 5889): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 5889): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 5889): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 5889): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:237)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:218)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 5889): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime_3_crash( 5889): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 5889): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 5889): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 5889): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 5889): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 5889): 	... 4 more
I/MultiDex( 5929): VM with version 2.1.0 has multidex support
I/MultiDex( 5929): install
I/MultiDex( 5929): VM has multidex support, MultiDex support library is disabled.
D/Process (  975): killProcessQuiet, pid=5396
I/ActivityManager(  975): Killing 5396:com.google.android.apps.plus/u0a176 (adj 15): empty #17
D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.trimApplications:19085 
I/ActivityManager(  975): Recipient 5396
,D/Process (  975): killProcessQuiet, pid=5396
,W/libprocessgroup(  975): failed to open /acct/uid_10176/pid_5396/cgroup.procs: No such file or directory,
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
,V/JNIHelp ( 5929): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 5929): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5929): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@436400c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5929): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 5929): Failed to open lock file
W/NativeLibraryUtils( 5929): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5929): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 5929): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 5929): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 5929): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 5929): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5929): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5929): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 5929): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 5929): 	... 3 more
E/SQLiteLog( 1758): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1758): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0xb8407340
,E/AndroidRuntime( 1758): FATAL EXCEPTION: main
E/AndroidRuntime( 1758): Process: com.google.process.gapps, PID: 1758
E/AndroidRuntime( 1758): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1758): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.main(ActivityThread.java:5696)
E/AndroidRuntime( 1758): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1758): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1028)
E/AndroidRuntime( 1758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:823)
E/AndroidRuntime( 1758): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:764)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1758): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1758): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1758): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1758): 	... 9 more
E/ActivityManager(  975): App crashed! Process: com.google.process.gapps
,E/DropBoxManagerService(  975): Can't write: system_app_crash
E/DropBoxManagerService(  975): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  975): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  975): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  975): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  975): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  975): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  975): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12635)
E/DropBoxManagerService(  975): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  975): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  975): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  975): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  975): 	... 5 more
,I/ActivityManager(  975): Killing 4625:com.google.android.gms.wearable/u0a25 (adj 15): empty #17
D/Process (  975): killProcessQuiet, pid=4625
,D/Process (  975): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18815 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18658 
,I/ActivityManager(  975): Recipient 4625,
,D/Process (  975): killProcessQuiet, pid=4625
D/Process (  975): com.android.server.am.ActivityManagerService.appDiedLocked:5092 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1212 android.os.BinderProxy.sendDeathNotice:559 
W/libprocessgroup(  975): failed to open /acct/uid_10025/pid_4625/cgroup.procs: No such file or directory
,W/FileUtils( 5929): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system),
V/Finsky  ( 5889): [1] GearheadStateMonitor.onReady: sIsProjecting:false
W/ServiceConnection( 5929): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5929): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 5929): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 5929): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1088)
W/ServiceConnection( 5929): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
W/ServiceConnection( 5929): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 5929): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 5929): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 5929): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 5929): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 5929): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 5929): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 5929): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 5929): 	... 7 more
,I/Prism.ItemManager( 1490): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true,
,I/Prism.ItemManager( 1490): loadItems() com.htc.launcher.pageview.WidgetManager@1b7c46fa +,
I/Prism.WidgetManager( 1490): onLoadItems() +,
,W/ResourcesManager( 1490): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Prism.ItemManager( 2257): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
D/PMS     (  975): acquireWL(165da37d): PARTIAL_WAKE_LOCK  *alarm* 0x1 975 1000 WorkSource{10075}
I/Prism.ItemManager( 2257): loadItems() com.htc.launcher.pageview.WidgetManager@4c10eca +
V/AlarmManager(  975): sending alarm PendingIntent{3d5ce272: PendingIntentRecord{3e5059f com.android.vending startService}}, i=null, t=0, cnt=1, w=1447834376248, Int=0
I/Prism.WidgetManager( 2257): onLoadItems() +
D/PMS     (  975): releaseWL(165da37d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10075}
D/Finsky  ( 5889): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ResourcesManager( 2257): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/Prism.WidgetManager( 1490): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1490): onLoadItems() -
I/Prism.ItemManager( 1490): loadItems() com.htc.launcher.pageview.WidgetManager@1b7c46fa -
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
W/ResourcesManager( 2257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed,
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
E/Prism.WidgetManager( 2257): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 2257): onLoadItems() -
I/Prism.ItemManager( 2257): loadItems() com.htc.launcher.pageview.WidgetManager@4c10eca -
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted,
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
,E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
,E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
,E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8,
E/qdoverlay(  363): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
,E/qdoverlay(  363): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  363): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdhwcomposer(  363): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  363): hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=16 dpy=0 numHwLayers=9
E/qdoverlay(  363): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  363): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
E/qdhwcomposer(  363): hwc_set_primary: display commit fail for 0 dpy!
,E/qdoverlay(  363): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  363): MdpCtrl close error in unset
,D/PhoneApp( 1448): EVENT_QUERY_MO_PACKAGES,
D/PhoneApp( 1448): -- N1 =0
D/PhoneApp( 1448): -- N2 =0
D/PhoneApp( 1448): -- N3 =0

```
