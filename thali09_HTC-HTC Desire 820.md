#### Test 57924002d5e0b14_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/AutoSetting( 1323): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:83, mTXpacketCount:38, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/AutoSetting( 1323): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1323): service - requestNLP() NetworkLocationProvider not enabled
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
--------- beginning of /dev/log/system
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
D/PMS     (  910): acquireWL(42a5ed88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
E/cutils-trace( 4087): Error opening trace file: No such file or directory (2)
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
D/PMS     (  910): acquireWL(42a2d240): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42a5ed88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
D/PMS     (  910): releaseWL(42a2d240): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
D/CustomizationManager( 4087): ====startRecUseTime====
D/htc.customization.log.level( 4087):  is 
W/CustomizationLogLevel( 4087): Level value is invalid, use default level 2
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
D/PMS     (  910): acquireWL(429c3840): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
D/PhoneApp( 1253): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  910): releaseWL(429c3840): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42a63bc8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4087):  Read ACC file spent 0.075 (s)
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4087): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4087): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4087): Parsing tag category name = system
I/CustomizationCIDLoader( 4087): Parsing tag category name = application
I/CustomizationCIDLoader( 4087): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4087): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4087): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4087): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4087): Parsing tag category name = Settings
D/CustomizationManager( 4087):  Read CID file spent 0.125 (s)
D/CustomizationManager( 4087):  All configurations done spent 0.125 (s)
W/HtcNativeFlag( 4087): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4087): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4087): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4087): Fail to get flag for type 'language', use default value: -1
D/PMS     (  910): releaseWL(42a63bc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(429c6930): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4087
D/PMS     (  910): releaseWL(429c6930): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42a4d208): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42a4d208): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42a000c8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42a000c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(429995c8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429995c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(429e81c8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429e81c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(4299ebb8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1279): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1279): loadItems() com.htc.launcher.pageview.WidgetManager@41eb5c70 +
I/Prism.WidgetManager( 1279): onLoadItems() +
D/PMS     (  910): releaseWL(4299ebb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 3780): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3780): loadItems() com.htc.launcher.pageview.WidgetManager@41e9abd0 +
I/Prism.WidgetManager( 3780): onLoadItems() +
,I/IcingCorporaProvider( 2860): UpdateCorporaTask done [took 1531 ms] updated apps [took 1531 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
W/PackageManager(  910): Unable to load service info ResolveInfo{42a69478 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  910): acquireWL(42a95058): PARTIAL_WAKE_LOCK  AsyncService 0x1 3668 10160 null
D/PMS     (  910): releaseWL(42a95058): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4101 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
W/dalvikvm( 4101): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/Settings:HtcWirelessFeatureFlags( 3848): id/is att sku: 99/false
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4101, uid=10074, userID:0
W/SystemReader( 3848): Cannot find devicepolicy_lower_fp_quality, use default value instead
D/Finsky  ( 4101): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4101/10074)
W/SystemReader( 3848): Cannot find support_harman, use default value instead
W/SystemReader( 3848): Cannot find effect_manager_id, use default value instead
E/Settings:HtcWrapHeaderInfo( 3848): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3848): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3848): updateDevelopment, bPrefShow = true
W/dalvikvm( 4101): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
E/Settings:HtcUmcWidgetEnabler( 3848): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]support         :false
W/dalvikvm( 4101): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]support         :false
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (4101/10074)
W/FingerprintManager( 3848): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 3848): isSupportVoWifi: null
D/Finsky  ( 4101): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
E/ActivityThread( 3848): Failed to find provider info for com.htc.vowifi
W/dalvikvm( 4101): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4101): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4101): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 4101): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4101): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4101): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3848): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3848): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3848): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3848): [supportHomeButton]support         :false
W/FingerprintManager( 3848): hasFingerprint() - sSensorCode = 0
W/dalvikvm( 4101): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4101, uid=10074, userID:0
I/ActivityManager(  910): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3848): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 3848): isSupportVoWifi: null
D/Ads     ( 4101): Skipping gmscore version check
D/Finsky  ( 4101): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4101): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4101): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/dalvikvm( 4101): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  910): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/Finsky  ( 4101): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/Prism.WidgetManager( 1279): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1279): onLoadItems() -
I/Prism.ItemManager( 1279): loadItems() com.htc.launcher.pageview.WidgetManager@41eb5c70 -
D/Process (  910): killProcessQuiet, pid=3823
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Killing 3823:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Recipient 3823
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  910): Client connection lost with reason: 4
I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/PMS     (  910): acquireWL(42ae3448): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/Prism.WidgetManager( 3780): onLoadItems() -
I/Prism.ItemManager( 3780): loadItems() com.htc.launcher.pageview.WidgetManager@41e9abd0 -
,W/dalvikvm( 2197): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2197): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2197): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2197): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2197): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2197): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2197): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2197, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2197): cleanUpNonGplusAccounts done.
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,D/NotificationService(  910): notification sound not played, stream=5 volume=0 always=false
,D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1591): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/RemoteViews( 1122): com.htc.updater (true,33751552)
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{422000e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1122): com.htc.updater 5 11 0 10
,I/RemoteViews( 1122): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41e2c628 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.htc.updater 7 11 1 10
,I/GCoreNlp( 1233): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/Process (  910): killProcessQuiet, pid=3780
,I/ActivityManager(  910): Killing 3780:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42b32960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42b32960): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  910): applying state to connected service
D/PMS     (  910): acquireWL(42b34a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b35cf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b34a20): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b35cf8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Recipient 3780
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 7 times.
,D/PhoneApp( 1253): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1253): -- N1 =0
,D/PhoneApp( 1253): -- N2 =0
,D/PhoneApp( 1253): -- N3 =0
,I/Icing   ( 2197): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2197): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  910): releaseWL(42ae3448): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4151 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/SensorManager(  910): mEventCount = 450
,W/GAV2    ( 4151): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  910): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  910): acquireWL(42b477d0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b477d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4174 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  910): killProcessQuiet, pid=3754
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3754:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,D/PMS     (  910): acquireWL(42b51c70): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b51c70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3754
,I/Gmail   ( 4151): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4151): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4151): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4151): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/Process (  910): killProcessQuiet, pid=3767
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3767:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3767
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/dalvikvm( 4174): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4174): VFY: unable to resolve instance field 36
,W/dalvikvm( 4174): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/Babel   ( 4174): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4174): MmsConfig.loadMmsSettings
,V/JNIHelp ( 4174): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3798): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3798): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4174, uid=10111, userID:0
,I/Babel   ( 4174): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4174): MmsConfig.loadFromDatabase
,W/Settings( 4174): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 4174): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4174): MmsConfig.loadFromResources
,E/Babel   ( 4174): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4174): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4174, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4174, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4174, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4174, uid=10111, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4174, uid=10111, userID:0
D/PMS     (  910): acquireWL(42b1bb18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4174 10111 null
,D/PMS     (  910): acquireWL(42ae20d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(42ae20d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a50108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 4174): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/GCoreFlp( 1233): No location to return for getLastLocation()
,W/FusedLocationProvider( 1233): location=null
D/PMS     (  910): releaseWL(42a50108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(429f6c90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429f6c90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/PMS     (  910): acquireWL(429d2268): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,W/SQLiteConnectionPool( 2197): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  910): releaseWL(42b1bb18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  910): killProcessQuiet, pid=3867
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3867:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/PMS     (  910): acquireWL(4275a020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(4275a020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42703b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(429d2268): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(42703b78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42864768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42864768): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Recipient 3867
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  910): acquireWL(429a2f30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(429a2f30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(429435f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  910): acquireWL(41f41988): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4174 10111 null
D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
D/PMS     (  910): releaseWL(41f41988): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4224 uid=10041 gids={50041}
,D/ConnectivityService(  910): Done.
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,D/ConnectivityService(  910): Setting timer for 720seconds
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(429435f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42904440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3489 10071 null
,I/ActivityManager(  910): Killing 3460:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/Process (  910): killProcessQuiet, pid=3460
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  910): acquireWL(42976b58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3489 10071 null
E/TodoTaskNotifyService( 3489): java.lang.NullPointerException
,W/System.err( 3489): java.lang.NullPointerException
W/System.err( 3489): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3489): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3489): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3489): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  910): releaseWL(42904440): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  910): Recipient 3460
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/NotifyReceiver( 3489): stopSelfResult true
,E/TodoTaskNotifyService( 3489): java.lang.NullPointerException
W/System.err( 3489): java.lang.NullPointerException
W/System.err( 3489): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3489): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3489): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3489): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  910): acquireWL(4274dd50): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3489 10071 null
D/PMS     (  910): releaseWL(42976b58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  910): acquireWL(42801ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3489 10071 null
D/PMS     (  910): releaseWL(4274dd50): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  910): releaseWL(42801ba8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/PMS     (  910): acquireWL(42912348): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3489 10071 null
,W/NotifyReceiver( 3489): stopSelfResult true
E/TodoTaskNotifyService( 3489): java.lang.NullPointerException
W/System.err( 3489): java.lang.NullPointerException
W/System.err( 3489): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3489): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
,W/System.err( 3489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3489): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3489): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  910): acquireWL(4296d5d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3489 10071 null
D/PMS     (  910): releaseWL(42912348): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  910): releaseWL(4296d5d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3489): stopSelfResult true
,D/WearableService( 1233): callingUid 10029, callindPid: 1233
,D/LocationInitializer( 2197): Restart initialization of location
,D/AuthorizationBluetoothService( 1373): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1373): Proximity feature is not enabled.
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1233): [107] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(429e6810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1233): No location to return for getLastLocation()
,W/FusedLocationProvider( 1233): location=null
D/PMS     (  910): releaseWL(429e6810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(429fecd8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 910 1000 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
I/WSP     ( 1323): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1323): Weather sync is On
,I/WSP     ( 1323): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 21:17:25 CET 2016
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(4290eb18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(41f42800): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1323/10055)
D/PMS     (  910): releaseWL(429fecd8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
D/PMS     (  910): releaseWL(4290eb18): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (2197/10029)
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.sense.hsp (1323/10055)
I/ActivityManager(  910): Delay finish: com.htc.task/.TodoReceiver
D/PMS     (  910): acquireWL(429aa688): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1323 10055 null
,D/TodoTaskshortcut( 3489): update TASK shortcut>
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  910): acquireWL(42981ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029}
,V/AlarmManager(  910): sending alarm PendingIntent{428868e0: PendingIntentRecord{426496f0 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454440639666, Int=1800000
,V/AlarmManager(  910): sending alarm PendingIntent{428d0af0: PendingIntentRecord{428a2158 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454440646206, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42397220: PendingIntentRecord{4214d0a8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454440647960, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{421488d0: PendingIntentRecord{421462f0 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454440648007, Int=0
,I/iu.UploadsManager( 2197): End new media; added: 0, uploading: 0, time: 80 ms
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 8 times.
,I/GAV2    ( 4151): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4174): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1535): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1535): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(428e0ef8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4174 10111 null
,I/ActivityManager(  910): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  910): releaseWL(428e0ef8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1323): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1323): handle notify Blinkfeed plugin client changed
I/ActivityManager(  910): Resuming delayed broadcast
,I/IcingCorporaProvider( 2860): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  910): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  910): acquireWL(42a102b0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a102b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42927718): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42927718): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a08468): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a08468): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42993fc0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42993fc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(429cf208): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(429cf208): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(428cdfe8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,D/PMS     (  910): releaseWL(428cdfe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(41f42528): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(41f42528): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42856150): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42856150): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(429657c0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(429657c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2860): UpdateCorporaTask done [took 316 ms] updated apps [took 316 ms] 
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  910): acquireWL(4298fa58): PARTIAL_WAKE_LOCK  AsyncService 0x1 3668 10160 null
,D/PMS     (  910): releaseWL(4298fa58): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  910): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2197): Null package name or gms related package.  Ignoreing.
,D/PMS     (  910): acquireWL(42b1f118): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2197): updateResources: need to parse f{com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2197, uid=10029, userID:0
,I/CheckinService( 2197): Done disabling old GoogleServicesFramework version
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2197, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2197, uid=10029, userID:0
,D/PMS     (  910): acquireWL(42b3b240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42b3b240): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 2197): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2197): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2197): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  910): releaseWL(42b1f118): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42b43de0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3902 10154 null
,I/ActivityManager(  910): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3902): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3902): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3902): Conditions not met for autocaching.
,I/MusicLeanback( 3902): Stop autocaching.
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3902, uid=10154, userID:0
D/PMS     (  910): releaseWL(42b43de0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3884): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  910): Resuming delayed broadcast
,D/PMS     (  910): acquireWL(42b27088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): releaseWL(42b27088): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(429e19e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(429e19e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(429188e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
D/PMS     (  910): acquireWL(42863370): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(41ff8300): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429188e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42863370): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2197): Aggregate from 1454440636390 (log), 1454438839629 (data)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4282 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  910): releaseWL(41ff8300): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SyncApplication( 4282): Loading default preferences
,W/Resources( 4282): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  910): New client listening to asynchronous messages
,D/SyncApplication( 4282): Overriding preferences with custom values
,D/SyncApplication( 4282): Updating preferences succeeded
,E/SyncApplication( 4282): Application created.
D/VolumeInfo( 4282): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4282): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4282): Found 0 mount point(s)
,V/VolumeInfo( 4282): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4282): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 4282): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4282): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 4282): getNewCalendarAuthority()...
,D/SyncApplication( 4282): enableAppOperation()+
,D/SyncApplication( 4282): enableAppOperation()-
,D/HTCUtilities( 4282): isNeorSinged() + 
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4282, uid=10008, userID:0
W/PackageManager(  910): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4282, uid=10008, userID:0
W/PackageManager(  910): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4282): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4282): isNeorSinged() return false
,D/CDMountReceiver( 4282): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4282): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4282): enable CD Auto-mount: true
,D/DotMatrix( 1591): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4282): enable auto-mount
,D/HTCUtilities( 4282): enable auto-mount
,I/RemoteViews( 1122): com.nero.android.htc.sync (false,0)
I/ActivityManager(  910): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  910): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  910): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  910): Resuming delayed broadcast,
D/PMS     (  910): releaseWL(42981ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41fc9f88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.nero.android.htc.sync 1 17 4 11
,I/RemoteViews( 1122): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{41fd62c0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  910): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4303 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/Process (  910): killProcessQuiet, pid=4001
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/RemoteViews.Performance( 1122): com.nero.android.htc.sync 1 14 2 16
I/ActivityManager(  910): Killing 4001:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,D/CalendarApplication( 4303): onCreate
D/ProviderChangeReceiver( 4303): ---------------------------------------------------
,D/ProviderChangeReceiver( 4303): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4303): start to updateAlertNotification!
,D/Process (  910): killProcessQuiet, pid=4041
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4317 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  910): Killing 4041:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4041
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AlertService( 4303): No fired or scheduled alerts
D/HtcAlertUtils( 4303): -- cancelReminderNotification --
D/HtcAlertUtils( 4303): broadcastExistReminder!
D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  910): Recipient 4001
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  910): Client connection lost with reason: 4
,V/Settings:HtcSettingsApplication( 4317): [4317/4317] onCreate()
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,D/Process (  910): killProcessQuiet, pid=3927
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  910): Killing 3927:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3927
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42a57e70 u0 com.htc.musicenhancer/.EnhancerService}
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 9 times.
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  910): releaseWL(429aa688): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=55 rxSum=46} preTxRxSum={txSum=55 rxSum=46}
D/WifiDataStallTracker(  910): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=19611 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19612 delay=15s
D/PMS     (  910): acquireWL(4288cfe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{427e8df0: PendingIntentRecord{427860e0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=75469, Int=0
D/PMS     (  910): releaseWL(4288cfe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  910): mEventCount = 600
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:83, mTXpacketCount:83, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 10 times.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/Finsky  ( 4101): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4101): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  910): acquireWL(41f41be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10074}
V/AlarmManager(  910): sending alarm PendingIntent{425be290: PendingIntentRecord{41e9f798 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454440660739, Int=0
D/PMS     (  910): releaseWL(41f41be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.android.vending (4101/10074)
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4101): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4101): [NET] getaddrinfo-,err=8
D/libc    ( 4101): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4101): [NET] getaddrinfo-, 1
,D/libc    ( 4101): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1832 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4101): [NET] getaddrinfo_proxy-, success
,I/global  ( 4101): call createSocket() return a new socket.
D/libc    ( 4101): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4101): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4101): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4101): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1122): WifiActivity: 3
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4101): untagSocket(69) failed with errno -22
,D/Finsky  ( 4101): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4101): untagSocket(69) failed with errno -22
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4101): untagSocket(69) failed with errno -22
,D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=4 [66][3][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074),
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/ContactMessageStore( 1253): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1253): MSG_NOTIFY_CS_TO_SYNC <<
D/ConnectivityService(  910): getNetworkInfo networkType=1 called by com.android.vending (4101/10074)
,D/Finsky  ( 4101): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  910): acquireWL(42ac3978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10074}
,V/AlarmManager(  910): sending alarm PendingIntent{42944f30: PendingIntentRecord{42a6ad40 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454440663414, Int=0
,D/PMS     (  910): acquireWL(429a5be8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4101 10074 null
,D/WearableService( 1233): callingUid 10029, callindPid: 1233
,D/PMS     (  910): releaseWL(42ac3978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4101): [437] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1233): client connected with version: 8296000
,D/Finsky  ( 4101): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4101): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4101): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4101): [NET] getaddrinfo-,err=8
D/libc    ( 4101): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4101): [NET] getaddrinfo-, 1,
,D/libc    ( 4101): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4fa6 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299,
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS,
,D/libc    ( 4101): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  910): releaseWL(429a5be8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 11 times.
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1323): service - mHandler: update timezone
,D/AutoSetting( 1323): service - handleMessage() stop self
,D/AutoSetting( 1323): service - handleMessage() quit looper
,D/AutoSetting( 1323): service - onDestroy() END
,D/Process (  910): killProcessQuiet, pid=3959
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3959:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3959
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1535): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1535): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1535): service - onCreate()
W/ActivityManager(  910): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1535): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1535): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1535): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1535): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1535): service - mHandler: update timezone
,D/AutoSetting( 1535): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1535): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1535): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1535): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1591): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1591): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [13][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/RemoteViews( 1122): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1122): release indeterminate drawable android.widget.OnDemandProgressBar{42243938 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1122): com.htc.htclocationservice 1 7 2 11
,I/SensorManager(  910): mEventCount = 750
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 12 times.
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=132 rxSum=116} preTxRxSum={txSum=55 rxSum=46}
D/WifiDataStallTracker(  910): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=19612 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19613 delay=15s
,D/PMS     (  910): acquireWL(42aa63e0): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b453a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4296d388: PendingIntentRecord{427860e0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=90476, Int=0
,D/PMS     (  910): releaseWL(42b453a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): releaseWL(42aa63e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b43d40): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b43d40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b3c080): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b3c080): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b3bbd8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b3bbd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b27088): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b27088): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:165, mTXpacketCount:83, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1535): handler message = 4011
,E/HtcModeClient( 1535): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1535): Don't start project servcice
,D/HtcModeClient( 1535): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1535): connectState: CONNECTION_READY = false
,D/SilentMusic( 1535): call stop
,D/HtcModeClient( 1535): close connection
,W/HtcModeClient( 1535): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1535): read the terminate packet, so break
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4351 uid=10078 gids={50078}
,D/PMS     (  910): acquireWL(42a5ed88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10078}
,V/AlarmManager(  910): sending alarm PendingIntent{42a0bf58: PendingIntentRecord{4270c520 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454440676083, Int=60000
,D/PMS     (  910): releaseWL(42a5ed88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4351): SMSBackupAgentService started
,D/SMSBackup( 4351): Checking restore status
D/SMSBackup( 4351): Restore complete
,D/SMSBackup( 4351): cancelCheckAlarm
,D/SMSBackup( 4351): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  910): killProcessQuiet, pid=4060
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
I/ActivityManager(  910): Killing 4060:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4060
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42a07e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10074}
,V/AlarmManager(  910): sending alarm PendingIntent{427350e0: PendingIntentRecord{429cfb70 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454440677243, Int=0
,D/PMS     (  910): releaseWL(42a07e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4101): [428] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4101): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/PMS     (  910): acquireWL(426f27e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1122): now=1454440680008 next=59992
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=99378, Int=0
,D/PMS     (  910): releaseWL(426f27e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{4296a5e8 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  910): setLight #0: color=#25
,V/LightsService(  910): setLight #0: color=#22
,V/LightsService(  910): setLight #0: color=#18
,V/LightsService(  910): setLight #0: color=#14
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiDataStallTracker(  910): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  910): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  910): updateDataStallInfo: mDataStallTxRxSum={txSum=132 rxSum=116} preTxRxSum={txSum=132 rxSum=116}
D/WifiDataStallTracker(  910): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  910): onDataStallAlarm: tag=19613 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19614 delay=15s
D/PMS     (  910): acquireWL(42664b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{4268cb20: PendingIntentRecord{427860e0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=105480, Int=0
D/PMS     (  910): releaseWL(42664b38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  910):    returned true
,D/WifiStateMachine(  910): [ScoreAP] + current TXpacket:165, mTXpacketCount:165, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  910): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1122): WifiActivity: 1
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  910):    returned true
,I/SensorManager(  910): mEventCount = 900
,I/PMS     (  910): Going to sleep due to screen timeout...
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@4257ecc0
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Light sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@4257ecc0, eanble = 0, strlen(mName) = 59
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  910): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322810
W/SensorService(  910): Listener[1] = com.htc.smartdim.sensor_eye@429dc668
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WirelessDisplayService(  910): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  910): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  910): mWirelessDisplayManager is null
W/BatSI   (  910): Couldn't get kernel wake lock stats
V/LightsService(  910): setLight #2: color=#0
D/qdlights(  910): set_light_buttons_func: on=0 brightness=0
V/LightsService(  910): setLight #0: color=#0
,D/SurfaceControl(  910): Excessive delay in blankDisplay() while turning screen off: 345ms
,W/PnPMgr  (  349): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  910): nativeSetInteractive:false
D/PMS     (  910): nativeSetInteractive:false done
D/PMS     (  910): nativeSetAutoSuspend:true
D/PMS     (  910): nativeSetAutoSuspend:true done
D/HABCtrl (  910): TPE algorithm. remove timeout.
D/PMS     (  910): OOBE c monitor 11
I/InputManager(  910): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  910): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42974598)
D/NfcService( 1264): ScreenObserver: OFF
D/NfcService( 1264): applyRouting - 0
,I/IntentController( 1122): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1264): applyRouting -2
I/InputMethodManagerService(  910): screenObserver, isScreenOn=false
I/InputMethodManagerService(  910): Disable input method client, pid=1279
D/PMN     (  910): wakingUp
D/PMS     (  910): acquireWL(42acd670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1264 1027 null
,V/KeyguardServiceDelegate(  910): **** SHOWN CALLED ****
D/PMS     (  910): releaseWL(42acd670): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  910): No lock screen! windowToken=null
,D/PMN     (  910): onScreenOn
,D/PMS     (  910): acquireWL(4295dde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
W/XT9_C   ( 1217): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1217): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1217): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  910): releaseWL(4295dde8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/MtpService( 2396): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/MtpService( 2396): [MTP][onReceive]-
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/NfcService( 1264): applyRouting - 0
D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  910): acquireWL(42a1f390): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1264 1027 null
D/NfcService( 1264): applyRouting -2
D/PMS     (  910): releaseWL(42a1f390): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4371 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/AlarmManager(  910): ACTION_SCREEN_ON
I/AlarmManager(  910): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  910): [AlarmQueuing] done recovering
I/AlarmManager(  910): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  910): [AlarmQueuing] done EPS screen off alarm recovering
D/WirelessDisplayService(  910): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
,I/ClockThread( 1122): stop update clock
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  910): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  910): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_ON
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/WifiDataStallTracker(  910): startDataStallAlarm: tag=19615 delay=15s
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:On
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  910):    returned true
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1122): WifiActivity: 1
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  910): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
V/NotificationService(  910): batLight: Full, plugged
V/LightsService(  910): setLight #8: color=#c8c800
D/qdlights(  910): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  910): setLight #8: color=#c800
D/qdlights(  910): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  910): [LedInfo] has indicator attribute
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/qdlights(  910): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WIFI_ICON( 1122): WifiActivity: 0
,D/StatusBar.NetworkController( 1122): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  910): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  910): doBoolean: SignalStrength 97
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  910):    returned true
,D/NetworkPolicy(  910): updateScreenOn: false
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3848): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3848): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3848): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3848): Cust_ConnectToPC   : spcsc>false
D/        ( 3848): Cust_ConnectToPC   : IPT>true
,D/        ( 3848): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3848): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3848): Index of the first 1 = -1
W/Settings( 3848): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3848): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3848): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3848): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3848): [ACC]android_networking:tethering_guard_support=false
W/ContextImpl( 3848): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 3848): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1323): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1323): service - onCreate()
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/TetherSettings( 3848): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3848): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3848): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3848): Cust_ConnectToPC   : spcsc>false
D/        ( 3848): Cust_ConnectToPC   : IPT>true
D/        ( 3848): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3848): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3848): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3848): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3848): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1323): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1323): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3848): onReceive:android.intent.action.USER_PRESENT
D/PMS     (  910): acquireWL(42a53c48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42a53c48): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/ContextImpl( 3848): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,D/LocationManagerService(  910): request 428da0e0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  910): provider request: passive ProviderRequest[ON interval=0]
I/SmartNS_PSService( 3848): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3848): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3848):  defaultType:0
D/PMS     (  910): acquireWL(42a2d2c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a2d2c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1784): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): onScreenOn: 1454440691386
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1784): onScreenOn: 1454440691386
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322810
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 2
W/SensorService(  910): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
,W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42322810, eanble = 0, strlen(mName) = 91
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  910): Listener[0] = com.htc.smartdim.sensor_eye@429dc668
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  910): goingToSleep
D/PMS     (  910): acquireWL(42b420f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 910 1000 null
,I/FeedHostManager( 1279): [onPause]
,I/FeedProviderManager( 1279): onPause
,I/FeedHostManager( 1279): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42544218
I/SocialFeedProvider( 1279): +onPause
,I/SocialFeedProvider( 1279): -onPause
,D/AlarmManager(  910): ACTION_SCREEN_OFF
I/AlarmManager(  910): [AlarmQueuing] screen off now: 
I/AlarmManager(  910): [AlarmQueuing] data connection: true
,I/AlarmManager(  910): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  910): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  910): stopDataStallAlarm: current tag=19615 mDataStallAlarmIntent=PendingIntent{42a023d0: PendingIntentRecord{427860e0 android broadcastIntent}}
D/WifiNative-wlan0(  910): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): SET_SCREEN_ON:Off
I/wpa_supplicant( 1163): htc_wext_set_keepalive +
I/wpa_supplicant( 1163): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1163): getPrivFuncNum +	
I/wpa_supplicant( 1163): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1163): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1163): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1163): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1163): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  910): doBoolean: DRIVER SETSUSPENDMODE 1
,D/WifiNative-wlan0(  910):    returned true
D/PMS     (  910): releaseWL(42b420f0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): acquireWL(42a1dbc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 910 1000 null
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
W/ContextImpl( 4371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/NetworkPolicy(  910): updateScreenOn: false
,D/ContactMessageStore( 1253): start background delete task...
D/ContactMessageStore( 1253): size: 0 , 0
,D/ContactMessageStore( 1253): Background delete complete
,D/SmartSyncUtils( 4371): isEpsOn(), nState = 0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  910):    returned true
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(42b34e48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4371 1000 null
D/PMS     (  910): releaseWL(42a1dbc8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/SmartSyncUtils( 4371): getMobilePolicyEnabled, result = true
W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  910): releaseWL(42b34e48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 4371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/SmartSyncUtils( 4371): isEpsOn(), nState = 0
,D/DotMatrix( 1591): [EventService] getTotalRam: 1873 Mb
,D/SmartSyncUtils( 4371): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4371): isEpsOn(), nState = 0
D/WifiService(  910): New client listening to asynchronous messages
D/PMS     (  910): acquireWL(429592d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(429592d8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42999ca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42999ca8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1784): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): onScreenOff
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1784): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1784): onScreenOff
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@429dc668
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 1
W/SensorService(  910): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@429dc668, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  910): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  910): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  910): pid=910, uid=1000
W/SensorService(  910): Active sensors: size = 0
W/SensorService(  910): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@429dc668, eanble = 0, strlen(mName) = 36
W/SensorService(  910): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  910): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  910): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@429dc668
D/AutoSetting( 1323): service - mHandler: cancel location update
,D/AutoSetting( 1323): service -           changes count: 0
E/ActivityThread(  910): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429dcbb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@429dcbb0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  910): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  910): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  910): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  910): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  910): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  910): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  910): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  910): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  910): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  910): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  910): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  910): 	at dalvik.system.NativeStart.main(Native Method)
,D/ContactMessageStore( 1253): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1253): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1535): service - handleMessage() stop self
,D/AutoSetting( 1535): service - onDestroy() END
,D/AutoSetting( 1535): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=3736
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3736:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3736
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=3941
,I/ActivityManager(  910): Killing 3941:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 3941
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42a04570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{429904c8: PendingIntentRecord{42985e90 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=124985, Int=0
,D/PMS     (  910): releaseWL(42a04570): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(4299cbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42b4b280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b4b280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(4299cbe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b1daa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42b1daa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42ad5a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42a05fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a42c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1233): Vacuum at: now=1454440705869 tag=VacuumService
,D/PMS     (  910): releaseWL(42ad5a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42a05fb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a51050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42a51050): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a4ee50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,D/PMS     (  910): releaseWL(42a42c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(42a4ee50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b47338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42b47338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b4ec18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  910): releaseWL(42b4ec18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  910): acquireWL(42b1fa38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): acquireWL(42abf598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42abf598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42adcb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42b1fa38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a992f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42a992f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{42af4970 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1233): Scheduling Phenotype for one-off execution 9021 seconds from now (1454440706638)
,D/GetConfigurationSnapshotOperation( 1233): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1233): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1233): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1233): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1233): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1233): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1233): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=100 [1][1][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1233): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/libc    ( 1233): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1233): [NET] getaddrinfo-,err=8
D/libc    ( 1233): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1233): [NET] getaddrinfo-, 1
,D/libc    ( 1233): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f7eb +++++
,D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1233): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1233): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1233): [NET] getaddrinfo-,err=8
D/libc    ( 1233): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1233): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  910): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1233/10029)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/PMS     (  910): releaseWL(42adcb88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b0ac38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42b0ac38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42b11410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  910): doString: SIGNAL_POLL
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42b11410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): acquireWL(42a747c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  910): releaseWL(42a747c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42a7a370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  910): sending alarm PendingIntent{428fb6c0: PendingIntentRecord{4299fb68 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140947, Int=0
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/PMS     (  910): releaseWL(42a7a370): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1323): service - handleMessage() stop self
,D/AutoSetting( 1323): service - onDestroy() END
,D/AutoSetting( 1323): service - handleMessage() quit looper
,D/Process (  910): killProcessQuiet, pid=3798
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3798:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3798
,D/PMS     (  910): acquireWL(42a80580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,D/GpsLocationProvider(  910): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
V/AlarmManager(  910): sending alarm PendingIntent{4281c658: PendingIntentRecord{4281d870 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141283, Int=0
D/PMS     (  910): acquireWL(42a817f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 910 1000 null
D/PMS     (  910): releaseWL(42a80580): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  910): [NET] getaddrinfo-,err=8
D/libc    (  910): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  910): [NET] getaddrinfo-, 1
,D/libc    (  910): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b749 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  910): [NET] getaddrinfo_proxy-, success
,I/global  (  910): call createSocket() return a new socket.
D/libc    (  910): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  910): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  910): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  910): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  910): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  910):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  910): releaseWL(42a817f0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  910): acquireWL(42ba2d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=159378, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42ba2d40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42ba52d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,I/BatteryService(  910): n_update end
I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): releaseWL(42ba52d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(42bab010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{10027}
,V/AlarmManager(  910): sending alarm PendingIntent{426326e0: PendingIntentRecord{4287af08 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176012, Int=0
,D/PMS     (  910): releaseWL(42bab010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  910): acquireWL(42baca78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42baca78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
D/PowerUI ( 1122): closing low battery warning: level=100
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1253): switchBindHtcMsgCursor: null
,D/PMS     (  910): acquireWL(42bb2220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bb2220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42bb3b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=219378, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42bb3b20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42bb5d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bb5d80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42bb7680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=279377, Int=0
,D/PMS     (  910): releaseWL(42bb7680): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42bb9900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bb9900): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42bbb200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=339377, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42bbb200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  910): killProcessQuiet, pid=4224
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 4224:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 4224
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42bc0690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bc0690): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42bc1f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=399378, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42bc1f90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42bc4210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bc4210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42bc60d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=459378, Int=0
,D/PMS     (  910): releaseWL(42bc60d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  910): acquireWL(42bc8380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/PMS     (  910): releaseWL(42bc8380): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,I/IntentController( 1122): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1591): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1591): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1122): closing low battery warning: level=100
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/PowerUI ( 1122): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1122): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  910): acquireWL(42bcdb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bcdb28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(42bcf428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=519377, Int=0
,D/PMS     (  910): releaseWL(42bcf428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  416): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  910): acquireWL(42bd16a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bd16a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42bd2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=579378, Int=0
,D/PMS     (  910): releaseWL(42bd2fa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bd5208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bd5208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1253): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1253): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1253): sku_id=99
D/ContactMessageStore( 1253): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1253): start background delete task...
D/ContactMessageStore( 1253): size: 0 , 0
,D/ContactMessageStore( 1253): Background delete complete
,D/PMS     (  910): acquireWL(42bd6b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=639378, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42bd6b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bda2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bda2a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42bdbba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=699378, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42bdbba8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42bdde08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42bdde08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42bdf708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=759378, Int=0
,D/PMS     (  910): releaseWL(42bdf708): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42be1f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42be1f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42be3830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=819378, Int=0
,D/PMS     (  910): releaseWL(42be3830): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42be5ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42be5ab0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42be7978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=879377, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42be7978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42be9bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42be9bd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42beb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=939377, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42beb4d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  910): Sampling interval elapsed, updating statistics ..
,D/PMS     (  910): acquireWL(42bedc90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42080c60: PendingIntentRecord{427b6090 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785085, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{42281580: PendingIntentRecord{429f2830 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=951187, Int=0
,D/PMS     (  910): acquireWL(42bf87d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  910): releaseWL(42bf87d8): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): Done.
,D/ConnectivityService(  910): Setting timer for 720seconds
,I/ActivityManager(  910): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4426 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  910): sending alarm PendingIntent{428f8970: PendingIntentRecord{42a2fad0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454440791207, Int=10800000
,V/AlarmManager(  910): sending alarm PendingIntent{42a37a08: PendingIntentRecord{42971870 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454441511560, Int=900000
,W/ContextImpl( 4371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4371): call getInstance()
,D/PMS     (  910): releaseWL(42bedc90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageList:PowerUsageHelper( 4371): MY_DEBUG = false
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.aurora (4426/10049)
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,D/Process (  910): killProcessQuiet, pid=3489
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3489:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 3489
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42aa5020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1373 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
,D/ConnectivityService(  910): reportInetCondition for net 1, percentage: 100 by  (1373/10029)
D/ConnectivityService(  910): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  910): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  910): getActiveNetworkInfo called by  (1373/10029)
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023656
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023855
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023957
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023960
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023963
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360023966
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025479
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025497
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360028193
,D/PMS     (  910): releaseWL(42aa5020): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  910): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  910): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  910): acquireWL(42afa9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42afa9e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42af33e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=999378, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42af33e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42afda28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42863598: PendingIntentRecord{42aaa238 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454441591537, Int=0
,D/SmartSyncUtils( 4371): isEpsOn(), nState = 0
D/PMS     (  910): acquireWL(42afecf0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4371 1000 null
D/PMS     (  910): releaseWL(42afda28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 4371): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4371): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4371): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4371): SettingOnTime = 1454479200000, randomSettingOnTime = 1454476397000
,D/SmartSyncScreenOnOffTimeReceiver( 4371): SettingOffTime = 1454464800000, randomSettingOffTime = 1454467520000
,D/SmartSyncScreenOnOffTimeReceiver( 4371): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4371): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4371): bNightModeTurnOffOnce = false
D/PMS     (  910): releaseWL(42afecf0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  910): acquireWL(42a64580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42a64580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42a65d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1059378, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a65d30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ab4658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ab4658): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42ab5e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1119377, Int=0
,I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42ab5e08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42ab0f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42ab0f78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  910): acquireWL(42b1a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1179378, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42b1a168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42b04cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42b04cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  349): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  910): acquireWL(42a96338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{42453628: PendingIntentRecord{42376bd8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1239378, Int=0
I/IntentController( 1122): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  910): releaseWL(42a96338): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  910): acquireWL(42add630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(42add630): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4443): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4443): ====startRecUseTime====
D/htc.customization.log.level( 4443):  is 
W/CustomizationLogLevel( 4443): Level value is invalid, use default level 2
D/CustomizationManager( 4443):  Read ACC file spent 0.104 (s)
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4443): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4443): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4443): Parsing tag category name = system
I/CustomizationCIDLoader( 4443): Parsing tag category name = application
I/CustomizationCIDLoader( 4443): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4443): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4443): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4443): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4443): Parsing tag category name = Settings
D/CustomizationManager( 4443):  Read CID file spent 0.153 (s)
D/CustomizationManager( 4443):  All configurations done spent 0.154 (s)
W/HtcNativeFlag( 4443): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4443): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4443): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  910): deletePackageAsUser: pkg=com.test.thalitest, pid=4443, uid=2000 user=0
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  910): Skipping PackageSetting{42549270 com.example.hello/10397} due to missing metadata
W/PackageSettings(  910): Skipping PackageSetting{4254d548 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  910): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1279): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1279): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1122): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1591): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1591): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1591): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1233): Ignoring removeGeofence because network location is disabled.
D/PMS     (  910): acquireWL(42c8d940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1233 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1345): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  910): releaseWL(42c8d940): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  910): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  910): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
W/AccTypeManager( 1345): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1345): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
D/VoicemailCleanupService( 1302): Cleaning up data for package: com.test.thalitest
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
W/SystemReader( 1264): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/Prism.PackageStateRece_( 1279): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1323): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1323): handle notify Blinkfeed plugin client changed
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "sms"
E/ExternalAccountType( 1345): Unsupported attribute readOnly
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/IcingCorporaProvider( 2860): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1253 :
I/ActivityManager(  910): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4457 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PhoneApp( 1253): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2860): UpdateCorporaTask done [took 182 ms] updated apps [took 182 ms] 
W/PackageManager(  910): Unable to load service info ResolveInfo{42961ad8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4457): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4457): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4457): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4457): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4457): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4457): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4457): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4457): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4457): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4457): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4457): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4457): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4457): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4457): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4457): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4457): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4457): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4457): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4457): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4457): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4457): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4457): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4457): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4457): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4457): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4457): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4457): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4457): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4457): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4457): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4457): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4457): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4457): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4457): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4457): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4457): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4457): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4457): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4457): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4457): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4457): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4457): threadid=11: thread exiting with uncaught exception (group=0x419f0e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4457): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4457): Process: com.google.android.apps.docs, PID: 4457
E/AndroidRuntime( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4457): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4457): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4457): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4457): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4457): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4457): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4457): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4457): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4457): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4457): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4457): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4457): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4457): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4457): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4457): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4457): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4457): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4457): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4457): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4457): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4457): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4457): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4457): Opened ClientFlag.db in read-only mode
I/ActivityManager(  910): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4476 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
W/GAV2    ( 4457): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/Process ( 4457): killProcess, pid=4457
E/SQLiteDatabase( 4457): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4457): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4457): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4457): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4457): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4457): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4457): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/SQLiteDatabase( 4457): 	at aid.a(DatabaseModelLoader.java:340)
E/SQLiteDatabase( 4457): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/SQLiteDatabase( 4457): 	at fv.run(DocsApplication.java:288)
D/Process ( 4457): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AbstractDatabaseInstance( 4457): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4457): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AbstractDatabaseInstance( 4457): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AbstractDatabaseInstance( 4457): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AbstractDatabaseInstance( 4457): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AbstractDatabaseInstance( 4457): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AbstractDatabaseInstance( 4457): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AbstractDatabaseInstance( 4457): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AbstractDatabaseInstance( 4457): 	at azJ.a(Suppliers.java:125)
E/AbstractDatabaseInstance( 4457): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AbstractDatabaseInstance( 4457): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4457): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4457): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4457): 	at fv.run(DocsApplication.java:288)
W/dalvikvm( 4457): threadid=12: thread exiting with uncaught exception (group=0x419f0e30)
W/BroadcastQueue(  910): Skipping deliver [background] BroadcastRecord{429d2160 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{429904f0 4457 com.google.android.apps.docs/10100/u0 remote:42358e18}: process crashing
D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  910): start
I/ActivityManager(  910): Recipient 4457
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.google.android.apps.docs (pid 4457) has died.
W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/ActivityManager(  910): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4476): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4494 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4476): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4476): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4476): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4476): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4476): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4476): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4476): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4476): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4476): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4476): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4476): threadid=10: thread exiting with uncaught exception (group=0x419f0e30)
E/AndroidRuntime( 4476): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4476): Process: com.android.keychain, PID: 4476
E/AndroidRuntime( 4476): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4476): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4476): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4476): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4476): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4476): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4476): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4476): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4476): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4476): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  910): App crashed! Process: com.android.keychain
D/ErrorReport(  910): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4476): killProcess, pid=4476
D/Process ( 4476): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  910): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  910): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454441856419.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  910): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  910): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  910): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  910): 	... 4 more
I/ActivityManager(  910): Recipient 4476
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Process com.android.keychain (pid 4476) has died.
W/ActivityManager(  910): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10889ms
D/AppTag  ( 4494): getInstance(Context context)
D/AppTag  ( 4494): getInstance(Context context)
D/AppTag  ( 4494): onCreate()
D/PMS     (  910): acquireWL(42a5e778): PARTIAL_WAKE_LOCK  AsyncService 0x1 3668 10160 null
D/PMS     (  910): releaseWL(42a5e778): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4101): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  910): killProcessQuiet, pid=4174
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 4174:com.google.android.talk/u0a111 (adj 15): empty #17
D/PackageBroadcastService( 2197): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2197): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2197): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2197): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2197): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2197): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/Prism.ItemManager( 1279): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1279): loadItems() com.htc.launcher.pageview.WidgetManager@41eb5c70 +
I/Prism.WidgetManager( 1279): onLoadItems() +
E/SQLiteDatabase( 2197): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2197): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2197): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 4174
W/dalvikvm( 2197): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2197): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2197): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2197): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2197): App measurement is starting up, version: 8489
I/GMPM-SVC( 2197): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2197): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2197): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x659330a8
I/ActivityManager(  910): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/DriveAsyncService( 2197): disk I/O error (code 3850)
E/DriveAsyncService( 2197): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2197): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2197): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2197): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2197): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2197): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2197): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteDatabase( 2197): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/SQLiteLog( 2197): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 2197): Opening the database failed, dropping and recreating it
E/SQLiteDBG( 2197): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6625bcf0
W/dalvikvm( 2197): threadid=49: thread exiting with uncaught exception (group=0x419f0e30)
E/ActivityManager(  910): App crashed! Process: com.google.android.gms
E/SQLiteDatabase( 2197): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2197): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2197): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2197): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2197): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2197): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2197): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2197): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/AndroidRuntime( 2197): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2197): Process: com.google.android.gms, PID: 2197
E/AndroidRuntime( 2197): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2197): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2197): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2197): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2197): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2197): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2197): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  910): acquireWL(42af1fd8): PARTIAL_WAKE_LOCK  Icing 0x1 2197 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 2197): doRemovePackageData com.test.thalitest
E/GMPM-SVC( 2197): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
D/Process ( 2197): killProcess, pid=2197
W/GMPM-SVC( 2197): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
D/Process ( 2197): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  910): Can't write: system_app_crash
E/DropBoxManagerService(  910): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  910): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  910): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  910): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  910): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  910): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  910): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  910): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  910): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  910): 	... 5 more

```
