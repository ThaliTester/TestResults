#### Test 58380500306a2c5_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bedde8 +
I/Prism.WidgetManager( 1272): onLoadItems() +
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/Process (  906): killProcessQuiet, pid=3609
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  906): killProcessQuiet, pid=3395
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  906): Killing 3609:com.google.android.apps.plus/u0a160 (adj 15): empty #17
I/ActivityManager(  906): Killing 3395:com.htc.mms.backupagent/u0a78 (adj 15): empty #18
W/PackageManager(  906): Unable to load service info ResolveInfo{42735328 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  906): Recipient 3395
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3609
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/Prism.WidgetManager( 1272): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1272): onLoadItems() -
I/Prism.ItemManager( 1272): loadItems() com.htc.launcher.pageview.WidgetManager@41bedde8 -
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1244): -- N1 =0
D/PhoneApp( 1244): -- N2 =0
D/PhoneApp( 1244): -- N3 =0
E/cutils-trace( 4013): Error opening trace file: No such file or directory (2)
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
D/WIFI_ICON( 1113): WifiActivity: 1
D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  906): notification sound not played, stream=5 volume=0 always=false
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=30 rxSum=28} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19474 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19475 delay=15s
I/RemoteViews( 1113): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41cabd00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1113): com.htc.updater 2 8 0 10
D/CustomizationManager( 4013): ====startRecUseTime====
D/htc.customization.log.level( 4013):  is 
W/CustomizationLogLevel( 4013): Level value is invalid, use default level 2
I/RemoteViews( 1113): com.htc.updater (true,33751552)
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41e1aa20 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4026 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/RemoteViews.Performance( 1113): com.htc.updater 1 7 0 10
I/GCoreNlp( 1226): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  906): acquireWL(427fdf68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427fdf68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  906): applying state to connected service
D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(428091c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42809ea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(428091c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42809ea0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4013):  Read ACC file spent 0.070 (s)
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4013): Parsing tag item name = HTC__031
I/Gmail   ( 3982): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/CustomizationCIDLoader( 4013): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4013): Parsing tag category name = system
I/CustomizationCIDLoader( 4013): Parsing tag category name = application
I/CustomizationCIDLoader( 4013): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4013): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4013): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4013): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4013): Parsing tag category name = Settings
D/CustomizationManager( 4013):  Read CID file spent 0.122 (s)
D/CustomizationManager( 4013):  All configurations done spent 0.122 (s)
I/Gmail   ( 3982): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/HtcNativeFlag( 4013): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4013): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4013): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4013): Fail to get flag for type 'language', use default value: -1
I/Gmail   ( 3982): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3982): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Babel   ( 4026): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4026): MmsConfig.loadMmsSettings
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4013
W/dalvikvm( 4026): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4026): VFY: unable to resolve instance field 36
W/dalvikvm( 4026): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
V/JNIHelp ( 4026): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/MmsCustomizationProvider( 2723): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2723): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4026): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4026): MmsConfig.loadFromDatabase
E/Babel   ( 4026): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4026): MmsConfig.loadFromResources
E/Babel   ( 4026): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4026): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4026, uid=10111, userID:0
W/Settings( 4026): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4026, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4026, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4026, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4026, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4026, uid=10111, userID:0
D/PMS     (  906): acquireWL(42818310): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4026 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
I/ProviderInstaller( 4026): Installed default security provider GmsCore_OpenSSL
D/PMS     (  906): releaseWL(42818310): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(4281cbd0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4026 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
D/PMS     (  906): releaseWL(4281cbd0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3762
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3762:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 2841): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3762
D/WifiService(  906): Client connection lost with reason: 4
,D/PMS     (  906): acquireWL(42825be0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42825be0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4280dfe8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4280dfe8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427f81f8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427f81f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427f3080): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427f3080): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427ef328): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/SocialFeedProvider( 1272): +disConnect socialManager
,I/SocialFeedProvider( 1272): disconnect socialManager
,I/SocialFeedProvider( 1272): -disConnect socialManager
D/PMS     (  906): releaseWL(427ef328): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427a1308): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427a1308): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4279ca98): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4279ca98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42791068): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42791068): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2841): UpdateCorporaTask done [took 409 ms] updated apps [took 409 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4075 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(426ee788): PARTIAL_WAKE_LOCK  AsyncService 0x1 4075 10160 null
,D/PMS     (  906): releaseWL(426ee788): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(426ed990): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4075 10160 null
,I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  906): acquireWL(426e67b8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4075 10160 null
,D/PMS     (  906): releaseWL(426ed990): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4075/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4075/10160)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(426e67b8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4102 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Settings:HtcWirelessFeatureFlags( 3783): id/is att sku: 99/false
,W/SystemReader( 3783): Cannot find devicepolicy_lower_fp_quality, use default value instead
W/SystemReader( 3783): Cannot find support_harman, use default value instead
W/SystemReader( 3783): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3783): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3783): The wrap header doesn't exist in header list.
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/Settings:HtcWrapHeaderInfo( 3783): updateDevelopment, bPrefShow = true
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4102, uid=10074, userID:0
,E/Settings:HtcUmcWidgetEnabler( 3783): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]support         :false
,W/FingerprintManager( 3783): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,D/Finsky  ( 4102): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4102/10074)
,E/Settings:HtcVoWifiWidgetEnabler( 3783): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3783): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4102/10074)
,D/Finsky  ( 4102): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4102): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4102): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3783): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3783): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3783): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3783): [supportHomeButton]support         :false
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4102, uid=10074, userID:0
,W/FingerprintManager( 3783): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3783): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3783): Failed to find provider info for com.htc.vowifi
,D/Ads     ( 4102): Skipping gmscore version check
,D/Finsky  ( 4102): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4102): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4102): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4102): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4102): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3009
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3009:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3009
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42668ea0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4026 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): acquireWL(42668748): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42668ea0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/Process (  906): killProcessQuiet, pid=3799
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3799:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  906): releaseWL(42668748): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3799
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(424a7598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/PMS     (  906): acquireWL(4241f528): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(424a7598): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2187): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2187): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2187): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2187): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2187): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2187): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2187): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2187): cleanUpNonGplusAccounts done.
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(424f0460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(424f0460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4149 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  906): sending alarm PendingIntent{4269d768: PendingIntentRecord{42450620 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455058162497, Int=0
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
D/PMS     (  906): acquireWL(425ebf90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/PMS     (  906): releaseWL(425ebf90): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
D/PMS     (  906): acquireWL(426b6e18): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/ImageRamCache( 4149): create image Cache, size: 31457280.
I/ImageRamCache( 4149): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4149): create image Cache, size: 12582912.
,I/FeedSettings( 4149): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4149): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4149): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4149): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4149): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4149): loadGridSize() with Alternative
,W/SQLiteConnectionPool( 2187): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SocialManager[SocialBiLogHelper]( 4149): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4149): last commit ulog time 1455021437164
,I/SocialManager[SocialBiLogHelper]( 4149): skip commit this time
,D/Process (  906): killProcessQuiet, pid=3422
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3422:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/PMS     (  906): releaseWL(426b6e18): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3422
,I/SensorManager(  906): mEventCount = 450
,D/PMS     (  906): acquireWL(425c9038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(425c9038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42693e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
D/PMS     (  906): releaseWL(42693e50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(426cbdf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426cbdf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(426ab140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426ab140): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426410c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4169 uid=10041 gids={50041}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426410c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4278d3c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3456 10071 null
,D/PMS     (  906): acquireWL(426d5618): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3456 10071 null
,D/Process (  906): killProcessQuiet, pid=3911
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3911:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
E/TodoTaskNotifyService( 3456): java.lang.NullPointerException
,W/System.err( 3456): java.lang.NullPointerException
W/System.err( 3456): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3456): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3456): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3456): stopSelfResult true
D/PMS     (  906): releaseWL(4278d3c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  906): releaseWL(426d5618): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3911
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,D/LocationInitializer( 2187): Restart initialization of location
,E/MDM     ( 1226): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1355): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1355): Proximity feature is not enabled.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1226): No location to return for getLastLocation()
,W/FusedLocationProvider( 1226): location=null
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
D/PMS     (  906): acquireWL(427518f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427518f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/PMS     (  906): acquireWL(4278eb00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3456 10071 null
,D/PMS     (  906): acquireWL(427a27d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3456 10071 null
,D/PMS     (  906): acquireWL(426e9918): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3456 10071 null
,I/ActivityManager(  906): Delay finish: com.htc.task/.notification.NotifyReceiver
,D/PMS     (  906): releaseWL(4278eb00): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): acquireWL(427a27d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3456 10071 null
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,E/TodoTaskNotifyService( 3456): java.lang.NullPointerException
,W/System.err( 3456): java.lang.NullPointerException
W/System.err( 3456): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3456): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3456): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3456): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3456): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3456): stopSelfResult true
D/PMS     (  906): releaseWL(426e9918): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(427a27d0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/WSP     ( 1318): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1318): Weather sync is On
D/PMS     (  906): releaseWL(4270c110): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/WSP     ( 1318): [Receiver] next auto-sync alarm event is 60 mins later, at time: Wed Feb 10 00:49:23 CET 2016
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.gcm.gmsproc.GmsAutoStarter
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1318/10055)
,D/PMS     (  906): acquireWL(4258e5b8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1318 10055 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(4278a8f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41d421d8: PendingIntentRecord{425551e8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58270, Int=0
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
V/AlarmManager(  906): sending alarm PendingIntent{42665930: PendingIntentRecord{4268f9c0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455058163423, Int=0
D/PMS     (  906): releaseWL(4241f528): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1355): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3456): update TASK shortcut>
,I/GAV2    ( 3982): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 2187): Google Analytics 8.4.89 is starting up.
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 6 times.
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/AlarmManager(  906): sending alarm PendingIntent{42593ab0: PendingIntentRecord{4257d818 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455058165238, Int=0
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97,
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:53, mTXpacketCount:33, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
,I/GAV4    ( 4026): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  906): acquireWL(42756190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42756190): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1113): closing low battery warning: level=100
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/Process (  906): killProcessQuiet, pid=3944
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3944:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3944
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/CheckinService( 2187): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/CalendarProvider2( 1520): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1520): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(426d81b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4026 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  906): releaseWL(426d81b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2841): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(426bf298): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426bf298): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426b7030): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426b7030): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426ade78): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426ade78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426a3010): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426a3010): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4269e290): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4269e290): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426912b0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 7 times.
,D/PMS     (  906): releaseWL(426912b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42682958): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42682958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426724f0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426724f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42670420): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42670420): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4266ecc8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4266ecc8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2841): UpdateCorporaTask done [took 292 ms] updated apps [took 292 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42669e08): PARTIAL_WAKE_LOCK  AsyncService 0x1 4075 10160 null
D/PMS     (  906): releaseWL(42669e08): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2187): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PMS     (  906): acquireWL(42668748): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 2187): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2187): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42668748): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(41b73350): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3838 10154 null
,I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3838): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3838, uid=10154, userID:0
,W/ContextImpl( 3838): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 3838): Conditions not met for autocaching.
,I/MusicLeanback( 3838): Stop autocaching.
D/PMS     (  906): releaseWL(41b73350): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3816): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42740fe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42740fe0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42793c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(42793c40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(4273c8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(427787b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4227 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42761fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(427787b0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42761fb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(4273c8d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/SyncApplication( 4227): Loading default preferences
,W/Resources( 4227): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 4227): Overriding preferences with custom values
,D/SyncApplication( 4227): Updating preferences succeeded
,E/SyncApplication( 4227): Application created.
D/VolumeInfo( 4227): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4227): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4227): Found 0 mount point(s)
,V/VolumeInfo( 4227): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4227): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4227): getNewCalendarAuthority()...
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4227, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4227, uid=10008, userID:0
,D/SyncApplication( 4227): enableAppOperation()+
D/VolumeInfo( 4227): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4227): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4227): enableAppOperation()-
,D/HTCUtilities( 4227): isNeorSinged() + 
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4227): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4227): isNeorSinged() return false
,D/CDMountReceiver( 4227): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4227): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4227): enable CD Auto-mount: true
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4227): enable auto-mount
,D/HTCUtilities( 4227): enable auto-mount
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f1b0e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  906): Resuming delayed broadcast
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
,D/PMS     (  906): releaseWL(4278a8f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 1 12 3 11
,I/RemoteViews( 1113): com.nero.android.htc.sync (false,0)
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4248 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41d0c850 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.nero.android.htc.sync 1 10 3 16
,D/CalendarApplication( 4248): onCreate
D/ProviderChangeReceiver( 4248): ---------------------------------------------------
,D/ProviderChangeReceiver( 4248): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4248): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4262 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3859
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3859:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3859
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4248): No fired or scheduled alerts
,D/HtcAlertUtils( 4248): -- cancelReminderNotification --
,D/HtcAlertUtils( 4248): broadcastExistReminder!
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4262): [4262/4262] onCreate(),
W/ContextImpl( 4262): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3891
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  906): Killing 3891:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3891
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{426c2720 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): releaseWL(4258e5b8): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 8 times.
,D/Process (  906): killProcessQuiet, pid=3969
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3969:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3969
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=30 rxSum=28} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19475 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19476 delay=15s
D/PMS     (  906): acquireWL(42641398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{423aed48: PendingIntentRecord{42443a98 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70982, Int=0
D/PMS     (  906): releaseWL(42641398): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42789d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42789d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1113): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  906): mEventCount = 600
,D/Finsky  ( 4102): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  906): acquireWL(4278e9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{4250d220: PendingIntentRecord{4270e010 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455058177625, Int=0
,D/PMS     (  906): releaseWL(4278e9f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
W/dalvikvm( 4102): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4102/10074)
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4102): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4102): [NET] getaddrinfo-,err=8
D/libc    ( 4102): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4102): [NET] getaddrinfo-, 1
D/libc    ( 4102): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =89a7 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4102): [NET] getaddrinfo_proxy-, success
I/global  ( 4102): call createSocket() return a new socket.
D/libc    ( 4102): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4102): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4102): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4102): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1113): WifiActivity: 3
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4102): untagSocket(69) failed with errno -22
,D/Finsky  ( 4102): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=13 [15][2][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/NetworkManagementSocketTagger( 4102): untagSocket(69) failed with errno -22
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 9 times.
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4102): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4102/10074)
,D/Finsky  ( 4102): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(4255a590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42427148: PendingIntentRecord{425a2d40 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455058179652, Int=0
,D/WearableService( 1226): callingUid 10029, callindPid: 1226
,D/Finsky  ( 4102): [441] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/PMS     (  906): acquireWL(41b7a090): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4102 10074 null
,D/PMS     (  906): releaseWL(4255a590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/DeviceConnectionService( 1226): client connected with version: 8296000
,D/Finsky  ( 4102): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4102): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4102): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4102): [NET] getaddrinfo-,err=8
D/libc    ( 4102): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4102): [NET] getaddrinfo-, 1
,D/libc    ( 4102): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a81a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4102): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  906): releaseWL(41b7a090): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=10 [58][6][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:134, mTXpacketCount:53, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1318): service - has update message, not stop
,D/AutoSetting( 1318): service - mHandler: update timezone
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1520): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1520): service - onCreate()
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1520): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1520): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1520): service - mHandler: update timezone
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1520): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1520): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1520): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1557): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1113): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1113): release indeterminate drawable android.widget.OnDemandProgressBar{41f782b8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1113): com.htc.htclocationservice 2 6 3 11
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 10 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/PMS     (  906): acquireWL(42580f70): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42580f70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(424305f0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(424305f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426d0250): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426d0250): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42766c80): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42766c80): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 11 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/SensorManager(  906): mEventCount = 750
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42634480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=93} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19476 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19477 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{424f7ec0: PendingIntentRecord{42443a98 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=85987, Int=0
D/PMS     (  906): releaseWL(42634480): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times.
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:135, mTXpacketCount:134, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  906): acquireWL(4280bad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4280bad0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
,D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{42736a20 u0 com.htc.htclocationservice/.AutoSettingService}
,I/HtcModeClient( 1520): handler message = 4011
,E/HtcModeClient( 1520): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1520): Don't start project servcice
,D/HtcModeClient( 1520): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1520): connectState: CONNECTION_READY = false
,D/SilentMusic( 1520): call stop
D/HtcModeClient( 1520): close connection
,W/HtcModeClient( 1520): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1520): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(426e3ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{42759e88: PendingIntentRecord{42766dd8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455058193988, Int=0
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4298 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{4245e140: PendingIntentRecord{423226d0 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455058199397, Int=60000
,D/PMS     (  906): releaseWL(426e3ad8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4298): SMSBackupAgentService started
,D/SMSBackup( 4298): Checking restore status
D/SMSBackup( 4298): Restore complete
,D/SMSBackup( 4298): cancelCheckAlarm
,D/SMSBackup( 4298): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/Finsky  ( 4102): [431] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4102): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=3621
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3621:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3621
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(426a0340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=95018, Int=0
,D/PMS     (  906): releaseWL(426a0340): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1113): now=1455058200054 next=59946
,V/LightsService(  906): setLight #0: color=#24
,V/LightsService(  906): setLight #0: color=#21
,V/LightsService(  906): setLight #0: color=#1a
,V/LightsService(  906): setLight #0: color=#14
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=102 rxSum=93} preTxRxSum={txSum=102 rxSum=93}
D/WifiDataStallTracker(  906): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=19477 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19478 delay=15s
D/PMS     (  906): acquireWL(42741568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42750be0: PendingIntentRecord{42443a98 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100992, Int=0
D/PMS     (  906): releaseWL(42741568): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1113): WifiActivity: 1
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1113): WifiActivity: 0
,D/StatusBar.NetworkController( 1113): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42253990
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42253990, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d3c110
W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@42777c38
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 318ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426baa88)
D/NfcService( 1257): ScreenObserver: OFF
D/NfcService( 1257): applyRouting - 0
D/PMN     (  906): wakingUp
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
,D/NfcService( 1257): applyRouting -2
I/InputMethodManagerService(  906): Disable input method client, pid=1272
I/WindowManager(  906): No lock screen! windowToken=null
D/PMS     (  906): acquireWL(427072e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
D/PMS     (  906): acquireWL(42708050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
D/PMS     (  906): releaseWL(427072e0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  906): onScreenOn
D/PMS     (  906): releaseWL(42708050): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1113): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/MtpService( 2385): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2385): [MTP][onReceive]-
,D/NfcService( 1257): applyRouting - 0
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/AutoSetting( 1318): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1257): applyRouting -2
,D/AutoSetting( 1318): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/PMS     (  906): acquireWL(42802fe8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1257 1027 null
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/PMS     (  906): releaseWL(42802fe8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/TetherSettings( 3783): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3783): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3783): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3783): Cust_ConnectToPC   : spcsc>false
D/        ( 3783): Cust_ConnectToPC   : IPT>true
D/        ( 3783): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3783): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3783): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3783): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3783): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=19479 delay=15s
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:On
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1166): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,I/PSReceiver( 3783): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3783): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3783): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3783):  defaultType:0
W/ContextImpl( 3783): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/ClockThread( 1113): stop update clock
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1166): WiFioffload: SignalStrength: =97
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  906):    returned true
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  906): updateScreenOn: false
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4319 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  906): acquireWL(427ea0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427ea0b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427eb638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427eb638): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOn: 1455058208056
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOn: 1455058208056
,D/SmartSyncUtils( 4319): isEpsOn(), nState = 0
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d3c110
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41d3c110, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@42777c38
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  906): acquireWL(427b7ac8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4319 1000 null
D/PMN     (  906): goingToSleep
I/FeedHostManager( 1272): [onPause]
,I/FeedProviderManager( 1272): onPause
I/SocialFeedProvider( 1272): +onPause
,I/SocialFeedProvider( 1272): -onPause
,I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c69a58
D/PMS     (  906): acquireWL(427ba2b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19479 mDataStallAlarmIntent=PendingIntent{42475ed8: PendingIntentRecord{42443a98 android broadcastIntent}}
,D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1166): SET_SCREEN_ON:Off
I/wpa_supplicant( 1166): htc_wext_set_keepalive +
I/wpa_supplicant( 1166): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1166): getPrivFuncNum +	
I/wpa_supplicant( 1166): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1166): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1166): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1166): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1166): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  906):    returned true
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/PMS     (  906): releaseWL(427b7ac8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
D/PMS     (  906): acquireWL(427c1a68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  906): releaseWL(427ba2b0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 4319): getMobilePolicyEnabled, result = true
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
D/NetworkPolicy(  906): updateScreenOn: false
,D/Process (  906): killProcessQuiet, pid=2723
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2723:com.htc.sense.mms/u0a65 (adj 15): empty #17
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/wpa_supplicant( 1166): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(427c1a68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/SmartSyncUtils( 4319): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4319): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4319): isEpsOn(), nState = 0
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42777c38
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42777c38, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42777c38, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42777c38
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiService(  906): New client listening to asynchronous messages
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426504e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426504e8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/AutoSetting( 1318): service - mHandler: cancel location update
D/AutoSetting( 1318): service -           changes count: 0
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): acquireWL(4285fa68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4285fa68): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42860ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42860ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOff
,I/ActivityManager(  906): Recipient 2723
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1520): service - handleMessage() stop self
,D/AutoSetting( 1520): service - onDestroy() END
,D/AutoSetting( 1520): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=4149
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4149:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4149
,D/Process (  906): killProcessQuiet, pid=3873
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3873:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3873
,D/PMS     (  906): acquireWL(4286a910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42777018: PendingIntentRecord{427596e0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=117801, Int=0
,D/PMS     (  906): releaseWL(4286a910): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4286c6a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42872990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42872990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4286c6a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428784f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(428784f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4287c488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42885288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4288d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1226): Vacuum at: now=1455058223058 tag=VacuumService
D/PMS     (  906): releaseWL(4287c488): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42885288): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42897c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(4288d428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42897c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4289c338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(4289c338): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(428a3118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(428a3118): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428a70b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(428a70b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(428ad9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(428b6cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428b6cb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428be648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428ad9a0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428c36c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(428c36c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [1][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1226): Scheduling Phenotype for one-off execution 8389 seconds from now (1455058223602)
,D/GetConfigurationSnapshotOperation( 1226): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1226): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1226): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1226): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
W/dalvikvm( 1226): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1226): [NET] getaddrinfo-, 1
,D/libc    ( 1226): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =85d1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1226): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
D/libc    ( 1226): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1226): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [10][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1226/10029)
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(428be648): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428e7060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(428e7060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428ed9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1166): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1166): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1166): nl80211: survey data missing!
E/wpa_supplicant( 1166): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1166): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(428ed9c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  906): acquireWL(428f5ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(428f5ee8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(428fb280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{423d78f8: PendingIntentRecord{42797ab8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133228, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
,D/PMS     (  906): releaseWL(428fb280): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1318): service - handleMessage() stop self
,D/AutoSetting( 1318): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=4169
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 4169:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/AutoSetting( 1318): service - handleMessage() quit looper
,I/ActivityManager(  906): Recipient 4169
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42901980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4207f9b0: PendingIntentRecord{4249d2a0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141067, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(42902c88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(42901980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1e81 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.,
D/libc    (  906): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(42902c88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(42933750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=155019, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42933750): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42935af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42935af0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42937578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{423c6fb8: PendingIntentRecord{42087b80 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169115, Int=0
,D/PMS     (  906): releaseWL(42937578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42939730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42939730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4293f320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=215018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4293f320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42941580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42941580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  906): acquireWL(42942e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=275019, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42942e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42945100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42945100): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4294a8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4294a8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4294c1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=335018, Int=0
,D/PMS     (  906): releaseWL(4294c1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4294e9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4294e9d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42950898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=395018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42950898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(42952b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42952b18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42954418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=455018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42954418): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(42956678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42956678): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42957f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=515018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42957f78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4295a1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4295a1f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4295baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=575019, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4295baf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4295dd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4295dd58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  906): acquireWL(4295f658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=635018, Int=0
,D/PMS     (  906): releaseWL(4295f658): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429630d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429630d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428cf210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=695018, Int=0
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4367 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425f18a0: PendingIntentRecord{4264cff8 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455058315344, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{41ed2c08: PendingIntentRecord{426f8298 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.reminders.REFRESH_NOTIFICATION, t=0, cnt=1, w=1455058800000, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{420619d0: PendingIntentRecord{426ec1a8 com.htc.launcher broadcastIntent}}, i=com.htc.laucher.NIGHT_MODE_BEGIN, t=0, cnt=1, w=1455058800000, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4242afb0: PendingIntentRecord{424a22b0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_UPDATE_GOLDEN_TABLE, t=0, cnt=1, w=1455058800000, Int=86400000
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
D/PMS     (  906): acquireWL(42814af8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2187 10029 null
,D/PMS     (  906): acquireWL(42810460): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/FeedHostManager( 1272): onReceive() -- Intent { act=com.htc.laucher.NIGHT_MODE_BEGIN flg=0x14 (has extras) }
D/PMS     (  906): acquireWL(4280dfe8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 1272 10076 null
D/PMS     (  906): releaseWL(4280dfe8): PARTIAL_WAKE_LOCK  NightModeSyncReceiver_20 0x1 null
D/PMS     (  906): releaseWL(42814af8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  906): releaseWL(42810460): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(428cf210): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  906): acquireWL(427f75a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4319 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4367/10049)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/Process (  906): killProcessQuiet, pid=3456
,I/ActivityManager(  906): Killing 3456:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Recipient 3456
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(427a5678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10071}
,V/AlarmManager(  906): sending alarm PendingIntent{425e65c0: PendingIntentRecord{4263e780 com.htc.task broadcastIntent}}, i=com.htc.task.date.change, t=1, cnt=1, w=1455058800529, Int=0
,I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.TodoReceiver: pid=4383 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  906): releaseWL(427a5678): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10071}
D/TodoTaskshortcut( 4383): update TASK shortcut>
,D/Process (  906): killProcessQuiet, pid=4026
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4026:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4026
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1244): notify MmsSms
D/AccFlag ( 1244): sense_version=6.0
,D/AccFlag ( 1244): sku_id=99
,D/PMS     (  906): acquireWL(427bb7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029}
,V/AlarmManager(  906): sending alarm PendingIntent{426fd180: PendingIntentRecord{425fab78 com.google.android.gms startService}}, i=com.google.android.gms.icing.proxy.action.SMS_CHANGED, t=2, cnt=1, w=5000, Int=0
,D/PMS     (  906): releaseWL(427bb7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 32
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 72
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 71
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 63
,D/AccFlag ( 1244): sku_id=99
,D/TelephUtils( 1244): QUERY for  <hidden uri>  [ com.android.phone ] tid: 38
,D/PMS     (  906): acquireWL(427dc828): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427dc828): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428fadb0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=4398 uid=10041 gids={50041}
,D/SMSBackup( 4298): Got a database change event
,I/Icing   ( 2187): Indexing 9EC334276810E6DA9F550691EDBF16BE1CDE9A62 from com.google.android.gms
,I/Icing   ( 2187): Indexing done 9EC334276810E6DA9F550691EDBF16BE1CDE9A62
,D/Process (  906): killProcessQuiet, pid=4075
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(428fadb0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Killing 4075:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4075
,D/PMS     (  906): releaseWL(427f75a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(429d6960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429d6960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429d8260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=755018, Int=0
,D/PMS     (  906): releaseWL(429d8260): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429da9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41df2cd0: PendingIntentRecord{4243c580 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=778020, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{42110878: PendingIntentRecord{4271dc40 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1455058800724, Int=1800000
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,D/PMS     (  906): acquireWL(429ea7a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429da9c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  906): acquireWL(429ecdb0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(429ea7a8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2187): Aggregate from 1455058153755 (log), 1455057000664 (data)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(429ecdb0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429f7510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429f7510): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429f8e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=815018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429f8e10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429fb090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429fb090): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429fc990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=875018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429fc990): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429febf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429febf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42a004f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=935018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42a004f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42a02be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{42163798: PendingIntentRecord{42791ab0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=943652, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{4243ed20: PendingIntentRecord{426d1390 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455059035672, Int=900000
,D/PMS     (  906): acquireWL(42a04c48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42a04c48): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4319): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4319): MY_DEBUG = false
D/PMS     (  906): releaseWL(42a02be0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(429fdb10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1355 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1355/10029)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1355/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023526
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023646
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023703
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023707
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023713
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023718
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025044
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025056
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360027738
,D/PMS     (  906): releaseWL(429fdb10): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(429e9fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429e9fd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429e9a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=995019, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429e9a88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429e9520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4319): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{4215e908: PendingIntentRecord{427c32a8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455059108139, Int=0
D/PMS     (  906): acquireWL(429e8ed0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4319 1000 null
,D/PMS     (  906): releaseWL(429e9520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4319): [updateNmRange] bManual = false
D/SmartSyncScreenOnOffTimeReceiver( 4319): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4319): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4319): SettingOnTime = 1455084000000, randomSettingOnTime = 1455082488000
D/SmartSyncScreenOnOffTimeReceiver( 4319): SettingOffTime = 1455069600000, randomSettingOffTime = 1455070012000
D/SmartSyncScreenOnOffTimeReceiver( 4319): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4319): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4319): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(429e8ed0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(429e87f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1113): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): releaseWL(429e87f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1557): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1557): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1113): closing low battery warning: level=100
D/PowerUI ( 1113): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1113): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(429e5028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429e5028): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429e4aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1055018, Int=0
I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429e4aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429e3938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429e3938): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(429e2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1115019, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(429e2e68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(429dbfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(429dbfc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(4295f828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1175018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4295f828): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42947cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42947cf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(4293c688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{423e1208: PendingIntentRecord{423dec90 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1235018, Int=0
,I/IntentController( 1113): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4293c688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4418): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4418): ====startRecUseTime====
D/htc.customization.log.level( 4418):  is 
W/CustomizationLogLevel( 4418): Level value is invalid, use default level 2
D/CustomizationManager( 4418):  Read ACC file spent 0.115 (s)
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4418): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4418): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4418): Parsing tag category name = system
I/CustomizationCIDLoader( 4418): Parsing tag category name = application
I/CustomizationCIDLoader( 4418): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4418): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4418): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4418): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4418): Parsing tag category name = Settings
D/CustomizationManager( 4418):  Read CID file spent 0.170 (s)
D/CustomizationManager( 4418):  All configurations done spent 0.171 (s)
W/HtcNativeFlag( 4418): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4418): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4418): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4418): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4418, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{4225a110 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{4225ed30 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1113): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1557): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1557): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1226): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(42a03900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1226 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): releaseWL(42a03900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1300): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Scheme: "smsto"
W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1318): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/[PluginManager]RegisterService( 1318): handle notify Blinkfeed plugin client changed
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/IcingCorporaProvider( 2841): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
E/ExternalAccountType( 1339): Unsupported attribute readOnly
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4434 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
F/PackageManager(  906): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  906): java.io.IOException: write failed: EROFS (Read-only file system)
F/PackageManager(  906): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  906): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  906): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  906): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.appendIndent(FastXmlSerializer.java:127)
F/PackageManager(  906): 	at com.android.internal.util.FastXmlSerializer.startTag(FastXmlSerializer.java:358)
F/PackageManager(  906): 	at android.content.IntentFilter.writeToXml(IntentFilter.java:1285)
F/PackageManager(  906): 	at com.android.server.pm.PreferredActivity.writeToXml(PreferredActivity.java:52)
F/PackageManager(  906): 	at com.android.server.pm.Settings.writePreferredActivitiesLPr(Settings.java:1111)
F/PackageManager(  906): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1212)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  906): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  906): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  906): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  906): Caused by: libcore.io.ErrnoException: write failed: EROFS (Read-only file system)
F/PackageManager(  906): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  906): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  906): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  906): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  906): 	... 17 more
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  906): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1455059372963.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  906): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  906): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  906): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  906): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  906): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  906): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  906): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  906): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  906): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  906): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  906): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  906): 	... 18 more
E/SQLiteLog( 2841): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2841): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63a6dde8
W/dalvikvm( 2841): threadid=14: thread exiting with uncaught exception (group=0x4172ae30)
E/AndroidRuntime( 2841): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2841): Process: com.google.android.googlequicksearchbox:search, PID: 2841
E/AndroidRuntime( 2841): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2841): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2841): 	at cid.d(PG:186)
E/AndroidRuntime( 2841): 	at clo.g(PG:594)
E/AndroidRuntime( 2841): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2841): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2841): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2841): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2841): 	at clr.tL(PG:827)
E/AndroidRuntime( 2841): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2841): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2841): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2841): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2841): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2841): killProcess, pid=2841
D/Process ( 2841): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 2841
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.googlequicksearchbox:search (pid 2841) has died.
D/WifiService(  906): Client connection lost with reason: 4
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/ActivityManager(  906): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  906): Client com.google.android.googlequicksearchbox (pid 2841): Died!
E/SQLiteDatabase( 4434): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4434): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4434): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4434): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4434): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4434): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4434): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4434): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4434): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4434): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4434): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4434): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4434): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4434): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4434): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4434): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4434): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4434): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4434): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4434): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4434): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4434): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4434): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4434): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4434): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4434): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4434): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4434): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4434): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4434): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4434): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4434): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4434): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4434): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4434): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4434): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4434): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4434): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4434): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4434): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4434): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4434): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4434): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4434): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4434): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4434): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4434): threadid=11: thread exiting with uncaught exception (group=0x4172ae30)
E/AndroidRuntime( 4434): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4434): Process: com.google.android.apps.docs, PID: 4434
E/AndroidRuntime( 4434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4434): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4434): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4434): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4434): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4434): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
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
D/Process ( 4434): killProcess, pid=4434
E/SQLiteDatabase( 4434): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4434): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4434): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4434): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4434): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4434): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4434): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4434): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4434): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4434): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4434): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4434): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4434): 	at dalvik.system.NativeStart.main(Native Method)
D/Process ( 4434): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4450 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Recipient 4434
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4434) has died.
W/ContextImpl( 4450): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4463 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4450): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4450): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4450): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4450): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4450): threadid=10: thread exiting with uncaught exception (group=0x4172ae30)
E/AndroidRuntime( 4450): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4450): Process: com.android.keychain, PID: 4450
E/AndroidRuntime( 4450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4450): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4450): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4450): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4450): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4450): killProcess, pid=4450
D/Process ( 4450): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455059373851.dbox_tmp: open failed: EROFS (Read-only file system)
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
D/AppTag  ( 4463): getInstance(Context context)
D/AppTag  ( 4463): getInstance(Context context)
D/AppTag  ( 4463): onCreate()
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4478 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3838
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3838:com.google.android.music:main/u0a154 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3838
D/MediaRouterService(  906): Client com.google.android.music (pid 3838): Died!
I/ActivityManager(  906): Recipient 4450
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4450) has died.

```
