#### Test 58497659c9ea290_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  906): releaseWL(42686638): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4260e0a0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4260e0a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(425cfc18): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(425cfc18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4259c770): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4259c770): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42576550): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42576550): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(424c3930): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(424c3930): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
--------- beginning of /dev/log/main
I/IcingCorporaProvider( 2854): UpdateCorporaTask done [took 413 ms] updated apps [took 413 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
V/AlarmManager(  906): sending alarm PendingIntent{41c3ebc8: PendingIntentRecord{424d69b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59561, Int=0
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4118 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  906): acquireWL(421fb450): PARTIAL_WAKE_LOCK  AsyncService 0x1 4118 10160 null
D/PMS     (  906): releaseWL(421fb450): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(42492e38): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4118 10160 null
I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  906): acquireWL(41be64c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4118 10160 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42492e38): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4118/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (4118/10160)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(41be64c0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4145 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3815
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3815:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/JavaBinder(  906): !!! FAILED BINDER TRANSACTION !!!
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Recipient 3815
W/dalvikvm( 4145): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4145, uid=10074, userID:0
D/Settings:HtcWirelessFeatureFlags( 3841): id/is att sku: 99/false
D/Finsky  ( 4145): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
E/cutils-trace( 4116): Error opening trace file: No such file or directory (2)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4145/10074)
W/SystemReader( 3841): Cannot find devicepolicy_lower_fp_quality, use default value instead
W/SystemReader( 3841): Cannot find support_harman, use default value instead
W/SystemReader( 3841): Cannot find effect_manager_id, use default value instead
E/Settings:HtcWrapHeaderInfo( 3841): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3841): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3841): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3841): isSupportMusicChannel(): false
W/dalvikvm( 4145): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]support         :false
W/dalvikvm( 4145): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
W/FingerprintManager( 3841): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
E/Settings:HtcVoWifiWidgetEnabler( 3841): isSupportVoWifi: null
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (4145/10074)
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3841): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 4145): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4145): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4145): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4145): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4145): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4145): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4145, uid=10074, userID:0
D/CustomizationManager( 4116): ====startRecUseTime====
D/htc.customization.log.level( 4116):  is 
W/CustomizationLogLevel( 4116): Level value is invalid, use default level 2
I/HtcModeClient( 1518): handler message = 4011
E/HtcModeClient( 1518): Check connection and retry 6 times.
D/Ads     ( 4145): Skipping gmscore version check
D/Finsky  ( 4145): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4145): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4145): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/dalvikvm( 4145): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  906): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/Finsky  ( 4145): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/Process (  906): killProcessQuiet, pid=3734
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3734:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3734
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3841): The wrap header doesn't exist in header list.
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
E/Settings:HtcWrapHeaderInfo( 3841): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3841): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3841): [supportHomeButton]support         :false
W/FingerprintManager( 3841): hasFingerprint() - sSensorCode = 0
E/Settings:HtcVoWifiWidgetEnabler( 3841): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3841): Failed to find provider info for com.htc.vowifi
D/PMS     (  906): acquireWL(4266d078): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4266d078): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/CustomizationManager( 4116):  Read ACC file spent 0.059 (s)
D/PMS     (  906): acquireWL(42783938): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4116): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4116): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4116): Parsing tag category name = system
I/CustomizationCIDLoader( 4116): Parsing tag category name = application
I/CustomizationCIDLoader( 4116): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4116): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4116): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4116): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4116): Parsing tag category name = Settings
D/CustomizationManager( 4116):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4116):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4116): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4116): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4116): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4116): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4116
W/dalvikvm( 2176): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2176): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2176): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2176): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2176): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2176): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 2176): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2176, uid=10029, userID:0
I/PeopleDatabaseHelper( 2176): cleanUpNonGplusAccounts done.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  906): releaseWL(42783938): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4197 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  906): killProcessQuiet, pid=3748
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3748:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3748
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 4197): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4197): MmsConfig.loadMmsSettings
,W/dalvikvm( 4197): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4197): VFY: unable to resolve instance field 36
,W/dalvikvm( 4197): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4197): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 3775): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3775): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4197): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4197): MmsConfig.loadFromDatabase
,E/Babel   ( 4197): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4197): MmsConfig.loadFromResources
,E/Babel   ( 4197): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4197): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4197, uid=10111, userID:0
,W/Settings( 4197): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4197, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4197, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4197, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4197, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4197, uid=10111, userID:0
D/PMS     (  906): acquireWL(42815c30): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4197): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  906): releaseWL(42815c30): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4260f840): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
,I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  906): releaseWL(4260f840): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(42649580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/Process (  906): killProcessQuiet, pid=3861
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  906): Killing 3861:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,I/ActivityManager(  906): Recipient 3861
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,D/PMS     (  906): releaseWL(42649580): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(42811bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42811bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  906): acquireWL(427157f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42484d68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427157f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  906): releaseWL(42484d68): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4278f790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,D/Process (  906): killProcessQuiet, pid=3445
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ActivityManager(  906): Killing 3445:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  906): releaseWL(4278f790): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426b7dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(426b7dd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4269d968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4269d968): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42686958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(42686958): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4242ace8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Recipient 3445
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4240 uid=10041 gids={50041}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4242ace8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=3996
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  906): acquireWL(42337f58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3479 10071 null
D/PMS     (  906): acquireWL(422b71e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3479 10071 null
I/ActivityManager(  906): Killing 3996:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
E/TodoTaskNotifyService( 3479): java.lang.NullPointerException
,W/System.err( 3479): java.lang.NullPointerException
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42337f58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): acquireWL(424ecab8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
W/System.err( 3479): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3479): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3479): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3479): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3479): stopSelfResult true
D/PMS     (  906): releaseWL(422b71e0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  906): releaseWL(424ecab8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
D/PMS     (  906): acquireWL(424c6e88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3479 10071 null
,D/PMS     (  906): acquireWL(41cd0470): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3479 10071 null
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:91, mTXpacketCount:45, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/ConnectivityService(  906): Done.
D/ConnectivityService(  906): Setting timer for 720seconds
D/PMS     (  906): releaseWL(424c6e88): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 3479): java.lang.NullPointerException
W/System.err( 3479): java.lang.NullPointerException
W/System.err( 3479): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3479): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3479): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3479): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3479): stopSelfResult true
E/TodoTaskNotifyService( 3479): java.lang.NullPointerException
W/System.err( 3479): java.lang.NullPointerException
W/System.err( 3479): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3479): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3479): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 3479): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3479): stopSelfResult true
D/PMS     (  906): releaseWL(41cd0470): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  906): acquireWL(4262b368): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3479 10071 null
D/PMS     (  906): acquireWL(424c58d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3479 10071 null
D/PMS     (  906): releaseWL(4262b368): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  906): releaseWL(424c58d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/LocationInitializer( 2176): Restart initialization of location
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1223): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  906): Recipient 3996
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
,I/WSP     ( 1315): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1315): Weather sync is On
,I/WSP     ( 1315): [Receiver] next auto-sync alarm event is 60 mins later, at time: Sat Feb 06 01:26:56 CET 2016
D/PMS     (  906): acquireWL(425d5cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(425d5cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
D/PMS     (  906): acquireWL(42562738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1315/10055)
,I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
D/PMS     (  906): releaseWL(42562738): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/PMS     (  906): acquireWL(4244a058): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1315 10055 null
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2854): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(425fc6b8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425fc6b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426f73b0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426f73b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(422ef370): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(422ef370): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42692608): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,W/SQLiteConnectionPool( 2176): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PMS     (  906): releaseWL(42692608): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4243f278): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4243f278): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42716a30): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42716a30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42577200): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42577200): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4253d498): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4253d498): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4269def0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4269def0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42389108): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42389108): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2854): UpdateCorporaTask done [took 248 ms] updated apps [took 248 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42585f48): PARTIAL_WAKE_LOCK  AsyncService 0x1 4118 10160 null
,D/PMS     (  906): releaseWL(42585f48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4277 uid=10016 gids={50016, 3003, 5012, 2001}
,D/PMS     (  906): acquireWL(426dc848): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4277): Update started
,I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,E/UpdateRequestReceiver( 4277): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 4277): Update started
,I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/DownloadManager( 2417): Download 335 starting
D/PMS     (  906): acquireWL(425c4548): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2417 10021 WorkSource{10016}
D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
W/ActivityThread( 2417): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(426f18a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(426f18a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
I/ActivityManager(  906): Resuming delayed broadcast
,E/UpdateRequestReceiver( 4277): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4277): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4277): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/PMS     (  906): acquireWL(426544d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2417 10021 WorkSource{10016}
I/DownloadManager( 2417): Download 336 starting
D/libc    ( 2417): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2417): [NET] getaddrinfo-,err=8
D/libc    ( 2417): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    ( 2417): [NET] getaddrinfo-, 1
D/libc    ( 2417): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =739f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=4316 uid=10032 gids={50032, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3920
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3920:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
D/libc    ( 2417): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 4
D/libc    ( 2417): [NET] getaddrinfo-,err=8
D/libc    ( 2417): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
D/libc    ( 2417): [NET] getaddrinfo-, 1
D/libc    ( 2417): [NET] getaddrinfo_proxy+
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x7777772e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/libc    (  363): [NET] +++++ res_nsend xid =a8fb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=49
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2417): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.GservicesChangedReceiver
,D/libc    (  363): [NET]res_nsend:resplen=49
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2417): [NET] getaddrinfo_proxy-, success
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3920
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.youtube, clsName=null, state=1, flag=0, pid=4316, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.maps, clsName=null, state=1, flag=0, pid=4316, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.magazines, clsName=null, state=1, flag=0, pid=4316, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.books, clsName=null, state=1, flag=0, pid=4316, uid=10032, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.videos, clsName=null, state=1, flag=0, pid=4316, uid=10032, userID:0
,D/PMS     (  906): acquireWL(426bdc90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426bdc90): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/DownloadManager( 2417): Ignoring Content-Length since Transfer-Encoding is also defined
,D/PMS     (  906): acquireWL(4260ddd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4260ddd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
,D/PMS     (  906): acquireWL(427a6d20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(427a6d20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(4263e3b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4263e3b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(425b2700): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(425b2700): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2417): Ignoring Content-Length since Transfer-Encoding is also defined
D/PMS     (  906): acquireWL(4271d6f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4271d6f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/DownloadManager( 2417): Download 336 finished with status SUCCESS
D/PMS     (  906): releaseWL(426544d8): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,D/PMS     (  906): acquireWL(42783638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42783638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3878
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3878:com.htc.mediamanager/u0a34 (adj 15): empty #17
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [3][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.GservicesChangedReceiver: pid=4344 uid=10079 gids={50079, 3003, 5012}
I/DownloadManager( 2417): Download 335 finished with status SUCCESS
D/PMS     (  906): releaseWL(425c4548): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
V/AlarmManager(  906): sending alarm PendingIntent{4262a130: PendingIntentRecord{4262d740 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454714816853, Int=0
E/PhoneMonitor( 4344): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4344): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/Process (  906): killProcessQuiet, pid=3959
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3959:com.htc.sdm/u0a81 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4344/10079)
I/ContactAccountLoggerTas( 2854): canRun() : Opted Out
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4344/10079)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (4344/10079)
D/PMS     (  906): acquireWL(4277f528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3959
D/PMS     (  906): acquireWL(4270fff8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/Search.GservicesUpdateTask( 2854): Updating Gservices keys
D/PMS     (  906): releaseWL(4277f528): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1454714811696 min interval config: 0 actual interval: 5195
I/ActivityManager(  906): Recipient 3878
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CheckinService( 2176): Checking schedule, now: 1454714816901 next: 1454714841631
I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
D/PMS     (  906): releaseWL(4270fff8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/ContactAccountLoggerTas( 2854): canRun() : Opted Out
I/ContactAccountLoggerTas( 2854): canRun() : Opted Out
I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/com.google.android.apps.moviemaker.app.ApplicationEnabler$Receiver
I/ContactAccountLoggerTas( 2854): canRun() : Opted Out
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.MovieMakerActivity, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.analyzer.AnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PostCaptureAnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.service.PluggedInAnalyzerService, state=0, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.NewVideoReceiver, state=2, flag=1, pid=4118, uid=10160, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.apps.plus, clsName=com.google.android.apps.moviemaker.receiver.PowerStatusReceiver, state=2, flag=1, pid=4118, uid=10160, userID:0
V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1359): [NET] getaddrinfo-, 1
D/libc    ( 1359): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =aaeb +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1359): [NET] getaddrinfo_proxy-, success
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
D/libc    ( 1359): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1359): [NET] getaddrinfo-,err=8
I/ContactAccountLoggerTas( 2854): canRun() : Opted Out
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(4265c150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42657278): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1454714811696 min interval config: 0 actual interval: 5717
D/PMS     (  906): releaseWL(4265c150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checking schedule, now: 1454714817418 next: 1454714841631
I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
I/SystemUpdateService( 2176): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
D/PMS     (  906): acquireWL(4248a088): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42657278): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 2176): onCreate
D/SystemUpdateService( 2176): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/dalvikvm( 2176): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/SystemUpdateService( 2176): cancelUpdate (empty URL)
I/SystemUpdateService( 2176): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,D/Icing   ( 2176): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(426dc848): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/PMS     (  906): releaseWL(4248a088): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2176): onDestroy
,E/DynamiteModule( 2176): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 2176): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-1.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /data/app-lib/com.google.android.gms-1, /vendor/lib, /system/lib]]
E/DynamiteModule( 2176): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 2176): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 2176): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 2176): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 2176): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 2176): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 2176): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 2176): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 2176): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 2176): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/DynamiteModule( 2176): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/DynamiteModule( 2176): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/DynamiteModule( 2176): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 2176): 	at android.os.Looper.loop(Looper.java:157)
E/DynamiteModule( 2176): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/DynamiteModule( 2176): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 2176): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 2176): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/DynamiteModule( 2176): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/DynamiteModule( 2176): 	at dalvik.system.NativeStart.main(Native Method)
I/DynamiteModule( 2176): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 2176): Selected local version of com.google.android.gms.flags
,D/PMS     (  906): acquireWL(423b0fd8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,D/SystemEventReceiver( 2176): Received GSERVICES_CHANGED broadcast
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,I/OcrUtils( 2176): Updating ocr activity enabled=false
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.ocr.SecuredCreditCardOcrActivity, state=2, flag=1, pid=2176, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.social.location.service.LocationSharingSettingInjectorService, state=2, flag=1, pid=1223, uid=10029, userID:0
,D/PMS     (  906): releaseWL(423b0fd8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/ActivityManager(  906): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 2176): Updating downloaded model state (gservices changed)
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.analytics.service.AnalyticsService, state=1, flag=1, pid=2176, uid=10029, userID:0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(425b4808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/GCM     ( 1359): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(423ec6f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 906 1000 WorkSource{10029}
,I/GAV2    ( 4077): Thread[GAThread,5,main]: No campaign data found.
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): releaseWL(425b4808): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42444b80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42444b80): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42602338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(423ec6f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  906): releaseWL(42602338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
,E/dalvikvm( 1223): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 1223): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  906): acquireWL(425f4130): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{4281a210: PendingIntentRecord{41ad5180 com.google.android.gms startService}}) : type=2 triggerAtTime=315360064416 win=-1 tElapsed=315360064416 maxElapsed=551880064415 interval=0 standalone=false
,I/GCoreUlr( 1223): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1223): DispatchingService.onCreate()
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  906): acquireWL(42621360): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/TodoTaskshortcut( 3479): update TASK shortcut>
,D/PMS     (  906): acquireWL(42695070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): releaseWL(42695070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,E/ctxmgr  ( 1223): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1223): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ctxmgr  ( 1223): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10029, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1223): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
D/PMS     (  906): releaseWL(425f4130): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4248abf8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4248abf8): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426acd88): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426acd88): PARTIAL_WAKE_LOCK  ContextManagerWakeLock 0x1 WorkSource{10029 com.google.android.gms}
,I/GCoreUlr( 1223): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1223): Unbound from all location providers
,I/GCoreUlr( 1223): Place inference reporting - stopped
V/AlarmManager(  906): sending alarm PendingIntent{42642378: PendingIntentRecord{424b9c30 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454714818609, Int=0
D/PMS     (  906): acquireWL(42813a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42813a10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42621360): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/GCoreUlr( 1223): DispatchingService.onDestroy()
,I/GCoreUlr( 1223): Stopping handler for UlrDispSvcFast
D/PMS     (  906): acquireWL(4282c040): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4282c040): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1223): Unbound from all location providers
I/GCoreUlr( 1223): Place inference reporting - stopped
,I/iu.UploadsManager( 2176): End new media; added: 0, uploading: 0, time: 49 ms
V/AlarmManager(  906): sending alarm PendingIntent{4265bfa8: PendingIntentRecord{426a86b8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454714818663, Int=0
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 7 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=66084, Int=0
,I/GAV4    ( 4197): Thread[GAThread,5,main]: No campaign data found.
,I/ClockThread( 1115): now=1454714820417 next=59583
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2176, uid=10029, userID:0
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Done disabling old GoogleServicesFramework version
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,I/SensorManager(  906): mEventCount = 600
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,I/Prism.ItemManager( 3707): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3707): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/dalvikvm-heap( 1271): Grow heap (frag case) to 13.192MB for 53840-byte allocation
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
,I/GAV2    ( 4118): Thread[GAThread,5,main]: No campaign data found.
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/PackageManager(  906): Unable to load service info ResolveInfo{4266d328 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(426d86b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): releaseWL(426d86b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4257cd50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4257cd50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42618638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42618638): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4278fb88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(4278fb88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 3707): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3707): loadItems() com.htc.launcher.pageview.WidgetManager@41b52020 +
,I/Prism.WidgetManager( 3707): onLoadItems() +
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b71e88 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/CalendarProvider2( 1518): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1518): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): acquireWL(41be70d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
E/Prism.WidgetManager( 3707): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 3707): onLoadItems() -
,I/Prism.ItemManager( 3707): loadItems() com.htc.launcher.pageview.WidgetManager@41b52020 -
D/PMS     (  906): acquireWL(427a6d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): acquireWL(423c8c20): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3896 10154 null
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  906): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
D/PMS     (  906): releaseWL(41be70d0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
D/PMS     (  906): releaseWL(427a6d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3896, uid=10154, userID:0
,I/MusicLeanback( 3896): Conditions not met for autocaching.
,I/MusicLeanback( 3896): Stop autocaching.
,W/ContextImpl( 3896): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  906): releaseWL(423c8c20): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(425b6fc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(425b6fc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(42802a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42802a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426ad908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4407 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1271): onLoadItems() -
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b71e88 -
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): releaseWL(426ad908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 4407): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  906): Resuming delayed broadcast
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 8 times.
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,I/DownloadManager( 2417): Download 337 starting
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
D/PMS     (  906): acquireWL(427d9288): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2417 10021 WorkSource{10016}
D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,I/DownloadManager( 2417): Ignoring Content-Length since Transfer-Encoding is also defined
I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/Process (  906): killProcessQuiet, pid=4040
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4433 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Killing 4040:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  906): Recipient 4040
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(427c65f0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 2417 10021 WorkSource{10016}
,I/DownloadManager( 2417): Download 338 starting
D/ConnectivityService(  906): getAllNetworkInfo called by  (2417/10021)
,D/SyncApplication( 4433): Loading default preferences
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/Resources( 4433): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/DownloadManager( 2417): Ignoring Content-Length since Transfer-Encoding is also defined
,D/WifiService(  906): New client listening to asynchronous messages
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (2417/10021)
D/SyncApplication( 4433): Overriding preferences with custom values
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=6 [31][2][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/SyncApplication( 4433): Updating preferences succeeded
E/SyncApplication( 4433): Application created.
D/VolumeInfo( 4433): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 4433): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4433): Found 0 mount point(s)
V/VolumeInfo( 4433): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/CalendarDefines( 4433): getNewCalendarAuthority()...
,D/SyncApplication( 4433): enableAppOperation()+
D/SyncApplication( 4433): enableAppOperation()-
,D/VolumeInfo( 4433): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/HTCUtilities( 4433): isNeorSinged() + 
,I/DownloadManager( 2417): Download 337 finished with status SUCCESS
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4433, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4433, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/PMS     (  906): releaseWL(427d9288): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
D/VolumeInfo( 4433): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 4433): Can not create volume ID for unmounted volume null
,D/HTCUtilities( 4433): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4433): isNeorSinged() return false
,D/CDMountReceiver( 4433): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4433): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4433): enable CD Auto-mount: true
,I/DownloadManager( 2417): Download 338 finished with status SUCCESS
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
D/PMS     (  906): releaseWL(427c65f0): PARTIAL_WAKE_LOCK  DownloadManager 0x1 WorkSource{10016}
,I/ActivityManager(  906): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/HTCUtilities( 4433): enable auto-mount
D/HTCUtilities( 4433): enable auto-mount
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/Process (  906): killProcessQuiet, pid=3707
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  906): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(42674a08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/ActivityManager(  906): Killing 3707:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c82488 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 10 2 11
I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ecef80 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 1 7 2 16
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3707
,D/PMS     (  906): acquireWL(42755ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1177): nl80211: survey data missing!
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42755ab8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427de920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
D/PMS     (  906): releaseWL(427de920): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(4270fff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(427098c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
I/ActivityManager(  906): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(427098c8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4270fff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/IcingCorporaProvider( 2854): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  906): acquireWL(426a5f18): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426a5f18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42686e48): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42686e48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426868b8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426868b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426867c8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426867c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42686728): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): releaseWL(42686728): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42686688): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(42686688): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2854): UpdateCorporaTask done [took 271 ms] updated apps [took 271 ms] 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(42686510): PARTIAL_WAKE_LOCK  AsyncService 0x1 4118 10160 null
,D/PMS     (  906): releaseWL(42686510): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(42683a20): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4265a3b8 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4469 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4469): onCreate
D/ProviderChangeReceiver( 4469): ---------------------------------------------------
,D/ProviderChangeReceiver( 4469): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4469): start to updateAlertNotification!
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4483 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=4059
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 4059:com.htc.updater/u0a85 (adj 15): empty #17
,D/AlertService( 4469): No fired or scheduled alerts
,D/HtcAlertUtils( 4469): -- cancelReminderNotification --
,D/HtcAlertUtils( 4469): broadcastExistReminder!
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  906): Recipient 4059
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4483): [4483/4483] onCreate()
W/ContextImpl( 4483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4277): Update downloaded, starting installation
,I/UpdateFetcherService( 4277): Started installation
I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.SmsShortCodes.SmsShortCodesUpdateRequestReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,W/ContextImpl( 4277): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 4277): Update downloaded, starting installation
,I/ActivityManager(  906): Delay finish: com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
I/UpdateFetcherService( 4277): Started installation
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3721
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3721:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ConfigUpdateInstallReceiver(  906): Not installing, new version is <= current version
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Recipient 3721
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(420e2eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(420e2eb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2176): Loaded CLD2 Version V2.0 - 20141016
D/PMS     (  906): releaseWL(4244a058): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42683a20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/PackageSettings(  906): Skipping PackageSetting{421da668 com.example.hello/10397} due to missing metadata
,W/PackageSettings(  906): Skipping PackageSetting{421de2d8 com.test.thalitest/10389} due to missing metadata
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=126 rxSum=114} preTxRxSum={txSum=62 rxSum=56}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20195 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20196 delay=15s
D/PMS     (  906): acquireWL(42631768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{420ad248: PendingIntentRecord{42577960 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=73800, Int=0
D/PMS     (  906): releaseWL(42631768): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 9 times.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Finsky  ( 4145): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4145): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;,
D/PMS     (  906): acquireWL(42787378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
V/AlarmManager(  906): sending alarm PendingIntent{426abc50: PendingIntentRecord{426fabe8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454714830213, Int=0
D/PMS     (  906): releaseWL(42787378): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.vending (4145/10074)
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-,err=8
D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4145): [NET] getaddrinfo-, 1
D/libc    ( 4145): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =236c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4145): [NET] getaddrinfo_proxy-, success
I/global  ( 4145): call createSocket() return a new socket.
D/libc    ( 4145): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4145): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4145): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/Finsky  ( 4145): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [27][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:187, mTXpacketCount:91, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4145): untagSocket(69) failed with errno -22
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.android.vending (4145/10074)
,D/Finsky  ( 4145): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  906): acquireWL(426da0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10074}
,V/AlarmManager(  906): sending alarm PendingIntent{424212e0: PendingIntentRecord{426d9ad0 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454714832292, Int=0
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
D/PMS     (  906): acquireWL(4280fe18): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4145 10074 null
,D/PMS     (  906): releaseWL(426da0e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4145): [443] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1223): client connected with version: 8296000
,D/Finsky  ( 4145): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4145): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4145): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4145): [NET] getaddrinfo-,err=8
D/libc    ( 4145): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4145): [NET] getaddrinfo-, 1
,D/libc    ( 4145): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7529 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=87
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4145): [NET] getaddrinfo_proxy-, success
,D/PMS     (  906): releaseWL(4280fe18): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 10 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=5 [52][3][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  906): mEventCount = 750
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1315): service - mHandler: update timezone
,D/AutoSetting( 1315): service - handleMessage() stop self
,D/AutoSetting( 1315): service - handleMessage() quit looper
,D/AutoSetting( 1315): service - onDestroy() END
,D/Process (  906): killProcessQuiet, pid=3775
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3775:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1518): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1518): service - onCreate()
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  906): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1518): service - mHandler: update timezone
,D/AutoSetting( 1518): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1518): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1518): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1518): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1518): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1518): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f06710 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 7 2 11
,I/ActivityManager(  906): Recipient 3775
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 11 times.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(426e0c68): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426e0c68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427539f8): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427539f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426d5010): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426d5010): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  906): acquireWL(42744ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=203 rxSum=182} preTxRxSum={txSum=126 rxSum=114}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20196 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20197 delay=15s
V/AlarmManager(  906): sending alarm PendingIntent{427aeab0: PendingIntentRecord{42577960 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88805, Int=0
D/PMS     (  906): releaseWL(42744ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 12 times.
,I/SensorManager(  906): mEventCount = 900
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:242, mTXpacketCount:187, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1518): handler message = 4011
,E/HtcModeClient( 1518): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1518): Don't start project servcice
,D/HtcModeClient( 1518): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1518): connectState: CONNECTION_READY = false
D/SilentMusic( 1518): call stop
D/HtcModeClient( 1518): close connection
,W/HtcModeClient( 1518): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1518): read the terminate packet, so break
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/PMS     (  906): acquireWL(427797a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029}
,V/AlarmManager(  906): sending alarm PendingIntent{424ecee8: PendingIntentRecord{42620768 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454714841631, Int=522937000
,V/AlarmManager(  906): sending alarm PendingIntent{425d2c48: PendingIntentRecord{4263ca50 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454714846579, Int=0
,D/PMS     (  906): acquireWL(427a4480): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4520 uid=10078 gids={50078}
,V/AlarmManager(  906): sending alarm PendingIntent{42501768: PendingIntentRecord{424cade8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454714849372, Int=60000
,D/PMS     (  906): releaseWL(427797a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/PMS     (  906): acquireWL(42740ea0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1454714811696 min interval config: 0 actual interval: 37732
D/PMS     (  906): releaseWL(427a4480): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checking schedule, now: 1454714849436 next: 1454714841631
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1454714806899
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/SMSBackup( 4520): SMSBackupAgentService started
,D/SMSBackup( 4520): Checking restore status
,D/SMSBackup( 4520): Restore complete
,D/SMSBackup( 4520): cancelCheckAlarm
,D/SMSBackup( 4520): SMSBackupAgentService completed: completed in 0.0 seconds
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,I/CheckinRequestBuilder( 2176): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4534 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Finsky  ( 4145): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4145): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  906): killProcessQuiet, pid=4316
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4316:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4316
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4534): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4534): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4534): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4534): install
,I/MultiDex( 4534): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4534): loading existing secondary dex files
,I/MultiDex( 4534): load found 3 secondary dex files
,I/MultiDex( 4534): install done
,W/dalvikvm( 4534): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4534): VFY: unable to resolve instance field 36
,W/dalvikvm( 4534): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4534): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4534): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1223): callingUid 10029, callindPid: 1223
,D/LocationInitializer( 2176): Restart initialization of location
,W/dalvikvm( 4534): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4534): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,E/MDM     ( 1223): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1359): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1359): Proximity feature is not enabled.
,W/dalvikvm( 4534): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4534): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 4534): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4534): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4534): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,V/GLSActivity( 1359): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  906): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,W/GCoreFlp( 1223): No location to return for getLastLocation()
,W/FusedLocationProvider( 1223): location=null
D/PMS     (  906): acquireWL(426868b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426868b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4534): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  370): PrepareKeyRequest: nonce=2527341272
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4534): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4534): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4534): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4534): Local Branch: 
I/Adreno-EGL( 4534): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4534): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4534):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4534): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4534): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4534): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4534): Local Branch: 
I/Adreno-EGL( 4534): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4534): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4534):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  370): PrepareKeyRequest: nonce=1045240437
,I/WVCdm   (  370): CdmEngine::CloseSession
,I/Adreno-EGL( 4534): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4534): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4534): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4534): Local Branch: 
I/Adreno-EGL( 4534): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4534): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4534):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (4534/10029)
,W/Settings( 4534): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =61ee +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12273 bytes)
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4277c560 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=28 [14][4][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/CheckinRequestBuilder( 2176): Checkin reason type: 3 attempt count: 1
I/ActivityManager(  906): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 2176): Checking schedule, now: 1454714852357 next: 1455237789353
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1454714852378
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42740ea0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/GCM     ( 1359): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/LightsService(  906): setLight #0: color=#24
,V/LightsService(  906): setLight #0: color=#21
,V/LightsService(  906): setLight #0: color=#1a
,V/LightsService(  906): setLight #0: color=#14
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Process (  906): killProcessQuiet, pid=4344
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4344:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 4344
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  906): mEventCount = 1050
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=218 rxSum=197} preTxRxSum={txSum=203 rxSum=182}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20197 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20198 delay=15s
D/PMS     (  906): acquireWL(42380700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{42364e88: PendingIntentRecord{42577960 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=103812, Int=0
D/PMS     (  906): releaseWL(42380700): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  906): acquireWL(4265c400): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4197 10111 null
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Scheme: "smsto"
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
D/PMS     (  906): releaseWL(4265c400): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
,I/IcingCorporaProvider( 2854): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1339): Unsupported attribute readOnly
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  906): acquireWL(4274e498): PARTIAL_WAKE_LOCK  AsyncService 0x1 4118 10160 null
D/PMS     (  906): releaseWL(4274e498): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  906): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
D/PMS     (  906): acquireWL(4274cb88): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  906): Resuming delayed broadcast
D/PMS     (  906): releaseWL(4274cb88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42687410): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  906): Resuming delayed broadcast
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  906): Unable to load service info ResolveInfo{42674768 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/IcingCorporaProvider( 2854): UpdateCorporaTask done [took 442 ms] updated apps [took 442 ms] 
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,I/GCoreNlp( 1223): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  906): applying state to connected service
,D/LocationProviderProxy(  906): applying state to connected service
D/PMS     (  906): acquireWL(427a2618): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(427a2618): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42830438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42830438): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(42745110): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(42745110): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PMS     (  906): Going to sleep due to screen timeout...
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421c97c0
D/WirelessDisplayService(  906): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  906): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  906): pid=906, uid=1000
,W/SensorService(  906): Active sensors: size = 2
,W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
,W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421c97c0, eanble = 0, strlen(mName) = 59
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  906): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7c790
,W/SensorService(  906): Listener[1] = com.htc.smartdim.sensor_eye@423d5430
,W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  906): mWirelessDisplayManager is null
W/BatSI   (  906): Couldn't get kernel wake lock stats
V/LightsService(  906): setLight #2: color=#0
D/qdlights(  906): set_light_buttons_func: on=0 brightness=0
V/LightsService(  906): setLight #0: color=#0
,D/SurfaceControl(  906): Excessive delay in blankDisplay() while turning screen off: 311ms
,W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  906): nativeSetInteractive:false
D/PMS     (  906): nativeSetInteractive:false done
D/PMS     (  906): nativeSetAutoSuspend:true
D/PMS     (  906): nativeSetAutoSuspend:true done
D/HABCtrl (  906): TPE algorithm. remove timeout.
D/PMS     (  906): OOBE c monitor 11
I/InputManager(  906): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  906): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42883788)
D/NfcService( 1256): ScreenObserver: OFF
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
I/InputMethodManagerService(  906): screenObserver, isScreenOn=false
I/InputMethodManagerService(  906): Disable input method client, pid=1271
D/PMN     (  906): wakingUp
D/PMS     (  906): acquireWL(428842a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,V/KeyguardServiceDelegate(  906): **** SHOWN CALLED ****
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  906): releaseWL(428842a0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  906): acquireWL(42885968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
I/WindowManager(  906): No lock screen! windowToken=null
D/AlarmManager(  906): ACTION_SCREEN_ON
I/AlarmManager(  906): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done recovering
I/AlarmManager(  906): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  906): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  906): releaseWL(42885968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMN     (  906): onScreenOn
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/MtpService( 2417): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2417): [MTP][onReceive]-
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_ON
D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20199 delay=15s
D/PMS     (  906): acquireWL(4288bfb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  906): releaseWL(4288bfb8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/WirelessDisplayService(  906): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/ClockThread( 1115): stop update clock
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800,
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  906): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  906): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:On
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
,I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1177): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4586 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  906): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -50 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
V/NotificationService(  906): batLight: Full, plugged
V/LightsService(  906): setLight #8: color=#c8c800
D/qdlights(  906): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  906): setLight #8: color=#c800
D/qdlights(  906): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  906): [LedInfo] has indicator attribute
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  906): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/NetworkPolicy(  906): updateScreenOn: false
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1177): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/WifiStateMachine(  906): [ScoreAP] + current TXpacket:261, mTXpacketCount:242, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  906): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): acquireWL(428a1a80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4586 1000 null
,D/PMS     (  906): acquireWL(428a25a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4586): isEpsOn(), nState = 0
D/PMS     (  906): releaseWL(428a25a0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428a4908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428a1a80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4586): getMobilePolicyEnabled, result = true
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1753): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): onScreenOn: 1454714860796
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1753): onScreenOn: 1454714860796
,D/AutoSetting( 1315): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  906): releaseWL(428a4908): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/TetherSettings( 3841): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3841): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3841): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3841): Cust_ConnectToPC   : spcsc>false
D/        ( 3841): Cust_ConnectToPC   : IPT>true
D/        ( 3841): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3841): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AutoSetting( 1315): service - onCreate()
E/SmartNS_Utility( 3841): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3841): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3841): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/SensorManager(  906): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7c790
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 2
W/SensorService(  906): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f7c790, eanble = 0, strlen(mName) = 91
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  906): Listener[0] = com.htc.smartdim.sensor_eye@423d5430
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/AutoSetting( 1315): service - AddressCache: using context: com.htc.Weather
D/PMN     (  906): goingToSleep
D/PMS     (  906): acquireWL(428afc28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 906 1000 null
,D/AutoSetting( 1315): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/FeedHostManager( 1271): [onPause]
D/LocationManagerService(  906): request 423343b8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
I/FeedProviderManager( 1271): onPause
,D/LocationManagerService(  906): provider request: passive ProviderRequest[ON interval=0]
,I/SocialFeedProvider( 1271): +onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c49d80
,I/SocialFeedProvider( 1271): -onPause
D/AlarmManager(  906): ACTION_SCREEN_OFF
I/AlarmManager(  906): [AlarmQueuing] screen off now: 
I/AlarmManager(  906): [AlarmQueuing] data connection: true
,I/AlarmManager(  906): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  906): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20199 mDataStallAlarmIntent=PendingIntent{423e5aa0: PendingIntentRecord{42577960 android broadcastIntent}}
,I/PSReceiver( 3841): onReceive:android.intent.action.USER_PRESENT
D/WifiNative-wlan0(  906): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  906): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1177): SET_SCREEN_ON:Off
I/wpa_supplicant( 1177): htc_wext_set_keepalive +
I/wpa_supplicant( 1177): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1177): getPrivFuncNum +	
I/wpa_supplicant( 1177): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1177): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1177): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1177): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1177): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  906):    returned true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
D/PMS     (  906): acquireWL(428b7de8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 906 1000 null
W/ContextImpl( 3841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3841): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3841): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3841):  defaultType:0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  906): releaseWL(428afc28): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/ContactMessageStore( 1244): start background delete task...
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
D/NetworkPolicy(  906): updateScreenOn: false
,D/wpa_supplicant( 1177): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(428b7de8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,W/ContextImpl( 4586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4586): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4586): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4586): isEpsOn(), nState = 0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,D/WifiService(  906): New client listening to asynchronous messages
I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423d5430
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 1
W/SensorService(  906): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423d5430, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  906): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  906): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  906): pid=906, uid=1000
W/SensorService(  906): Active sensors: size = 0
W/SensorService(  906): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@423d5430, eanble = 0, strlen(mName) = 36
W/SensorService(  906): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  906): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/SensorManager(  906): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@423d5430
E/ActivityThread(  906): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42011be0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  906): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42011be0 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,D/PMS     (  906): acquireWL(428d8c10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  906): releaseWL(428d8c10): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): acquireWL(428da1d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(428da1d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1753): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1753): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1753): onScreenOff
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  906): releaseWL(42687410): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b71e88 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b71e88 -
,D/PhoneApp( 1244): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1244): -- N1 =0
,D/PhoneApp( 1244): -- N2 =0
,D/PhoneApp( 1244): -- N3 =0
,D/AutoSetting( 1518): service - handleMessage() stop self
,D/AutoSetting( 1518): service - onDestroy() END
,D/AutoSetting( 1518): service - handleMessage() quit looper
,D/Process (  906): killProcessQuiet, pid=3479
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3479:com.htc.task/u0a71 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3479
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1244): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  906): killProcessQuiet, pid=3934
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3934:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3934
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1315): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1315): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1315): service - requestNLP() NetworkLocationProvider not enabled
,D/PMS     (  906): acquireWL(428f5d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{426724d8: PendingIntentRecord{4264ed20 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=121865, Int=0
,D/PMS     (  906): releaseWL(428f5d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(428f7ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{428aeb78 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(428fe248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428f7ad0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428fe248): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42903dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42903dc0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(429082d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(428a0c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4286b500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1223): Vacuum at: now=1454714876193 tag=VacuumService
,D/PMS     (  906): releaseWL(429082d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(428a0c70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42823a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42823a58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42818260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(4286b500): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42818260): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42803e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42803e08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42802cd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(42802cd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(427fa560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): acquireWL(426867c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(426867c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(423563d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(427fa560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4271fa30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(4271fa30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1223): Scheduling Phenotype for one-off execution 5855 seconds from now (1454714877139)
,D/GetConfigurationSnapshotOperation( 1223): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1223): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1223): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1223): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =50a8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=10 [10][1][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  906): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/PMS     (  906): releaseWL(423563d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(4261f310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(4261f310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(42415690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=50 [2][1][0]
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(42415690): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): acquireWL(426fa7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=126084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426fa7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427f2a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): releaseWL(427f2a70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1315): service - handleMessage() stop self
,D/AutoSetting( 1315): service - handleMessage() quit looper
,D/AutoSetting( 1315): service - onDestroy() END
D/Process (  906): killProcessQuiet, pid=3896
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3896:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/PMS     (  906): acquireWL(425c4718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  906): sending alarm PendingIntent{421a9cd8: PendingIntentRecord{426a5630 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137057, Int=0
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,D/PMS     (  906): releaseWL(425c4718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  906): Recipient 3896
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  906): Client com.google.android.music (pid 3896): Died!
,D/PMS     (  906): acquireWL(4267f438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4205efb8: PendingIntentRecord{4205a448 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141727, Int=0
,D/GpsLocationProvider(  906): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  906): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  906): acquireWL(428a1a88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
D/PMS     (  906): releaseWL(4267f438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-,err=8
D/libc    (  906): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  906): [NET] getaddrinfo-, 1
,D/libc    (  906): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e095 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  906): [NET] getaddrinfo_proxy-, success
I/global  (  906): call createSocket() return a new socket.
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  906): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  906): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  906): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  906):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  906): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  906): releaseWL(428a1a88): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  906): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  906): acquireWL(426aed68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426aed68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(424e57f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10027}
,V/AlarmManager(  906): sending alarm PendingIntent{42639330: PendingIntentRecord{423d0ca8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173274, Int=0
,D/PMS     (  906): releaseWL(424e57f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/ClearcutLoggerApiImpl( 1359): disconnect managed GoogleApiClient
,D/TelephonyReceiver( 1244): switchBindHtcMsgCursor: null
,D/PMS     (  906): acquireWL(42744ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=186084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42744ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42890f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(42890f80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(425b9fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b9fb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(4275ba00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=246084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4275ba00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425ceec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): releaseWL(425ceec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(42704b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42704b28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(428c2f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=306084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428c2f38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428b9440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/PMS     (  906): releaseWL(428b9440): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/Process (  906): killProcessQuiet, pid=4407
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4407:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4407
,D/PMS     (  906): acquireWL(42894dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/PMS     (  906): releaseWL(42894dc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425b8b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=366084, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425b8b08): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427507c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427507c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(427d0478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427d0478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(426388e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=426084, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(426388e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426092c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426092c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(428b4bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428b4bb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  906): acquireWL(425f1a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=486084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(425f1a60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428153c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428153c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  906): acquireWL(426b17b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426b17b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  906): acquireWL(4260de28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=546084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4260de28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427bbc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427bbc08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(426fc4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(426fc4e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42884870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=606084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42884870): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4282c608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4282c608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1244): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1244): sku_id=99
D/ContactMessageStore( 1244): start background delete task...
,D/ContactMessageStore( 1244): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1244): size: 0 , 0
,D/ContactMessageStore( 1244): Background delete complete
,D/PMS     (  906): acquireWL(42651408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=666084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42651408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426254a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): releaseWL(426254a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42740208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42740208): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428a0a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=726084, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428a0a80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42756820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42756820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42742fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(42742fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427f4c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=786084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427f4c98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42793cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(42793cd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ConnectivityService(  906): Sampling interval elapsed, updating statistics ..
D/PMS     (  906): acquireWL(4279d0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
V/AlarmManager(  906): sending alarm PendingIntent{41d15ea8: PendingIntentRecord{42470608 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782023, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{41c3ebc8: PendingIntentRecord{424d69b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=822093, Int=0
D/ConnectivityService(  906): Done.
,D/ConnectivityService(  906): Setting timer for 720seconds
,I/ActivityManager(  906): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4654 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  906): sending alarm PendingIntent{425e69b0: PendingIntentRecord{423b9bd0 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454714965321, Int=10800000
,V/AlarmManager(  906): sending alarm PendingIntent{424d82d8: PendingIntentRecord{426ee238 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454715079471, Int=1800000
,D/PMS     (  906): acquireWL(426f35c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(42799618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): acquireWL(426de940): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4279d0c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029}
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(426c72b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(426de940): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=11 [127][14][0]
,D/PMS     (  906): acquireWL(428812a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 906 1000 WorkSource{10160}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
,I/EventLogService( 2176): Aggregate from 1454714849493 (log), 1454713279423 (data)
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(4272f470): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 906 1000 WorkSource{10029}
D/PMS     (  906): releaseWL(426f35c0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  906): releaseWL(42799618): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1177): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1177): nl80211: survey data missing!
E/wpa_supplicant( 1177): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1177): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42768a48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/PMS     (  906): releaseWL(42768a48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/PMS     (  906): acquireWL(42764298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.aurora (4654/10049)
D/PMS     (  906): releaseWL(42764298): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428f5138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(428f5138): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,D/PMS     (  906): releaseWL(426c72b8): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(428bd578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1223/10029)
,D/PMS     (  906): releaseWL(428812a0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
,D/PMS     (  906): releaseWL(428bd578): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  906): killProcessQuiet, pid=4433
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 4433:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 4433
,D/WifiService(  906): Client connection lost with reason: 4
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360822365
,W/AlarmManager(  906): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42563540: PendingIntentRecord{42896d40 com.google.android.gms startService}}) : type=2 triggerAtTime=315360822365 win=-1 tElapsed=315360822365 maxElapsed=551880822362 interval=0 standalone=false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): acquireWL(427e4aa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(4272f470): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  906): releaseWL(427e4aa8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(428dea80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PMS     (  906): releaseWL(428dea80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(428e4a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=846084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(428e4a28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428e6ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428e6ca8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  906): acquireWL(42831c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{41c3ebc8: PendingIntentRecord{424d69b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=852198, Int=0
,D/PMS     (  906): acquireWL(42832bd0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 906 1000 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/PMS     (  906): releaseWL(42831c20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(42834b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 906 1000 null
,D/PMS     (  906): releaseWL(42832bd0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  906): releaseWL(42834b08): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  906): acquireWL(4283c250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
,D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(4283c250): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
,I/HtcPowerSaver(  906): >> updateStatus
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42842230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=906084, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42842230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(428444b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(428444b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4284a5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{10029 com.google.android.gms}
V/AlarmManager(  906): sending alarm PendingIntent{4267bab8: PendingIntentRecord{426e5b88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=947592, Int=0
V/AlarmManager(  906): sending alarm PendingIntent{41fcb0a8: PendingIntentRecord{4239b468 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454715685669, Int=900000
D/PMS     (  906): acquireWL(4284c628): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  906): releaseWL(4284c628): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4586): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  906): releaseWL(4284a5c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PowerUsageService( 4586): call getInstance()
D/PowerUsageList:PowerUsageHelper( 4586): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(427448b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427448b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4242bb38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1359 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
,D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1359/10029)
,D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1359/10029)
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023746
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360023983
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024174
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024208
W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024225
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360024235
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025791
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360025809
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360028319
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360064416
,W/AlarmManager(  906): Converted elapesd time is over 1 year! when = 315360822365
,D/PMS     (  906): releaseWL(4242bb38): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  906): acquireWL(4288fb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=966084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4288fb60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(421880d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(421880d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  906): onReceive BATTERY_CHANGED
,D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42690a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,D/SmartSyncUtils( 4586): isEpsOn(), nState = 0
V/AlarmManager(  906): sending alarm PendingIntent{42036a38: PendingIntentRecord{428a6718 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454715760909, Int=0
,D/SmartSyncScreenOnOffTimeReceiver( 4586): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4586): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/PMS     (  906): releaseWL(42690a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(426ef188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4586 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4586): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4586): SettingOnTime = 1454738400000, randomSettingOnTime = 1454737710000
D/SmartSyncScreenOnOffTimeReceiver( 4586): SettingOffTime = 1454724000000, randomSettingOffTime = 1454730649000
D/SmartSyncScreenOnOffTimeReceiver( 4586): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4586): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 4586): bNightModeTurnOffOnce = false
,D/PMS     (  906): releaseWL(426ef188): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  906): acquireWL(4256f0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4256f0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427f6118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1026084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427f6118): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(4289fd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4289fd00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  906): updateBatteryInfo
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4265dff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(4265dff0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(427623e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1086084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(427623e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(41f23f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(41f23f90): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(425b0730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b0730): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  906): updateBatteryInfo
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(4269d040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1146084, Int=0
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(4269d040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427cc2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(427cc2f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  906): acquireWL(42999600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1206083, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(42999600): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(425b11b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/PMS     (  906): releaseWL(425b11b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  906): updateBatteryInfo
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  906): acquireWL(41be8810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 906 1000 WorkSource{1000}
,V/AlarmManager(  906): sending alarm PendingIntent{4233e898: PendingIntentRecord{422508b0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1266084, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  906): releaseWL(41be8810): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  906): acquireWL(427f6d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  906): n_update end
,D/UsbnetService(  906): BroadcastReceiver::onReceive+
D/UsbnetService(  906): onReceive BATTERY_CHANGED
D/UsbnetService(  906):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  906): BroadcastReceiver::onReceive-
D/PMS     (  906): releaseWL(427f6d00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  906): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  906): runPSCheck
D/HtcPowerSaver(  906): Checking...
I/HtcPowerSaver(  906): >> updateStatus
,I/HtcPowerSaver(  906): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  906): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4692): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4692): ====startRecUseTime====
D/htc.customization.log.level( 4692):  is 
W/CustomizationLogLevel( 4692): Level value is invalid, use default level 2
D/CustomizationManager( 4692):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4692): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4692): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4692): Parsing tag category name = system
I/CustomizationCIDLoader( 4692): Parsing tag category name = application
I/CustomizationCIDLoader( 4692): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4692): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4692): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4692): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4692): Parsing tag category name = Settings
D/CustomizationManager( 4692):  Read CID file spent 0.092 (s)
D/CustomizationManager( 4692):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 4692): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4692): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4692): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4692): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  906): deletePackageAsUser: pkg=com.test.thalitest, pid=4692, uid=2000 user=0
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  906): Skipping PackageSetting{421da668 com.example.hello/10397} due to missing metadata
W/PackageSettings(  906): Skipping PackageSetting{421de2d8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  906): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  906): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  906): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1223): Ignoring removeGeofence because network location is disabled.
D/PMS     (  906): acquireWL(429e4450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1223 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  906): releaseWL(429e4450): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1339): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
W/AccTypeManager( 1339): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1339): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1315): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1315): handle notify Blinkfeed plugin client changed
I/IcingCorporaProvider( 2854): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4708 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1339): Unsupported attribute readOnly
I/IcingCorporaProvider( 2854): UpdateCorporaTask done [took 90 ms] updated apps [took 89 ms] 
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4708): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4708): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4708): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4708): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4708): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4708): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4708): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4708): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4708): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4708): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4708): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4708): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4708): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4708): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4708): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4708): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4708): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4708): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4708): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4708): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4708): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4708): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4708): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4708): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4708): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4708): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4708): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4708): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4708): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4708): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4708): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4708): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4708): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4708): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4708): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4708): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4708): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4708): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4708): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4708): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4708): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4708): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4708): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4708): threadid=11: thread exiting with uncaught exception (group=0x416aee30)
E/AndroidRuntime( 4708): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4708): Process: com.google.android.apps.docs, PID: 4708
E/AndroidRuntime( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4708): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4708): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4708): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4708): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4708): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  906): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4708): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4708): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4708): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4708): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4708): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4708): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4708): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4708): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4708): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4708): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4708): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4708): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4708): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4708): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4708): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4708): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4708): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4708): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4708): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4708): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4708): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4708): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4708): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4708): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4708): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4708): Opened ClientFlag.db in read-only mode
I/ActivityManager(  906): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4725 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4708): killProcess, pid=4708
D/Process ( 4708): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  906): Recipient 4708
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.google.android.apps.docs (pid 4708) has died.
W/ContextImpl( 4725): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4739 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4725): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4725): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4725): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4725): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4725): threadid=10: thread exiting with uncaught exception (group=0x416aee30)
E/AndroidRuntime( 4725): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4725): Process: com.android.keychain, PID: 4725
E/AndroidRuntime( 4725): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4725): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4725): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4725): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4725): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4725): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4725): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4725): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4725): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  906): App crashed! Process: com.android.keychain
D/ErrorReport(  906): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4739): getInstance(Context context)
D/Process ( 4725): killProcess, pid=4725
D/Process ( 4725): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  906): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  906): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454716029830.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  906): Recipient 4725
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Process com.android.keychain (pid 4725) has died.
W/ActivityManager(  906): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4739): getInstance(Context context)
D/AppTag  ( 4739): onCreate()
W/PackageManager(  906): Unable to load service info ResolveInfo{42713bb8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b71e88 +
I/Prism.WidgetManager( 1271): onLoadItems() +
D/PMS     (  906): acquireWL(42705dd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4118 10160 null
D/PMS     (  906): releaseWL(42705dd8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4145): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  906): killProcessQuiet, pid=4240
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 4240:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/ActivityManager(  906): Recipient 4240
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest

```
