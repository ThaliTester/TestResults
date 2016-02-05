#### Test 5753124374916c2_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
--------- beginning of /dev/log/main
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
I/RemoteViews( 1115): com.htc.updater (true,33751552)
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=104 rxSum=85} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20952 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20953 delay=15s
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41cdc7e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.htc.updater 2 9 1 10
I/RemoteViews( 1115): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e9cfb0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.htc.updater 1 7 0 10
I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4057 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(42744588): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): releaseWL(42744588): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(42746908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42747d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42747d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42746908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4274a0a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4274a0a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42751de0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42751de0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 4057): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b4bdb0 -
I/ActivityManager(  907): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4079 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
V/AlarmManager(  907): sending alarm PendingIntent{425c1010: PendingIntentRecord{42625058 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454681654541, Int=0
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  907): acquireWL(427603a8): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(427603a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  907): killProcessQuiet, pid=3003
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3003:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Recipient 3003
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
I/ImageRamCache( 4079): create image Cache, size: 31457280.
I/ImageRamCache( 4079): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4079): create image Cache, size: 12582912.
I/IcingCorporaProvider( 2849): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/FeedSettings( 4079): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4079): GroupBudget 0.500000 0.380000
I/FeedSettings( 4079): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4079): changeLocale(): en_GB
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/Prism.AllAppsOptionsMa_( 4079): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4079): loadGridSize() with Alternative
D/PMS     (  907): acquireWL(427b9930): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1241): -- N1 =0
D/PhoneApp( 1241): -- N2 =0
D/PhoneApp( 1241): -- N3 =0
I/SocialManager[SocialBiLogHelper]( 4079): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4079): last commit ulog time 1454578885926
I/SocialManager[SocialBiLogHelper]( 4079): do commit ulog
I/ActivityManager(  907): Delaying start of: ServiceRecord{427bd248 u0 com.htc.launcher/com.htc.BiLogClient.BiLogUploadService}
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/AlarmManager(  907): sending alarm PendingIntent{41b2f7f8: PendingIntentRecord{424b0398 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59948, Int=0
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/cutils-trace( 4071): Error opening trace file: No such file or directory (2)
D/PMS     (  907): releaseWL(427b9930): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(427c1f70): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(427c1f70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(427c4108): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
V/SocialManagerService( 1320): getDataSources
I/SocialManagerService( 1320): plugin added: com.facebook.auth.login
I/SocialManagerService( 1320): plugin added: com.twitter.android.auth.login
I/SocialManagerService( 1320): plugin added: com.htc.linkedin
I/SocialManagerService( 1320): plugin added: com.htc.venuesrecommend
I/SocialManagerService( 1320): plugin added: com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1320): plugin added: com.htc.drive.activator
I/SocialManagerService( 1320): plugin added: com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1320): plugin added: com.htc.opensense.htcnews
I/SocialManagerService( 1320): plugin added: com.google
I/SocialManagerService( 1320): device total memory: 1873M
I/SocialManagerService( 1320): groupAccounts
D/PMS     (  907): releaseWL(427c4108): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(427bd5d0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
E/SocialManagerService( 1320): cannot find this plugin service: com.htc.drive.activator
E/SocialManagerService( 1320): error when get process name! process name is null!
E/SocialManagerService( 1320): skip binding the plugin without process namecom.htc.drive.activator
I/SocialManagerService( 1320): add com.facebook.auth.login to pending queue!
I/SocialManagerService( 1320): add com.htc.linkedin to pending queue!
I/SocialManagerService( 1320): add com.twitter.android.auth.login to pending queue!
I/SocialManagerService( 1320): add com.htc.venuesrecommend to pending queue!
I/SocialManagerService( 1320): add com.htc.sense.socialnetwork.instagram to pending queue!
I/SocialManagerService( 1320): add com.htc.socialnetwork.rss.octopus to pending queue!
I/SocialManagerService( 1320): add com.htc.opensense.htcnews to pending queue!
I/SocialManagerService( 1320): add com.google to pending queue!
I/SocialManagerService( 1320): consume pending plugin session
I/SocialManagerService( 1320): add com.facebook.auth.login to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.facebook.auth.login
I/SocialManagerService( 1320): com.facebook.auth.login connecting, adding msg, has message?true
D/PMS     (  907): releaseWL(427bd5d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/SocialManagerService( 1320): add com.htc.linkedin to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.htc.linkedin
I/SocialManagerService( 1320): com.htc.linkedin connecting, adding msg, has message?true
I/ActivityManager(  907): Start proc com.htc.sense.socialplugins for service com.htc.sense.socialnetwork.facebook/com.htc.plugin.facebook.FacebookSocialPluginService: pid=4116 uid=10025 gids={50025, 3003, 5012, 1028, 1015, 1023}
I/SocialManagerService( 1320): add com.twitter.android.auth.login to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.twitter.android.auth.login
I/SocialManagerService( 1320): com.twitter.android.auth.login connecting, adding msg, has message?true
D/PMS     (  907): acquireWL(42786288): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4071): ====startRecUseTime====
D/htc.customization.log.level( 4071):  is 
W/CustomizationLogLevel( 4071): Level value is invalid, use default level 2
I/SocialManagerService( 1320): add com.htc.venuesrecommend to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.htc.venuesrecommend
I/SocialManagerService( 1320): com.htc.venuesrecommend connecting, adding msg, has message?true
I/SocialManagerService( 1320): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1320): add com.htc.socialnetwork.rss.octopus to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1320): com.htc.socialnetwork.rss.octopus connecting, adding msg, has message?true
I/SocialManagerService( 1320): add com.htc.opensense.htcnews to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.htc.opensense.htcnews
I/SocialManagerService( 1320): com.htc.opensense.htcnews connecting, adding msg, has message?true
D/LocationSocialPlugin( 4079): onBind
I/SocialManagerService( 1320): skip to add com.google, plugin per process full!
I/SocialManagerService( 1320): com.htc.venuesrecommend connected, removed msg, has message?false
D/LocationIdentityProvider( 4079): is_approved false
D/LocationSocialPlugin( 4079): account null
D/LocationSocialPlugin( 4079): URI:intent:#Intent;component=com.htc.launcher/com.htc.venuesrecommend.AuthActivity;end
D/SocialManagerService( 1320): handling plugin: com.htc.venuesrecommend set result in bg
I/SocialManagerService( 1320): remove account type: com.htc.venuesrecommend from process map!
I/SocialManagerService( 1320): com.htc.socialnetwork.rss.octopus connected, removed msg, has message?false
D/StreamPluginService( 4079): getDataSources start
V/SocialManagerService( 1320): on plugin completed! plugin session type com.htc.venuesrecommend
I/SocialManagerService( 1320): consume pending plugin session
I/SocialManagerService( 1320): skip to add com.google, plugin per process full!
I/SocialManagerService( 1320): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/PMS     (  907): releaseWL(42786288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/SocialManagerService( 1320): handling plugin: com.htc.socialnetwork.rss.octopus set result in bg
I/SocialManagerService( 1320): remove account type: com.htc.socialnetwork.rss.octopus from process map!
V/SocialManagerService( 1320): on plugin completed! plugin session type com.htc.socialnetwork.rss.octopus
I/SocialManagerService( 1320): consume pending plugin session
I/SocialManagerService( 1320): skip to add com.google, plugin per process full!
I/SocialManagerService( 1320): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
I/SocialManagerService( 1320): com.htc.opensense.htcnews connected, removed msg, has message?false
D/PMS     (  907): acquireWL(4273f018): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/SocialManagerService( 1320): handling plugin: com.htc.opensense.htcnews set result in bg
I/SocialManagerService( 1320): remove account type: com.htc.opensense.htcnews from process map!
I/SocialManagerService( 1320): remove process: com.htc.sense.news from process map!
V/SocialManagerService( 1320): on plugin completed! plugin session type com.htc.opensense.htcnews
I/SocialManagerService( 1320): consume pending plugin session
I/SocialManagerService( 1320): skip to add com.google, plugin per process full!
I/SocialManagerService( 1320): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
D/PMS     (  907): releaseWL(4273f018): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/LinkedIn( 4116): contentprovider oncreate getReadableDatabase
D/PMS     (  907): acquireWL(4273ed80): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4273ed80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/SocialManagerService( 1320): com.facebook.auth.login connected, removed msg, has message?false
D/PMS     (  907): acquireWL(42734520): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/LinkedIn( 4116): service onBind
D/PMS     (  907): releaseWL(42734520): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/SocialManagerService( 1320): com.htc.linkedin connected, removed msg, has message?false
D/g       ( 4116): get htcisdemo: false
D/FacebookSocialPluginService( 4116): get htcisdemo: false
D/Facebook_Session( 4116): MSG_QUERY_ACCOUNT
D/Facebook_Session( 4116): queryAccount
D/Facebook_Session( 4116): queryAccount enter lock
D/SocialManagerService( 1320): handling plugin: com.htc.linkedin set result in bg
D/Facebook_Session( 4116): Facebook Session created
D/Facebook_Session( 4116): queryAccount
D/CustomizationManager( 4071):  Read ACC file spent 0.087 (s)
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__016
I/SocialManagerService( 1320): remove account type: com.htc.linkedin from process map!
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4071): Parsing tag item name = HTC__031
I/SocialManagerService( 1320): com.twitter.android.auth.login connected, removed msg, has message?false
V/CustomizationCIDLoader( 4071): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4071): Parsing tag category name = system
I/CustomizationCIDLoader( 4071): Parsing tag category name = application
V/SocialManagerService( 1320): on plugin completed! plugin session type com.htc.linkedin
I/SocialManagerService( 1320): consume pending plugin session
I/CustomizationCIDLoader( 4071): Parsing tag category name = SettingsProvider
I/SocialManagerService( 1320): add com.google to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.google
I/CustomizationCIDLoader( 4071): Parsing tag category name = AutomotiveHome
I/SocialManagerService( 1320): com.google connecting, adding msg, has message?true
I/CustomizationCIDLoader( 4071): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4071): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4071): Parsing tag category name = Settings
D/CustomizationManager( 4071):  Read CID file spent 0.135 (s)
D/CustomizationManager( 4071):  All configurations done spent 0.135 (s)
I/SocialManagerService( 1320): skip to add com.htc.sense.socialnetwork.instagram, plugin per process full!
W/HtcNativeFlag( 4071): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4071): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4071): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4071): Fail to get flag for type 'language', use default value: -1
D/PMS     (  907): acquireWL(426fe2e0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
D/Facebook_Session( 4116): Query Facebook account complete
D/Facebook_Session( 4116): queryAccount enter lock
I/HtcModeClient( 1499): handler message = 4011
E/HtcModeClient( 1499): Check connection and retry 6 times.
D/GooglePlusSocialPluginService( 4116): Bind
I/SocialManagerService( 1320): com.google connected, removed msg, has message?false
D/Facebook_Session( 4116): Query Facebook account complete
I/GooglePlusSocialPluginService( 4116): getDataSources start
D/PMS     (  907): releaseWL(426fe2e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/SocialManagerService( 1320): handling plugin: com.facebook.auth.login set result in bg
I/SocialManagerService( 1320): remove account type: com.facebook.auth.login from process map!
I/GooglePlusSocialPluginService( 4116): getDataSources end
V/SocialManagerService( 1320): on plugin completed! plugin session type com.facebook.auth.login
I/SocialManagerService( 1320): consume pending plugin session
I/SocialManagerService( 1320): add com.htc.sense.socialnetwork.instagram to process map!
V/SocialManagerService( 1320): initiating bind to plugin type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1320): com.htc.sense.socialnetwork.instagram connecting, adding msg, has message?true
D/SocialManagerService( 1320): handling plugin: com.google set result in bg
I/SocialManagerService( 1320): remove account type: com.google from process map!
V/SocialManagerService( 1320): on plugin completed! plugin session type com.google
D/SocialManagerService( 1320): handling plugin: com.twitter.android.auth.login set result in bg
I/SocialManagerService( 1320): remove account type: com.twitter.android.auth.login from process map!
V/SocialManagerService( 1320): on plugin completed! plugin session type com.twitter.android.auth.login
I/SocialManagerService( 1320): com.htc.sense.socialnetwork.instagram connected, removed msg, has message?false
D/GooglePlusSocialPluginService( 4116): Unbind
D/SocialManagerService( 1320): handling plugin: com.htc.sense.socialnetwork.instagram set result in bg
I/SocialManagerService( 1320): remove account type: com.htc.sense.socialnetwork.instagram from process map!
I/SocialManagerService( 1320): remove process: com.htc.sense.socialplugins from process map!
V/SocialManagerService( 1320): on plugin completed! plugin session type com.htc.sense.socialnetwork.instagram
I/SocialManagerService( 1320): onSessionCompleted
D/Process (  907): killProcessQuiet, pid=3673
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3673:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/SocialManager[SocialBiLogHelper]( 4079): social manager disconnect
I/IcingCorporaProvider( 2849): UpdateCorporaTask done [took 485 ms] updated apps [took 485 ms] 
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4071
I/ActivityManager(  907): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4143 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  907): killProcessQuiet, pid=3812
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3812:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3812
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Recipient 3673
I/ImageRamCache( 4143): create image Cache, size: 31457280.
I/ImageRamCache( 4143): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4143): create image Cache, size: 12582912.
I/FeedSettings( 4143): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4143): GroupBudget 0.500000 0.380000
I/FeedSettings( 4143): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4143): changeLocale(): en_GB
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Prism.AllAppsOptionsMa_( 4143): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4143): loadGridSize() with Alternative
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3837:com.android.settings/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3837
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Recipient 3837
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4158 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(425ec490): PARTIAL_WAKE_LOCK  AsyncService 0x1 4158 10160 null
,D/PMS     (  907): releaseWL(425ec490): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425e9d10): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4158 10160 null
,D/Process (  907): killProcessQuiet, pid=3747
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4179 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3747:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,D/PMS     (  907): acquireWL(423e64d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4158 10160 null
,D/PMS     (  907): releaseWL(425e9d10): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  907): Recipient 3747
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4158/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4158/10160)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/SensorManager(  907): mEventCount = 450
,D/PMS     (  907): releaseWL(423e64d0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/HtcFingerPrintQuickLaunchProvider( 4179): -onCreate()
,V/Settings:HtcSettingsApplication( 4179): [4179/4179] onCreate()
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4196 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3461
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3461:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3461
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/Settings:HtcWirelessFeatureFlags( 4179): id/is att sku: 99/false
,D/Process (  907): killProcessQuiet, pid=3854
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4196, uid=10074, userID:0
I/ActivityManager(  907): Killing 3854:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,W/SystemReader( 4179): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/ActivityManager(  907): Recipient 3854
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 4196): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4196/10074)
W/SystemReader( 4179): Cannot find support_harman, use default value instead
W/SystemReader( 4179): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4179): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4179): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4179): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4179): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]support         :false
,W/FingerprintManager( 4179): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4179): isSupportVoWifi: null
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4179): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4196/10074)
,D/Finsky  ( 4196): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4196): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4196): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 4196): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4196): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4196): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4196, uid=10074, userID:0
,D/Ads     ( 4196): Skipping gmscore version check
,D/Finsky  ( 4196): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4196): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4196): [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,W/dalvikvm( 4196): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4196): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  907): killProcessQuiet, pid=3473
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3473:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3473
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4179): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4179): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4179): isSupportMusicChannel(): false
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4179): [supportHomeButton]support         :false
,D/PackageBroadcastService( 2193): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4237 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/FingerprintManager( 4179): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 4179): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4179): Failed to find provider info for com.htc.vowifi
D/PMS     (  907): acquireWL(4256a7a0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4256a7a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423751e0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2193): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2193): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2193): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2193): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2193): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2193): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2193): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/Babel   ( 4237): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4237): MmsConfig.loadMmsSettings
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2193, uid=10029, userID:0
,W/dalvikvm( 4237): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4237): VFY: unable to resolve instance field 36
,W/dalvikvm( 4237): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/PeopleDatabaseHelper( 2193): cleanUpNonGplusAccounts done.
,V/JNIHelp ( 4237): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 2160): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2160): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/Settings( 4237): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel   ( 4237): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4237): MmsConfig.loadFromDatabase
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4237, uid=10111, userID:0
E/Babel   ( 4237): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4237): MmsConfig.loadFromResources
E/Babel   ( 4237): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4237): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4237, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4237, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4237, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4237, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4237, uid=10111, userID:0
D/PMS     (  907): acquireWL(426092f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4237 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4237): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  907): releaseWL(426092f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(423a8648): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4237 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(423a8648): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3507:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3507
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4275a560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4275a560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4273f0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(4273f0e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/GCM     ( 2878): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  907): acquireWL(4270b110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
D/PMS     (  907): releaseWL(4270b110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2193/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
D/PMS     (  907): acquireWL(426c49e8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Recipient 3507
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(426a6398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/SQLiteConnectionPool( 2193): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(426a6398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(41f866f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(41f866f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42394d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
D/PMS     (  907): releaseWL(42394d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(423761d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
D/PMS     (  907): releaseWL(426c49e8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(423761d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(4262ed40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4283 uid=10041 gids={50041}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=3968
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/GCM     ( 2193): Message from null null
,E/GCM     ( 2193): Dropping message from null
D/PMS     (  907): releaseWL(4262ed40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Killing 3968:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
I/ActivityManager(  907): Recipient 3968
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4296 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(42351528): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4296 10071 null
,D/PMS     (  907): acquireWL(4235b7b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4296 10071 null
,D/Process (  907): killProcessQuiet, pid=4008
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4008:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/PMS     (  907): releaseWL(42351528): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
I/ActivityManager(  907): Recipient 4008
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/TodoTaskNotifyService( 4296): java.lang.NullPointerException
W/System.err( 4296): java.lang.NullPointerException
W/System.err( 4296): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4296): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4296): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4296): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4296): stopSelfResult true
D/PMS     (  907): releaseWL(4235b7b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(4278d7e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4237 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(4278d7e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4237/10111)
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 2878): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2878): [NET] getaddrinfo-,err=8
D/libc    ( 2878): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2878): [NET] getaddrinfo-, 1
,D/libc    ( 2878): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c544 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2878): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2878): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2878): [NET] getaddrinfo-,err=8
,I/Icing   ( 2193): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2193): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(423751e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 2878): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2878): [NET] getaddrinfo-,err=8
D/libc    ( 2878): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2878): [NET] getaddrinfo-,err=8
,I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  907): Done.
,E/MDM     ( 1220): [107] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ConnectivityService(  907): Setting timer for 720seconds
,D/LocationInitializer( 2193): Restart initialization of location
,D/AuthorizationBluetoothService( 2878): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2878): Proximity feature is not enabled.
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
D/PMS     (  907): acquireWL(42542518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42542518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(4265d720): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4296 10071 null
,D/PMS     (  907): acquireWL(426f8c00): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4296 10071 null
,D/PMS     (  907): releaseWL(4265d720): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,E/TodoTaskNotifyService( 4296): java.lang.NullPointerException
,W/System.err( 4296): java.lang.NullPointerException
W/System.err( 4296): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4296): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4296): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4296): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4296): stopSelfResult true
D/PMS     (  907): releaseWL(426f8c00): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(4265f808): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4296 10071 null
E/TodoTaskNotifyService( 4296): java.lang.NullPointerException
W/System.err( 4296): java.lang.NullPointerException
W/System.err( 4296): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4296): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4296): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4296): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): acquireWL(426a1630): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4296 10071 null
D/PMS     (  907): releaseWL(4265f808): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(426a1630): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
W/NotifyReceiver( 4296): stopSelfResult true
I/WSP     ( 1320): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1320): Weather sync is On
,I/WSP     ( 1320): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Feb 05 16:14:17 CET 2016
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2193/10029)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.gcm.gmsproc.GmsAutoStarter
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/PMS     (  907): acquireWL(42669d48): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1320 10055 null
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4237): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 4237): [NET] getaddrinfo-,err=8
D/libc    ( 4237): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 4237): [NET] getaddrinfo-, 1
,D/libc    ( 4237): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7857 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 140
D/libc    (  364): [NET]res_nsend:resplen=86
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4237): [NET] getaddrinfo_proxy-, success
,D/libc    ( 4237): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 4237): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(4260ad30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4260ad30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,V/AlarmManager(  907): sending alarm PendingIntent{4247bf90: PendingIntentRecord{426b0768 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454681658061, Int=0
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [18][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:161, mTXpacketCount:116, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  907): acquireWL(42649b50): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4237 10111 null
,I/Babel   ( 4237): Account registration complete:Redacted-21
,D/PMS     (  907): releaseWL(42649b50): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/GAV2    ( 4057): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  907): sending alarm PendingIntent{425bb518: PendingIntentRecord{426bfb98 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454681659820, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42566138: PendingIntentRecord{425310c8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454681659872, Int=0
,I/iu.UploadsManager( 2193): End new media; added: 0, uploading: 0, time: 59 ms
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 7 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4237): Thread[GAThread,5,main]: No campaign data found.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2193, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2193, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2193, uid=10029, userID:0
I/CheckinService( 2193): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 2878): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): acquireWL(42613550): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4237 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  907): releaseWL(42613550): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3913
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3913:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Recipient 3913
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2849): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(422c5000): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(422c5000): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4264cdc8): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4264cdc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4258d040): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4258d040): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4269d658): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4269d658): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427b3c20): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427b3c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4274bd60): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4274bd60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42633880): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42633880): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426dc960): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426dc960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2849): UpdateCorporaTask done [took 285 ms] updated apps [took 285 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(42650d48): PARTIAL_WAKE_LOCK  AsyncService 0x1 4158 10160 null
,D/PMS     (  907): releaseWL(42650d48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2193): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2193): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): acquireWL(427b0d10): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2193): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/Icing   ( 2193): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2193): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2193): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(427b0d10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 8 times.
,D/TodoTaskshortcut( 4296): update TASK shortcut>
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425f37a0 u0 com.htc.musicenhancer/.EnhancerService},
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(426d5c18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42496d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(426d5c18): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42496d28): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  907): acquireWL(42757ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/PMS     (  907): acquireWL(427b4d38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3893 10154 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/ContextImpl( 3893): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42757ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 3893): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/MusicLeanback( 3893): Conditions not met for autocaching.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3893, uid=10154, userID:0
,D/PMS     (  907): releaseWL(427b4d38): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,I/MusicLeanback( 3893): Stop autocaching.
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(427be4b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(427be4b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42790e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42790e38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,W/MediaManager( 3873): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4362 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4362): Loading default preferences
,W/Resources( 4362): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4362): Overriding preferences with custom values
,D/SyncApplication( 4362): Updating preferences succeeded
,E/SyncApplication( 4362): Application created.
D/VolumeInfo( 4362): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4362): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4362): Found 0 mount point(s)
V/VolumeInfo( 4362): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4362): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4362): getNewCalendarAuthority()...
,D/VolumeInfo( 4362): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4362): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4362): enableAppOperation()+
,D/SyncApplication( 4362): enableAppOperation()-
D/HTCUtilities( 4362): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4362, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4362, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4362): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4362): isNeorSinged() return false
,D/CDMountReceiver( 4362): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4362): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4362): enable CD Auto-mount: true
,D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4362): enable auto-mount
,D/HTCUtilities( 4362): enable auto-mount
I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/Process (  907): killProcessQuiet, pid=3950
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
D/PMS     (  907): releaseWL(422ff300): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
I/ActivityManager(  907): Killing 3950:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3950
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c5b4a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 3 15 3 11
I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c5a488 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 7 2 16
D/PMS     (  907): releaseWL(42669d48): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(42613e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42613e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  907): runPSCheck
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=124 rxSum=103} preTxRxSum={txSum=104 rxSum=85}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20953 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20954 delay=15s
D/PMS     (  907): acquireWL(425c5960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42220d10: PendingIntentRecord{425c43f8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=74528, Int=0
D/PMS     (  907): releaseWL(425c5960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/CalendarProvider2( 1499): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1499): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 9 times.
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4385 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4385): onCreate
D/ProviderChangeReceiver( 4385): ---------------------------------------------------
,D/ProviderChangeReceiver( 4385): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4385): start to updateAlertNotification!
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4399 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=4028
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4028:com.htc.updater/u0a85 (adj 15): empty #17
,D/AlertService( 4385): No fired or scheduled alerts
,D/HtcAlertUtils( 4385): -- cancelReminderNotification --
,D/HtcAlertUtils( 4385): broadcastExistReminder!
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  907): Recipient 4028
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4399): [4399/4399] onCreate()
W/ContextImpl( 4399): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4079
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4079:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4079
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 600
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Finsky  ( 4196): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4196): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  907): acquireWL(41d6fb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{424104e0: PendingIntentRecord{426bee48 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454681671841, Int=0
,D/PMS     (  907): releaseWL(41d6fb80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4196/10074)
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4196): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4196): [NET] getaddrinfo-,err=8
,D/libc    ( 4196): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4196): [NET] getaddrinfo-, 1
D/libc    ( 4196): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8db4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4196): [NET] getaddrinfo_proxy-, success
,I/global  ( 4196): call createSocket() return a new socket.
D/libc    ( 4196): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4196): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4196): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4196): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4196): untagSocket(69) failed with errno -22
,D/Finsky  ( 4196): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4196): untagSocket(69) failed with errno -22
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=3 [30][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:195, mTXpacketCount:161, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4196): untagSocket(69) failed with errno -22
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4196/10074)
,D/Finsky  ( 4196): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  907): acquireWL(4266ea90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{42687438: PendingIntentRecord{42595660 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454681674258, Int=0
,D/PMS     (  907): acquireWL(4275e950): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4196 10074 null
,D/PMS     (  907): releaseWL(4266ea90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4196): [449] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/WearableService( 1220): callingUid 10029, callindPid: 1220
D/DeviceConnectionService( 1220): client connected with version: 8296000
D/Finsky  ( 4196): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4196): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2878): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4196): [NET] getaddrinfo-,err=8
D/libc    ( 4196): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4196): [NET] getaddrinfo-, 1
,D/libc    ( 4196): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =8dc4 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 107
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4196): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  907): releaseWL(4275e950): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 10 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=7 [53][4][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4116
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4116:com.htc.sense.socialplugins/u0a25 (adj 15): empty #17
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1499): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1499): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1499): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1499): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1499): service - mHandler: update timezone
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz: ,
,D/AutoSetting( 1499): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1499): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1499): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1545): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41edc450 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 7 2 11
,I/ActivityManager(  907): Recipient 4116
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 11 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(4239d358): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
I/SensorManager(  907): mEventCount = 750
,D/PMS     (  907): releaseWL(4239d358): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426587a0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426587a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4268b4a0): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4268b4a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4270bf80): PARTIAL_WAKE_LOCK  Icing 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4270bf80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=206 rxSum=175} preTxRxSum={txSum=124 rxSum=103}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20954 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20955 delay=15s
D/PMS     (  907): acquireWL(42757c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4256a968: PendingIntentRecord{425c43f8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=89534, Int=0
D/PMS     (  907): releaseWL(42757c18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 12 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:253, mTXpacketCount:195, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1499): Don't start project servcice
,D/HtcModeClient( 1499): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1499): connectState: CONNECTION_READY = false
,D/SilentMusic( 1499): call stop
,D/HtcModeClient( 1499): close connection
,W/HtcModeClient( 1499): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1499): read the terminate packet, so break
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(422c2150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029}
,V/AlarmManager(  907): sending alarm PendingIntent{41abcaa8: PendingIntentRecord{426d9488 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454681677471, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42605da8: PendingIntentRecord{4266c6b0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454681688463, Int=0
,D/PMS     (  907): acquireWL(426cf770): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4428 uid=10078 gids={50078}
,V/AlarmManager(  907): sending alarm PendingIntent{425047d0: PendingIntentRecord{4254b378 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454681690912, Int=60000
,D/PMS     (  907): releaseWL(422c2150): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  907): acquireWL(42769008): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2193 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426cf770): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2193): Aggregate from 1454681648323 (log), 1454679877422 (data)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,D/SMSBackup( 4428): SMSBackupAgentService started
,D/SMSBackup( 4428): Checking restore status
D/SMSBackup( 4428): Restore complete
,D/SMSBackup( 4428): cancelCheckAlarm
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
D/PMS     (  907): releaseWL(42769008): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SMSBackup( 4428): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/Finsky  ( 4196): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4196): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  907): killProcessQuiet, pid=4143
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4143:com.htc.launcher:biclient/u0a76 (adj 15): empty #17
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4143
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{426c8550 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,V/LightsService(  907): setLight #0: color=#3f
,V/LightsService(  907): setLight #0: color=#3c
,V/LightsService(  907): setLight #0: color=#35
,V/LightsService(  907): setLight #0: color=#2f
,V/LightsService(  907): setLight #0: color=#28
,V/LightsService(  907): setLight #0: color=#21
,V/LightsService(  907): setLight #0: color=#1b
,V/LightsService(  907): setLight #0: color=#14
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(4263bc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4263bc98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(42635098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{425f39b8: PendingIntentRecord{425c43f8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104539, Int=0
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=206 rxSum=175} preTxRxSum={txSum=206 rxSum=175}
D/WifiDataStallTracker(  907): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20955 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20956 delay=15s
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  907): releaseWL(42635098): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42626bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105194, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42626bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1115): now=1454681700056 next=59944
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42114a98
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42114a98, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202cd10
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@422c40a8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 345ms
,W/PnPMgr  (  357): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
I/InputMethodManagerService(  907): Disable input method client, pid=1270
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4264ea60)
,D/NfcService( 1249): ScreenObserver: OFF
,D/NfcService( 1249): applyRouting - 0
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,D/NfcService( 1249): applyRouting -2
D/PMN     (  907): wakingUp
I/WindowManager(  907): No lock screen! windowToken=null
,D/PMS     (  907): acquireWL(423e6758): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(423e6758): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(42550438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/MtpService( 2750): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2750): [MTP][onReceive]-
,D/NfcService( 1249): applyRouting - 0
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42550438): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1249): applyRouting -2
D/PMS     (  907): acquireWL(42595400): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1249 1027 null
D/PMS     (  907): releaseWL(42595400): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/AutoSetting( 1320): service - onCreate()
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/TetherSettings( 4179): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4179): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4179): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4179): Cust_ConnectToPC   : spcsc>false
D/        ( 4179): Cust_ConnectToPC   : IPT>true
,D/        ( 4179): Cust_ConnectToPC   : Singel_USB>false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/ClockThread( 1115): stop update clock
,W/Settings( 4179): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20957 delay=15s
E/SmartNS_Utility( 4179): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4179): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4179): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:On
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1183): htc_wext_set_TX_TRACKING - ret = 0
,D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 4179): onReceive:android.intent.action.USER_PRESENT
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
W/ContextImpl( 4179): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 4179): onReceive:android.intent.action.USER_PRESENT,
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/Settings( 4179): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4179):  defaultType:0
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/LocationManagerService(  907): request 42519668 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1183): WiFioffload: SignalStrength: =97
D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:253, mTXpacketCount:253, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  907): updateScreenOn: false
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4459 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(4264ce48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4264ce48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(424d9470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424d9470): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOn: 1454681702455
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOn: 1454681702455
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202cd10
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4202cd10, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@422c40a8
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(4254b7f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
,I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bc79e0
I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/AlarmManager(  907): ACTION_SCREEN_OFF
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20957 mDataStallAlarmIntent=PendingIntent{425837c8: PendingIntentRecord{425c43f8 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1183): SET_SCREEN_ON:Off
I/wpa_supplicant( 1183): htc_wext_set_keepalive +
I/wpa_supplicant( 1183): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1183): getPrivFuncNum +	
I/wpa_supplicant( 1183): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1183): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1183): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1183): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1183): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(427b5958): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(4254b7f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
,D/wpa_supplicant( 1183): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): acquireWL(42712490): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4459 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(427b5958): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42712490): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4459): getMobilePolicyEnabled, result = true
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 57
W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4459): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422c40a8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422c40a8, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422c40a8, eanble = 0, strlen(mName) = 36,
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422c40a8
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422c45f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@422c45f0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] getTotalRam: 1873 Mb
D/PMS     (  907): acquireWL(42745460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42745460): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(422c2758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(422c2758): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1740): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1740): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1740): onScreenOff
,D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/AutoSetting( 1499): service - handleMessage() stop self
,D/AutoSetting( 1499): service - onDestroy() END
,D/AutoSetting( 1499): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3659
,I/ActivityManager(  907): Killing 3659:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3659
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3929
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3929:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3929
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42783f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42652ec0: PendingIntentRecord{426e3048 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121660, Int=0
,D/PMS     (  907): releaseWL(42783f70): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42751638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(426f4e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426f4e48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42751638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4258ad80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(4258ad80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4279f140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42732cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42700a68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1454681716780 tag=VacuumService
,D/PMS     (  907): releaseWL(4279f140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42732cf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426e5448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(426e5448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4276a998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42700a68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4276a998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427070c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(427070c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4277dcc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4277dcc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427042a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0],
,D/PMS     (  907): acquireWL(42777d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42777d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4274a828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{426b2b80 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): releaseWL(427042a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4230e0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(4230e0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 6709 seconds from now (1454681717649),
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =4a81 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [7][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4274a828): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42720d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(42720d10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42727700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(42727700): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4272ee08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4272ee08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(427f0d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{422c2950: PendingIntentRecord{42710680 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137864, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
,D/PMS     (  907): releaseWL(427f0d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - onDestroy() END
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=2160
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2160:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2160
,D/PMS     (  907): acquireWL(427f6f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424c68c8: PendingIntentRecord{424a2878 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142394, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(427f8280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(427f6f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =85c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 7,
D/libc    (  364): [NET]res_nsend:resplen=238,
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
,D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4,
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(427f8280): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(42828f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42828f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4282acc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4282acc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42830af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{426185a8: PendingIntentRecord{426c3a50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173887, Int=0
,D/PMS     (  907): releaseWL(42830af8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(42832be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42832be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(428344e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428344e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42836738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42836738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42838030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=285194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42838030): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4283a2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4283a2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  907): killProcessQuiet, pid=4283
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4283:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4283
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4283e4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=345194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283e4e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42840740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42840740): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42842038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=405193, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42842038): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(428442d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428442d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42845bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=465194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42845bd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42847648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42847648): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4284cde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4284cde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4284e6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=525194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4284e6e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42850938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42850938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42852230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=585193, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42852230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(428544a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428544a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  907): acquireWL(42856368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=645193, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42856368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4285a3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4285a3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4285bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=705193, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4285bcc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4285e500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4285e500): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4285fdf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=765194, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4285fdf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42862050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42862050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42863948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=825193, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42863948): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42865bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42865bc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(428674b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=885194, Int=0
,D/PMS     (  907): releaseWL(428674b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42868f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42868f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4286e6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4286e6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4286ffc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=945194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4286ffc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42872278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41c6fb28: PendingIntentRecord{42449c70 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782362, Int=0
,I/ActivityManager(  907): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=4507 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{4265d938: PendingIntentRecord{42502178 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{425e3f80: PendingIntentRecord{426fd0c0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=948194, Int=0
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4519 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{41edbe48: PendingIntentRecord{423c84b0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454681806850, Int=10800000
,V/AlarmManager(  907): sending alarm PendingIntent{4247dc58: PendingIntentRecord{42416a88 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454682527116, Int=900000
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/PMS     (  907): acquireWL(42881db8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): releaseWL(42881db8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42889508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=6 [117][8][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/PowerUsageService( 4459): call getInstance()
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(42872278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 4459): MY_DEBUG = false
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,I/ImageRamCache( 4507): create image Cache, size: 31457280.
I/ImageRamCache( 4507): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4507): create image Cache, size: 12582912.
,I/FeedSettings( 4507): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4507): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4507): GroupBudget 60 45 15
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4519/10049)
,I/Prism.ExternalStringMa_( 4507): changeLocale(): en_GB
W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/Prism.AllAppsOptionsMa_( 4507): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4507): loadGridSize() with Alternative
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): acquireWL(428cb670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2193): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2193): Loading module APK com.google.android.play.games
D/PMS     (  907): releaseWL(42889508): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 4507): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 4
D/libc    ( 4507): [NET] getaddrinfo-,err=8
D/libc    ( 4507): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    ( 4507): [NET] getaddrinfo-, 1
,D/libc    ( 4507): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 17(0x637362692e6874),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3e52 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/dalvikvm( 2193): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2193): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 2193): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 2193): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/GamesSyncServiceMain( 2193): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 2193): Failed to execute periodic sync, missing client context - aborting
D/PMS     (  907): releaseWL(428cb670): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42791b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(42791b18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427a57c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1183): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1183): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1183): nl80211: survey data missing!
E/wpa_supplicant( 1183): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1183): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/PMS     (  907): releaseWL(427a57c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=4237
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4237:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4237
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42721ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42721ad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=206
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4507): [NET] getaddrinfo_proxy-, success
D/PMS     (  907): acquireWL(42763f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2878 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (2878/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2878/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
D/PMS     (  907): releaseWL(42763f68): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4507/10076)
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (4507/10076)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024863
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025117
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025194
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025197
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025203
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026648
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026690
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360029440
,D/Process (  907): killProcessQuiet, pid=4158
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4158:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4158
,D/PMS     (  907): acquireWL(427c2f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(427c2f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4276a238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1005194, Int=0
,D/PMS     (  907): releaseWL(4276a238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncUtils( 4459): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(4288e1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4268f7a0: PendingIntentRecord{42780a30 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454682602615, Int=0
D/PMS     (  907): releaseWL(4288e1f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): acquireWL(4288fae8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4459 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4459): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4459): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4459): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4459): SettingOnTime = 1454738400000, randomSettingOnTime = 1454737956000
,D/SmartSyncScreenOnOffTimeReceiver( 4459): SettingOffTime = 1454724000000, randomSettingOffTime = 1454724191000
,D/SmartSyncScreenOnOffTimeReceiver( 4459): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4459): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4459): bNightModeTurnOffOnce = false,
,D/PMS     (  907): releaseWL(4288fae8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  907): acquireWL(426c9d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(426c9d40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(427836a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(427836a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(426ea110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426ea110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/ContextImpl( 4459): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4179): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4179): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4179): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4179): Cust_ConnectToPC   : spcsc>false
D/        ( 4179): Cust_ConnectToPC   : IPT>true
D/        ( 4179): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 4179): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4179): Index of the first 1 = 3
W/Settings( 4179): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4179): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4179): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4179): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4179): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4179): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4179): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(424bed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1065194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(424bed48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4275fe58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): releaseWL(4275fe58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42747d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42747d10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4283dab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1125194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283dab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4230f0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(4230f0f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(428d81a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428d81a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4287c068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1185194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4287c068): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4287e2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(4287e2e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  357): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(42890c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42890c38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42724e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41b16b68: PendingIntentRecord{4232cf10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1245194, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42724e58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(427270b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(427270b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1545): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1545): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4555): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4555): ====startRecUseTime====
D/htc.customization.log.level( 4555):  is 
W/CustomizationLogLevel( 4555): Level value is invalid, use default level 2
D/CustomizationManager( 4555):  Read ACC file spent 0.054 (s)
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4555): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4555): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4555): Parsing tag category name = system
I/CustomizationCIDLoader( 4555): Parsing tag category name = application
I/CustomizationCIDLoader( 4555): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4555): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4555): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4555): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4555): Parsing tag category name = Settings
D/CustomizationManager( 4555):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4555):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4555): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4555): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4555): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4555): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4555, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{41ec6d20 com.example.hello/10397} due to missing metadata
W/PackageSettings(  907): Skipping PackageSetting{41d8f728 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  907): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  907): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1545): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1545): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1545): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1341): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(4289b758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4289b758): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 4507): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 4507): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/AccTypeManager( 1341): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1341): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
E/ExternalAccountType( 1341): Unsupported attribute readOnly
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
W/SystemReader( 1249): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/IcingCorporaProvider( 2849): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4570 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2849): UpdateCorporaTask done [took 81 ms] updated apps [took 81 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{426794f0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4570): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4570): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4570): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4570): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4570): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4570): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4570): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4570): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4570): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4570): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4570): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4570): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4570): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4570): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4570): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4570): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4570): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4570): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4570): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4570): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4570): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4570): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4570): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4570): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4570): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4570): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4570): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4570): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4570): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4570): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4570): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4570): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4570): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4570): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4570): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4570): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4570): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4570): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4570): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4570): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4570): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4570): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4570): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4570): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4570): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4570): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4570): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4570): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4570): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4570): threadid=11: thread exiting with uncaught exception (group=0x41688e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4570): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4570): Process: com.google.android.apps.docs, PID: 4570
E/AndroidRuntime( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4570): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4570): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4570): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4570): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4570): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4570): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4570): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4570): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4570): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4570): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4570): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4570): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4570): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4570): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4570): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4570): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4570): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4570): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4570): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4570): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4570): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4570): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4570): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4570): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4570): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4570): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4570): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4570): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4570): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4570): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4570): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4570): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4570): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4570): Opened ClientFlag.db in read-only mode
D/Process ( 4570): killProcess, pid=4570
D/Process ( 4570): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4589 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  907): Skipping deliver [background] BroadcastRecord{42745cc8 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42717ed0 4570 com.google.android.apps.docs/10100/u0 remote:426da8d0}: process crashing
I/ActivityManager(  907): Recipient 4570
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/Process (  907): killProcessQuiet, pid=4296
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4296:com.htc.task/u0a71 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4570) has died.
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4589): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4589): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4589): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4589): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4589): threadid=10: thread exiting with uncaught exception (group=0x41688e30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4603 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4589): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4589): Process: com.android.keychain, PID: 4589
E/AndroidRuntime( 4589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4589): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4589): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4589): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4589): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4589): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4589): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4589): killProcess, pid=4589
D/Process ( 4589): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454682871534.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4589
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4589) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/ActivityManager(  907): Recipient 4296
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4603): getInstance(Context context)
D/AppTag  ( 4603): getInstance(Context context)
D/AppTag  ( 4603): onCreate()
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4618 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/PMS     (  907): acquireWL(427131d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4618 10160 null
D/PMS     (  907): releaseWL(427131d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
E/SQLiteDatabase( 4618): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4618): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4618): 	at del.a(PG:264)
E/SQLiteDatabase( 4618): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4618): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4196): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
I/ActivityManager(  907): Killing 3893:com.google.android.music:main/u0a154 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3893
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/SQLiteDatabase( 4618): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4618): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4618): 	at del.a(PG:264)
E/SQLiteDatabase( 4618): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4618): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4618): Failed app initialization
E/EsApplication( 4618): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4618): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4618): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4618): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4618): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4618): 	at del.a(PG:264)
E/EsApplication( 4618): 	at eeq.run(PG:187)
E/EsApplication( 4618): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 2193): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2193): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2193): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2193): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2193): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2193): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2193): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2193): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2193): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2193): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2193): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65646140
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/DriveAsyncService( 2193): disk I/O error (code 3850)
E/DriveAsyncService( 2193): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2193): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2193): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2193): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2193): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2193): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2193): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2193): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2193): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2193): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2193): 	at java.lang.Thread.run(Thread.java:864)
E/PhenotypeInitializer( 2193): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2193): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2193): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 2193): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2193): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 2193): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2193): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2193): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2193): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2193): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2193): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2193): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2193): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2193): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2193): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2193): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2193): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2193): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2193): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2193): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2193): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2193): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2193): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2193): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
W/BaseAppContext( 2193): Using Auth Proxy for data requests.
E/SQLiteLog( 2193): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 2193): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 2193): threadid=44: thread exiting with uncaught exception (group=0x41688e30)
E/AndroidRuntime( 2193): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 2193): Process: com.google.android.gms, PID: 2193
E/AndroidRuntime( 2193): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 2193): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2193): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2193): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2193): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2193): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2193): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 2193): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 2193): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2193): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2193): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2193): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
W/BaseAppContext( 2193): Using Auth Proxy for data requests.
W/BaseAppContext( 2193): Using Auth Proxy for data requests.
W/BaseAppContext( 2193): Using Auth Proxy for data requests.
D/Process ( 2193): killProcess, pid=2193
D/Process ( 2193): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3893
D/MediaRouterService(  907): Client com.google.android.music (pid 3893): Died!
I/ActivityManager(  907): Recipient 2193
I/ActivityManager(  907): Process com.google.android.gms (pid 2193) has died.
D/WifiService(  907): Client connection lost with reason: 4
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
E/SQLiteLog( 2878): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2878): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x65af32e0
W/dalvikvm( 2878): threadid=1: thread exiting with uncaught exception (group=0x41688e30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 2878): FATAL EXCEPTION: main
E/AndroidRuntime( 2878): Process: com.google.process.gapps, PID: 2878
E/AndroidRuntime( 2878): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2878): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2878): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2878): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2878): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2878): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2878): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2878): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2878): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2878): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2878): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2878): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2878): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2878): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2878): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2878): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2878): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2878): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerSer,vice(  907): 	... 5 more
D/Process ( 2878): killProcess, pid=2878
D/Process ( 2878): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4650 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4650): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4650 dbg=false s=true
I/DeviceManagement( 4650): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4650): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4650): WorkflowService: Starting workflow service
I/ActivityManager(  907): Recipient 2878
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Process com.google.process.gapps (pid 2878) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
I/DeviceManagement( 4650): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41aec008] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4650): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4650): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4650): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4650): ModelRegistry: Loading model meta data from resources...

```
