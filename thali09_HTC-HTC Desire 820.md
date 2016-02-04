#### Test 58135655a685cd3_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/SoundPicker( 3939): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3939): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3939): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3939): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3939): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3939): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3939): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3939): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3939): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3939): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
--------- beginning of /dev/log/system
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): releaseWL(42528958): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
I/ActivityManager(  909): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/MediaStoreImporter( 3882): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(425a49d0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1496 10014 null
I/ActivityManager(  909): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/PMS     (  909): releaseWL(425a49d0): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
D/TelephonyReceiver( 1244): bind: false
D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
I/ActivityManager(  909): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4046 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
D/PMS     (  909): acquireWL(4272d470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/Process (  909): killProcessQuiet, pid=3768
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3768:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  909): Recipient 3768
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): releaseWL(4272d470): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/cutils-trace( 4043): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4043): ====startRecUseTime====
D/htc.customization.log.level( 4043):  is 
W/CustomizationLogLevel( 4043): Level value is invalid, use default level 2
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b60bd0 +
I/Prism.WidgetManager( 1272): onLoadItems() +
D/CustomizationManager( 4043):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4043): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4043): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4043): Parsing tag category name = system
I/CustomizationCIDLoader( 4043): Parsing tag category name = application
I/CustomizationCIDLoader( 4043): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4043): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4043): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4043): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4043): Parsing tag category name = Settings
D/CustomizationManager( 4043):  Read CID file spent 0.115 (s)
D/CustomizationManager( 4043):  All configurations done spent 0.116 (s)
W/HtcNativeFlag( 4043): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4043): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4043): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4043): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4043
I/SocialFeedProvider( 1272): +disConnect socialManager
I/SocialFeedProvider( 1272): disconnect socialManager
I/SocialFeedProvider( 1272): -disConnect socialManager
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
I/RemoteViews( 1117): com.htc.updater (true,33751552)
D/NotificationService(  909): notification sound not played, stream=5 volume=0 always=false
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e699b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=80 rxSum=63} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
I/ActivityManager(  909): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4074 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19952 Sent 0 pkts since last received, < watchdogTrigger=5
D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19953 delay=15s
I/RemoteViews.Performance( 1117): com.htc.updater 2 15 1 10
I/RemoteViews( 1117): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c12440 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/RemoteViews.Performance( 1117): com.htc.updater 2 8 1 10
D/PMS     (  909): acquireWL(427abdc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427abdc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(427b5eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  909): applying state to connected service
D/LocationProviderProxy(  909): applying state to connected service
D/PMS     (  909): releaseWL(427b5eb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(427b9318): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427b9318): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 4074): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  909): Delay finish: com.google.android.gm/.MailIntentReceiver
E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b60bd0 -
D/Process (  909): killProcessQuiet, pid=3786
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3786:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  909): Recipient 3786
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): acquireWL(427ba720): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(427c7fc8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427ba720): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427c7fc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(427c0cc0): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1244): -- N1 =0
D/PhoneApp( 1244): -- N2 =0
D/PhoneApp( 1244): -- N3 =0
D/PMS     (  909): releaseWL(427c0cc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4279d958): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
I/Gmail   ( 4074): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4074): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4074): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4074): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  909): releaseWL(4279d958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4279d538): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4279d538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4279d3a8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4279d3a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4279ce50): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4279ce50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42783910): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42783910): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42737538): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42737538): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42737498): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42737498): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(427373f8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427373f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 386 ms] updated apps [took 386 ms] 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  909): acquireWL(4272d308): PARTIAL_WAKE_LOCK  AsyncService 0x1 3623 10160 null
D/PMS     (  909): releaseWL(4272d308): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4111 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4111, uid=10074, userID:0
,I/ActivityManager(  909): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4128 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  909): sending alarm PendingIntent{424e6010: PendingIntentRecord{4262dc08 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454591052449, Int=0
,D/Finsky  ( 4111): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (4111/10074)
,I/ImageRamCache( 4128): create image Cache, size: 31457280.
I/ImageRamCache( 4128): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4128): create image Cache, size: 12582912.
,I/FeedSettings( 4128): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4128): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4128): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4128): changeLocale(): en_GB
,D/Settings:HtcWirelessFeatureFlags( 3828): id/is att sku: 99/false
I/Prism.AllAppsOptionsMa_( 4128): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4128): loadGridSize() with Alternative
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/SystemReader( 3828): Cannot find devicepolicy_lower_fp_quality, use default value instead
,I/SocialManager[SocialBiLogHelper]( 4128): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4128): last commit ulog time 1454578885926
,I/SocialManager[SocialBiLogHelper]( 4128): skip commit this time
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Process (  909): killProcessQuiet, pid=3802
,I/ActivityManager(  909): Killing 3802:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/SystemReader( 3828): Cannot find support_harman, use default value instead
,W/SystemReader( 3828): Cannot find effect_manager_id, use default value instead
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (4111/10074)
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3802
,D/WifiService(  909): Client connection lost with reason: 4
,E/Settings:HtcWrapHeaderInfo( 3828): no such activity!
,D/Finsky  ( 4111): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4111): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4111): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3828): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3828): updateDevelopment, bPrefShow = true
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,E/Settings:HtcUmcWidgetEnabler( 3828): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]support         :false
,W/FingerprintManager( 3828): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
E/Settings:HtcVoWifiWidgetEnabler( 3828): isSupportVoWifi: null
W/dalvikvm( 4111): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3828): Failed to find provider info for com.htc.vowifi
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4111, uid=10074, userID:0
,D/Ads     ( 4111): Skipping gmscore version check
,D/Finsky  ( 4111): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4111): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4111): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3828): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3828): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3828): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportRecentAppsButton]support         :false
,W/dalvikvm( 4111): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3828): [supportHomeButton]support         :false
,I/ActivityManager(  909): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
,D/Finsky  ( 4111): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/FingerprintManager( 3828): hasFingerprint() - sSensorCode = 0
,D/Process (  909): killProcessQuiet, pid=3723
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Resuming delayed broadcast
I/ActivityManager(  909): Killing 3723:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,E/Settings:HtcVoWifiWidgetEnabler( 3828): isSupportVoWifi: null
I/ActivityManager(  909): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3828): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  909): Recipient 3723
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,D/PMS     (  909): acquireWL(423ef610): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(423ef610): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42215a18): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,W/IcingInternalCorpora( 2181): getNumBytesRead when not calculated.
,W/dalvikvm( 2181): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2181): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2181): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2181): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2181): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2181): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2181): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2181, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2181): cleanUpNonGplusAccounts done.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,V/AlarmManager(  909): sending alarm PendingIntent{41d17720: PendingIntentRecord{424ca228 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59118, Int=0
,D/Process (  909): killProcessQuiet, pid=3737
,I/ActivityManager(  909): Killing 3737:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 3737
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2181): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2181): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A,
D/PMS     (  909): releaseWL(42215a18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4171 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 6 times.
,I/Babel   ( 4171): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4171): MmsConfig.loadMmsSettings
,W/dalvikvm( 4171): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4171): VFY: unable to resolve instance field 36
,W/dalvikvm( 4171): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4171): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3749): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3749): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4171): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4171): MmsConfig.loadFromDatabase
,E/Babel   ( 4171): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4171): MmsConfig.loadFromResources
,E/Babel   ( 4171): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4171): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4171, uid=10111, userID:0
,W/Settings( 4171): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4171, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4171, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4171, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4171, uid=10111, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4171, uid=10111, userID:0
D/PMS     (  909): acquireWL(425a8828): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4171 10111 null
I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4171): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  909): releaseWL(425a8828): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(4242cf80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4171 10111 null
,I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  909): releaseWL(4242cf80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
D/Process (  909): killProcessQuiet, pid=3845
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3845:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  909): acquireWL(4257fc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Recipient 3845
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4257fc58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42678ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
I/ActivityManager(  909): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  909): releaseWL(42678ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
D/PMS     (  909): acquireWL(424f35d8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(426c6d58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(426c6d58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(424f35d8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(426e3948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/Process (  909): killProcessQuiet, pid=3435
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3435:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Recipient 3435
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): releaseWL(426e3948): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  909): acquireWL(425cdcc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(425cdcc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(4275e5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4275e5c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42661b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(42661b00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42661ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4213 uid=10041 gids={50041}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(42661ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  909): killProcessQuiet, pid=3469
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3469:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3469
,I/BroadcastQueue(  909): Schedule to resend BroadcastRecord{4270c640 u0 com.htc.intent.lockscreen.ClearTASKReminder callingPid=3469 callingUid=10071} for ResolveInfo{4270c408 com.htc.task/.notification.NotifyReceiver m=0x108000} of com.htc.task
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4226 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  909): acquireWL(4261d1b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4226 10071 null
,D/PMS     (  909): acquireWL(4237c508): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4226 10071 null
,D/PMS     (  909): acquireWL(427680f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4171 10111 null
,D/PMS     (  909): releaseWL(4261d1b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 4226): java.lang.NullPointerException
,W/System.err( 4226): java.lang.NullPointerException
W/System.err( 4226): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4226): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4226): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,W/NotifyReceiver( 4226): stopSelfResult true
D/PMS     (  909): releaseWL(4237c508): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): releaseWL(427680f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
,D/Process (  909): killProcessQuiet, pid=3982
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3982:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/ConnectivityService(  909): Done.
D/ConnectivityService(  909): Setting timer for 720seconds
D/PMS     (  909): acquireWL(4275e140): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4226 10071 null
D/PMS     (  909): acquireWL(4269fae8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4226 10071 null
D/PMS     (  909): acquireWL(426ede10): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4226 10071 null
D/PMS     (  909): releaseWL(4275e140): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4226): java.lang.NullPointerException
W/System.err( 4226): java.lang.NullPointerException
W/System.err( 4226): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4226): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 4226): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4226): stopSelfResult true
E/TodoTaskNotifyService( 4226): java.lang.NullPointerException
W/System.err( 4226): java.lang.NullPointerException
W/System.err( 4226): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4226): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4226): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  909): Recipient 3982
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  909): Client connection lost with reason: 4
D/PMS     (  909): acquireWL(4269fae8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4226 10071 null
D/PMS     (  909): releaseWL(426ede10): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  909): releaseWL(4269fae8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
E/NotifyReceiver( 4226): mStartingService is null
W/NotifyReceiver( 4226): stopSelfResult false
D/WearableService( 1223): callingUid 10029, callindPid: 1223
,E/MDM     ( 1223): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2181): Restart initialization of location
D/AuthorizationBluetoothService( 1367): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1367): Proximity feature is not enabled.
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): acquireWL(42648f30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42648f30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/WSP     ( 1319): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1319): Weather sync is On
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,I/WSP     ( 1319): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Feb 04 15:04:15 CET 2016
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2181/10029)
,D/PMS     (  909): acquireWL(4279d2e0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1319 10055 null
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  909): acquireWL(4279cc98): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4171 10111 null
I/ActivityManager(  909): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  909): releaseWL(4279cc98): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
I/ActivityManager(  909): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  909): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  909): acquireWL(427373a8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(427373a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4272d308): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4272d308): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4270f050): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4270f050): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(426ed838): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(426ed838): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(426e1330): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms},
,D/PMS     (  909): releaseWL(426e1330): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(426d3e48): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(426d3e48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(426cfc38): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(426cfc38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 273 ms] updated apps [took 273 ms] 
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  909): acquireWL(426c6620): PARTIAL_WAKE_LOCK  AsyncService 0x1 3623 10160 null
,D/PMS     (  909): releaseWL(426c6620): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2181): Null package name or gms related package.  Ignoreing.
,D/PMS     (  909): acquireWL(426a9048): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
,I/Icing   ( 2181): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 4226): update TASK shortcut>
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/AlarmManager(  909): sending alarm PendingIntent{426bbda0: PendingIntentRecord{4270c530 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454591055705, Int=0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:107, mTXpacketCount:73, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  909): acquireWL(426596c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426596c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/Icing   ( 2181): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/Icing   ( 2181): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2181): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  909): releaseWL(426a9048): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 4074): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  909): sending alarm PendingIntent{41f42cf8: PendingIntentRecord{426c1dd8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454591057468, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{4257bc28: PendingIntentRecord{426d4548 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454591057487, Int=0
,I/SensorManager(  909): mEventCount = 450
,I/iu.UploadsManager( 2181): End new media; added: 0, uploading: 0, time: 75 ms
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 7 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/GAV4    ( 4171): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2181, uid=10029, userID:0
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2181, uid=10029, userID:0
,I/CheckinService( 2181): Done disabling old GoogleServicesFramework version
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2181, uid=10029, userID:0
,I/CalendarProvider2( 1496): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1496): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(423b0a88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 909 1000 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(42004ee0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(423b0a88): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  909): releaseWL(42004ee0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  909): acquireWL(42671520): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3882 10154 null
,I/ActivityManager(  909): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3882): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3882, uid=10154, userID:0
,D/PMS     (  909): releaseWL(42671520): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3882): Conditions not met for autocaching.
,I/MusicLeanback( 3882): Stop autocaching.
,W/ContextImpl( 3882): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  909): Resuming delayed broadcast
,D/PMS     (  909): acquireWL(425732b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(425732b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(41e3edc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(41e3edc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(4272e920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4272e920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,W/MediaManager( 3862): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4283 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4283): Loading default preferences
,W/Resources( 4283): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  909): New client listening to asynchronous messages
,D/SyncApplication( 4283): Overriding preferences with custom values
,D/SyncApplication( 4283): Updating preferences succeeded
,E/SyncApplication( 4283): Application created.
D/VolumeInfo( 4283): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4283): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4283): Found 0 mount point(s)
V/VolumeInfo( 4283): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 4283): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/CalendarDefines( 4283): getNewCalendarAuthority()...
D/VolumeInfo( 4283): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 4283): Can not create volume ID for unmounted volume null
D/SyncApplication( 4283): enableAppOperation()+
D/SyncApplication( 4283): enableAppOperation()-
D/HTCUtilities( 4283): isNeorSinged() + 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4283, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4283, uid=10008, userID:0
W/PackageManager(  909): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4283): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4283): isNeorSinged() return false
,D/CDMountReceiver( 4283): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4283): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c814b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/CDMountReceiver( 4283): enable CD Auto-mount: true
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 11 3 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,I/ActivityManager(  909): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4283): enable auto-mount
,D/HTCUtilities( 4283): enable auto-mount
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b56c90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  909): Resuming delayed broadcast
D/PMS     (  909): releaseWL(42689f50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 11 2 16
D/MountService(  909): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4304 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/Process (  909): killProcessQuiet, pid=4018
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4018:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 4018
,D/CalendarApplication( 4304): onCreate
D/ProviderChangeReceiver( 4304): ---------------------------------------------------
,D/ProviderChangeReceiver( 4304): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4304): start to updateAlertNotification!
,I/ActivityManager(  909): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4318 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  909): killProcessQuiet, pid=3907
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3907:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3907
,D/AlertService( 4304): No fired or scheduled alerts
,D/HtcAlertUtils( 4304): -- cancelReminderNotification --
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/HtcAlertUtils( 4304): broadcastExistReminder!
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4318): [4318/4318] onCreate()
W/ContextImpl( 4318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  909): Resuming delayed broadcast
,D/Process (  909): killProcessQuiet, pid=3939
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  909): Killing 3939:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3939
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 8 times.
I/ActivityManager(  909): Waited long enough for: ServiceRecord{42644cd8 u0 com.htc.musicenhancer/.EnhancerService}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/PMS     (  909): releaseWL(4279d2e0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/PMS     (  909): acquireWL(4277aa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4277aa78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(426d1e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=80 rxSum=63} preTxRxSum={txSum=80 rxSum=63}
D/WifiDataStallTracker(  909): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19953 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19954 delay=15s
V/AlarmManager(  909): sending alarm PendingIntent{4220a088: PendingIntentRecord{425a0838 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=72261, Int=0
D/PMS     (  909): releaseWL(426d1e30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  909): mEventCount = 600
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 9 times.
,D/Finsky  ( 4111): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4111): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  909): acquireWL(426658a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
V/AlarmManager(  909): sending alarm PendingIntent{423bd1f8: PendingIntentRecord{4263d518 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454591069175, Int=0
D/PMS     (  909): releaseWL(426658a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.android.vending (4111/10074)
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4111): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4111): [NET] getaddrinfo-,err=8
D/libc    ( 4111): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4111): [NET] getaddrinfo-, 1
D/libc    ( 4111): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =74b4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4111): [NET] getaddrinfo_proxy-, success
I/global  ( 4111): call createSocket() return a new socket.
D/libc    ( 4111): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4111): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4111): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4111): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4111): untagSocket(69) failed with errno -22
,D/Finsky  ( 4111): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4111): untagSocket(69) failed with errno -22
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=18 [27][5][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:139, mTXpacketCount:107, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/NetworkManagementSocketTagger( 4111): untagSocket(69) failed with errno -22
,D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.android.vending (4111/10074)
,D/Finsky  ( 4111): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  909): acquireWL(423ac0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
,V/AlarmManager(  909): sending alarm PendingIntent{423fa7b8: PendingIntentRecord{423f18c8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454591071492, Int=0
,D/PMS     (  909): acquireWL(4254e910): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4111 10074 null
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/Finsky  ( 4111): [437] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1223): client connected with version: 8296000
D/PMS     (  909): releaseWL(423ac0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4111): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4111): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1367): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4111): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4111): [NET] getaddrinfo-,err=8
D/libc    ( 4111): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4111): [NET] getaddrinfo-, 1
,D/libc    ( 4111): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b0e7 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 60
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4111): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  909): releaseWL(4254e910): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 10 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=6 [48][3][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1319): service - mHandler: update timezone
,D/AutoSetting( 1319): service - handleMessage() stop self
,D/AutoSetting( 1319): service - handleMessage() quit looper
,D/AutoSetting( 1319): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=4046
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4046:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4046
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1496): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1496): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1496): service - onCreate()
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  909): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1496): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1496): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1496): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1496): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1496): service - mHandler: update timezone
,D/AutoSetting( 1496): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1496): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1496): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1496): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41efab88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 2 7 2 11
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  909): mEventCount = 750
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 11 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  909): acquireWL(424f0d00): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(424f0d00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(427bd060): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(427bd060): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42540818): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42540818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PMS     (  909): acquireWL(425e1608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{423bddc8: PendingIntentRecord{425a0838 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87267, Int=0
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=128} preTxRxSum={txSum=80 rxSum=63}
D/WifiDataStallTracker(  909): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19954 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19955 delay=15s
D/PMS     (  909): releaseWL(425e1608): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 12 times.
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:191, mTXpacketCount:139, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1496): handler message = 4011
,E/HtcModeClient( 1496): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1496): Don't start project servcice
,D/HtcModeClient( 1496): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1496): connectState: CONNECTION_READY = false
D/SilentMusic( 1496): call stop
,D/HtcModeClient( 1496): close connection
,W/HtcModeClient( 1496): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1496): read the terminate packet, so break
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/PMS     (  909): acquireWL(425a1248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10074}
,V/AlarmManager(  909): sending alarm PendingIntent{425f3898: PendingIntentRecord{426f1980 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454591085737, Int=0
,I/ActivityManager(  909): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4351 uid=10078 gids={50078}
,V/AlarmManager(  909): sending alarm PendingIntent{4250db58: PendingIntentRecord{42433fb8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454591089645, Int=60000
,D/PMS     (  909): releaseWL(425a1248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4351): SMSBackupAgentService started
,D/SMSBackup( 4351): Checking restore status
,D/SMSBackup( 4351): Restore complete
,D/SMSBackup( 4351): cancelCheckAlarm
,D/SMSBackup( 4351): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/Finsky  ( 4111): [428] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4111): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  909): killProcessQuiet, pid=4128
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4128:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4128
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{42708f60 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,V/LightsService(  909): setLight #0: color=#3d
,V/LightsService(  909): setLight #0: color=#3a
,V/LightsService(  909): setLight #0: color=#33
,V/LightsService(  909): setLight #0: color=#2d
,V/LightsService(  909): setLight #0: color=#26
,V/LightsService(  909): setLight #0: color=#1f
,V/LightsService(  909): setLight #0: color=#19
,V/LightsService(  909): setLight #0: color=#14
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  909):    returned true,
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  909): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  909): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  909): updateDataStallInfo: mDataStallTxRxSum={txSum=154 rxSum=128} preTxRxSum={txSum=154 rxSum=128}
D/WifiDataStallTracker(  909): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  909): onDataStallAlarm: tag=19955 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19956 delay=15s
D/PMS     (  909): acquireWL(4272f0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{42673170: PendingIntentRecord{425a0838 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102272, Int=0
,D/PMS     (  909): releaseWL(4272f0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  909): Going to sleep due to screen timeout...
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421fc7e0
D/WirelessDisplayService(  909): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  909): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  909): disable: get sensor name = CM36282 Light sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421fc7e0, eanble = 0, strlen(mName) = 59
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  909): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bf6b88
W/SensorService(  909): Listener[1] = com.htc.smartdim.sensor_eye@426b0248
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  909): mWirelessDisplayManager is null
W/BatSI   (  909): Couldn't get kernel wake lock stats
V/LightsService(  909): setLight #2: color=#0
D/qdlights(  909): set_light_buttons_func: on=0 brightness=0
V/LightsService(  909): setLight #0: color=#0
,D/SurfaceControl(  909): Excessive delay in blankDisplay() while turning screen off: 319ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  909): nativeSetInteractive:false
D/PMS     (  909): nativeSetInteractive:false done
D/PMS     (  909): nativeSetAutoSuspend:true
D/PMS     (  909): nativeSetAutoSuspend:true done
D/HABCtrl (  909): TPE algorithm. remove timeout.
D/PMS     (  909): OOBE c monitor 11
I/InputManager(  909): Cancel all due to getting PMS screen off broadcast
D/NfcService( 1251): ScreenObserver: OFF
D/NfcService( 1251): applyRouting - 0
,V/KeyguardServiceDelegate(  909): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42778aa8)
,D/NfcService( 1251): applyRouting -2
,I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  909): screenObserver, isScreenOn=false
I/InputMethodManagerService(  909): Disable input method client, pid=1272
D/PMN     (  909): wakingUp
D/PMS     (  909): acquireWL(42717d28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
,D/PMS     (  909): releaseWL(42717d28): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/WirelessDisplayService(  909): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,V/KeyguardServiceDelegate(  909): **** SHOWN CALLED ****
I/WindowManager(  909): No lock screen! windowToken=null
D/PMS     (  909): acquireWL(42685110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/MtpService( 2378): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2378): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting - 0
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  909): releaseWL(42685110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMN     (  909): onScreenOn
D/AutoSetting( 1319): receiver - intent: android.intent.action.USER_PRESENT
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1251): applyRouting -2
D/PMS     (  909): acquireWL(4264a3b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): releaseWL(4264a3b0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  909): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  909): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/TetherSettings( 3828): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3828): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3828): Cust_ConnectToPC   : Modem_Link>false
D/AutoSetting( 1319): service - onCreate()
D/        ( 3828): Cust_ConnectToPC   : spcsc>false
D/        ( 3828): Cust_ConnectToPC   : IPT>true
D/        ( 3828): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3828): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3828): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3828): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3828): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
,D/AutoSetting( 1319): service - AddressCache: using context: com.htc.Weather
,D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  909): startDataStallAlarm: tag=19957 delay=15s
I/ClockThread( 1117): stop update clock
,I/PSReceiver( 3828): onReceive:android.intent.action.USER_PRESENT
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
D/AlarmManager(  909): ACTION_SCREEN_ON
I/AlarmManager(  909): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done recovering
I/AlarmManager(  909): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  909): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/LocationManagerService(  909): request 425551e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  909): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 3828): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3828): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3828):  defaultType:0
D/PMS     (  909): acquireWL(426ab5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105631, Int=0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:On
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1159): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1159): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:191, mTXpacketCount:191, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  909): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/SRS_Proc(  373): ParamSet string: screen_state=on
V/NotificationService(  909): batLight: Full, plugged
V/LightsService(  909): setLight #8: color=#c8c800
D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  909): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  909): updateScreenOn: false
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
I/ActivityManager(  909): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4376 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  909): acquireWL(427cce08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427cce08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(427863c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOn: 1454591100288
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOn: 1454591100288
D/PMS     (  909): releaseWL(427863c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bf6b88
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 2
W/SensorService(  909): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41bf6b88, eanble = 0, strlen(mName) = 91
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  909): Listener[0] = com.htc.smartdim.sensor_eye@426b0248
,W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  909): goingToSleep
D/PMS     (  909): acquireWL(427aa1f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 909 1000 null
D/PMS     (  909): acquireWL(427aac50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4376 1000 null
,D/PMS     (  909): releaseWL(427aac50): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1272): [onPause]
,I/FeedProviderManager( 1272): onPause
,D/SmartSyncUtils( 4376): isEpsOn(), nState = 0
,I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c19038
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
I/SocialFeedProvider( 1272): +onPause
,I/SocialFeedProvider( 1272): -onPause
,D/PMS     (  909): releaseWL(426ab5f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): releaseWL(427aa1f8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AlarmManager(  909): ACTION_SCREEN_OFF
I/AlarmManager(  909): [AlarmQueuing] screen off now: 
I/AlarmManager(  909): [AlarmQueuing] data connection: true
,I/AlarmManager(  909): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  909): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=19957 mDataStallAlarmIntent=PendingIntent{41b09158: PendingIntentRecord{425a0838 android broadcastIntent}}
D/WifiNative-wlan0(  909): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  909): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1159): SET_SCREEN_ON:Off
I/wpa_supplicant( 1159): htc_wext_set_keepalive +
I/wpa_supplicant( 1159): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1159): getPrivFuncNum +	
I/wpa_supplicant( 1159): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1159): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1159): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1159): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1159): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  909):    returned true
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): acquireWL(4276ca30): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 909 1000 null
V/SRS_Proc(  373): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4376): getMobilePolicyEnabled, result = true
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  909): updateScreenOn: false
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/wpa_supplicant( 1159): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  909):    returned true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  909): releaseWL(4276ca30): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4376): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4376): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4376): isEpsOn(), nState = 0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiService(  909): New client listening to asynchronous messages
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b0248
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 1
W/SensorService(  909): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b0248, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  909): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  909): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  909): pid=909, uid=1000
W/SensorService(  909): Active sensors: size = 0
W/SensorService(  909): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b0248, eanble = 0, strlen(mName) = 36
W/SensorService(  909): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  909): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  909): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b0248
E/ActivityThread(  909): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b0740 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b0740 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  909): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  909): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  909): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  909): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  909): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  909): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  909): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  909): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  909): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  909): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  909): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  909): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  909): acquireWL(427944a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] getTotalRam: 1873 Mb
D/PMS     (  909): releaseWL(427944a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(427959c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1767): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1767): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1767): onScreenOff
D/PMS     (  909): releaseWL(427959c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1319): service - mHandler: cancel location update
,D/AutoSetting( 1319): service -           changes count: 0
,D/AutoSetting( 1496): service - handleMessage() stop self
,D/AutoSetting( 1496): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=3692
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/AutoSetting( 1496): service - handleMessage() quit looper
I/ActivityManager(  909): Killing 3692:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3692
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  909): killProcessQuiet, pid=3921
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3921:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3921
,D/PMS     (  909): acquireWL(4273c8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  909): sending alarm PendingIntent{426d8970: PendingIntentRecord{4270d830 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120217, Int=0
,D/PMS     (  909): releaseWL(4273c8d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4273e660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(427449a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(427449a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4273e660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4274a520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(4274a520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4274e3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(427fa1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42802388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1454591114894 tag=VacuumService
,D/PMS     (  909): releaseWL(4274e3f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(427fa1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4280cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(4280cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42810a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42802388): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{426b3758 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/PMS     (  909): releaseWL(42810a28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42817f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(42817f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4281c2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
D/PMS     (  909): releaseWL(4281c2b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): acquireWL(42823068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(4282bdc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(4282bdc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42833758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): releaseWL(42823068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(428388b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(428388b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 5048 seconds from now (1454591115660)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1ab +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  909): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=10 [10][1][0]
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): releaseWL(42833758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4285a988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(4285a988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(42860f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1159): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1159): nl80211: survey data missing!
E/wpa_supplicant( 1159): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1159): environment dirty rate=0 [0][0][0],
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
,D/PMS     (  909): releaseWL(42860f40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  909): acquireWL(42868b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42868b08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(4286dea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{41f52cb8: PendingIntentRecord{42736d30 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136124, Int=0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
,D/PMS     (  909): releaseWL(4286dea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1319): service - handleMessage() stop self
,D/AutoSetting( 1319): service - handleMessage() quit looper
,D/AutoSetting( 1319): service - onDestroy() END
,D/Process (  909): killProcessQuiet, pid=3749
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3749:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3749
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(428747e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{42519c20: PendingIntentRecord{42386b28 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141451, Int=0
,D/GpsLocationProvider(  909): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  909): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  909): acquireWL(42875ae8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
D/PMS     (  909): releaseWL(428747e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =fb15 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  909): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  909): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  909): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  909):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  909): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  909): releaseWL(42875ae8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  909): acquireWL(428ad138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165632, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  909): acquireWL(428ae410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428ae410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  909): updateBatteryInfo
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
,I/HtcPowerSaver(  909): >> updateStatus
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  909): << updateStatus
,W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  909): releaseWL(428ad138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TetherSettings( 3828): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3828): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3828): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3828): Cust_ConnectToPC   : spcsc>false
D/        ( 3828): Cust_ConnectToPC   : IPT>true
D/        ( 3828): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3828): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3828): Index of the first 1 = -1
W/Settings( 3828): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3828): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3828): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3828): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3828): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
D/SmartNS_Utility( 3828): [ACC]android_networking:tethering_guard_support=false
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(428b7b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{10027}
,V/AlarmManager(  909): sending alarm PendingIntent{423ff3c0: PendingIntentRecord{426b7260 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171839, Int=0
,D/PMS     (  909): releaseWL(428b7b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  909): acquireWL(428b9c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428b9c08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(428bb158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428bb158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
,D/HtcPowerSaver(  909): updateBatteryInfo
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(428c0cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=225632, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428c0cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(428c2f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428c2f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(428c4810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=285632, Int=0
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428c4810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(428c6a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428c6a88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  909): killProcessQuiet, pid=4213
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4213:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4213
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(428cacc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=345631, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428cacc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(428ccf20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428ccf20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  909): acquireWL(428cea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428cea38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(428d45c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=405631, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428d45c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(428d6840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(428d6840): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(428d8138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=465631, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(428d8138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  909): acquireWL(427cc790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(427cc790): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  909): acquireWL(427c7fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=525631, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(427c7fc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  909): acquireWL(427c7f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(427c7f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(427c7e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/UsbnetService(  909): BroadcastReceiver::onReceive+
D/UsbnetService(  909): onReceive BATTERY_CHANGED
D/UsbnetService(  909):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  909): BroadcastReceiver::onReceive-
,I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  909): releaseWL(427c7e88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  909): updateBatteryInfo
D/PMS     (  909): runPSCheck
D/HtcPowerSaver(  909): Checking...
I/HtcPowerSaver(  909): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  909): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  909): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  909): acquireWL(4279d3a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=585632, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4279d3a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4279ce50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4279ce50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  909): acquireWL(4279c268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=645631, Int=0
,D/PMS     (  909): releaseWL(4279c268): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(427885b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(427885b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(427855b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=705631, Int=0
,D/PMS     (  909): releaseWL(427855b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42779170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42779170): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4276e9e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=765631, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4276e9e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42761370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42761370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42760048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=825631, Int=0
,D/PMS     (  909): releaseWL(42760048): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42737538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42737538): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42737498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=885631, Int=0
,D/PMS     (  909): releaseWL(42737498): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42737358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42737358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(42730528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=945631, Int=0
,D/PMS     (  909): releaseWL(42730528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4272d728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/ConnectivityService(  909): Sampling interval elapsed, updating statistics ..
D/ConnectivityService(  909): Done.
,D/ConnectivityService(  909): Setting timer for 720seconds
,V/AlarmManager(  909): sending alarm PendingIntent{41d4d0b0: PendingIntentRecord{42463eb8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780610, Int=0
,V/AlarmManager(  909): sending alarm PendingIntent{4241ea48: PendingIntentRecord{42732248 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=945844, Int=0
,I/ActivityManager(  909): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4431 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,D/PMS     (  909): acquireWL(426ee038): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  909): sending alarm PendingIntent{425f37b0: PendingIntentRecord{42354c38 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454591205613, Int=10800000
,V/AlarmManager(  909): sending alarm PendingIntent{420cef78: PendingIntentRecord{42629f28 com.htc.checkinprovider broadcastIntent}}, i=com.htc.checkin.HTC_CHECKIN, t=0, cnt=1, w=1454591422072, Int=1209600000
,V/AlarmManager(  909): sending alarm PendingIntent{42384868: PendingIntentRecord{426896a0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454591925941, Int=900000
,D/PMS     (  909): releaseWL(426ee038): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/HtcTelephonyCapability(  909): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability(  909): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils(  909): getRATByHtcTelephonyCapability:1
,W/SystemReader(  909): Cannot find qct_8960_interface, use default value instead
,D/htcCheckinService(  909): Roaming is :false
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000),
I/htcCheckinService(  909): == Checkin triggered == A6.1(KK)
,E/htcCheckinService(  909): can't get the url information = 
E/htcCheckinService(  909): java.lang.NullPointerException
E/htcCheckinService(  909): 	at com.htc.checkinprovider.htcCheckinService$CheckinThread.run(htcCheckinService.java:3740)
W/ContextImpl( 4376): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4376): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4376): MY_DEBUG = false
D/PMS     (  909): releaseWL(4272d728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.aurora (4431/10049)
D/PMS     (  909): acquireWL(424c09c0): PARTIAL_WAKE_LOCK  htcCheckinService_300 0x1 909 1000 null
,W/BatSI   (  909): Couldn't get kernel wake lock stats
D/htcCheckinService.CheckinProtocol(  909): getIMEI()
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
V/HtcTelephonyInternal( 1244): CMD_GET_IMEI xxxxxxxxxxxxxxx
W/SystemReader(  909): Cannot find device_type, use default value instead
,D/ConnectivityService(  909): getNetworkInfo networkType=55 called by  (909/1000)
,I/htcCheckinService(  909): Dump Checkin info:
,I/htcCheckinService(  909): Sending checkin request, times: 1, (926 bytes)...
D/libc    (  909): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3ed0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,W/BatSI   (  909): Couldn't get kernel wake lock stats
,D/Process (  909): killProcessQuiet, pid=4171
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 4171:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 4171
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 6896
D/libc    (  363): [NET]res_nsend:resplen=51
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
,I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x36302e3139392e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/PMS     (  909): acquireWL(42954ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1367/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1367/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360023453
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024077
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024240
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024270
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024273
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024279
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025712
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025728
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360028568
D/PMS     (  909): releaseWL(42954ea8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/libc    (  909): [NET] getaddrinfo+,hn 17(0x616e646368696e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
W/ActivityThread(  909): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/htcCheckinService(  909): (from server)bUpdateAction:true
,I/htcCheckinService(  909): Download request accepted.
D/libc    (  909): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
,D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x666f7461646c2d),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e925 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 807
D/libc    (  363): [NET]res_nsend:resplen=116
D/libc    (  363): [NET]res_queryN: exit 3, ancount=3
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x36382e3233322e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/htcCheckinService(  909): fota confirm intent waits app update response result
,D/htcCheckinService.appUpdateExecuter(  909): setFotaConfirmIntent()
,I/htcCheckinService.appUpdateExecuter(  909): === FOTA AppUpdate Client 6.0 ===
,D/htcCheckinService.CheckinProtocol(  909): getIMEI()
,V/HtcTelephonyInternal( 1244): CMD_GET_IMEI xxxxxxxxxxxxxxx
,W/SystemReader(  909): Cannot find device_type, use default value instead
,D/ConnectivityService(  909): getNetworkInfo networkType=55 called by  (909/1000)
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
,D/libc    (  909): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
D/libc    (  909): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 1024
D/libc    (  909): [NET] getaddrinfo-, 1
D/libc    (  909): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1197 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 9751
D/libc    (  363): [NET]res_nsend:resplen=51
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  909): [NET] getaddrinfo_proxy-, success
I/global  (  909): call createSocket() return a new socket.
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x36302e3139392e),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-, SUCCESS
,D/libc    (  909): [NET] getaddrinfo+,hn 17(0x6170752d636869),sn(),family 0,flags 4
,D/libc    (  909): [NET] getaddrinfo-,err=8
,D/htcCheckinService.appUpdateExecuter(  909): notifyFotaConfirmIntent()
W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.checkinprovider.appUpdateExecuter.notifyFotaConfirmIntent:152 com.htc.checkinprovider.appUpdateExecuter.doAppCheckin:259 com.htc.checkinprovider.htcCheckinService.notifyIntent:2283 
,W/ContextImpl(  909): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1399 android.content.ContextWrapper.sendBroadcast:377 com.htc.checkinprovider.appUpdateExecuter.doAppCheckin:298 com.htc.checkinprovider.htcCheckinService.notifyIntent:2283 com.htc.checkinprovider.htcCheckinService.doCheckin:2823 
,I/htcCheckinService(  909): Checkin success
I/ActivityManager(  909): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4456 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,E/htcCheckinService.RunAppUpdateReceiver(  909): Err in mRunUpdateReceiver.onReceive(). Err:java.lang.NullPointerException, [Ljava.lang.StackTraceElement;@425f2b20
,I/htcCheckinService.RunAppUpdateReceiver(  909): == Run AppUpdate Receiver Finished ==
,D/Process (  909): killProcessQuiet, pid=4226
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  909): Killing 4226:com.htc.task/u0a71 (adj 15): empty #17
,I/htcCheckinService(  909): == Checkin finished ==
D/PMS     (  909): releaseWL(424c09c0): PARTIAL_WAKE_LOCK  htcCheckinService_300 0x1 null
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 4226
,V/NotificationService(  909): batLight: Full, plugged
,V/LightsService(  909): setLight #8: color=#c8c800
,D/qdlights(  909): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  909): setLight #8: color=#c800
,D/qdlights(  909): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  909): [LedInfo] has indicator attribute
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  909): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1564): [NotificationService] onNotificationRemoved, pkgName: com.htc.updater, id: 2130837512
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.htc.updater does not support DotMatrix
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  909): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41c20f30 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.updater 2 9 0 10
,D/PMS     (  909): acquireWL(426d49a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(426d49a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(426b1730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1005631, Int=0
,D/PMS     (  909): releaseWL(426b1730): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42716100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,D/SmartSyncUtils( 4376): isEpsOn(), nState = 0
V/AlarmManager(  909): sending alarm PendingIntent{41e8d5a8: PendingIntentRecord{42758658 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454592000413, Int=0
,D/PMS     (  909): acquireWL(4262e1f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4376 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4376): [updateNmRange] bManual = false
,D/PMS     (  909): releaseWL(42716100): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4376): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4376): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4376): SettingOnTime = 1454652000000, randomSettingOnTime = 1454650617000
D/SmartSyncScreenOnOffTimeReceiver( 4376): SettingOffTime = 1454637600000, randomSettingOffTime = 1454644410000
D/SmartSyncScreenOnOffTimeReceiver( 4376): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4376): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4376): bNightModeTurnOffOnce = false
,D/PMS     (  909): releaseWL(4262e1f0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  909): acquireWL(42540810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42540810): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(426dd3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1065631, Int=0
,D/PMS     (  909): releaseWL(426dd3a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42620288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42620288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4259cf40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1125631, Int=0
,D/PMS     (  909): releaseWL(4259cf40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(4263e2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(4263e2c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  909): acquireWL(4266b180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1185632, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(4266b180): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  909): acquireWL(42756990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  909): n_update end
,D/PMS     (  909): releaseWL(42756990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  909): acquireWL(42625aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 909 1000 WorkSource{1000}
,V/AlarmManager(  909): sending alarm PendingIntent{4229f110: PendingIntentRecord{41d845a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1245632, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  909): releaseWL(42625aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),D/CustomizationManager( 4478): ====startRecUseTime====
D/htc.customization.log.level( 4478):  is 
W/CustomizationLogLevel( 4478): Level value is invalid, use default level 2
D/CustomizationManager( 4478):  Read ACC file spent 0.106 (s)
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4478): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4478): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4478): Parsing tag category name = system
I/CustomizationCIDLoader( 4478): Parsing tag category name = application
I/CustomizationCIDLoader( 4478): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4478): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4478): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4478): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4478): Parsing tag category name = Settings
D/CustomizationManager( 4478):  Read CID file spent 0.159 (s)
D/CustomizationManager( 4478):  All configurations done spent 0.159 (s)
W/HtcNativeFlag( 4478): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4478): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4478): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4478): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  909): deletePackageAsUser: pkg=com.test.thalitest, pid=4478, uid=2000 user=0
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  909): Skipping PackageSetting{42172078 com.example.hello/10397} due to missing metadata
W/PackageSettings(  909): Skipping PackageSetting{4217b088 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  909): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  909): acquireWL(424f1d30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(424f1d30): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  909): Package source /data/app/com.test.thalitest-2.apk does not exist.
E/cutils-trace( 4478): Error opening trace file: No such file or directory (2)
W/PackageManager(  909): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/VoicemailCleanupService( 1288): Cleaning up data for package: com.test.thalitest
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1319): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/[PluginManager]RegisterService( 1319): handle notify Blinkfeed plugin client changed
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "sms"
I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  909): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4493 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 103 ms] updated apps [took 103 ms] 
I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  909): Unable to load service info ResolveInfo{424f6b20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4493): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4493): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4493): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4493): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4493): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4493): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4493): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4493): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4493): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4493): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4493): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4493): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4493): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4493): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4493): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4493): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4493): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4493): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4493): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4493): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4493): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4493): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4493): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4493): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4493): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4493): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4493): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4493): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4493): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4493): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4493): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4493): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4493): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4493): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4493): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4493): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4493): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4493): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4493): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4493): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4493): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4493): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4493): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4493): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4493): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4493): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4493): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4493): threadid=11: thread exiting with uncaught exception (group=0x4169de30)
E/AndroidRuntime( 4493): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4493): Process: com.google.android.apps.docs, PID: 4493
E/AndroidRuntime( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4493): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4493): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4493): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4493): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4493): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  909): App crashed! Process: com.google.android.apps.docs
E/SQLiteDatabase( 4493): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4493): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4493): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4493): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4493): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4493): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4493): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4493): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4493): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4493): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4493): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4493): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4493): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4493): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4493): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4493): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4493): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4493): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4493): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4493): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4493): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4493): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4493): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4493): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4493): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4493): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4493): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4493): Opened ClientFlag.db in read-only mode
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
D/Process ( 4493): killProcess, pid=4493
D/Process ( 4493): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4511 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  909): Skipping deliver [background] BroadcastRecord{42625d70 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42615040 4493 com.google.android.apps.docs/10100/u0 remote:422f20c0}: process crashing
D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  909): start
I/ActivityManager(  909): Recipient 4493
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  909): killProcessQuiet, pid=3623
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3623:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  909): Process com.google.android.apps.docs (pid 4493) has died.
W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4511): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4511): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4511): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4511): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4511): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4511): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4511): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4511): threadid=10: thread exiting with uncaught exception (group=0x4169de30)
I/ActivityManager(  909): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4524 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  909): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4511): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4511): Process: com.android.keychain, PID: 4511
E/AndroidRuntime( 4511): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4511): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4511): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4511): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4511): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4511): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4511): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4511): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4511): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454592264746.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
D/Process ( 4511): killProcess, pid=4511
D/Process ( 4511): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  909): Recipient 4511
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Process com.android.keychain (pid 4511) has died.
W/ActivityManager(  909): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4524): getInstance(Context context)
D/AppTag  ( 4524): getInstance(Context context)
D/AppTag  ( 4524): onCreate()
E/JavaBinder(  909): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue(  909): Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
W/BroadcastQueue(  909): android.os.TransactionTooLargeException
W/BroadcastQueue(  909): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  909): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  909): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:15076)
W/BroadcastQueue(  909): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:401)
W/BroadcastQueue(  909): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2330)
W/BroadcastQueue(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/BroadcastQueue(  909): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4539 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4539): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4539): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4539): 	at del.a(PG:264)
E/SQLiteDatabase( 4539): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4539): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  909): acquireWL(4260ce80): PARTIAL_WAKE_LOCK  AsyncService 0x1 4539 10160 null
W/dalvikvm( 4111): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
E/SQLiteDatabase( 4539): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4539): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4539): 	at del.a(PG:264)
E/SQLiteDatabase( 4539): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4539): 	at java.lang.Thread.run(Thread.java:864)
E/EsApplication( 4539): Failed app initialization
E/EsApplication( 4539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4539): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4539): 	at del.a(PG:264)
E/EsApplication( 4539): 	at eeq.run(PG:187)
E/EsApplication( 4539): 	at java.lang.Thread.run(Thread.java:864)
D/PackageBroadcastService( 2181): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2181): Clearing selected account for com.test.thalitest
D/PMS     (  909): releaseWL(4260ce80): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2181): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2181): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2181): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2181): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2181): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2181): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2181): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2181): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2181): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2181): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2181): App measurement is starting up, version: 8489
I/GMPM-SVC( 2181): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b60bd0 +
I/Prism.WidgetManager( 1272): onLoadItems() +
E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x6b10bcc8
E/DriveAsyncService( 2181): disk I/O error (code 3850)
E/DriveAsyncService( 2181): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2181): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2181): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2181): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2181): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2181): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2181): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  909): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2181): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2181): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6e5a7c50
W/dalvikvm( 2181): threadid=50: thread exiting with uncaught exception (group=0x4169de30)
I/Icing   ( 2181): doRemovePackageData com.test.thalitest
D/PMS     (  909): acquireWL(4264b9f8): PARTIAL_WAKE_LOCK  Icing 0x1 2181 10029 WorkSource{10029 com.google.android.gms}
E/AndroidRuntime( 2181): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2181): Process: com.google.android.gms, PID: 2181
E/AndroidRuntime( 2181): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2181): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2181): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2181): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2181): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2181): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 2181): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2181): Module APK com.google.android.play.games already loaded
E/ActivityManager(  909): App crashed! Process: com.google.android.gms
D/Process ( 2181): killProcess, pid=2181
E/SQLiteDatabase( 2181): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2181): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2181): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2181): Opening the database failed, dropping and recreating it
E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop149.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
E/SQLiteDatabase( 2181): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2181): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2181): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2181): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2181): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2181): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2181): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
D/PMS     (  909): releaseWL(4264b9f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}

```
