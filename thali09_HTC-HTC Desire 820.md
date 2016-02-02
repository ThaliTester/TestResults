#### Test 5753124305d96c2_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Ads     ( 4080): Skipping gmscore version check
D/Finsky  ( 4080): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4080): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4080): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/dalvikvm( 4080): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
--------- beginning of /dev/log/system
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/Finsky  ( 4080): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Process (  906): killProcessQuiet, pid=3671
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3671:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  906): Recipient 3671
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426bab60): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2177): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2177): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2177): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2177): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2177): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2177): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 2177): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2177, uid=10029, userID:0
I/PeopleDatabaseHelper( 2177): cleanUpNonGplusAccounts done.
E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bfac38 -
I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4131 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
V/AlarmManager(  906): sending alarm PendingIntent{425d2330: PendingIntentRecord{425fd088 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1454422497880, Int=0
E/cutils-trace( 4129): Error opening trace file: No such file or directory (2)
I/ImageRamCache( 4131): create image Cache, size: 31457280.
I/ImageRamCache( 4131): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4131): create image Cache, size: 12582912.
I/FeedSettings( 4131): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4131): GroupBudget 0.500000 0.380000
I/FeedSettings( 4131): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4131): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 4131): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 4131): loadGridSize() with Alternative
D/PhoneApp( 1237): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1237): -- N1 =0
D/PhoneApp( 1237): -- N2 =0
D/PhoneApp( 1237): -- N3 =0
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/SocialManager[SocialBiLogHelper]( 4131): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4131): last commit ulog time 1454392527077
I/SocialManager[SocialBiLogHelper]( 4131): skip commit this time
D/Process (  906): killProcessQuiet, pid=3404
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3404:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  906): applying state to connected service
D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(425127a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(425127a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426e9400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426e9400): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4129): ====startRecUseTime====
D/htc.customization.log.level( 4129):  is 
W/CustomizationLogLevel( 4129): Level value is invalid, use default level 2
D/PMS     (  906): acquireWL(427abb98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427abb98): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4276f3a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4276f3a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3404
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 4129):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4129): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4129): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4129): Parsing tag category name = system
I/CustomizationCIDLoader( 4129): Parsing tag category name = application
I/CustomizationCIDLoader( 4129): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4129): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4129): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4129): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4129): Parsing tag category name = Settings
D/CustomizationManager( 4129):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4129):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4129): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4129): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4129): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4129): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4129
D/Process (  906): killProcessQuiet, pid=3790
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3790:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3790
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/AlarmManager(  906): sending alarm PendingIntent{41d97f08: PendingIntentRecord{425645a8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58885, Int=0
I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(426bab60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(427ab2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(427ab2a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(426e1738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426e1738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/PMS     (  906): acquireWL(42571840): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1221): No location to return for getLastLocation()
W/FusedLocationProvider( 1221): location=null
D/PMS     (  906): acquireWL(4270f748): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42571840): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4270f748): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): acquireWL(426b1f20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/SQLiteConnectionPool( 2177): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
I/HtcModeClient( 1476): handler message = 4011
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
E/HtcModeClient( 1476): Check connection and retry 6 times.
D/PMS     (  906): releaseWL(426b1f20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42708ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
D/PMS     (  906): releaseWL(42708ec0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  906): killProcessQuiet, pid=3416
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(41d23cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
I/ActivityManager(  906): Killing 3416:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3416
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(41d23cc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(426b0da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426b0da8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(426d7038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4163 uid=10041 gids={50041}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426d7038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/Process (  906): killProcessQuiet, pid=3906
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  906): acquireWL(426bc9f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3450 10071 null
I/ActivityManager(  906): Killing 3906:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/PMS     (  906): acquireWL(426ef170): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3450 10071 null
D/PMS     (  906): releaseWL(426bc9f0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3450): java.lang.NullPointerException
W/System.err( 3450): java.lang.NullPointerException
W/System.err( 3450): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3450): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3450): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(427fc168): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4011 10111 null
D/PMS     (  906): releaseWL(426ef170): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
W/NotifyReceiver( 3450): stopSelfResult true
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  906): Recipient 3906
D/WifiService(  906): Client connection lost with reason: 4
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(4280d4b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3450 10071 null
D/PMS     (  906): releaseWL(427fc168): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
E/TodoTaskNotifyService( 3450): java.lang.NullPointerException
W/System.err( 3450): java.lang.NullPointerException
W/System.err( 3450): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3450): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3450): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(42766950): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3450 10071 null
D/PMS     (  906): releaseWL(4280d4b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(42766950): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
W/NotifyReceiver( 3450): stopSelfResult true
E/TodoTaskNotifyService( 3450): java.lang.NullPointerException
W/System.err( 3450): java.lang.NullPointerException
W/System.err( 3450): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3450): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3450): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  906): acquireWL(427016f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3450 10071 null
D/PMS     (  906): acquireWL(42803958): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3450 10071 null
D/PMS     (  906): releaseWL(427016f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  906): releaseWL(42803958): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3450): stopSelfResult true
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,E/MDM     ( 1221): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2177): Restart initialization of location
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,I/WSP     ( 1318): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
W/FusedLocationProvider( 1221): location=null
,D/WeatherUtility( 1318): Weather sync is On
,I/WSP     ( 1318): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 16:14:59 CET 2016
D/PMS     (  906): acquireWL(426dbe00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426dbe00): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
D/PMS     (  906): acquireWL(427a1e80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1318 10055 null
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3450): update TASK shortcut>
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=60313, Int=0
,I/GAV2    ( 3983): Thread[GAThread,5,main]: No campaign data found.
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAv4-SVC( 2177): Google Analytics 8.4.89 is starting up.
,V/AlarmManager(  906): sending alarm PendingIntent{426c7970: PendingIntentRecord{426c7938 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454422500189, Int=0
,I/ClockThread( 1115): now=1454422500342 next=59658
,I/GAV4    ( 4011): Thread[GAThread,5,main]: No campaign data found.
,I/SensorManager(  906): mEventCount = 450
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,V/AlarmManager(  906): sending alarm PendingIntent{42725558: PendingIntentRecord{423005e0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454422501882, Int=0
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:63, mTXpacketCount:36, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  906): acquireWL(4275c440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/PowerUI ( 1115): closing low battery warning: level=99
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(4275c440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
V/AlarmManager(  906): sending alarm PendingIntent{4278ad20: PendingIntentRecord{4278ac60 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454422501944, Int=0
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/iu.UploadsManager( 2177): End new media; added: 0, uploading: 0, time: 80 ms
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 7 times.
,D/Process (  906): killProcessQuiet, pid=3945
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3945:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3945
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/CalendarProvider2( 1476): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1476): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4270b128): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4011 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(4270b128): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  906): acquireWL(426e5590): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426e5590): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426db2b0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426db2b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426cdab8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426cdab8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426c2228): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426c2228): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426ae390): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426ae390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426a83b8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426a83b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42699a38): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42699a38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42691f00): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42691f00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(4251d438): PARTIAL_WAKE_LOCK  AsyncService 0x1 4054 10160 null
,D/PMS     (  906): releaseWL(4251d438): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2177): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/Icing   ( 2177): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  906): acquireWL(41de36c8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/CheckinService( 2177): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2177): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(41de36c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42549558): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3831 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3831): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3831, uid=10154, userID:0
,I/MusicLeanback( 3831): Conditions not met for autocaching.
,I/MusicLeanback( 3831): Stop autocaching.
,W/ContextImpl( 3831): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  906): releaseWL(42549558): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42354db8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(41d8ec10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42354db8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(41d8ec10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(42427748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  906): releaseWL(42427748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426643f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426643f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42681130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  906): releaseWL(42681130): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/MediaManager( 3807): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4225 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4225): Loading default preferences
,W/Resources( 4225): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4225): Overriding preferences with custom values
,D/SyncApplication( 4225): Updating preferences succeeded
,E/SyncApplication( 4225): Application created.
D/VolumeInfo( 4225): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4225): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4225): Found 0 mount point(s)
,V/VolumeInfo( 4225): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4225): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4225): getNewCalendarAuthority()...
,D/VolumeInfo( 4225): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4225): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4225): enableAppOperation()+
,D/SyncApplication( 4225): enableAppOperation()-
,D/HTCUtilities( 4225): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4225, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4225, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4225): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4225): isNeorSinged() return false
,D/CDMountReceiver( 4225): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4225): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4225): enable CD Auto-mount: true
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/HTCUtilities( 4225): enable auto-mount
,D/HTCUtilities( 4225): enable auto-mount
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(426d6bd8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41d0bc20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4246 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 14 3 11
I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41d09978 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 9 3 16
,D/CalendarApplication( 4246): onCreate
D/ProviderChangeReceiver( 4246): ---------------------------------------------------
,D/ProviderChangeReceiver( 4246): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4246): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4260 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3851
,I/ActivityManager(  906): Killing 3851:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/AlertService( 4246): No fired or scheduled alerts
I/ActivityManager(  906): Recipient 3851
,D/HtcAlertUtils( 4246): -- cancelReminderNotification --
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcAlertUtils( 4246): broadcastExistReminder!
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4260): [4260/4260] onCreate()
W/ContextImpl( 4260): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3887
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3887:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3887
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42753750 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 8 times.
,D/PMS     (  906): releaseWL(427a1e80): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/Process (  906): killProcessQuiet, pid=3967
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3967:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3967
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=38 rxSum=31} preTxRxSum={txSum=38 rxSum=31}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20096 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20097 delay=15s
D/PMS     (  906): acquireWL(427a4eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{4263d488: PendingIntentRecord{422ec8a8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70171, Int=0
D/PMS     (  906): releaseWL(427a4eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(427f1060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427f1060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,I/SensorManager(  906): mEventCount = 600
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 9 times.
,D/PMS     (  906): acquireWL(427e6440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,D/Finsky  ( 4080): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4080): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  906): sending alarm PendingIntent{420e4998: PendingIntentRecord{42623f18 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454422515212, Int=0
D/PMS     (  906): releaseWL(427e6440): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4080/10074)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4080): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4080): [NET] getaddrinfo-,err=8
D/libc    ( 4080): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4080): [NET] getaddrinfo-, 1
D/libc    ( 4080): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4627 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4080): [NET] getaddrinfo_proxy-, success
I/global  ( 4080): call createSocket() return a new socket.
D/libc    ( 4080): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4080): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4080): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4080): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4080): untagSocket(69) failed with errno -22
,D/Finsky  ( 4080): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4080): untagSocket(69) failed with errno -22
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4080): untagSocket(69) failed with errno -22
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [61][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:124, mTXpacketCount:63, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4080/10074)
,D/Finsky  ( 4080): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(4256e758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{425b5b08: PendingIntentRecord{425b5ab0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454422517280, Int=0
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
D/PMS     (  906): acquireWL(42762938): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4080 10074 null
,D/Finsky  ( 4080): [437] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1221): client connected with version: 8296000
D/PMS     (  906): releaseWL(4256e758): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4080): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4080): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4080): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4080): [NET] getaddrinfo-,err=8
D/libc    ( 4080): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4080): [NET] getaddrinfo-, 1
,D/libc    ( 4080): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ff0c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4080): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(42762938): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 10 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=16 [12][2][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1318): service - handleMessage() quit looper
,D/AutoSetting( 1318): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=2724
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2724:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/AutoSetting( 1476): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1476): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1476): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1476): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1476): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1476): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1476): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1476): service - mHandler: update timezone
,D/AutoSetting( 1476): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1476): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1476): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1476): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f90e70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 8 2 11
,I/ActivityManager(  906): Recipient 2724
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1237): MSG_NOTIFY_CS_TO_SYNC <<
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 11 times.
,D/PMS     (  906): acquireWL(425473f8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425473f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4281e7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4281e7b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42679dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{426d3640: PendingIntentRecord{422ec8a8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=85178, Int=0
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=110 rxSum=94} preTxRxSum={txSum=38 rxSum=31}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20097 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20098 delay=15s
D/PMS     (  906): acquireWL(4258e4d8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42679dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): releaseWL(4258e4d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4272dc78): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4272dc78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 12 times.
,I/SensorManager(  906): mEventCount = 750
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:139, mTXpacketCount:124, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1476): handler message = 4011
,E/HtcModeClient( 1476): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1476): Don't start project servcice
,D/HtcModeClient( 1476): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1476): connectState: CONNECTION_READY = false
,D/SilentMusic( 1476): call stop
D/HtcModeClient( 1476): close connection
,W/HtcModeClient( 1476): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1476): read the terminate packet, so break
,D/PMS     (  906): acquireWL(426edb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{426712b0: PendingIntentRecord{42739058 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454422531606, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4291 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{4274a5a8: PendingIntentRecord{426c5c48 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454422534995, Int=60000
,D/PMS     (  906): releaseWL(426edb18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4291): SMSBackupAgentService started
,D/SMSBackup( 4291): Checking restore status
,D/SMSBackup( 4291): Restore complete
,D/SMSBackup( 4291): cancelCheckAlarm
,D/SMSBackup( 4291): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Finsky  ( 4080): [428] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4080): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=4131
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4131:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4131
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42392638 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,V/LightsService(  906): setLight #0: color=#3e
,V/LightsService(  906): setLight #0: color=#3a
,V/LightsService(  906): setLight #0: color=#34
,V/LightsService(  906): setLight #0: color=#2d
,V/LightsService(  906): setLight #0: color=#26
,V/LightsService(  906): setLight #0: color=#20
,V/LightsService(  906): setLight #0: color=#19
,V/LightsService(  906): setLight #0: color=#14
,I/SensorManager(  906): mEventCount = 900
,D/PMS     (  906): acquireWL(42808ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
V/AlarmManager(  906): sending alarm PendingIntent{4270ee48: PendingIntentRecord{422ec8a8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100184, Int=0
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=110 rxSum=94} preTxRxSum={txSum=110 rxSum=94}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20098 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20099 delay=15s
D/PMS     (  906): releaseWL(42808ff0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42239848
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): Active sensors: size = 2
,W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42239848, eanble = 0, strlen(mName) = 59
,W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/PMS     (  906): mWirelessDisplayManager is null
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,W/BatSI   (  906): Couldn't get kernel wake lock stats
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424079d8
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@426a92a0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 343ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4281c478)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
D/PMN     (  906): wakingUp
V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1254): ScreenObserver: OFF
,D/NfcService( 1254): applyRouting - 0
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1270
I/WindowManager(  906): No lock screen! windowToken=null
D/PMN     (  906): onScreenOn
D/PMS     (  906): acquireWL(4276c7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1254): applyRouting -2
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/BatteryService(  906): n_update end
,D/PMS     (  906): acquireWL(4276d3f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/MtpService( 2391): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2391): [MTP][onReceive]-
D/PowerUI ( 1115): closing low battery warning: level=99
D/PMS     (  906): releaseWL(4276c7d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): releaseWL(4276d3f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/NfcService( 1254): applyRouting - 0
,D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/NfcService( 1254): applyRouting -2
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/HtcPowerSaver(  906): updateBatteryInfo
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): acquireWL(42826418): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1254 1027 null
D/PMS     (  906): releaseWL(42826418): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/TetherSettings( 3774): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3774): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3774): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3774): Cust_ConnectToPC   : spcsc>false
D/        ( 3774): Cust_ConnectToPC   : IPT>true
D/        ( 3774): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3774): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3774): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3774): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3774): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20100 delay=15s
D/AutoSetting( 1318): service - onCreate()
I/ClockThread( 1115): stop update clock
I/PSReceiver( 3774): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:On
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
W/ContextImpl( 3774): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1182): htc_wext_set_TX_TRACKING - ret = 0
D/AutoSetting( 1318): service - AddressCache: using context: com.htc.Weather
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3774): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3774): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3774):  defaultType:0
D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/LocationManagerService(  906): request 42474860 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  906): batLight: plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c80000
D/qdlights(  906): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1182): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:139, mTXpacketCount:139, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4316 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  906): acquireWL(4283c360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4283c360): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(4283dcc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOn: 1454422545880
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOn: 1454422545881
D/PMS     (  906): releaseWL(4283dcc0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424079d8
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424079d8, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@426a92a0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(42841298): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/FeedHostManager( 1270): [onPause]
,I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41ccec50
,I/SocialFeedProvider( 1270): +onPause
,I/SocialFeedProvider( 1270): -onPause
,D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20100 mDataStallAlarmIntent=PendingIntent{424a3d00: PendingIntentRecord{422ec8a8 android broadcastIntent}},
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/PMS     (  906): releaseWL(42841298): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): acquireWL(4284a318): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1182): SET_SCREEN_ON:Off
I/wpa_supplicant( 1182): htc_wext_set_keepalive +
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1182): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1182): getPrivFuncNum +	
I/wpa_supplicant( 1182): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1182): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1182): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1182): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1182): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  906): updateScreenOn: false
,D/ContactMessageStore( 1237): start background delete task...
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
D/PMS     (  906): acquireWL(42853930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4316 1000 null
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
,D/wpa_supplicant( 1182): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4284a318): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42853930): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 54
,D/SmartSyncUtils( 4316): getMobilePolicyEnabled, result = true
,W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4316): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
D/WifiService(  906): New client listening to asynchronous messages
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a92a0
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a92a0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426a92a0, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426a92a0
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a97c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426a97c8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(42869e88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42869e88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4286b3b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4286b3b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOff
,D/AutoSetting( 1318): service - mHandler: cancel location update
,D/AutoSetting( 1318): service -           changes count: 0
,D/AutoSetting( 1476): service - handleMessage() stop self
,D/AutoSetting( 1476): service - onDestroy() END
,D/AutoSetting( 1476): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3685
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3685:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3685
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42870be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(42870be8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
D/PowerUI ( 1115): closing low battery warning: level=99
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/Process (  906): killProcessQuiet, pid=3865
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3865:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3865
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42879820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{4281baa0: PendingIntentRecord{427845a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119331, Int=0
,D/PMS     (  906): acquireWL(4287b3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{425ae418: PendingIntentRecord{4269f7e8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454422542455, Int=1800000
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4287e958): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42879820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42883c88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4287e958): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42887748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2177): Aggregate from 1454422490354 (log), 1454420742419 (data)
,D/PMS     (  906): releaseWL(42887748): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4287b3b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42890208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(42890208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42894340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
D/PMS     (  906): releaseWL(42883c88): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(428a0918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428a8a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1454422559338 tag=VacuumService
,D/PMS     (  906): releaseWL(42894340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428a0918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428b3190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428a8a78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(428b3190): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428ba9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(428ba9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428be9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(428be9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428c2a68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(428c2a68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428c9908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(428d2c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428d2c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428da600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428c9908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428df950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505,
,D/PMS     (  906): releaseWL(428df950): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428e3b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428e3b98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 13223 seconds from now (1454422560325)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42828e40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =914 +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1221/10029),
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(428da600): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427f8ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(427f8ea0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427f2000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1182): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1182): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1182): nl80211: survey data missing!
E/wpa_supplicant( 1182): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1182): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(427f2000): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(427e4bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427e4bb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(427b4fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{41ef5a88: PendingIntentRecord{427ad240 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136436, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  906): releaseWL(427b4fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1318): service - handleMessage() quit looper
,D/AutoSetting( 1318): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4163
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4163:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4163
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(427a7178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41df6358: PendingIntentRecord{425bc738 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141607, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(427a4a48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(427a7178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =54b +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success,
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(427a4a48): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42300500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{4242ad50: PendingIntentRecord{420cc3e0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=170991, Int=0
,D/PMS     (  906): releaseWL(42300500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1237): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(41c3fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41c3fed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(420ca190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): releaseWL(420ca190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=99
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(424954a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(424954a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderNotification, total:0
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 1610): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
D/TetherSettings( 3774): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3774): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3774): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3774): Cust_ConnectToPC   : spcsc>false
D/        ( 3774): Cust_ConnectToPC   : IPT>true
D/        ( 3774): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3774): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3774): Index of the first 1 = -1
W/ContextImpl( 3774): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3774): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3774): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3774): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3774): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3774): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3774): [ACC]android_networking:tethering_guard_support=false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(4255abb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=240314, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4255abb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42385758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42385758): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(41c79788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41c79788): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427e3618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=300314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427e3618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4259fbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4259fbb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425522e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=360314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425522e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4272fc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  906): releaseWL(4272fc18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426cce00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=420313, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426cce00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42825a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42825a10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4257a790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=480313, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4257a790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42614240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42614240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4254f600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=540314, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4254f600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4268ce20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4268ce20): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4285b860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=600314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4285b860): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42773068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42773068): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1237): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1237): sku_id=99
,D/ContactMessageStore( 1237): start background delete task...
,D/ContactMessageStore( 1237): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1237): size: 0 , 0
,D/ContactMessageStore( 1237): Background delete complete
,D/PMS     (  906): acquireWL(42613ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=660314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42613ba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4282e1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4282e1b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42779fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=720314, Int=0
,D/PMS     (  906): releaseWL(42779fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428e20f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428e20f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42546be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42546be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428225b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=780314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428225b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426d6370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426d6370): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42896960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=840314, Int=0
,D/PMS     (  906): releaseWL(42896960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42632698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42632698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(427067e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=900314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427067e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4266bd80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4266bd80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42655ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41dc9298: PendingIntentRecord{424fd568 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=779518, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42643210: PendingIntentRecord{427a8b20 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=946429, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4374 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{4277ae28: PendingIntentRecord{424ce100 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454422650764, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{41d2a168: PendingIntentRecord{4254e7e0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454423371292, Int=900000
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(42734b90): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): releaseWL(42734b90): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(42655ea8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4316): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4316): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4374/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/Process (  906): killProcessQuiet, pid=3450
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3450:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3450
,D/PMS     (  906): acquireWL(429a3998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024149
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024214
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024218
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024222
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024228
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025665
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025676
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028505
,D/PMS     (  906): releaseWL(429a3998): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(4299b770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=960313, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4299b770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429993e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429993e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42996f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4316): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{41e35688: PendingIntentRecord{42855148 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454423446060, Int=0
D/PMS     (  906): acquireWL(42983d80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4316 1000 null
,D/PMS     (  906): releaseWL(42996f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4316): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4316): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4316): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4316): SettingOnTime = 1454479200000, randomSettingOnTime = 1454476534000
D/SmartSyncScreenOnOffTimeReceiver( 4316): SettingOffTime = 1454464800000, randomSettingOffTime = 1454465038000
D/SmartSyncScreenOnOffTimeReceiver( 4316): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4316): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4316): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(42983d80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(4297c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1020314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4297c850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42979140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42979140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42972f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1080314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42972f20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42970d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42970d30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4296fd40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1140314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4296fd40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42968e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42968e80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42965348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1200313, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42965348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42965010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42965010): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  906): acquireWL(42964ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423d2328: PendingIntentRecord{423c9a58 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1260314, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42964ce0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4390): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4390): ====startRecUseTime====
D/htc.customization.log.level( 4390):  is 
W/CustomizationLogLevel( 4390): Level value is invalid, use default level 2
D/CustomizationManager( 4390):  Read ACC file spent 0.115 (s)
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4390): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4390): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4390): Parsing tag category name = system
I/CustomizationCIDLoader( 4390): Parsing tag category name = application
I/CustomizationCIDLoader( 4390): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4390): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4390): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4390): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4390): Parsing tag category name = Settings
D/CustomizationManager( 4390):  Read CID file spent 0.171 (s)
D/CustomizationManager( 4390):  All configurations done spent 0.171 (s)
W/HtcNativeFlag( 4390): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4390): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4390): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4390): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4390, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{421eeda8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{421f6898 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(428582b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
D/PMS     (  906): releaseWL(428582b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1337): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1297): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
W/SystemReader( 1254): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1337): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1337): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/IcingCorporaProvider( 2840): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
E/ExternalAccountType( 1337): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2840): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4407 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1237 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
D/PhoneApp( 1237): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  906): acquireWL(42433b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(42433b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4407): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4407): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4407): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4407): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4407): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4407): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4407): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4407): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4407): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4407): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4407): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4407): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4407): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4407): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4407): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4407): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4407): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4407): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4407): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4407): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4407): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4407): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4407): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4407): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4407): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4407): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4407): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4407): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4407): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4407): threadid=11: thread exiting with uncaught exception (group=0x41737e30)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4407): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4407): Process: com.google.android.apps.docs, PID: 4407
E/AndroidRuntime( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4407): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4407): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4407): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4407): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4407): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4407): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4407): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4407): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4407): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4407): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4407): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4407): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4407): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4407): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4407): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4407): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4407): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4407): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4407): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4407): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4407): Opened ClientFlag.db in read-only mode
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
D/Process ( 4407): killProcess, pid=4407
D/Process ( 4407): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4425 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/BroadcastQueue(  906): Skipping deliver [background] BroadcastRecord{42723a60 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{42749c50 4407 com.google.android.apps.docs/10100/u0 remote:41d9e720}: process crashing
I/ActivityManager(  906): Recipient 4407
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4407) has died.
W/ContextImpl( 4425): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
W/PackageManager(  906): Unable to load service info ResolveInfo{42549b20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4437 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4425): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4425): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4425): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4425): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4425): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4425): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4425): threadid=10: thread exiting with uncaught exception (group=0x41737e30)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4425): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4425): Process: com.android.keychain, PID: 4425
E/AndroidRuntime( 4425): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4425): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4425): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4425): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4425): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4425): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4425): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4425): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4425): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41bfac38 +
I/Prism.WidgetManager( 1270): onLoadItems() +
D/Process ( 4425): killProcess, pid=4425
D/Process ( 4425): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4437): getInstance(Context context)
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454423711839.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 4425
I/ActivityManager(  906): Process com.android.keychain (pid 4425) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4437): getInstance(Context context)
D/AppTag  ( 4437): onCreate()
D/PMS     (  906): acquireWL(428425d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4054 10160 null
D/PMS     (  906): releaseWL(428425d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  906): killProcessQuiet, pid=4011
W/dalvikvm( 4080): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4011:com.google.android.talk/u0a111 (adj 15): empty #17
D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2177): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2177): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2177): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2177): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2177): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2177): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2177): App measurement is starting up, version: 8489
I/GMPM-SVC( 2177): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  906): Recipient 4011
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65741bc8
E/DriveAsyncService( 2177): disk I/O error (code 3850)
E/DriveAsyncService( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2177): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6d1f3808
W/dalvikvm( 2177): threadid=48: thread exiting with uncaught exception (group=0x41737e30)
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Module APK com.google.android.play.games already loaded
E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2177): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2177): Process: com.google.android.gms, PID: 2177
E/AndroidRuntime( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2177): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2177): killProcess, pid=2177
W/SQLiteOpenHelper( 2177): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2177): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2177): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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

```
