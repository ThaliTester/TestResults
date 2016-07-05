#### Test 72145431fb64fa4_thali02_HTC-HTC One M8s Logs


```
--------- beginning of main
07-05 12:49:28.038  2206  2206 I Kids    : [GCoreUtils] Current gmscore version, 7899448 is smaller than the required version 8400000
07-05 12:49:28.038  4927  4927 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
07-05 12:49:28.038  4927  4927 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
--------- beginning of system
07-05 12:49:28.068   954   985 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5056 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=arm64-v8a
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 4
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfo_proxy+
07-05 12:49:28.078  4598  5054 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:49:28.078   426  5070 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x636c69656e7473),sn(),hints(known),family 0,flags 1024
07-05 12:49:28.078   426  5070 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 12:49:28.088  5031  5031 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 12:49:28.088  5031  5031 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:49:28.098   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-05 12:49:28.098   954   954 E WifiTrafficPoller:  packet count Tx=141 Rx=201
07-05 12:49:28.118  5031  5031 I MultiDex: VM with version 2.1.0 has multidex support
07-05 12:49:28.118  5031  5031 I MultiDex: install
07-05 12:49:28.118  5031  5031 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 12:49:28.118   426  5070 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
07-05 12:49:28.118   426  5070 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 12:49:28.118  4598  5054 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 12:49:28.138  5031  5031 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
07-05 12:49:28.178  4598  5054 I Babel   : connection state changed from UNKNOWN to CONNECTED
07-05 12:49:28.178   954  4472 D Process : killProcessQuiet, pid=4164
07-05 12:49:28.178   954  4472 I ActivityManager: Killing 4164:com.htc.cs.dm/u0a99 (adj 15): empty #17
07-05 12:49:28.178   954  4472 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 12:49:28.188  5031  5031 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-05 12:49:28.188  5031  5031 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@252d2512: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-05 12:49:28.188  5031  5031 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-05 12:49:28.198  1626  1876 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-05 12:49:28.198  1626  1876 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@b3bcfb0 +
07-05 12:49:28.198  1626  1876 I Prism.WidgetManager: onLoadItems() +
07-05 12:49:28.248  1626  1876 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-05 12:49:28.328   954  1801 I ActivityManager: Recipient 4164
07-05 12:49:28.348   954  1266 E WifiStateMachine: handleMessage: E msg.what=131155
07-05 12:49:28.348   954  1266 E WifiStateMachine: processMsg: ConnectedState
07-05 12:49:28.358   954  1266 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=150 tx=11.0, 0.0, 0.0  rx=17.5 bcn=0 [on:0 tx:0 rx:0 period:2900] from screen [on:0 period:-1163046864] gl hn u24 rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 12:49:28.358   954  1266 E WifiStateMachine: processMsg: L2ConnectedState
07-05 12:49:28.358   954  1266 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=150 tx=11.0, 0.0, 0.0  rx=17.5 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1163046862] gl hn u24 rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 12:49:28.358   954  1266 E WifiStateMachine:  get link layer stats 0
07-05 12:49:28.358   954  1266 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 12:49:28.358  1454  1454 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
07-05 12:49:28.358  1454  1454 I wpa_supplicant: environment dirty rate=8 [57][5][0]
07-05 12:49:28.358   954  1266 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 12:49:28.358   954  1266 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-49 linkspeed=150
07-05 12:49:28.358   954  1266 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-49 "NG700"WPA_PSK
07-05 12:49:28.368   954  1266 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=34.01 txretriesrate=0.00 rxrate=39.27 userTriggerdPenalty0
07-05 12:49:28.368   954  1266 E WifiStateMachine:  good link -> stuck count =0
07-05 12:49:28.368   954  1266 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 12:49:28.368   954  1266 E WifiStateMachine:  isHighRSSI       ---> score=65
07-05 12:49:28.388   954  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -49, 3
07-05 12:49:28.388  1345  1345 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
07-05 12:49:28.388  1345  1345 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-05 12:49:28.398   954  1266 E WifiStateMachine: handleMessage: X
07-05 12:49:28.408   954  1660 D VoldConnector: SND -> {20 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
07-05 12:49:28.408   388   926 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
07-05 12:49:28.408  5056  5088 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
07-05 12:49:28.418  5083  5090 E cutils-trace: Error opening trace file: Permission denied (13)
07-05 12:49:28.418  5056  5056 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-05 12:49:28.418  5056  5056 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-05 12:49:28.418  5056  5056 I GAv4    :   adb logcat -s GAv4
07-05 12:49:28.418   954  1623 D VoldConnector: SND -> {21 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
07-05 12:49:28.418   388   926 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
07-05 12:49:28.418  5056  5088 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
07-05 12:49:28.438  1581  2200 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-05 12:49:28.438  1581  2200 D PhoneApp: -- N1 =0
07-05 12:49:28.438  1581  2200 D PhoneApp: -- N2 =0
07-05 12:49:28.438  1581  2200 D PhoneApp: -- N3 =0
07-05 12:49:28.448  5056  5056 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
07-05 12:49:28.448   954  1623 D VoldConnector: SND -> {22 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/}
07-05 12:49:28.448  5056  5101 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
07-05 12:49:28.448   388   926 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache/
07-05 12:49:28.458  1626  1876 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 12:49:28.468   954  1802 D VoldConnector: SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/}
07-05 12:49:28.468   388   926 E Vold    : Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.magazines/files/
07-05 12:49:28.468  5056  5056 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
07-05 12:49:28.468  5056  5101 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
07-05 12:49:28.478  5056  5105 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
07-05 12:49:28.518  5083  5083 D CustomizationManager: ====startRecUseTime====
07-05 12:49:28.518  5083  5083 D htc.customization.log.level:  is 
07-05 12:49:28.518  5083  5083 W CustomizationLogLevel: Level value is invalid, use default level 2
07-05 12:49:28.578  5056  5056 W global  : [apache-http] Connection GC has been deprecated!
07-05 12:49:28.588  5056  5056 W global  : [apache-http] Connection GC has been deprecated!
07-05 12:49:28.608  5083  5083 D CustomizationManager:  Read ACC file spent 0.056 (s)
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__Y13
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__032
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__031
07-05 12:49:28.618  5083  5083 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 12:49:28.618  5083  5083 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = system
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = application
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: Parsing tag category name = ACC
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 42507
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 21902
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23420
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 22299
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 24002
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23210
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23205
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23806
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23430
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23408
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 27205
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-05 12:49:28.618  5083  5083 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-05 12:49:28.618  5083  5083 D CustomizationManager:  Read CID file spent 0.100 (s)
07-05 12:49:28.618  5083  5083 D CustomizationManager:  All configurations done spent 0.100 (s)
07-05 12:49:28.628   432   432 I WVCdm   : CdmEngine::OpenSession
07-05 12:49:28.628   432   432 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
07-05 12:49:28.628  1626  1876 W asset   : Copying FileAsset 0xacbb0928 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.
07-05 12:49:28.648   432   432 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-05 12:49:28.668   432   432 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
07-05 12:49:28.668   954   983 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5083 on display 0
07-05 12:49:28.668   432   432 D DrmWidevineDash: Service_Initialize: starts!
07-05 12:49:28.668   954  1051 D PMS     : acquireHCC(106724e9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 954 1000 null
07-05 12:49:28.668   954  1051 D PMS     : acquireHCC(1e5fe56e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 954 1000 null
07-05 12:49:28.678   432   432 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 12:49:28.678   432   432 D QSEECOMAPI: : App is not loaded in QSEE
07-05 12:49:28.678   432   432 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-05 12:49:28.678   432   432 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 12:49:28.678   432   432 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 12:49:28.678   432   432 D QSEECOMAPI: : App is not loaded in QSEE
07-05 12:49:28.678   954   983 D PMS     : acquireWL(140426a5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null
07-05 12:49:28.688   954  1039 I AnimationUtil: isHTCRecent(ThaliTest/Recent screens.)/6
07-05 12:49:28.698  1626  1626 I FeedHostManager: [onPause]
07-05 12:49:28.698  1626  1626 I FeedProviderManager: onPause
07-05 12:49:28.698  1626  1626 I FeedHostManager: [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@3e595fa7
07-05 12:49:28.698  1626  2608 I SocialFeedProvider: +onPause
07-05 12:49:28.698  1626  2608 I SocialFeedProvider: -onPause
07-05 12:49:28.698  1626  1626 I ContextualWidget: onPause
07-05 12:49:28.698  1626  1626 I ContextualWidget: notifyWidgetDeactive
07-05 12:49:28.698   432   432 D QSEECOMAPI: : Loaded image: APP id = 6
07-05 12:49:28.698   954  1672 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
07-05 12:49:28.708   432   432 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 12:49:28.708   432   432 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
07-05 12:49:28.708   432   432 D QSAPPSVER: qsapps_get_capabilities: returns 0
07-05 12:49:28.708   432   432 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b4000
07-05 12:49:28.708   432   432 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b4000
07-05 12:49:28.708   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.708   514   525 D DrmLibTime: got the req here! ret=0
07-05 12:49:28.708   514   525 D DrmLibTime: command id, time_cmd_id = 770
07-05 12:49:28.708   514   525 D DrmLibTime: time_getutcsec starts!
07-05 12:49:28.708   514   525 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 12:49:28.708   514   525 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 12:49:28.708   514   525 D DrmLibTime: QSEE Time Listener: time_get_modem_time
07-05 12:49:28.708   514   525 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
07-05 12:49:28.718   514   525 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
07-05 12:49:28.718   514   525 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
07-05 12:49:28.718   514   525 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1467715768
07-05 12:49:28.718   514   525 D DrmLibTime: time_getutcsec returns 0, sec = 1467715768; nsec = 0
07-05 12:49:28.718   514   525 D DrmLibTime: time_getutcsec finished! 
07-05 12:49:28.718   954  1514 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5122 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:49:28.718   458   588 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 12:49:28.718   514   525 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 12:49:28.718   514   525 D DrmLibTime: before calling ioctl to read the next time_cmd
07-05 12:49:28.718   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.718  1626  1876 I Prism.WidgetManager: onLoadItems() -
07-05 12:49:28.718  1626  1876 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@b3bcfb0 -
07-05 12:49:28.718   432   432 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-05 12:49:28.718   432   432 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 12:49:28.718   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.728   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.728   432   432 D DrmWidevineDash: hlos api version =  9
07-05 12:49:28.728   432   432 D DrmWidevineDash: tz api version =  9
07-05 12:49:28.728   432   432 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 12:49:28.728   432   432 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-05 12:49:28.728   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.748  5056  5056 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
07-05 12:49:28.768   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 12:49:28.768   432   432 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xffe81328
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
07-05 12:49:28.768   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.768   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xab94f148, dataLength=8
07-05 12:49:28.768   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.768   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.768   432   432 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-05 12:49:28.778   432   432 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xab8d0a18, wrapped_rsa_key_length=1280
07-05 12:49:28.778   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.778   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.778   432   432 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 12:49:28.778   432   432 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-05 12:49:28.778   432  1060 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 12:49:28.778   432  1060 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 12:49:28.778   432  1060 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 12:49:28.778   432  1060 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab951b40, idLength=0xf4b356f8
07-05 12:49:28.778   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.778  1626  1626 I TrimMemoryManager: [trimMemory] 20
07-05 12:49:28.788   954  1037 D StatusBarManagerService: setSystemUiVisibility(0x8600)
07-05 12:49:28.788   954  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:49:28.788   954  1037 D StatusBarManagerService: hiding MENU key
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf4b3570e, maximum = 0xf4b3570f
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.818   432  1060 D DrmWidevineDash: hlos api version =  9
07-05 12:49:28.818   432  1060 D DrmWidevineDash: tz api version =  9
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 12:49:28.818   432  1060 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf4b3577c
07-05 12:49:28.818   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.828   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.828   432  1060 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 12:49:28.828   432  1060 D WVCdm   : PrepareKeyRequest: nonce=1168875022
07-05 12:49:28.828   432  1060 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab8f5a30
07-05 12:49:28.828   432  1060 D DrmWidevineDash: message_length=1611, signature=0xab8d07e0, signature_length=0xf4b356dc
07-05 12:49:28.828   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.828  5056  5056 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7898-7904)
07-05 12:49:28.828  5056  5056 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:49:28.848  5056  5056 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e4df255}
07-05 12:49:28.848  5056  5056 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 12:49:28.848  5056  5056 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 12:49:28.858  5056  5056 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:49:28.858  5056  5056 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 12:49:28.858  5056  5056 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 12:49:28.888  5056  5056 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-05 12:49:28.888  5056  5056 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:49:28.888  5056  5056 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:49:28.888  5056  5056 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-05 12:49:28.888  5056  5056 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 12:49:28.888  5056  5056 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 12:49:28.888  5056  5056 I Adreno-EGL: Local Branch: 
07-05 12:49:28.888  5056  5056 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 12:49:28.888  5056  5056 I Adreno-EGL: Local Patches: NONE
07-05 12:49:28.888  5056  5056 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 12:49:28.938   432  1060 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.938   432  1060 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 12:49:28.938   432  1061 I WVCdm   : CdmEngine::CloseSession
07-05 12:49:28.938   432  1061 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 12:49:28.938   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:28.938   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 12:49:28.938   432  1061 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 12:49:28.938   432  1061 I WVCdm   : L3 Terminate.
07-05 12:49:28.938   432  1061 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 12:49:28.938   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 12:49:28.938   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:28.938   432  1061 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 12:49:28.938   432  1061 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 12:49:28.938   432  1061 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 6
07-05 12:49:28.938   432  1061 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 12:49:28.938   432  1061 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 12:49:28.948  5122  5122 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,07-05 12:49:28.958  5056  5158 W AudioManagerAndroid: Requires BLUETOOTH permission,
,07-05 12:49:28.988  5056  5056 I NSApplication: Starting up...
,07-05 12:49:28.998  5162  5162 E cutils-trace: Error opening trace file: Permission denied (13),
07-05 12:49:28.998  5162  5162 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm64 --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
07-05 12:49:28.998  5162  5162 I dex2oat : dex2oat: override thread count:3
,07-05 12:49:29.018  5122  5122 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 8077-8091),
,07-05 12:49:29.018  5122  5122 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 12:49:29.038   954  1787 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5171 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=arm64-v8a
,07-05 12:49:29.038   954  1787 D Process : killProcessQuiet, pid=4405
07-05 12:49:29.038   954  1787 I ActivityManager: Killing 4405:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
07-05 12:49:29.038   954  1787 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-05 12:49:29.038  5122  5122 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {183a2a76}
07-05 12:49:29.038  5122  5122 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-05 12:49:29.048  5162  5162 I dex2oat : dex2oat took 42.198ms (threads: 3)
,07-05 12:49:29.048  5122  5122 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-05 12:49:29.068  5122  5122 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 12:49:29.068  5031  5055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-05 12:49:29.068  5031  5055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 12:49:29.068  5031  5055 I Adreno-EGL: Build Date: 04/17/15 Fri
,07-05 12:49:29.068  5031  5055 I Adreno-EGL: Local Branch: 
07-05 12:49:29.068  5031  5055 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 12:49:29.068  5031  5055 I Adreno-EGL: Local Patches: NONE
07-05 12:49:29.068  5031  5055 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 12:49:29.068  5122  5122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:49:29.068  5122  5122 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-05 12:49:29.098   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
07-05 12:49:29.098   954   954 E WifiTrafficPoller:  packet count Tx=145 Rx=205
,07-05 12:49:29.138  5031  5055 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU (),
07-05 12:49:29.138  5031  5055 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 12:49:29.138  5031  5055 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 12:49:29.138  5031  5055 I Adreno-EGL: Local Branch: 
07-05 12:49:29.138  5031  5055 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 12:49:29.138  5031  5055 I Adreno-EGL: Local Patches: NONE
07-05 12:49:29.138  5031  5055 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 12:49:29.148  5122  5122 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,07-05 12:49:29.158  5122  5122 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
07-05 12:49:29.158   954   983 I ActivityManager: Recipient 4405
07-05 12:49:29.158  5122  5122 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 12:49:29.158  5122  5122 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191__release_AU ()
07-05 12:49:29.158  5122  5122 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02,
07-05 12:49:29.158  5122  5122 I Adreno-EGL: Build Date: 04/17/15 Fri
07-05 12:49:29.158  5122  5122 I Adreno-EGL: Local Branch: 
07-05 12:49:29.158  5122  5122 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2.05.00.02.028.191
07-05 12:49:29.158  5122  5122 I Adreno-EGL: Local Patches: NONE
07-05 12:49:29.158  5122  5122 I Adreno-EGL: Reconstruct Branch: NOTHING
,07-05 12:49:29.218   954  1497 W System.err: java.lang.Throwable: stack dump,
07-05 12:49:29.218   954  1038 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
07-05 12:49:29.218   954  1497 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
07-05 12:49:29.218   954  1497 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
07-05 12:49:29.218   954  1497 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
07-05 12:49:29.218   954  1497 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-05 12:49:29.218   954  1038 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb115ef:true
,07-05 12:49:29.218  5122  5204 D BluetoothAdapter: 988861773: getState(). Returning 12
,07-05 12:49:29.278   954   954 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
,07-05 12:49:29.278   954  5207 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=125 rxSum=121} preTxRxSum={txSum=66 rxSum=61}
07-05 12:49:29.278   954  5207 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
07-05 12:49:29.278   954  5207 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
,07-05 12:49:29.318   432  1061 I WVCdm   : CdmEngine::OpenSession,
07-05 12:49:29.318   432  1061 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,07-05 12:49:29.328   432  1061 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory,
,07-05 12:49:29.338   432  1061 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
07-05 12:49:29.338   432  1061 D DrmWidevineDash: Service_Initialize: starts!
,07-05 12:49:29.338   432  1061 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 12:49:29.338   432  1061 D QSEECOMAPI: : App is not loaded in QSEE
07-05 12:49:29.338   432  1061 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-05 12:49:29.338   432  1061 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 12:49:29.338   432  1061 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 12:49:29.338   432  1061 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 12:49:29.348   432  1061 D QSEECOMAPI: : Loaded image: APP id = 7,
07-05 12:49:29.348   432  1061 D DrmWidevineDash: Service_Initialize: ends! returns 0,
,07-05 12:49:29.358   432  1061 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
07-05 12:49:29.358   432  1061 D QSAPPSVER: qsapps_get_capabilities: returns 0
07-05 12:49:29.358   432  1061 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b4000
07-05 12:49:29.358   432  1061 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xf46b4000
07-05 12:49:29.358   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.358   514   525 D DrmLibTime: got the req here! ret=0
07-05 12:49:29.358   514   525 D DrmLibTime: command id, time_cmd_id = 770
07-05 12:49:29.358   514   525 D DrmLibTime: time_getutcsec starts!
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: time_get_modem_time
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
07-05 12:49:29.358   514   525 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
07-05 12:49:29.358   514   525 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1467715769
07-05 12:49:29.358   514   525 D DrmLibTime: time_getutcsec returns 0, sec = 1467715769; nsec = 0
07-05 12:49:29.358   514   525 D DrmLibTime: time_getutcsec finished! 
07-05 12:49:29.358   514   525 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-05 12:49:29.358   514   525 D DrmLibTime: before calling ioctl to read the next time_cmd
07-05 12:49:29.358   458   588 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-05 12:49:29.358   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.368   432  1061 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-05 12:49:29.368   432  1061 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 12:49:29.368   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.368   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.368   432  1061 D DrmWidevineDash: hlos api version =  9
07-05 12:49:29.368   432  1061 D DrmWidevineDash: tz api version =  9
07-05 12:49:29.368   432  1061 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 12:49:29.368   432  1061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-05 12:49:29.368   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 12:49:29.388  5122  5122 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-05 12:49:29.388   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.388   432  1061 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 12:49:29.388   432  1061 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 12:49:29.388   432  1061 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xf4929928
07-05 12:49:29.388   432  1061 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
07-05 12:49:29.388   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xaba29aa0, dataLength=8
07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xaba21be8, wrapped_rsa_key_length=1280
07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 12:49:29.398   432  1061 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 12:49:29.398   432  1061 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 12:49:29.398   432  1061 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 12:49:29.398   432  1061 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 12:49:29.398   432  1061 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xab951b80, idLength=0xf49296f8
07-05 12:49:29.398   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 12:49:29.408  5122  5122 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-05 12:49:29.418   954  1028 I ActivityManager: Waited long enough for: ServiceRecord{187688ec u0 com.htc.HTCSpeaker/.NGFService},
,07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xf492970e, maximum = 0xf492970f
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
,07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: hlos api version =  9
07-05 12:49:29.418   432  1061 D DrmWidevineDash: tz api version =  9
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xf492977c
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 12:49:29.418   432  1061 D WVCdm   : PrepareKeyRequest: nonce=4138211165
07-05 12:49:29.418   432  1061 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xab8a0a88
07-05 12:49:29.418   432  1061 D DrmWidevineDash: message_length=1642, signature=0xab8d07e0, signature_length=0xf49296dc
07-05 12:49:29.418   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,07-05 12:49:29.428  5122  5122 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,07-05 12:49:29.438  5122  5122 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
07-05 12:49:29.438  5122  5122 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-05 12:49:29.498  4717  4748 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
07-05 12:49:29.498  5122  5202 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-05 12:49:29.528   954  1797 D Process : killProcessQuiet, pid=4429
07-05 12:49:29.528   954  1797 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5224 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
07-05 12:49:29.528   954  1797 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
07-05 12:49:29.528   954  1797 I ActivityManager: Killing 4429:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,07-05 12:49:29.528   432  1061 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.528   432  1061 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0,
07-05 12:49:29.538  2206  2228 W art     : Suspending all threads took: 15.180ms
,07-05 12:49:29.538   432   432 I WVCdm   : CdmEngine::CloseSession
,07-05 12:49:29.538   432   432 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 12:49:29.538   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.538   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.538   432   432 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 12:49:29.538   432   432 I WVCdm   : L3 Terminate.
07-05 12:49:29.538   432   432 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-05 12:49:29.538   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
07-05 12:49:29.538   432   432 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
07-05 12:49:29.538   432   432 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 12:49:29.538   432   432 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 12:49:29.538   432   432 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 7
07-05 12:49:29.538   432   432 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 12:49:29.538   432   432 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
07-05 12:49:29.538  2206  2228 I art     : Background sticky concurrent mark sweep GC freed 3134(264KB) AllocSpace objects, 9(180KB) LOS objects, 7% free, 5MB/6MB, paused 20.741ms total 45.508ms
,07-05 12:49:29.608   954  1799 I ActivityManager: Recipient 4429
,07-05 12:49:29.648  2206  2206 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,07-05 12:49:29.658  5224  5224 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-05 12:49:29.678   954  3238 I art     : Explicit concurrent mark sweep GC freed 19935(1125KB) AllocSpace objects, 2(104KB) LOS objects, 33% free, 16MB/24MB, paused 2.743ms total 161.366ms
,07-05 12:49:29.708  5122  5122 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,07-05 12:49:29.788  2206  5018 I CheckinRequestBuilder: Classify the device as Phone.
,07-05 12:49:29.838  5122  5122 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2333aafe, mServedView=org.apache.cordova.engine.SystemWebView{398d625f VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@9a604ac
,07-05 12:49:29.848   954  1497 I InputMethodManagerService: Disable input method client, pid=1626,
07-05 12:49:29.848   954  1497 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 12:49:29.848   954  1497 I InputMethodManagerService: Enable input method client, pid=5122
,07-05 12:49:29.848  1345  1345 I PhoneStatusBar: setImeWindowStatus(false,false)
,07-05 12:49:29.858   954  1039 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s161ms
,07-05 12:49:29.858   954  1660 D PMS     : releaseWL(140426a5): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfofornet-, err=8
07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfo_proxy+,
07-05 12:49:29.868  2206  5018 D libc    : [NET] android_getaddrinfo_proxy get netid:0
07-05 12:49:29.868   426  5257 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
07-05 12:49:29.878   426  5257 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
07-05 12:49:29.878   426  5257 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
07-05 12:49:29.878   426  5257 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
07-05 12:49:29.878  2206  5018 D libc    : [NET] android_getaddrinfo_proxy-, success
,07-05 12:49:29.898  1518  1518 W XT9_C   : [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
,07-05 12:49:29.898  1518  1518 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#0
07-05 12:49:29.898  1518  1518 I XT9_C   : [T9_ReleaseBuffer] Reset LDB#1
07-05 12:49:29.898  1518  1518 D XT9_C   : [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,07-05 12:49:29.908  1581  1740 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
,07-05 12:49:29.908  1581  1740 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,07-05 12:49:29.928  2206  5018 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 12:49:29.928  2206  5018 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:49:29.938  5122  5122 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5122,
,07-05 12:49:29.968  2206  5018 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
07-05 12:49:29.968  2206  5018 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:49:29.968  2206  5018 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
07-05 12:49:29.968  2206  5018 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-05 12:49:29.978  2206  5018 I CheckinTask: Sending checkin request (10611 bytes)
,07-05 12:49:30.068  5122  5122 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,07-05 12:49:30.098   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7,
07-05 12:49:30.098   954   954 E WifiTrafficPoller:  packet count Tx=158 Rx=216
,07-05 12:49:30.148   954   985 D Process : killProcessQuiet, pid=4450,
07-05 12:49:30.148   954   985 I ActivityManager: Killing 4450:com.android.smith/1000 (adj 15): empty #17,
07-05 12:49:30.148   954   985 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,07-05 12:49:30.188   454   454 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 12:49:30.298   954  1497 I ActivityManager: Recipient 4450,
,07-05 12:49:30.378  1943  5276 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,07-05 12:49:30.378  1943  1943 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-05 12:49:30.398  2206  2206 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-05 12:49:30.398  2206  5018 I CheckinRequestBuilder: Checkin reason type: 8 attempt count: 1
,07-05 12:49:30.398   954  1497 I ActivityManager: Cannot resolve ContentProvider=com.google.android.wearable.settings
07-05 12:49:30.408  2206  5018 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-05 12:49:30.418   954  1787 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=2206, uid=10024, userID:0,
,07-05 12:49:30.418  5122  5255 D jxcore_app_log: JniHelper::setJavaVM(0xab4a87b8), pthread_self() = -1401131864
,07-05 12:49:30.438   954  3238 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=5278 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
,07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 12:49:30.438  5122  5255 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15025029 added. We now have 1 listener(s)
07-05 12:49:30.448   954   983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
07-05 12:49:30.448  2206  5292 D LocationInitializer: Restart initialization of location
,07-05 12:49:30.448  5122  5255 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
07-05 12:49:30.448  5122  5255 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:F6:69:77"
,07-05 12:49:30.458  5122  5255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 12:49:30.458  5122  5255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 12:49:30.458  5122  5255 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1889f0dc added. We now have 1 listener(s)
07-05 12:49:30.458  5122  5255 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 12:49:30.478  5122  5255 D BluetoothAdapter: 988861773: getState(). Returning 12,
07-05 12:49:30.478   954  1268 D WifiService: New client listening to asynchronous messages,
07-05 12:49:30.478  5122  5255 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-05 12:49:30.478   954  1802 I ActivityManager: Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=5302 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
07-05 12:49:30.478   954   954 E WifiTrafficPoller: ADD_CLIENT: 8
07-05 12:49:30.478  5122  5255 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-05 12:49:30.478  5122  5255 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 12:49:30.478  5122  5255 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 12:49:30.478  5122  5255 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 12:49:30.498  5122  5255 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-05 12:49:30.498   954  3238 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
07-05 12:49:30.508  3352  3409 I HtcModeClient: handler message = 4011
07-05 12:49:30.508  3352  3409 E HtcModeClient: Check connection and retry 4 times.
,07-05 12:49:30.508  5122  5255 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,07-05 12:49:30.528  5122  5255 D BluetoothAdapter: 988861773: getState(). Returning 12,
,07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 12:49:30.528  5122  5255 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 12:49:30.528  5278  5278 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-05 12:49:30.528  5122  5255 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 12:49:30.528  5278  5278 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
07-05 12:49:30.528  5122  5255 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 12:49:30.528  5122  5255 I io.jxcore.node.LifeCycleMonitor: start: OK
07-05 12:49:30.528  5122  5122 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:49:30.538  5122  5122 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 12:49:30.558  5278  5278 I MultiDex: VM with version 2.1.0 has multidex support
07-05 12:49:30.558  5278  5278 I MultiDex: install
07-05 12:49:30.558  5278  5278 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 12:49:30.558  5302  5302 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 12:49:30.558  5122  5122 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 12:49:30.578  5278  5278 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,07-05 12:49:30.608  5302  5302 D CalendarApplication: onCreate
,07-05 12:49:30.628  5302  5302 D ProviderChangeReceiver: ---------------------------------------------------
07-05 12:49:30.628  5278  5278 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
07-05 12:49:30.628  5302  5302 D ProviderChangeReceiver: ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,07-05 12:49:30.628  5278  5278 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@252d2512: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 12:49:30.628  5278  5278 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 12:49:30.638  5302  5327 D HtcAlertService: start to updateAlertNotification!
,07-05 12:49:30.658   954  1797 I ActivityManager: Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=5328 uid=10035 gids={50035, 9997} abi=arm64-v8a
,07-05 12:49:30.658   954  1797 D Process : killProcessQuiet, pid=4359
07-05 12:49:30.658   954  1797 I ActivityManager: Killing 4359:com.android.settings/1000 (adj 15): empty #17
,07-05 12:49:30.658   954  1797 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-05 12:49:30.748   954  1497 I ActivityManager: Recipient 4359
,07-05 12:49:30.768   954  1051 D PMS     : releaseHCC(106724e9): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
07-05 12:49:30.778   954  1051 D PMS     : releaseHCC(1e5fe56e): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,07-05 12:49:30.798  5302  5327 D HtcAlertService: No fired or scheduled alerts
,07-05 12:49:30.798  5302  5327 D HtcAlertUtils: -- cancelReminderNotification --
,07-05 12:49:30.798  5302  5327 D HtcAlertUtils: broadcastExistReminder!
,07-05 12:49:30.808  1451  1451 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
07-05 12:49:30.808  5278  5278 D WearableService: callingUid 10024, callindPid: 5278
,07-05 12:49:30.858   954   983 I ActivityManager: Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=5351 uid=10076 gids={50076, 9997} abi=arm64-v8a
,07-05 12:49:30.858   954   983 D Process : killProcessQuiet, pid=4512
07-05 12:49:30.858   954   983 I ActivityManager: Killing 4512:com.google.android.gms:car/u0a24 (adj 15): empty #17
07-05 12:49:30.858   954   983 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-05 12:49:30.878   438   438 I art     : Explicit concurrent mark sweep GC freed 8662(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 157us total 25.086ms,
,07-05 12:49:30.898   438   438 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 174us total 17.017ms,
,07-05 12:49:30.918   438   438 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 184us total 19.841ms,
,07-05 12:49:31.028   954  1799 I ActivityManager: Recipient 4512
,07-05 12:49:31.098   954  1497 D Process : killProcessQuiet, pid=4473
07-05 12:49:31.098   954  1497 I ActivityManager: Killing 4473:com.android.vending/u0a72 (adj 15): empty #17,
07-05 12:49:31.098   954  1497 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 12:49:31.098   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 12:49:31.098   954   954 E WifiTrafficPoller:  packet count Tx=167 Rx=225
,07-05 12:49:31.128  1943  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: AndroidCheckInServer,
07-05 12:49:31.138  1943  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
07-05 12:49:31.138  1943  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-05 12:49:31.138  1943  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-05 12:49:31.158  5122  5324 W jxcore-log: Initializing JXcore engine
07-05 12:49:31.158  5122  5324 W jxcore-log: JXcore engine is ready
,07-05 12:49:31.208  5122  5324 W jxcore-log: Starting JXcore engine,
,07-05 12:49:31.238   954  1796 I ActivityManager: Recipient 4473,
,07-05 12:49:31.288  5122  5324 W jxcore-log: Platform android,
07-05 12:49:31.288  5122  5324 W jxcore-log: 
07-05 12:49:31.288  5122  5324 W jxcore-log: Process ARCH arm
07-05 12:49:31.288  5122  5324 W jxcore-log: 
,07-05 12:49:31.308  5351  5351 D SMSBackup: Got a database change event
,07-05 12:49:31.318  1847  5277 E MDM     : [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null},
,07-05 12:49:31.318  1943  1978 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,07-05 12:49:31.338   954  1256 I ActivityManager: Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=5372 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,07-05 12:49:31.338   954  1256 V AlarmManager: sending alarm PendingIntent{a63e151: PendingIntentRecord{30d3cdb6 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=60377, Int=0
,07-05 12:49:31.368   954  1266 E WifiStateMachine: handleMessage: E msg.what=131155,
07-05 12:49:31.368   954  1266 E WifiStateMachine: processMsg: ConnectedState
07-05 12:49:31.368   954  1266 E WifiStateMachine:  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=150 tx=34.0, 0.0, 0.0  rx=39.3 bcn=0 [on:0 tx:0 rx:0 period:2975] from screen [on:0 period:-1163043851] gl hn u24 rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
07-05 12:49:31.368   954  1266 E WifiStateMachine: processMsg: L2ConnectedState,
07-05 12:49:31.368   954  1266 E WifiStateMachine:  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-49 f=2447 sc=60 link=150 tx=34.0, 0.0, 0.0  rx=39.3 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1163043849] gl hn u24 rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,07-05 12:49:31.368   954  1266 E WifiStateMachine:  get link layer stats 0
07-05 12:49:31.368   954  1266 W WifiHW  : QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
07-05 12:49:31.368  1454  1454 D wpa_supplicant: wlan0: Control interface command 'SIGNAL_POLL'
,07-05 12:49:31.388  1454  1454 I wpa_supplicant: environment dirty rate=0 [22][0][0]
07-05 12:49:31.388   954  1266 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative RSSI = -49 abnormalRssiCnt = 0 newLinkSpeed = 150
07-05 12:49:31.388   954  1266 E WifiStateMachine: fetchRssiLinkSpeedAndFrequencyNative rssi=-49 linkspeed=150
07-05 12:49:31.388   954  1266 E WifiConfigStore: updateConfiguration freq=2447 BSSID=f4:f2:6d:22:99:3e RSSI=-49 "NG700"WPA_PSK
07-05 12:49:31.388   954  1266 E WifiStateMachine: calculateWifiScore freq=2447 speed=150 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=28.00 txretriesrate=0.00 rxrate=29.64 userTriggerdPenalty0
07-05 12:49:31.388   954  1266 E WifiStateMachine:  good link -> stuck count =0
07-05 12:49:31.388   954  1266 E WifiStateMachine:  badRSSI count0 lowRSSI count0 --> score 60
07-05 12:49:31.388   954  1266 E WifiStateMachine:  isHighRSSI       ---> score=65
07-05 12:49:31.398   954  1291 D WifiWatchdogStateMachine: RSSI current: 3 new: -49, 3
,07-05 12:49:31.398   954  1266 E WifiStateMachine: handleMessage: X
07-05 12:49:31.398  1345  1345 D WIFI_ICON: updateWifiState: RSSI_CHANGED 3 -> 3
,07-05 12:49:31.398  1345  1345 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-05 12:49:31.408  2206  5018 W CheckinRequestBuilder: awaiting user notification for token
07-05 12:49:31.408  1451  1487 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true, isForDotMatrix: false
07-05 12:49:31.408  1451  1487 D DotMatrix: [EventService] notificationPosted, eventType:1014
,07-05 12:49:31.418  1345  1345 I RemoteViews: reapply : com.google.android.gms 2 40,
,07-05 12:49:31.418  1451  1487 D DotMatrix: [EventService] notificationPosted, This eventType was disabled by user.
,07-05 12:49:31.438  2206  5018 I CheckinRequestBuilder: Classify the device as Phone.
07-05 12:49:31.438   954   985 I ActivityManager: Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=5396 uid=10069 gids={50069, 9997, 1023, 3003, 1028, 1015} abi=arm64-v8a
,07-05 12:49:31.438   954   985 D Process : killProcessQuiet, pid=3893
07-05 12:49:31.438   954   985 I ActivityManager: Killing 3893:com.htc.sense.mms/u0a64 (adj 15): empty #17
07-05 12:49:31.438   954   985 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
,07-05 12:49:31.458  5122  5324 I jxcore-log: JXcore Cordova bridge is ready!,
07-05 12:49:31.458  5122  5324 I jxcore-log: 
07-05 12:49:31.458  5122  5324 W jxcore-log: JXcore engine is started
,07-05 12:49:31.468  5122  5255 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 12:49:31.468  5122  5122 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,07-05 12:49:31.478  5122  5324 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-05 12:49:31.478  5122  5324 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-05 12:49:31.488  5122  5122 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-05 12:49:31.488  5122  5122 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-05 12:49:31.568   954  1797 I ActivityManager: Recipient 3893
,07-05 12:49:31.678  5396  5396 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-05 12:49:31.708  5122  5122 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 12:49:31.708   954  3238 D PMS     : acquireWL(3373cb53): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 954 1000 null
07-05 12:49:31.708  5122  5122 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-05 12:49:31.708  5122  5255 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 219ms. Plugin should use CordovaInterface.getThreadPool().
,07-05 12:49:31.718  1943  2184 I art     : Explicit concurrent mark sweep GC freed 9424(486KB) AllocSpace objects, 5(420KB) LOS objects, 49% free, 4MB/8MB, paused 859us total 61.531ms,
,07-05 12:49:31.728   954  1802 I ActivityManager: Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=5421 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a,
,07-05 12:49:31.738   954  1672 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
,07-05 12:49:31.758   954  1799 D PMS     : acquireWL(5730c90): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 5396 10069 null
,07-05 12:49:31.758   954  4472 D Process : killProcessQuiet, pid=4636
07-05 12:49:31.758   954  4472 I ActivityManager: Killing 4636:com.google.android.youtube/u0a176 (adj 15): empty #17
07-05 12:49:31.758   954  4472 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
07-05 12:49:31.758   954  3238 D PMS     : acquireWL(27306989): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 5396 10069 null
,07-05 12:49:31.768  2206  5018 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-05 12:49:31.858   954  1497 I ActivityManager: Recipient 4636
,07-05 12:49:31.858  5419  5444 E cutils-trace: Error opening trace file: Permission denied (13)
,07-05 12:49:31.868  2206  5018 I CheckinService: Checking schedule, now: 1467715771886 next: 1468252603778
,07-05 12:49:31.878  2206  5018 I CheckinService: active receiver: disabled
07-05 12:49:31.878   954  1799 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2206, uid=10024, userID:0
,07-05 12:49:31.898   954  1514 D PMS     : releaseWL(5730c90): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,07-05 12:49:31.898  1626  1626 I FeedHostManager: [onResume]
,07-05 12:49:31.898  1626  1626 I FeedProviderManager: onResume
,07-05 12:49:31.898  1626  2608 I SocialFeedProvider: +onResume
07-05 12:49:31.918   954   983 D PMS     : releaseWL(260dee09): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:49:31.898  1626  2608 I SocialFeedProvider: updateAccounts - Accounts is no change
07-05 12:49:31.898  1626  2608 I SocialFeedProvider: -onResume
07-05 12:49:31.908  1626  1626 I ContextualWidget: onResume
07-05 12:49:31.908  1626  1626 I ContextualWidget: notifyWidgetActive location size=0 user consent location=false
07-05 12:49:31.908  1626  1626 W SystemReader: Cannot find enable_suggestion_option, use default value instead
07-05 12:49:31.908  1626  1916 I ContextualWidget: handleMessage, what=1018 mode=GettingOut maxcount=8
07-05 12:49:31.908  1626  1626 I ContextualWidget: ignore uploadUsageData location=false usage data=false allowAutoUpload=true
07-05 12:49:31.908  1626  1626 W SystemReader: Cannot find enable_suggestion_option, use default value instead
,07-05 12:49:31.908  1626  1626 I ContextualWidget: postSyncRecommendedApps, isReady=false allowAutoSync=true syncMode=1 isEnableRecommend=true
,07-05 12:49:31.918  5396  5456 E TodoTaskNotifyService: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
07-05 12:49:31.918  5396  5456 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.lang.String.equals(java.lang.Object)' on a null object reference
,07-05 12:49:31.918  5396  5456 W System.err: 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
07-05 12:49:31.918  5396  5456 W System.err: 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
07-05 12:49:31.918   954  1037 D StatusBarManagerService: setSystemUiVisibility(0x8700)
07-05 12:49:31.928  5396  5456 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 12:49:31.928   954  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 12:49:31.928  5396  5456 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-05 12:49:31.928   954  1037 D StatusBarManagerService: hiding MENU key
07-05 12:49:31.928  5396  5456 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 12:49:31.928   954  1796 D PMS     : releaseWL(27306989): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,07-05 12:49:31.928  5396  5456 W NotifyReceiver: stopSelfResult true
,07-05 12:49:31.938  1626  1626 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,07-05 12:49:31.948  1626  1626 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-05 12:49:31.958   954   983 I InputMethodManagerService: Disable input method client, pid=5122
07-05 12:49:31.958  1345  1345 I PhoneStatusBar: setImeWindowStatus(false,false)
07-05 12:49:31.958   954   983 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
07-05 12:49:31.958   954   983 I InputMethodManagerService: Enable input method client, pid=1626
,07-05 12:49:31.958  3862  3862 D MtpReceiver: [MTP][handleUsbStateAsync]+
07-05 12:49:31.958  3862  3862 D MtpReceiver: [MTP][handleUsbStateAsync]1:1-
07-05 12:49:31.958  3862  5458 D MtpReceiver: [MTP][handleUsbState]+,
,07-05 12:49:31.958  5122  5122 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,07-05 12:49:31.978   954   985 I ActivityManager: Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=5459 uid=10005 gids={50005, 9997, 1024, 1023, 3003, 1007, 1028, 1015, 1018} abi=arm64-v8a
07-05 12:49:31.988  5419  5419 D CustomizationManager: ====startRecUseTime====
07-05 12:49:31.988  5419  5419 D htc.customization.log.level:  is 
,07-05 12:49:31.988   954  1514 D PMS     : releaseWL(3373cb53): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
07-05 12:49:31.988  5419  5419 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-05 12:49:31.988  3862  5458 D MtpReceiver: [MTP][scanExternalVolumeIfNeed] scan external volume
,07-05 12:49:31.998  3862  3862 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
07-05 12:49:31.998  3862  5458 D MtpReceiver: [MTP][handleUsbState]-
07-05 12:49:31.998  3862  5458 D MtpReceiver: [MTP][handleMessage]-
07-05 12:49:31.998  3862  3862 D MtpDatabase: TotalSize=1886532,MediaCacheLimit=6000
,07-05 12:49:31.998  3862  3862 D MtpService: [isMtpConnected] connected: true
,07-05 12:49:32.008   954  1037 D StatusBarManagerService: setSystemUiVisibility(0xc0000700),
07-05 12:49:32.008   954  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 12:49:32.008   954  1037 D StatusBarManagerService: hiding MENU key
,07-05 12:49:32.038  5372  5395 D MdScBoot: [4c.1.] 30@-104901 -> 40
,07-05 12:49:32.048   954  1028 D Process : killProcessQuiet, pid=4717
07-05 12:49:32.048   954  1028 I ActivityManager: Killing 4717:com.google.android.gm/u0a106 (adj 15): empty #17
,07-05 12:49:32.048   954  1028 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityStack.destroyActivityLocked:3435 
,07-05 12:49:32.048  5372  5483 D MdScBootUi: [4c.1.2.] boot 118 warn0
,07-05 12:49:32.078  5372  5395 D MdScSimSt: [4c.1.2.] qry 118: 0+1 running 0
,07-05 12:49:32.088  5419  5419 D CustomizationManager:  Read ACC file spent 0.053 (s),
,07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__001
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__102
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__Y13,
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__032,
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__M27
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__002
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__031,
07-05 12:49:32.098  5419  5419 D CIDMapFileReader: Parsing tag item name = HTC__A07
07-05 12:49:32.098  5419  5419 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = system
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = application
,07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = AudioService,
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = Settings
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 42507
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 21902
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
,07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23420
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 22299
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 24002
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23210
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23205
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23806
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23430
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23408
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 27205
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23205:D:2:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
07-05 12:49:32.098  5419  5419 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
07-05 12:49:32.098  5419  5419 D CustomizationManager:  Read CID file spent 0.117 (s)
07-05 12:49:32.098  5419  5419 D CustomizationManager:  All configurations done spent 0.117 (s)
07-05 12:49:32.098   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 8
07-05 12:49:32.098   954   954 E WifiTrafficPoller:  packet count Tx=167 Rx=225
07-05 12:49:32.098   954   954 E WifiTrafficPoller: notifying of data activity 0
07-05 12:49:32.098  3862  3862 E MediaScannerService: [onStartCommand] --- Should not be here, redirect request. ----
,07-05 12:49:32.108  3862  5478 E MediaScannerService: [handleMessage] --- Should not be here, ignore request. ----
,07-05 12:49:32.108  5372  5483 D MdScShr : [4c.1.2.] subId change: null -> -
,07-05 12:49:32.108  1345  1345 D WIFI_ICON: WifiActivity: 0
,07-05 12:49:32.108  1345  1345 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,07-05 12:49:32.138   954  1797 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest, pid=5419, uid=2000 userid=0
,07-05 12:49:32.138   954  1652 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2206, uid=10024, userID:0,
07-05 12:49:32.138   954  1796 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2206, uid=10024, userID:0
,07-05 12:49:32.148   954  1623 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2206, uid=10024, userID:0
07-05 12:49:32.148   954  1660 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2206, uid=10024, userID:0
07-05 12:49:32.148   954  1787 I ActivityManager: Recipient 4717
,07-05 12:49:32.168  5122  5122 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
07-05 12:49:32.168  5122  5122 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
,07-05 12:49:32.168  5122  5122 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-05 12:49:32.168  5122  5122 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-05 12:49:32.168  5122  5122 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-05 12:49:32.168  5122  5122 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-05 12:49:32.168  5122  5122 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-05 12:49:32.168  5122  5122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-05 12:49:32.168  5122  5122 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15025029 removed from the list
07-05 12:49:32.168  5122  5122 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-05 12:49:32.168  5122  5122 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1889f0dc removed from the list
07-05 12:49:32.168  5122  5122 D io.jxcore.node.ConnectivityMonitor: stop
07-05 12:49:32.168  5122  5122 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-05 12:49:32.208   954  1101 W PackageSettings: Skipping PackageSetting{202c9163 com.example.hello/10374} due to missing metadata,
,07-05 12:49:32.228  5459  5459 D SyncApplication: Loading default preferences,
,07-05 12:49:32.228   954  1101 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=0: pkg removed,
,07-05 12:49:32.228   954  1101 I ActivityManager: Killing 5122:com.test.thalitest/u0a195 (adj 9): stop com.test.thalitest,
07-05 12:49:32.238   954  1101 D Process : killProcessQuiet, pid=5122
,07-05 12:49:32.238   954  1101 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6372 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 ,
,07-05 12:49:32.238  5459  5459 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a},
,07-05 12:49:32.278   954   954 E WifiTrafficPoller: ADD_CLIENT: 9
,07-05 12:49:32.278   954  1268 D WifiService: New client listening to asynchronous messages
,07-05 12:49:32.298  5459  5459 D SyncApplication: Overriding preferences with custom values
,07-05 12:49:32.318  5459  5459 D SyncApplication: Updating preferences succeeded,
,07-05 12:49:32.328  3862  5487 E MediaScannerServiceEx: [getStorageMaskIdFromPath] path is null,
07-05 12:49:32.328  3862  5487 D MediaScannerServiceEx: [ServiceHandler][handleMessage] , action: null, Id: 0, path: /storage/emulated/0
07-05 12:49:32.328  3862  5487 D MediaScannerServiceEx: [handleExternalVolume] ext storage
07-05 12:49:32.328  3862  5487 D MediaProviderUtils: calcVolumeId: /storage/emulated/0
07-05 12:49:32.338  3862  5487 D MediaProviderUtils: calcVolumeId: /storage/ext_sd
07-05 12:49:32.338  3862  5487 D MediaProviderUtils: calcVolumeId: /storage/usb
07-05 12:49:32.338  3862  5487 D MediaScannerServiceEx: [handleExternalVolume] android.intent.action.MEDIA_MOUNTED : [vol] 11223344 : #0
07-05 12:49:32.338  3862  5487 D MediaScannerServiceEx: [AliveExtStorageRows]+65537, 11223344
,07-05 12:49:32.338  3862  5487 D MediaProvider: [update][6]#0#
07-05 12:49:32.338   954  1652 I WindowState: WIN DEATH: Window{b7f41c4 u0 com.test.thalitest/com.test.thalitest.MainActivity},
07-05 12:49:32.338  3862  5487 D MediaProvider: [update][2]#0#
07-05 12:49:32.338   954  1268 D WifiService: Client connection lost with reason: 4
07-05 12:49:32.338   954   983 I ActivityManager: Recipient 5122
07-05 12:49:32.348  1518  1518 E InputEventReceiver: Looper::removeFd(68) is failed, result(0), input channel 'ClientState{cd0e8ad uid 10195 pid 5122} (c)'
,07-05 12:49:32.358  3862  5487 D MediaProvider: [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
07-05 12:49:32.358  3862  5487 D MtpService: [sendStorageAdded] Already send to MTP: /storage/emulated/0
,07-05 12:49:32.358  3862  5487 D MediaProvider: [update][12]#1#
,07-05 12:49:32.358  3862  5487 D MediaScannerServiceEx: [AliveExtStorageRows]-0, 0
,07-05 12:49:32.358   954  1801 D PMS     : acquireWL(31562f43): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 3862 10017 null,
,07-05 12:49:32.468   954  1101 W ActivityManager: ProcessRecord{14eab9c0 5122:com.test.thalitest/u0a195} has been replaced to new process null,
,07-05 12:49:32.488   954  1028 I ActivityManager: Force stopping com.test.thalitest appid=10195 user=-1: uninstall pkg,
,07-05 12:49:32.498  1626  2193 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-05 12:49:32.508  1451  1451 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-05 12:49:32.508  1451  1451 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,07-05 12:49:32.518   954  1787 D PMS     : acquireWL(275fc63e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1847 10024 WorkSource{10024 com.google.android.gms},
07-05 12:49:32.518  1847  2263 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 12:49:32.518   954  1660 D PMS     : releaseWL(275fc63e): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:49:32.518   954   983 W ActivityManager: Spurious death for ProcessRecord{14eab9c0 0:com.test.thalitest/u0a195}, curProc for 5122: null,
07-05 12:49:32.528   954  1258 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-05 12:49:32.528   954  1276 W ActivityManager: unregisterReceiver: receiver object not existed in mRegisteredReceivers
07-05 12:49:32.528  1741  2139 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
,07-05 12:49:32.538   954  1264 V NetworkPolicy: ACTION_UID_REMOVED for uid=10195
,07-05 12:49:32.538  3862  5487 D MediaScanner: =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
07-05 12:49:32.538   954  1263 D PMS     : acquireWL(11ee00d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 954 1000 null
,07-05 12:49:32.538  5459  5459 E SyncApplication: Application created.
,07-05 12:49:32.548   954  1652 I ActivityManager: Killing 4800:com.google.android.partnersetup/u0a27 (adj 15): empty #17
07-05 12:49:32.548   954  1652 D Process : killProcessQuiet, pid=4800
,07-05 12:49:32.548   954  1652 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
07-05 12:49:32.548  1741  2139 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-05 12:49:32.558  5459  5493 W VolumeInfo: Unable to read mount points
07-05 12:49:32.558  5459  5493 W VolumeInfo: java.io.FileNotFoundException: /etc/vold.fstab: open failed: ENOENT (No such file or directory)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.io.FileReader.<init>(FileReader.java:66)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumeMountPoints(VolumeInfo.java:194)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.getVolumes(VolumeInfo.java:153),
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at com.nero.android.common.VolumeInfo.initializeVolumeIDs(VolumeInfo.java:474)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:51)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at com.nero.android.sync.SyncApplication$2.doInBackground(SyncApplication.java:1)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at java.lang.Thread.run(Thread.java:818)
07-05 12:49:32.558  5459  5493 W VolumeInfo: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
,07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at libcore.io.Posix.open(Native Method)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-05 12:49:32.558  5459  5493 W VolumeInfo: 	... 13 more
07-05 12:49:32.558  5459  5493 V VolumeInfo: Found 0 mount point(s),
07-05 12:49:32.558  5459  5493 V VolumeInfo: New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,07-05 12:49:32.578   954  1025 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
07-05 12:49:32.578  5459  5493 D VolumeInfo: read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
07-05 12:49:32.578  5459  5459 I CalendarDefines: getNewCalendarAuthority()...
07-05 12:49:32.578  1741  2139 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-05 12:49:32.578   954  1797 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=5459, uid=10005, userID:0
07-05 12:49:32.578   954  1797 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
07-05 12:49:32.588  1581  1581 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-05 12:49:32.588  5459  5459 D SyncApplication: enableAppOperation()+
,07-05 12:49:32.588   954   985 I PackageManager:  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=5459, uid=10005, userID:0
07-05 12:49:32.588  5459  5459 D SyncApplication: enableAppOperation()-
07-05 12:49:32.588   954   985 W PackageManager: Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,07-05 12:49:32.598  5459  5459 D HTCUtilities: isNeorSinged() + 
07-05 12:49:32.598  5459  5493 D VolumeInfo: Read the volume-id from the sd card: {9B5E872B-8520-47C6-8BD3-3081C2E38355}
,07-05 12:49:32.608  1626  1626 I art     : Explicit concurrent mark sweep GC freed 38489(2MB) AllocSpace objects, 46(3MB) LOS objects, 32% free, 32MB/48MB, paused 1.988ms total 109.256ms,
07-05 12:49:32.608  1741  2139 E ExternalAccountType: Unsupported attribute readOnly
07-05 12:49:32.608  5459  5493 W VolumeInfo: Can not create volume ID for unmounted volume null
,07-05 12:49:32.628  5459  5459 D HTCUtilities: sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,07-05 12:49:32.638  5459  5459 D HTCUtilities: isNeorSinged() return false
,07-05 12:49:32.638  5459  5459 D CDMountReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
07-05 12:49:32.638  5459  5459 D CDMountReceiver: USB connected to PC
,07-05 12:49:32.648   954  1787 I ActivityManager: Recipient 4800
,07-05 12:49:32.668  5459  5459 D FOTAReceiver: onReceive() enter 
07-05 12:49:32.668  5459  5459 D FOTAReceiver: receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,07-05 12:49:32.688   954   954 W PackageManager: Unable to load service info ResolveInfo{1b548b23 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
07-05 12:49:32.688   954   954 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 12:49:32.688   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:49:32.688   954   954 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-05 12:49:32.688   954   954 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-05 12:49:32.688   954   954 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 12:49:32.688   954   954 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:49:32.688   954   954 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:49:32.688   954   954 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 12:49:32.688  , 954   954 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
07-05 12:49:32.688   954  1623 D Process : killProcessQuiet, pid=4759
07-05 12:49:32.688   954  1623 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.NSReceiver: pid=5496 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 12:49:32.688   954  1623 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.trimApplications:19136 
07-05 12:49:32.688   954  1623 I ActivityManager: Killing 4759:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
07-05 12:49:32.698   954  1263 D PMS     : releaseWL(11ee00d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
07-05 12:49:32.698   954  1264 V NetworkPolicy: writePolicyLocked()
,07-05 12:49:32.718   954  1264 V NetworkPolicy: updateNetworkEnabledLocked()
07-05 12:49:32.718   954  1264 V NetworkPolicy: updateNotificationsLocked()
,07-05 12:49:32.728   954  1025 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 12:49:32.768   954  1101 I art     : Explicit concurrent mark sweep GC freed 32534(2MB) AllocSpace objects, 6(184KB) LOS objects, 33% free, 18MB/28MB, paused 2.043ms total 240.990ms
,07-05 12:49:32.778   954  1497 I ActivityManager: Recipient 4759
07-05 12:49:32.778   954  1268 D WifiService: Client connection lost with reason: 4,
,07-05 12:49:32.888   954   954 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,07-05 12:49:32.898  1626  1876 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,07-05 12:49:32.898  1626  1876 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-05 12:49:32.898   954  1300 D TaskPersister: removeObsoleteFile: deleting file=104_task.xml
,07-05 12:49:32.898   954  1300 D TaskPersister: removeObsoleteFile: deleting file=104_task_thumbnail.png
,07-05 12:49:32.918  1741  2139 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-05 12:49:32.918   954  1258 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-05 12:49:32.928  5496  5496 D Fingerprint/ HtcFingerPrintQuickLaunchProvider: -onCreate(),
,07-05 12:49:32.938  1741  2139 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,07-05 12:49:32.948   954  1025 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-05 12:49:32.958  1581  1581 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED,
,07-05 12:49:32.968  5496  5496 V Settings:HtcSettingsApplication: [5496/5496] onCreate()
07-05 12:49:32.968  1741  2139 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-05 12:49:32.978  5496  5496 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,07-05 12:49:32.978  5496  5496 D         : Cust_ConnectToPC   : Internet_Sharing>true
07-05 12:49:32.978  5496  5496 D         : Cust_ConnectToPC   : Modem_Link>false
07-05 12:49:32.978  5496  5496 D         : Cust_ConnectToPC   : spcsc>false
07-05 12:49:32.978  5496  5496 D         : Cust_ConnectToPC   : IPT>true
07-05 12:49:32.978  5496  5496 D         : Cust_ConnectToPC   : Singel_USB>false
,07-05 12:49:32.988  1741  2139 E ExternalAccountType: Unsupported attribute readOnly
,07-05 12:49:32.988   954   954 W PackageManager: Unable to load service info ResolveInfo{aea330f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-05 12:49:32.988   954   954 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-05 12:49:32.988   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950),
07-05 12:49:32.988   954   954 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 12:49:32.988   954   954 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
,07-05 12:49:32.988   954   954 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:324),
07-05 12:49:32.988   954   954 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:225)
07-05 12:49:32.988   954   954 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 12:49:32.988   954   954 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 12:49:32.988   954   954 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
07-05 12:49:32.988   954   954 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,07-05 12:49:32.988  1847  1847 V GmsNetworkLocationProvi: DISABLE
,07-05 12:49:32.998  5496  5496 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-05 12:49:32.998  1847  1847 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-05 12:49:33.008  5496  5496 E SmartNS_Utility: hasRemovableStorageSlot: true,
07-05 12:49:33.008  5496  5496 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
07-05 12:49:33.008  5496  5496 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,07-05 12:49:33.008  5496  5496 D SmartNS_Utility: usb_cable_connect = 1
07-05 12:49:33.018  5496  5496 D SmartNS_Utility: usb_denied = 0
07-05 12:49:33.018  5496  5496 I SmartNS_NSReceiver: locked:falsesecurity:falseisLocked:false
07-05 12:49:33.018  5496  5496 D SmartNS_NSReceiver: USB = true hasTethered = false isNSOpening: false
,07-05 12:49:33.028  5496  5496 I SmartNS_PSReceiver: onReceive:com.htc.intent.action.USB_CONNECT2PC
,07-05 12:49:33.028  5496  5496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.PSReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 
07-05 12:49:33.028   954  1801 D PMS     : acquireWL(35123d3d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1847 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.028   954  4472 D PMS     : releaseWL(35123d3d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.038  5496  5496 I SmartNS_PSService: onReceive:com.htc.intent.action.USB_CONNECT2PC,
,07-05 12:49:33.038  5496  5496 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
07-05 12:49:33.038  5496  5496 I SmartNS_PSService:  defaultType:0
07-05 12:49:33.038  5496  5496 I SmartNS_PSService: fail notificaiton:false
07-05 12:49:33.038  5496  5496 D SmartNS_Utility: usb_cable_connect = 1
07-05 12:49:33.038  5496  5496 D SmartNS_Utility: usb_denied = 0
07-05 12:49:33.038  5496  5496 I SmartNS_PSService: usb notificaiton:true
07-05 12:49:33.048   954  4472 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
07-05 12:49:33.048   954  1796 D PMS     : acquireWL(2aee6765): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1847 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.048   954   954 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
07-05 12:49:33.048   954  1802 D PMS     : releaseWL(2aee6765): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:49:33.048  5496  5496 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,07-05 12:49:33.058   954  1025 D LocationProviderProxy: applying state to connected service
07-05 12:49:33.058   954  1025 D LocationProviderProxy: applying state to connected service
,07-05 12:49:33.058   954  1025 D PMS     : acquireWL(2f1b1e1d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1847 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.058  5496  5496 D SmartNS_Utility: usb_cable_connect = 1
07-05 12:49:33.068  5496  5496 D SmartNS_Utility: usb_denied = 0
07-05 12:49:33.068  5496  5496 I SmartNS_PSService: usb notificaiton:true
,07-05 12:49:33.068   954   985 D PMS     : releaseWL(2f1b1e1d): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
07-05 12:49:33.068   954  1801 E WifiStateMachine: WiFiDisplay: getWifidisplayApEnabled=false
,07-05 12:49:33.068   954   954 D PMS     : acquireWL(15d07f19): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1847 10024 WorkSource{10024 com.google.android.gms}
07-05 12:49:33.068  1451  1498 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
07-05 12:49:33.068   954  1796 D PMS     : releaseWL(15d07f19): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.068  5496  5496 D SmartNS_Utility: usb_cable_connect = 1
07-05 12:49:33.078  5496  5496 D SmartNS_Utility: usb_denied = 0
,07-05 12:49:33.078  1345  1345 I RemoteViews: reapply : com.android.settings 1 36
07-05 12:49:33.078  5496  5496 I SmartNS_PSService: KeyGuard locked:falseKeyGuard is secured:false
,07-05 12:49:33.078  5496  5496 D SmartNS_PSService: USB Plugged, Set USBPlugged=  truePSenabled:false
07-05 12:49:33.078   954  1514 D Process : killProcessQuiet, pid=4862
07-05 12:49:33.078   954  1514 I ActivityManager: Killing 4862:com.google.android.music:main/u0a159 (adj 15): empty #17
07-05 12:49:33.078   954  1514 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 12:49:33.178   954  3238 I ActivityManager: Recipient 4862
,07-05 12:49:33.178   954  1796 D MediaRouterService: Client com.google.android.music (pid 4862): Died!
,07-05 12:49:33.188   954  1660 D PMS     : acquireWL(36d5ebde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1943 10024 WorkSource{10024 com.google.android.gms}
,07-05 12:49:33.198   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-05 12:49:33.198  1345  1345 D WIFI_ICON: WifiActivity: 3
07-05 12:49:33.198   954   954 E WifiTrafficPoller:  packet count Tx=171 Rx=230
,07-05 12:49:33.198  1345  1345 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
07-05 12:49:33.198   954   954 E WifiTrafficPoller: notifying of data activity 3
,07-05 12:49:33.208  1451  1498 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837809, tag: null, isClearable: false, isForDotMatrix: false
,07-05 12:49:33.208  1345  1345 I RemoteViews: reapply : com.android.settings 2 36,
,07-05 12:49:33.218   954   954 I ActivityManager: Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=5524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 12:49:33.228   954  1497 D PMS     : releaseWL(36d5ebde): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,07-05 12:49:33.398  5524  5524 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.backupreset.receiver.BackupResetReceiver.onReceive:45 android.app.ActivityThread.handleReceiver:2712 ,
,07-05 12:49:33.418  4927  4927 D FlexNetS: updateSvcAllowedInSettings:false
,07-05 12:49:33.438  1683  5547 D WeatherUtility: Weather sync is On
,07-05 12:49:33.438   954   985 I ActivityManager: Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=5548 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
07-05 12:49:33.448  1683  5547 D WSP     : [Receiver] auto sync agent, auto sync is enabled, reset schedule
,07-05 12:49:33.458   954  3238 I ActivityManager: Killing 4960:com.google.android.setupwizard/u0a77 (adj 15): empty #17,
07-05 12:49:33.458   954  3238 D Process : killProcessQuiet, pid=4960
,07-05 12:49:33.458   954  3238 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 12:49:33.568   954  1652 I ActivityManager: Recipient 4960,
,07-05 12:49:33.738   954  1796 I ActivityManager: Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=5570 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
,07-05 12:49:33.758  5548  5575 D WeatherUtility: Weather sync is On,
,07-05 12:49:33.898  5548  5575 W WeatherRequest: request cur loc, but there is no sys cur,
07-05 12:49:33.898  5548  5575 W Settings: Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-05 12:49:33.908  5570  5570 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,07-05 12:49:33.908  5548  5575 I ActionCombine: replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,07-05 12:49:33.918   954  1514 D PMS     : acquireWL(5d0e7ea): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 4927 10011 null,
,07-05 12:49:33.928  5570  5594 D PowerUtils: getUserIdOfProcess, curUserId = 0
,07-05 12:49:33.928  5570  5594 D PowerUtils: isRunningUnderOwner, isOwner = true
,07-05 12:49:33.938  1626  1626 I RemoteViews: reapply : com.htc.widget.weatherclock 12 17
,07-05 12:49:33.938  4927  5595 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 12:49:33.938  4927  5595 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.calendar/databases/calendar.db, handle: 0x5594e80870
,07-05 12:49:33.938  4927  5595 W CalendarAlarmManager: runScheduleNextAlarm : SQLiteException,android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 12:49:33.938  4927  5595 W System.err: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,07-05 12:49:33.948  4927  5595 W System.err: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:915)
07-05 12:49:33.948  4927  5595 W System.err: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
,07-05 12:49:33.948   954  1660 I ActivityManager: Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=5596 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 1023, 2001, 3002} abi=armeabi-v7a
,07-05 12:49:33.948  4927  5595 W System.err: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:565)
,07-05 12:49:33.948  4927  5595 W System.err: 	at com.android.providers.calendar.CalendarAlarmManager.runScheduleNextAlarm(CalendarAlarmManager.java:276)
,07-05 12:49:33.948  4927  5595 W System.err: 	at com.android.providers.calendar.CalendarProviderIntentService.onHandleIntent(CalendarProviderIntentService.java:46)
07-05 12:49:33.948  4927  5595 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-05 12:49:33.948  4927  5595 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 12:49:33.948  5570  5594 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-05 12:49:33.948  4927  5595 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-05 12:49:33.948  4927  5595 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 12:49:33.958   954  1514 D PMS     : releaseWL(5d0e7ea): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,07-05 12:49:33.968  5570  5594 D PowerUsageService: repeat time = 1467716673980,
,07-05 12:49:33.978   439   439 I art     : Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 442us total 33.224ms,
,07-05 12:49:34.008   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 418us total 28.491ms
,07-05 12:49:34.038   439   439 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 414us total 28.245ms
,07-05 12:49:34.078  5596  5596 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,07-05 12:49:34.078  5570  5594 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8,
,07-05 12:49:34.098  5570  5594 D PowerUtils: getUserIdOfProcess, curUserId = 0,
,07-05 12:49:34.108  5570  5594 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 1000, sipper.name = com.android.settings:remote,
07-05 12:49:34.108  5570  5594 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10024, sipper.name = com.google.android.gms.persistent
07-05 12:49:34.108  5570  5594 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 12:49:34.118  5570  5594 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,07-05 12:49:34.118  5570  5594 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 10041, sipper.name = com.htc.dotmatrixevent
,07-05 12:49:34.118  5570  5594 D PowerUsageList:PowerUsageHelper: calcPower(), skip because sipper.cpuTime = 0, sipper.uId = 0, sipper.name = null
,07-05 12:49:34.118   954  1801 E SQLiteLog: (3850) statement aborts at 36: [INSERT INTO secure(name,value) VALUES (?,?)] disk I/O error
07-05 12:49:34.118   954  1801 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.android.providers.settings/databases/settings.db, handle: 0x5594f4d9b0
,07-05 12:49:34.128   954  1801 E SQLiteDatabase: Error inserting ...
07-05 12:49:34.128   954  1801 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:810)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1549)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1404)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at com.android.providers.settings.SettingsProvider.insertForUser(SettingsProvider.java:1526)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:845)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:377)
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:318),
07-05 12:49:34.128   954  1801 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:454)
07-05 12:49:34.128  5570  5594 D PowerUsageService: calcPower(), no data
,07-05 12:49:34.128   954  1497 D Process : killProcessQuiet, pid=4983,
07-05 12:49:34.128   954  1497 I ActivityManager: Killing 4983:com.google.android.apps.photos/u0a197 (adj 15): empty #17,
07-05 12:49:34.128   954  1497 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18866 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18709 
,07-05 12:49:34.168  5596  5596 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 12:49:34.168  5596  5596 I MultiDex: install
07-05 12:49:34.168  5596  5596 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 12:49:34.198   954   954 E WifiTrafficPoller: TRAFFIC_STATS_POLL true Token 11 num clients 7
07-05 12:49:34.198  1345  1345 D WIFI_ICON: WifiActivity: 1
,07-05 12:49:34.198   954   954 E WifiTrafficPoller:  packet count Tx=171 Rx=233
07-05 12:49:34.198  1345  1345 D StatusBar.NetworkController: dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
07-05 12:49:34.198   954   954 E WifiTrafficPoller: notifying of data activity 1
,07-05 12:49:34.238   954   983 I ActivityManager: Recipient 4983
,07-05 12:49:34.278   954   954 E WifiDataStallTracker: DATA_MONITOR_POLL true Token 1
07-05 12:49:34.278   954  5618 D WifiDataStallTracker: updateDataStallInfo: mDataStallTxRxSum={txSum=151 rxSum=138} preTxRxSum={txSum=125 rxSum=121}
07-05 12:49:34.278   954  5618 D WifiDataStallTracker: updateDataStallInfo: IN/OUT
07-05 12:49:34.278   954  5618 D WifiDataStallTracker: onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5

```
