#### Test 58135655a1ee273_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4066 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{42390790: PendingIntentRecord{423a8de0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454597178334, Int=0
--------- beginning of /dev/log/main
I/ImageRamCache( 4066): create image Cache, size: 31457280.
I/ImageRamCache( 4066): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4066): create image Cache, size: 12582912.
I/FeedSettings( 4066): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4066): GroupBudget 0.500000 0.380000
I/FeedSettings( 4066): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4066): changeLocale(): en_GB
I/SensorManager(  906): mEventCount = 450
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/WIFI_ICON( 1116): WifiActivity: 1
I/Prism.AllAppsOptionsMa_( 4066): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4066): loadGridSize() with Alternative
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=50 rxSum=38} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20423 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20424 delay=15s
I/ActivityManager(  906): Delay finish: com.htc.launcher/.receiver.BiLogReceiver
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b08c78 +
I/Prism.WidgetManager( 1272): onLoadItems() +
I/SocialManager[SocialBiLogHelper]( 4066): action: com.htc.sense.hsp.HANDLE_ULOG
I/ActivityManager(  906): Resuming delayed broadcast
I/SocialManager[SocialBiLogHelper]( 4066): last commit ulog time 1454578885926
I/SocialManager[SocialBiLogHelper]( 4066): skip commit this time
I/ActivityManager(  906): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4089 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3723
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3723:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  906): acquireWL(4274d0d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3723
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/LocationProviderProxy(  906): applying state to connected service
D/DotMatrix( 1587): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/PMS     (  906): releaseWL(4274d0d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
I/RemoteViews( 1116): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41d96aa0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.htc.updater 4 12 0 10
D/PMS     (  906): acquireWL(426fedb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426dbe18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/RemoteViews( 1116): com.htc.updater (true,33751552)
D/PMS     (  906): releaseWL(426fedb8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426dbe18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41d51c60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.htc.updater 0 7 1 10
D/PMS     (  906): acquireWL(426b6eb8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426b6eb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/GAV2    ( 4089): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils-trace( 4078): Error opening trace file: No such file or directory (2)
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  906): acquireWL(42668cd8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42668cd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=3628
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3628:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3628
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
D/PMS     (  906): acquireWL(425d62e0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4078): ====startRecUseTime====
D/htc.customization.log.level( 4078):  is 
W/CustomizationLogLevel( 4078): Level value is invalid, use default level 2
I/Gmail   ( 4089): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4089): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4089): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4089): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PMS     (  906): releaseWL(425d62e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(423e00f0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423e00f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42393b50): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4078):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4078): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4078): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4078): Parsing tag category name = system
I/CustomizationCIDLoader( 4078): Parsing tag category name = application
I/CustomizationCIDLoader( 4078): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4078): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4078): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4078): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4078): Parsing tag category name = Settings
D/CustomizationManager( 4078):  Read CID file spent 0.137 (s)
D/CustomizationManager( 4078):  All configurations done spent 0.137 (s)
W/HtcNativeFlag( 4078): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4078): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4078): Fail to get flag for type 'language', use default value: -1
E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b08c78 -
D/PMS     (  906): releaseWL(42393b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(423e0d48): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423e0d48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4236ae80): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4078
D/PMS     (  906): releaseWL(4236ae80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PhoneApp( 1239): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1239): -- N1 =0
D/PMS     (  906): acquireWL(4227ff80): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4227ff80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PhoneApp( 1239): -- N2 =0
D/PhoneApp( 1239): -- N3 =0
D/PMS     (  906): acquireWL(424dd158): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(424dd158): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(423c5a00): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423c5a00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42207fe8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42207fe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 435 ms] updated apps [took 435 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4132 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  906): acquireWL(41b8e178): PARTIAL_WAKE_LOCK  AsyncService 0x1 4132 10160 null
D/PMS     (  906): releaseWL(41b8e178): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(424f6de0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4132 10160 null
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4156 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/PMS     (  906): acquireWL(424aa178): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4132 10160 null
D/PMS     (  906): releaseWL(424f6de0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4132/10160)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/Process (  906): killProcessQuiet, pid=3808
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(424aa178): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  906): Killing 3808:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
W/dalvikvm( 4156): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
V/AlarmManager(  906): sending alarm PendingIntent{41baf428: PendingIntentRecord{4246e300 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59626, Int=0
I/ActivityManager(  906): Recipient 3808
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4156, uid=10074, userID:0
D/Settings:HtcWirelessFeatureFlags( 3834): id/is att sku: 99/false
D/Finsky  ( 4156): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4156/10074)
W/SystemReader( 3834): Cannot find devicepolicy_lower_fp_quality, use default value instead
W/SystemReader( 3834): Cannot find support_harman, use default value instead
W/SystemReader( 3834): Cannot find effect_manager_id, use default value instead
E/Settings:HtcWrapHeaderInfo( 3834): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3834): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3834): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3834): isSupportMusicChannel(): false
W/dalvikvm( 4156): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]support         :false
W/dalvikvm( 4156): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
W/FingerprintManager( 3834): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4156/10074)
E/Settings:HtcVoWifiWidgetEnabler( 3834): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3834): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 4156): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4156): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4156): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4156): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 4156): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4156): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4156): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4156): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4156, uid=10074, userID:0
D/Ads     ( 4156): Skipping gmscore version check
D/Finsky  ( 4156): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4156): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4156): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3834): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3834): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3834): isSupportMusicChannel(): false
W/dalvikvm( 4156): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3834): [supportHomeButton]support         :false
W/FingerprintManager( 3834): hasFingerprint() - sSensorCode = 0
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 3834): isSupportVoWifi: null
D/Finsky  ( 4156): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/ActivityThread( 3834): Failed to find provider info for com.htc.vowifi
I/ActivityManager(  906): Resuming delayed broadcast
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/Process (  906): killProcessQuiet, pid=3754
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  906): Killing 3754:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/HtcModeClient( 1512): handler message = 4011
E/HtcModeClient( 1512): Check connection and retry 6 times.
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3754
D/PMS     (  906): acquireWL(422c16e0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(422c16e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4260cf08): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2185): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2185): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2185): cleanUpNonGplusAccounts done.
,D/Process (  906): killProcessQuiet, pid=3767
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3767:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3767
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(4260cf08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4203 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 4203): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4203): MmsConfig.loadMmsSettings
,W/dalvikvm( 4203): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4203): VFY: unable to resolve instance field 36
,W/dalvikvm( 4203): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4203): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3779): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3779): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4203): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4203): MmsConfig.loadFromDatabase
,E/Babel   ( 4203): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4203): MmsConfig.loadFromResources
,E/Babel   ( 4203): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4203): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4203, uid=10111, userID:0
,W/Settings( 4203): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4203, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4203, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4203, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4203, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4203, uid=10111, userID:0
D/PMS     (  906): acquireWL(4259b398): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4203 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4203): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(4259b398): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(426d89e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4203 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(426d89e0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3852
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3852:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  906): acquireWL(426bc218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
I/ActivityManager(  906): Recipient 3852
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426bc218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426b8368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  906): releaseWL(426b8368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/PMS     (  906): acquireWL(425ec428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(425ec428): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426d6048): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): releaseWL(426d6048): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PMS     (  906): acquireWL(42738078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42738078): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42705ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42705ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(426a3118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
D/PMS     (  906): releaseWL(426a3118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=3446
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3446:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(426037b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
I/ActivityManager(  906): Recipient 3446
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426037b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4221afa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4246 uid=10041 gids={50041}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4221afa8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=3475
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3475:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3475
,I/BroadcastQueue(  906): Schedule to resend BroadcastRecord{42661878 u0 com.htc.intent.lockscreen.ClearTASKReminder callingPid=3475 callingUid=10071} for ResolveInfo{426bd988 com.htc.task/.notification.NotifyReceiver m=0x108000} of com.htc.task
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4259 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(425d4d48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4259 10071 null
,D/PMS     (  906): acquireWL(425a9ce0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4259 10071 null
,D/PMS     (  906): acquireWL(4256c588): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4203 10111 null
,D/PMS     (  906): releaseWL(425d4d48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
E/TodoTaskNotifyService( 4259): java.lang.NullPointerException
W/System.err( 4259): java.lang.NullPointerException
W/System.err( 4259): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4259): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4259): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4259): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4259): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4259): stopSelfResult true
D/PMS     (  906): releaseWL(425a9ce0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  906): releaseWL(4256c588): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
D/Process (  906): killProcessQuiet, pid=3987
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3987:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
I/ActivityManager(  906): Recipient 3987
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
D/WearableService( 1221): callingUid 10029, callindPid: 1221
,E/MDM     ( 1221): [109] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2185): Restart initialization of location
D/AuthorizationBluetoothService( 1358): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1358): Proximity feature is not enabled.
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(420a49f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4259 10071 null
D/PMS     (  906): acquireWL(425517f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4259 10071 null
W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
,E/TodoTaskNotifyService( 4259): java.lang.NullPointerException
W/System.err( 4259): java.lang.NullPointerException
W/System.err( 4259): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4259): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4259): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4259): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4259): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(423d8b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(423d8b98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(420a49f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
D/PMS     (  906): releaseWL(425517f8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4259): stopSelfResult true
E/TodoTaskNotifyService( 4259): java.lang.NullPointerException
,W/System.err( 4259): java.lang.NullPointerException
W/System.err( 4259): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4259): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
D/PMS     (  906): acquireWL(42428538): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4259 10071 null
D/PMS     (  906): acquireWL(42388308): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4259 10071 null
,D/PMS     (  906): releaseWL(42428538): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/System.err( 4259): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4259): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4259): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4259): stopSelfResult true
,I/WSP     ( 1341): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1341): Weather sync is On
D/PMS     (  906): releaseWL(42388308): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WSP     ( 1341): [Receiver] next auto-sync alarm event is 60 mins later, at time: Thu Feb 04 16:46:22 CET 2016
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,D/PMS     (  906): acquireWL(424b3c80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1341 10055 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/GCM     ( 1358): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  906): acquireWL(4241c068): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4203 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(4241c068): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(424b11b0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424b11b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423c8818): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423c8818): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42676ae0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42676ae0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42665960): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42665960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42421960): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42421960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(420e4cf0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(420e4cf0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42638dc0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42638dc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(424f3280): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/PMS     (  906): releaseWL(424f3280): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:80, mTXpacketCount:54, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 232 ms] updated apps [took 232 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42642888): PARTIAL_WAKE_LOCK  AsyncService 0x1 4132 10160 null
,D/PMS     (  906): releaseWL(42642888): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2185): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  906): acquireWL(4261c2b0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2185): updateResources: need to parse f{com.google.android.gms}
,D/PMS     (  906): acquireWL(42634240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42634240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/TodoTaskshortcut( 4259): update TASK shortcut>
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,W/SQLiteConnectionPool( 2185): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,V/AlarmManager(  906): sending alarm PendingIntent{425bfef0: PendingIntentRecord{425a3920 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454597182984, Int=0
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/GAV2    ( 4089): Thread[GAThread,5,main]: No campaign data found.
,D/Icing   ( 2185): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(4261c2b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{41ec9648: PendingIntentRecord{4258f3c0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454597184646, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42390550: PendingIntentRecord{425636b8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454597184692, Int=0
,I/iu.UploadsManager( 2185): End new media; added: 0, uploading: 0, time: 50 ms
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 7 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 600
,I/GAV4    ( 4203): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/CheckinService( 2185): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/CalendarProvider2( 1512): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1512): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(425c2120): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(4271afa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(425c2120): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(4271afa0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  906): acquireWL(42701848): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3891 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3891): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3891): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3891): Conditions not met for autocaching.
,I/MusicLeanback( 3891): Stop autocaching.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3891, uid=10154, userID:0
D/PMS     (  906): releaseWL(42701848): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4263e790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4263e790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(425fd4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(425fd4a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426d5d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/PMS     (  906): releaseWL(426d5d00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,W/MediaManager( 3869): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4318 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4318): Loading default preferences
,W/Resources( 4318): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4318): Overriding preferences with custom values
,D/SyncApplication( 4318): Updating preferences succeeded
,E/SyncApplication( 4318): Application created.
D/VolumeInfo( 4318): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4318): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4318): Found 0 mount point(s)
,V/VolumeInfo( 4318): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4318): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4318): getNewCalendarAuthority()...
,D/VolumeInfo( 4318): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4318): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4318): enableAppOperation()+
,D/SyncApplication( 4318): enableAppOperation()-
,D/HTCUtilities( 4318): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4318, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4318, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4318): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4318): isNeorSinged() return false
,D/CDMountReceiver( 4318): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4318): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1587): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4318): enable CD Auto-mount: true
,D/HTCUtilities( 4318): enable auto-mount
,D/HTCUtilities( 4318): enable auto-mount
,I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e369f8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(425aa160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 1 12 4 11
,I/RemoteViews( 1116): com.nero.android.htc.sync (false,0)
,D/Process (  906): killProcessQuiet, pid=3912
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4339 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  906): Killing 3912:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e1e660 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.nero.android.htc.sync 1 11 3 16
I/ActivityManager(  906): Recipient 3912
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4339): onCreate
D/ProviderChangeReceiver( 4339): ---------------------------------------------------
,D/ProviderChangeReceiver( 4339): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4339): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4353 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  906): Killing 3946:com.htc.sdm/u0a81 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3946
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4339): No fired or scheduled alerts
,D/HtcAlertUtils( 4339): -- cancelReminderNotification --
,D/HtcAlertUtils( 4339): broadcastExistReminder!
I/ActivityManager(  906): Recipient 3946
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4353): [4353/4353] onCreate()
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 4026:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=4026
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,I/ActivityManager(  906): Recipient 4026
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 8 times.
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{425e45b0 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42537b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42537b60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=97
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  906): releaseWL(424b3c80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=50 rxSum=38} preTxRxSum={txSum=50 rxSum=38}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20424 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20425 delay=15s
D/PMS     (  906): acquireWL(424f7280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41c4a098: PendingIntentRecord{425324c8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=73491, Int=0
D/PMS     (  906): releaseWL(424f7280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 9 times.
,I/SensorManager(  906): mEventCount = 750
,D/Finsky  ( 4156): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4156): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  906): acquireWL(424ef1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{42338868: PendingIntentRecord{426b6a68 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454597196319, Int=0
D/PMS     (  906): releaseWL(424ef1f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4156/10074)
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4156): [NET] getaddrinfo-,err=8
D/libc    ( 4156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4156): [NET] getaddrinfo-, 1
D/libc    ( 4156): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2c6c +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4156): [NET] getaddrinfo_proxy-, success
I/global  ( 4156): call createSocket() return a new socket.
D/libc    ( 4156): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4156): [NET] getaddrinfo-, SUCCESS
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4156): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4156): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4156): untagSocket(69) failed with errno -22
,D/Finsky  ( 4156): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4156): untagSocket(69) failed with errno -22
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [24][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:104, mTXpacketCount:80, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4156): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4156/10074)
,D/Finsky  ( 4156): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(426d1348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{4273af00: PendingIntentRecord{42279040 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454597198400, Int=0
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/PMS     (  906): acquireWL(4261ddf8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4156 10074 null
,D/PMS     (  906): releaseWL(426d1348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4156): [447] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1221): client connected with version: 8296000
,D/Finsky  ( 4156): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4156): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1358): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4156): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4156): [NET] getaddrinfo-,err=8
D/libc    ( 4156): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4156): [NET] getaddrinfo-, 1
,D/libc    ( 4156): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2e46 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 236
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4156): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  906): releaseWL(4261ddf8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 10 times.
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=15 [52][8][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 900
,D/AutoSetting( 1341): service - has update message, not stop
,D/AutoSetting( 1341): service - mHandler: update timezone
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1512): service - mHandler: update timezone
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1587): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1587): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1116): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e9e6e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.htc.htclocationservice 2 7 3 11
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 11 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(42681650): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42681650): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426b58d0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426b58d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42678f08): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42678f08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(425e02d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=125 rxSum=109} preTxRxSum={txSum=50 rxSum=38}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20425 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20426 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{42355e28: PendingIntentRecord{425324c8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88497, Int=0
D/PMS     (  906): releaseWL(425e02d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:165, mTXpacketCount:104, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1512): Don't start project servcice
,D/HtcModeClient( 1512): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1512): connectState: CONNECTION_READY = false
,D/SilentMusic( 1512): call stop
,D/HtcModeClient( 1512): close connection
,W/HtcModeClient( 1512): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1512): read the terminate packet, so break
,D/PMS     (  906): acquireWL(4265cb38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{422a02e0: PendingIntentRecord{41e2fa00 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454597212721, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4384 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{423038a8: PendingIntentRecord{42509d70 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454597215509, Int=60000
D/PMS     (  906): releaseWL(4265cb38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SMSBackup( 4384): SMSBackupAgentService started
,D/SMSBackup( 4384): Checking restore status
,D/SMSBackup( 4384): Restore complete
,D/SMSBackup( 4384): cancelCheckAlarm
,D/SMSBackup( 4384): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Finsky  ( 4156): [437] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4156): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=4046
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4046:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4046
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1050
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4274ce28 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true,
,V/LightsService(  906): setLight #0: color=#3e
,V/LightsService(  906): setLight #0: color=#3a
,V/LightsService(  906): setLight #0: color=#34
,V/LightsService(  906): setLight #0: color=#2d
,V/LightsService(  906): setLight #0: color=#26
,V/LightsService(  906): setLight #0: color=#20
,V/LightsService(  906): setLight #0: color=#19
,V/LightsService(  906): setLight #0: color=#14
,D/PMS     (  906): acquireWL(4269eb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=100010, Int=0
,D/PMS     (  906): releaseWL(4269eb98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1116): now=1454597220060 next=59940
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=125 rxSum=109} preTxRxSum={txSum=125 rxSum=109}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20426 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20427 delay=15s
D/PMS     (  906): acquireWL(425f4ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{425eae20: PendingIntentRecord{425324c8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103502, Int=0
D/PMS     (  906): releaseWL(425f4ca0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,W/PMS     (  906): mWirelessDisplayManager is null
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4214a2a0
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  906): setLight #0: color=#0
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4214a2a0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3d288
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@4267c898
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 319ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,D/NfcService( 1253): applyRouting -2
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMS     (  906): OOBE c monitor 11
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1272
D/PMS     (  906): acquireWL(426fa690): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/PMS     (  906): releaseWL(426fa690): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426fbee8)
,I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
D/PMS     (  906): acquireWL(426fb730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMN     (  906): wakingUp
D/PMS     (  906): releaseWL(426fb730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
,D/MtpService( 2741): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/MtpService( 2741): [MTP][onReceive]-
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1253): applyRouting - 0
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/NfcService( 1253): applyRouting -2
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): acquireWL(4277c610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  906): releaseWL(4277c610): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/AutoSetting( 1341): receiver - intent: android.intent.action.USER_PRESENT
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/AutoSetting( 1341): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/ClockThread( 1116): stop update clock
D/TetherSettings( 3834): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3834): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3834): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3834): Cust_ConnectToPC   : spcsc>false
D/        ( 3834): Cust_ConnectToPC   : IPT>true
D/        ( 3834): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3834): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3834): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3834): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3834): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/PSReceiver( 3834): onReceive:android.intent.action.USER_PRESENT
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20428 delay=15s
I/SmartNS_PSService( 3834): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3834): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3834):  defaultType:0
I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:On
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1187): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
,D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
,D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1187): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:165, mTXpacketCount:165, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4406 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(42792e48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42792e48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42794410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42794410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1738): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1738): onScreenOn: 1454597226798
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1738): onScreenOn: 1454597226798
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3d288
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3d288, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@4267c898,
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SmartSyncUtils( 4406): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(427983d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4406 1000 null
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(42799980): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/PMS     (  906): releaseWL(427983d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/FeedHostManager( 1272): [onPause]
,I/FeedProviderManager( 1272): onPause
,I/SocialFeedProvider( 1272): +onPause
,I/SocialFeedProvider( 1272): -onPause
,I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b67488
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20428 mDataStallAlarmIntent=PendingIntent{4229e510: PendingIntentRecord{425324c8 android broadcastIntent}}
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1187): SET_SCREEN_ON:Off
I/wpa_supplicant( 1187): htc_wext_set_keepalive +
I/wpa_supplicant( 1187): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1187): getPrivFuncNum +	
I/wpa_supplicant( 1187): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1187): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1187): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1187): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1187): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(427a2ab0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
D/PMS     (  906): releaseWL(42799980): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
V/SRS_Proc(  370): ParamSet string: screen_state=off
D/ContactMessageStore( 1239): start background delete task...
D/NetworkPolicy(  906): updateScreenOn: false
D/ContactMessageStore( 1239): size: 0 , 0
D/ContactMessageStore( 1239): Background delete complete
D/wpa_supplicant( 1187): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(427a2ab0): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4406): isEpsOn(), nState = 0
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4267c898
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4267c898, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4267c898, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4267c898
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4267ce10 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4267ce10 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  906): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  906): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  906): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  906): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  906): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  906): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  906): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  906): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  906): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/AutoSetting( 1341): service - mHandler: cancel location update
,D/AutoSetting( 1341): service -           changes count: 0
,D/SmartSyncUtils( 4406): getMobilePolicyEnabled, result = true
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4406): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4406): getMobilePolicyEnabled, result = true
D/PMS     (  906): acquireWL(427b39b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): releaseWL(427b39b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(427b2d88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427b2d88): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1738): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1738): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1738): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1738): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1738): onScreenOff
,D/Process (  906): killProcessQuiet, pid=4066
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4066:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4066
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1512): service - handleMessage() stop self
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3641
,I/ActivityManager(  906): Killing 3641:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3641
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1239): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  906): killProcessQuiet, pid=3926
,I/ActivityManager(  906): Killing 3926:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3926
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(4270fd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{41bb7588: PendingIntentRecord{426a6c88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121758, Int=0
,D/PMS     (  906): releaseWL(4270fd98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426e8628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426c40a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426c40a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426e8628): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426c3c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(426c3c20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426bd160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426bc6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4266f0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1454597242063 tag=VacuumService
,D/PMS     (  906): releaseWL(426bd160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426bc6f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42394158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(42394158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(422d3d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4266f0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(422d3d58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425d5490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(425d5490): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  906): acquireWL(422889a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(422889a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(423097a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42547fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42547fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4247c240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(423097a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42428640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(42428640): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 5633 seconds from now (1454597242884)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =370c +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8,
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(4247c240): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4266c1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(4266c1e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423a7710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1187): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1187): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1187): nl80211: survey data missing!
E/wpa_supplicant( 1187): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1187): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(423a7710): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4271acb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4271acb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425ae5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42677468: PendingIntentRecord{42499e78 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137085, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,D/PMS     (  906): releaseWL(425ae5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1341): service - handleMessage() stop self
,D/AutoSetting( 1341): service - onDestroy() END
,D/AutoSetting( 1341): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3779
,I/ActivityManager(  906): Killing 3779:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3779
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425ac198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423a8990: PendingIntentRecord{42399400 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141874, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(427070e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(425ac198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ac51 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(427070e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(427920d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PMS     (  906): releaseWL(427920d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1116): closing low battery warning: level=97
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,97,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:97 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4260ceb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4260ceb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426db738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{41f5f390: PendingIntentRecord{42614268 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173407, Int=0
,D/PMS     (  906): releaseWL(426db738): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1239): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(427154c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427154c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425bba18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/PMS     (  906): releaseWL(425bba18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=98
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,98,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4265a330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4265a330): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4260d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4260d7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(425507e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=280010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425507e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425e0968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425e0968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426ddaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=340010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426ddaf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  906): killProcessQuiet, pid=4246
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4246:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4246
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(427a2990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427a2990): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(427ae870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(427ae870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426599a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=400010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426599a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42641e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42641e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(426dc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=460010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426dc070): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4234ecd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4234ecd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=99
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1116): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(426c75e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426c75e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426b7368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=520010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426b7368): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426cb040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426cb040): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42674db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  906): releaseWL(42674db8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1587): [EventService] reorderNotification, total:0
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1587): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/HeadsetPhoneState( 1626): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,W/ContextImpl( 4406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3834): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3834): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3834): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3834): Cust_ConnectToPC   : spcsc>false
D/        ( 3834): Cust_ConnectToPC   : IPT>true
,D/        ( 3834): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3834): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3834): Index of the first 1 = -1
W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,W/Settings( 3834): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 3834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 3834): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3834): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3834): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3834): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  906): acquireWL(426ae438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=580010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426ae438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42658208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42658208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1239): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1239): sku_id=99
,D/ContactMessageStore( 1239): start background delete task...
,D/ContactMessageStore( 1239): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1239): size: 0 , 0
,D/ContactMessageStore( 1239): Background delete complete
,D/PMS     (  906): acquireWL(4273c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=640010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4273c798): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427a7038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427a7038): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425d1c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=700010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425d1c68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426fab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426fab18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42782888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=760010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42782888): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42794910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42794910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4277c9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=820010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4277c9e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427aa850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427aa850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42687748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=880010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42687748): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42784b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42784b00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(427a8648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=940010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427a8648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426f96d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  906): sending alarm PendingIntent{41caced0: PendingIntentRecord{42407f20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782132, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{423ce108: PendingIntentRecord{424bcff0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=947304, Int=0
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(4278a338): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4278a338): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4463 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{422b5508: PendingIntentRecord{42617648 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454597331576, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{42401ff0: PendingIntentRecord{42672948 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454598051865, Int=900000
,W/ContextImpl( 4406): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4406): call getInstance()
,D/PMS     (  906): releaseWL(426f96d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4406): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4463/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=4203
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4203:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4203
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(425f01b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1358 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1358/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1358/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024485
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024629
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024689
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024692
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024698
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024701
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026179
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360026197
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360029170
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360030083
,D/PMS     (  906): releaseWL(425f01b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(42585b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42585b38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(425771a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1000010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425771a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4250af88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{422e7f58: PendingIntentRecord{427a59c0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454598126924, Int=0
,D/SmartSyncUtils( 4406): isEpsOn(), nState = 0
D/PMS     (  906): acquireWL(424b3c80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4406 1000 null
,D/PMS     (  906): releaseWL(4250af88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4406): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4406): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4406): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4406): SettingOnTime = 1454652000000, randomSettingOnTime = 1454649518000
D/SmartSyncScreenOnOffTimeReceiver( 4406): SettingOffTime = 1454637600000, randomSettingOffTime = 1454641751000
D/SmartSyncScreenOnOffTimeReceiver( 4406): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4406): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4406): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(424b3c80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(423e00f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(423e00f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423a50c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1060010, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423a50c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42377bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42377bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(423451c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1120010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(423451c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420c2608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(420c2608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(41cf43a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1180010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41cf43a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41fb16b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41fb16b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(42299cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41f77078: PendingIntentRecord{41a773f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1240010, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42299cc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4483): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4483): ====startRecUseTime====
D/htc.customization.log.level( 4483):  is 
W/CustomizationLogLevel( 4483): Level value is invalid, use default level 2
D/CustomizationManager( 4483):  Read ACC file spent 0.113 (s)
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4483): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4483): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4483): Parsing tag category name = system
I/CustomizationCIDLoader( 4483): Parsing tag category name = application
I/CustomizationCIDLoader( 4483): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4483): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4483): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4483): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4483): Parsing tag category name = Settings
D/CustomizationManager( 4483):  Read CID file spent 0.167 (s)
D/CustomizationManager( 4483):  All configurations done spent 0.167 (s)
W/HtcNativeFlag( 4483): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4483): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4483): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4483, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{421c5fc0 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{421cdbc0 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
D/DotMatrix( 1587): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1587): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1587): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(4267f2b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
D/PMS     (  906): releaseWL(4267f2b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/AccTypeManager( 1328): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/VoicemailCleanupService( 1296): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 1328): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1328): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
D/PMS     (  906): acquireWL(428f5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(428f5360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
E/ExternalAccountType( 1328): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1239 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4498 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PhoneApp( 1239): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
E/SQLiteDatabase( 4498): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4498): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4498): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4498): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4498): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4498): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4498): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4498): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4498): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4498): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4498): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4498): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4498): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4498): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4498): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4498): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4498): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4498): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4498): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4498): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4498): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4498): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4498): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4498): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4498): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4498): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4498): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4498): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4498): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4498): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4498): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4498): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4498): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4498): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4498): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4498): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4498): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4498): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4498): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4498): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4498): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4498): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4498): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4498): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4498): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4498): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4498): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4498): threadid=11: thread exiting with uncaught exception (group=0x41642e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4498): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4498): Process: com.google.android.apps.docs, PID: 4498
E/AndroidRuntime( 4498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4498): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4498): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4498): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4498): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4498): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4498): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4498): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4498): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4498): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4498): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4498): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4498): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4498): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4498): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4498): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4498): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4498): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4498): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4498): killProcess, pid=4498
D/Process ( 4498): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4515 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4498
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4498) has died.
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41b08c78 +
I/Prism.WidgetManager( 1272): onLoadItems() +
W/ContextImpl( 4515): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
W/PackageManager(  906): Unable to load service info ResolveInfo{42552f48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4528 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4515): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4515): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4515): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4515): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4515): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4515): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4515): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4515): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4515): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4515): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4515): threadid=10: thread exiting with uncaught exception (group=0x41642e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4515): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4515): Process: com.android.keychain, PID: 4515
E/AndroidRuntime( 4515): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4515): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4515): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4515): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4515): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4515): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4515): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4515): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4515): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4515): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4528): getInstance(Context context)
D/AppTag  ( 4528): getInstance(Context context)
D/Process ( 4515): killProcess, pid=4515
D/Process ( 4515): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4528): onCreate()
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454598393154.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 4 more
I/ActivityManager(  906): Recipient 4515
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4515) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/PMS     (  906): acquireWL(42638e40): PARTIAL_WAKE_LOCK  AsyncService 0x1 4132 10160 null
D/PMS     (  906): releaseWL(42638e40): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4156): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  906): killProcessQuiet, pid=4259
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4259:com.htc.task/u0a71 (adj 15): empty #17
I/ActivityManager(  906): Recipient 4259
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccountUtils( 2185): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2185): Removing dialog suppression flag for package com.test.thalitest

```
