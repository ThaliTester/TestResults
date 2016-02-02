#### Test 575312438097721_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/Settings:HtcVoWifiWidgetEnabler( 3795): isSupportVoWifi: null
--------- beginning of /dev/log/system
I/ActivityManager(  905): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3795): Failed to find provider info for com.htc.vowifi
W/dalvikvm( 4121): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4121): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4121): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4121): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4121, uid=10074, userID:0
,D/Ads     ( 4121): Skipping gmscore version check
D/Finsky  ( 4121): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4121): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4121): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/dalvikvm( 4121): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/ActivityManager(  905): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider
D/Finsky  ( 4121): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=3703
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3703:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  905): Recipient 3703
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/PMS     (  905): acquireWL(42790460): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42790460): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(4277ca70): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4277ca70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42775078): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2187): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2187): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2187): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2187): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2187): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2187): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
W/dalvikvm( 2187): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2187, uid=10029, userID:0
I/PeopleDatabaseHelper( 2187): cleanUpNonGplusAccounts done.
D/Process (  905): killProcessQuiet, pid=3811
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3811:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/ActivityManager(  905): Resuming delayed broadcast
D/Process (  905): killProcessQuiet, pid=3425
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3425:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  905): acquireWL(426c56b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
I/ActivityManager(  905): Recipient 3425
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1114): WifiActivity: 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  905): releaseWL(426c56b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(426b0bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/cutils-trace( 4163): Error opening trace file: No such file or directory (2)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
W/GCoreFlp( 1220): No location to return for getLastLocation()
W/FusedLocationProvider( 1220): location=null
D/PMS     (  905): acquireWL(41e00528): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(41e00528): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(426b0bd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3811
D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
D/PMS     (  905): acquireWL(426f9048): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(423d0af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/CustomizationManager( 4163): ====startRecUseTime====
D/htc.customization.log.level( 4163):  is 
W/CustomizationLogLevel( 4163): Level value is invalid, use default level 2
D/PMS     (  905): releaseWL(423d0af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): acquireWL(424196f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
I/SensorManager(  905): mEventCount = 450
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(424196f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42491310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
D/PMS     (  905): releaseWL(426f9048): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42491310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42638448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
D/CustomizationManager( 4163):  Read ACC file spent 0.070 (s)
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__002
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
D/CIDMapFileReader( 4163): Parsing tag item name = HTC__031
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
V/CustomizationCIDLoader( 4163): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4163): Parsing tag category name = system
I/CustomizationCIDLoader( 4163): Parsing tag category name = application
I/CustomizationCIDLoader( 4163): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4163): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4163): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4163): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4163): Parsing tag category name = Settings
D/CustomizationManager( 4163):  Read CID file spent 0.114 (s)
D/CustomizationManager( 4163):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 4163): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4163): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4163): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4163): Fail to get flag for type 'language', use default value: -1
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42638448): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(427139c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4186 uid=10041 gids={50041}
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4163
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(427139c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Killing 3598:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3598
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
D/ConnectivityService(  905): Done.
D/ConnectivityService(  905): Setting timer for 720seconds
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3598
I/BroadcastQueue(  905): Schedule to resend BroadcastRecord{425e2de8 u0 com.htc.intent.lockscreen.ClearTASKReminder callingPid=3598 callingUid=10071} for ResolveInfo{424c2458 com.htc.task/.notification.NotifyReceiver m=0x108000} of com.htc.task
I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4201 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
D/PMS     (  905): acquireWL(426673a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4201 10071 null
D/PMS     (  905): acquireWL(427647b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4201 10071 null
D/Process (  905): killProcessQuiet, pid=3925
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3925:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  905): releaseWL(426673a8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4201): java.lang.NullPointerException
W/System.err( 4201): java.lang.NullPointerException
W/System.err( 4201): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4201): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4201): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  905): releaseWL(427647b8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
W/NotifyReceiver( 4201): stopSelfResult true
I/ActivityManager(  905): Recipient 3925
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  905): Client connection lost with reason: 4
D/PMS     (  905): acquireWL(4277ecc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4201 10071 null
D/PMS     (  905): acquireWL(428113b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4201 10071 null
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 4201): java.lang.NullPointerException
W/System.err( 4201): java.lang.NullPointerException
W/System.err( 4201): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4201): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4201): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4201): stopSelfResult true
D/PMS     (  905): releaseWL(4277ecc8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  905): releaseWL(428113b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(4266f500): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4201 10071 null
D/PMS     (  905): acquireWL(426dd5d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4201 10071 null
I/ActivityManager(  905): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  905): releaseWL(4266f500): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4201): java.lang.NullPointerException
W/System.err( 4201): java.lang.NullPointerException
W/System.err( 4201): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4201): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4201): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4201): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4201): stopSelfResult true
D/PMS     (  905): releaseWL(426dd5d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
D/WearableService( 1220): callingUid 10029, callindPid: 1220
D/LocationInitializer( 2187): Restart initialization of location
D/AuthorizationBluetoothService( 1374): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1374): Proximity feature is not enabled.
E/MDM     ( 1220): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WSP     ( 1341): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1341): Weather sync is On
,I/WSP     ( 1341): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 18:14:08 CET 2016
D/PMS     (  905): acquireWL(42680e38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4045 10111 null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
W/GCoreFlp( 1220): No location to return for getLastLocation()
,W/FusedLocationProvider( 1220): location=null
I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
D/PMS     (  905): acquireWL(4278bdf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4278bdf8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1341/10055)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(42680e38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/PMS     (  905): acquireWL(41d0b090): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1341 10055 null
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  905): releaseWL(42775078): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  905): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed,
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2819): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  905): acquireWL(42704348): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42704348): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427c61d8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  905): releaseWL(427c61d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426bbe38): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426bbe38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42750268): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42750268): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425f3d70): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{426cb858: PendingIntentRecord{426b9860 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454429648923, Int=0
,D/PMS     (  905): releaseWL(425f3d70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(426aea30): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426aea30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42698f98): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42698f98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42812358): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42812358): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427894f8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(427894f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2819): UpdateCorporaTask done [took 341 ms] updated apps [took 341 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(42674b68): PARTIAL_WAKE_LOCK  AsyncService 0x1 4094 10160 null
,D/PMS     (  905): releaseWL(42674b68): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2187): Null package name or gms related package.  Ignoreing.
,D/PMS     (  905): acquireWL(4276fd60): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2187): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:131, mTXpacketCount:55, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/TodoTaskshortcut( 4201): update TASK shortcut>
,I/GAV2    ( 3999): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1114): WifiActivity: 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/PMS     (  905): acquireWL(42819280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PMS     (  905): releaseWL(42819280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2187): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,W/SQLiteConnectionPool( 2187): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PMS     (  905): releaseWL(4276fd60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager(  905): sending alarm PendingIntent{41f30c98: PendingIntentRecord{425c5cd8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454429650697, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{4232f8f8: PendingIntentRecord{423336a8 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454429650741, Int=0
,I/iu.UploadsManager( 2187): End new media; added: 0, uploading: 0, time: 92 ms
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV4    ( 4045): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 7 times.
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/CheckinService( 2187): Done disabling old GoogleServicesFramework version
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2187, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1271): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 4026): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 4026): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
,E/ExternalAccountType( 1326): Unsupported attribute readOnly
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/CalendarProvider2( 1527): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1527): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  905): Resuming delayed broadcast
,D/GCM     ( 1374): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2187/10029)
I/ActivityManager(  905): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,W/PackageManager(  905): Unable to load service info ResolveInfo{428444c0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  905): start
,D/PMS     (  905): acquireWL(42871b78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 905 1000 null
,D/PMS     (  905): acquireWL(42872d98): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3847 10154 null
,I/ActivityManager(  905): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3847): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GCoreNlp( 1220): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3847, uid=10154, userID:0
,W/ContextImpl( 3847): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/PMS     (  905): acquireWL(428a1ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428a1ef0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(428a4b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42871b78): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/LocationProviderProxy(  905): applying state to connected service
,D/LocationProviderProxy(  905): applying state to connected service
D/PMS     (  905): releaseWL(428a4b98): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  905): acquireWL(428adca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428aeaa0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428aeaa0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428b0478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428adca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428b0478): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/MusicLeanback( 3847): Conditions not met for autocaching.
,I/MusicLeanback( 3847): Stop autocaching.
D/PMS     (  905): releaseWL(42872d98): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3828): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  905): Resuming delayed broadcast
,D/PMS     (  905): acquireWL(42894af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42894af0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42819280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(42819280): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42521e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4259 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/PMS     (  905): releaseWL(42521e88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/SyncApplication( 4259): Loading default preferences
,W/Resources( 4259): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  905): New client listening to asynchronous messages
,D/SyncApplication( 4259): Overriding preferences with custom values
,D/SyncApplication( 4259): Updating preferences succeeded
,E/SyncApplication( 4259): Application created.
D/VolumeInfo( 4259): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4259): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4259): Found 0 mount point(s)
,V/VolumeInfo( 4259): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4259): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4259): getNewCalendarAuthority()...
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4259, uid=10008, userID:0
,D/VolumeInfo( 4259): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4259): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4259): enableAppOperation()+
,D/SyncApplication( 4259): enableAppOperation()-
,D/HTCUtilities( 4259): isNeorSinged() + 
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4259, uid=10008, userID:0
W/PackageManager(  905): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4259): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4259): isNeorSinged() return false
,D/CDMountReceiver( 4259): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4259): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4259): enable CD Auto-mount: true
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4259): enable auto-mount
,D/HTCUtilities( 4259): enable auto-mount
,I/RemoteViews( 1114): com.nero.android.htc.sync (false,0)
I/ActivityManager(  905): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  905): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): releaseWL(4241a050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/Process (  905): killProcessQuiet, pid=3871
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f35e70 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  905): Killing 3871:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/RemoteViews.Performance( 1114): com.nero.android.htc.sync 2 16 3 11
,I/RemoteViews( 1114): com.nero.android.htc.sync (false,0)
D/PMS     (  905): acquireWL(423728a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4045 10111 null
I/ActivityManager(  905): Recipient 3871
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f2b288 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.nero.android.htc.sync 1 9 3 16
D/PMS     (  905): releaseWL(423728a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
I/ActivityManager(  905): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/IcingCorporaProvider( 2819): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  905): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  905): acquireWL(427f7d90): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/PMS     (  905): releaseWL(427f7d90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4241ae38): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4241ae38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4211eb00): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4211eb00): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42686ec0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42686ec0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(424046e0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(424046e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(423f34c0): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(423f34c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(425554b8): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(425554b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42609698): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42609698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42840988): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42840988): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bfdcb0 +
,I/Prism.WidgetManager( 1271): onLoadItems() +
,I/IcingCorporaProvider( 2819): UpdateCorporaTask done [took 297 ms] updated apps [took 297 ms] 
I/ActivityManager(  905): Resuming delayed broadcast
,I/Prism.ItemManager( 4026): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 4026): loadItems() com.htc.launcher.pageview.WidgetManager@41be37c0 +
,I/Prism.WidgetManager( 4026): onLoadItems() +
,I/ActivityManager(  905): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  905): acquireWL(4267aa78): PARTIAL_WAKE_LOCK  AsyncService 0x1 4094 10160 null
,D/PMS     (  905): releaseWL(4267aa78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  905): Resuming delayed broadcast
,D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/PackageBroadcastService( 2187): Null package name or gms related package.  Ignoreing.
,D/PMS     (  905): acquireWL(42413b50): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2187): updateResources: need to parse f{com.google.android.gms}
,E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1271): onLoadItems() -
,I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bfdcb0 -
,I/Prism.WidgetManager( 4026): onLoadItems() -
,I/Prism.ItemManager( 4026): loadItems() com.htc.launcher.pageview.WidgetManager@41be37c0 -
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 8 times.
,I/Icing   ( 2187): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2187): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  905): releaseWL(42413b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4291 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4291): onCreate
D/ProviderChangeReceiver( 4291): ---------------------------------------------------
,D/ProviderChangeReceiver( 4291): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4291): start to updateAlertNotification!
,D/Process (  905): killProcessQuiet, pid=3959
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4305 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Killing 3959:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3959
,D/AlertService( 4291): No fired or scheduled alerts
,D/HtcAlertUtils( 4291): -- cancelReminderNotification --
,D/HtcAlertUtils( 4291): broadcastExistReminder!
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4305): [4305/4305] onCreate()
W/ContextImpl( 4305): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3903
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  905): Killing 3903:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3903
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{427d5230 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97,
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): releaseWL(41d0b090): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/PMS     (  905): acquireWL(42718620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PowerUI ( 1114): closing low battery warning: level=100
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42718620): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
,I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,I/SensorManager(  905): mEventCount = 600
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=99 rxSum=93} preTxRxSum={txSum=99 rxSum=93}
D/WifiDataStallTracker(  905): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19425 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19426 delay=15s
D/PMS     (  905): acquireWL(427b5fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{41c7b540: PendingIntentRecord{42412870 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=72899, Int=0
D/PMS     (  905): releaseWL(427b5fc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 9 times.
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Finsky  ( 4121): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4121): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  905): acquireWL(427d8b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
V/AlarmManager(  905): sending alarm PendingIntent{420e8668: PendingIntentRecord{4224ccc8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454429662677, Int=0
D/PMS     (  905): releaseWL(427d8b30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.android.vending (4121/10074)
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4121): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4121): [NET] getaddrinfo-,err=8
D/libc    ( 4121): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4121): [NET] getaddrinfo-, 1
D/libc    ( 4121): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3bc +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4121): [NET] getaddrinfo_proxy-, success
I/global  ( 4121): call createSocket() return a new socket.
D/libc    ( 4121): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 4121): [NET] getaddrinfo-, SUCCESS
,D/WIFI_ICON( 1114): WifiActivity: 3
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4121): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4121): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4121): untagSocket(69) failed with errno -22
,D/Finsky  ( 4121): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4121): untagSocket(69) failed with errno -22
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=3 [27][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:159, mTXpacketCount:131, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4121): untagSocket(69) failed with errno -22
,D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.android.vending (4121/10074)
,D/Finsky  ( 4121): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  905): acquireWL(4284a078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{41b61f00: PendingIntentRecord{427ad438 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454429665290, Int=0
,D/PMS     (  905): acquireWL(42759058): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4121 10074 null
,D/WearableService( 1220): callingUid 10029, callindPid: 1220
,D/PMS     (  905): releaseWL(4284a078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4121): [443] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1220): client connected with version: 8296000
,D/Finsky  ( 4121): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4121): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1374): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4121): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4121): [NET] getaddrinfo-,err=8
D/libc    ( 4121): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4121): [NET] getaddrinfo-, 1
,D/libc    ( 4121): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =537c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4121): [NET] getaddrinfo_proxy-, success,
,D/PMS     (  905): releaseWL(42759058): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 10 times.
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=13 [52][7][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/AutoSetting( 1341): service - mHandler: update timezone
,D/AutoSetting( 1341): service - handleMessage() stop self
,D/AutoSetting( 1341): service - handleMessage() quit looper
,D/AutoSetting( 1341): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3986,
,I/ActivityManager(  905): Killing 3986:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Recipient 3986
,D/AutoSetting( 1527): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1527): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1527): service - onCreate()
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  905): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found,
,D/AutoSetting( 1527): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1527): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1527): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1527): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1527): service - mHandler: update timezone
,D/AutoSetting( 1527): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1527): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1527): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1527): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1562): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1114): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1114): release indeterminate drawable android.widget.OnDemandProgressBar{41f88910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1114): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  905): acquireWL(42547968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): releaseWL(42547968): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [2][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/SensorManager(  905): mEventCount = 750
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 11 times.
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(42497600): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42497600): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42488288): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42488288): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42482f38): PARTIAL_WAKE_LOCK  Icing 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42482f38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=177 rxSum=162} preTxRxSum={txSum=99 rxSum=93}
D/WifiDataStallTracker(  905): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19426 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19427 delay=15s
D/PMS     (  905): acquireWL(41f05e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{42655dd8: PendingIntentRecord{42412870 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=87904, Int=0
D/PMS     (  905): releaseWL(41f05e40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 12 times.
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:220, mTXpacketCount:159, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1527): Don't start project servcice
,D/HtcModeClient( 1527): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1527): connectState: CONNECTION_READY = false
D/SilentMusic( 1527): call stop
D/HtcModeClient( 1527): close connection
,W/HtcModeClient( 1527): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1527): read the terminate packet, so break
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/PMS     (  905): acquireWL(42638010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10074}
,V/AlarmManager(  905): sending alarm PendingIntent{42722328: PendingIntentRecord{426e5698 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454429679447, Int=0
,I/ActivityManager(  905): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4338 uid=10078 gids={50078}
,V/AlarmManager(  905): sending alarm PendingIntent{426e3988: PendingIntentRecord{4278de20 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454429682613, Int=60000
,D/PMS     (  905): releaseWL(42638010): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4338): SMSBackupAgentService started
,D/SMSBackup( 4338): Checking restore status
D/SMSBackup( 4338): Restore complete
,D/SMSBackup( 4338): cancelCheckAlarm
,D/SMSBackup( 4338): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/Finsky  ( 4121): [434] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4121): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  905): killProcessQuiet, pid=4026
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4026:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  905): Recipient 4026
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{42733c20 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  905): setLight #0: color=#25
,V/LightsService(  905): setLight #0: color=#1e
,V/LightsService(  905): setLight #0: color=#18
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
V/LightsService(  905): setLight #0: color=#14
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1114): WifiActivity: 0
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  905): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  905): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  905): updateDataStallInfo: mDataStallTxRxSum={txSum=177 rxSum=162} preTxRxSum={txSum=177 rxSum=162}
D/WifiDataStallTracker(  905): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  905): onDataStallAlarm: tag=19427 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19428 delay=15s
D/PMS     (  905): acquireWL(42690d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
V/AlarmManager(  905): sending alarm PendingIntent{423807d0: PendingIntentRecord{42412870 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102909, Int=0
D/PMS     (  905): releaseWL(42690d60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,D/WIFI_ICON( 1114): WifiActivity: 1
,D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  905): Going to sleep due to screen timeout...
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@423e6b18
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = CM36282 Light sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@423e6b18, eanble = 0, strlen(mName) = 59
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  905): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208b8f0
W/SensorService(  905): Listener[1] = com.htc.smartdim.sensor_eye@4278e0e0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WirelessDisplayService(  905): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  905): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  905): mWirelessDisplayManager is null
W/BatSI   (  905): Couldn't get kernel wake lock stats
V/LightsService(  905): setLight #2: color=#0
D/qdlights(  905): set_light_buttons_func: on=0 brightness=0
V/LightsService(  905): setLight #0: color=#0
,D/SurfaceControl(  905): Excessive delay in blankDisplay() while turning screen off: 321ms
,W/PnPMgr  (  351): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  905): nativeSetInteractive:false
D/PMS     (  905): nativeSetInteractive:false done
D/PMS     (  905): nativeSetAutoSuspend:true
D/PMS     (  905): nativeSetAutoSuspend:true done
D/HABCtrl (  905): TPE algorithm. remove timeout.
I/InputManager(  905): Cancel all due to getting PMS screen off broadcast
D/PMS     (  905): OOBE c monitor 11
D/NfcService( 1253): ScreenObserver: OFF
,D/NfcService( 1253): applyRouting - 0
,V/KeyguardServiceDelegate(  905): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42785e10)
I/IntentController( 1114): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/NfcService( 1253): applyRouting -2
I/InputMethodManagerService(  905): screenObserver, isScreenOn=false
I/InputMethodManagerService(  905): Disable input method client, pid=1271
D/PMN     (  905): wakingUp
D/PMS     (  905): acquireWL(428620d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
,V/KeyguardServiceDelegate(  905): **** SHOWN CALLED ****
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): acquireWL(42740af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
D/PMS     (  905): releaseWL(428620d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  905): No lock screen! windowToken=null
D/PMS     (  905): releaseWL(42740af8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMN     (  905): onScreenOn
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,D/WirelessDisplayService(  905): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/MtpService( 2717): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1253): applyRouting - 0
,D/MtpService( 2717): [MTP][onReceive]-
,D/NfcService( 1253): applyRouting -2
,D/AutoSetting( 1341): receiver - intent: android.intent.action.USER_PRESENT
I/HtcPowerSaver(  905): << updateStatus
D/PMS     (  905): acquireWL(426eb230): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1253 1027 null
D/AlarmManager(  905): ACTION_SCREEN_ON
I/AlarmManager(  905): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done recovering
I/AlarmManager(  905): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  905): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  905): releaseWL(426eb230): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/TetherSettings( 3795): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3795): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3795): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3795): Cust_ConnectToPC   : spcsc>false
D/        ( 3795): Cust_ConnectToPC   : IPT>true
D/        ( 3795): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3795): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3795): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3795): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3795): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  905): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  905): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_ON
,D/AutoSetting( 1341): service - onCreate()
D/WifiDataStallTracker(  905): startDataStallAlarm: tag=19429 delay=15s
,I/ClockThread( 1114): stop update clock
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/PSReceiver( 3795): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 3795): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1341): service - AddressCache: using context: com.htc.Weather
W/Settings( 3795): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3795):  defaultType:0
W/ContextImpl( 3795): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1131): SET_SCREEN_ON:On
I/wpa_supplicant( 1131): htc_wext_set_keepalive +
I/wpa_supplicant( 1131): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1131): getPrivFuncNum +	
I/wpa_supplicant( 1131): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1131): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1131): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1131): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1131): htc_wext_set_TX_TRACKING - ret = 0
D/AutoSetting( 1341): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WifiNative-wlan0(  905):    returned true
D/LocationManagerService(  905): request 4264e700 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  905): provider request: passive ProviderRequest[ON interval=0]
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/WirelessDisplayService(  905): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/WIFI_ICON( 1114): WifiActivity: 0
D/StatusBar.NetworkController( 1114): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
V/NotificationService(  905): batLight: Full, plugged
V/LightsService(  905): setLight #8: color=#c8c800
D/qdlights(  905): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  905): setLight #8: color=#c800
D/qdlights(  905): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  905): [LedInfo] has indicator attribute
D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  905): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1131): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
,D/WifiStateMachine(  905): [ScoreAP] + current TXpacket:220, mTXpacketCount:220, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  905): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  905): updateScreenOn: false
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4363 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  905): acquireWL(4283d2f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4283d2f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(42865fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(42865fa0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOn: 1454429693051
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOn: 1454429693051
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208b8f0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 2
W/SensorService(  905): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
,W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208b8f0, eanble = 0, strlen(mName) = 91
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  905): Listener[0] = com.htc.smartdim.sensor_eye@4278e0e0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  905): goingToSleep
,D/PMS     (  905): acquireWL(428518d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
D/PMS     (  905): acquireWL(42677158): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 905 1000 null
,D/PMS     (  905): releaseWL(428518d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,I/FeedHostManager( 1271): [onPause]
D/WifiDataStallTracker(  905): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=19429 mDataStallAlarmIntent=PendingIntent{426d0b78: PendingIntentRecord{42412870 android broadcastIntent}}
,I/FeedProviderManager( 1271): onPause
D/AlarmManager(  905): ACTION_SCREEN_OFF
I/AlarmManager(  905): [AlarmQueuing] screen off now: 
I/AlarmManager(  905): [AlarmQueuing] data connection: true
I/AlarmManager(  905): [AlarmQueuing] wifi connection: true
I/SocialFeedProvider( 1271): +onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420aba60
,I/SocialFeedProvider( 1271): -onPause
,D/WifiNative-wlan0(  905): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1131): SET_SCREEN_ON:Off
I/wpa_supplicant( 1131): htc_wext_set_keepalive +
I/wpa_supplicant( 1131): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1131): getPrivFuncNum +	
I/wpa_supplicant( 1131): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1131): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1131): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1131): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1131): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  905): doBoolean: DRIVER SETSUSPENDMODE 1
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): acquireWL(426a1658): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 905 1000 null
,D/WifiNative-wlan0(  905):    returned true
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): releaseWL(42677158): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  371): ParamSet string: screen_state=off
D/NetworkPolicy(  905): updateScreenOn: false
,D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,D/wpa_supplicant( 1131): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(426a1658): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,I/PhoneStatusBar( 1114): removeHeadsNotification.gc: 53
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4363): getMobilePolicyEnabled, result = true
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4278e0e0
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  905): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 1
W/SensorService(  905): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4278e0e0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  905): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  905): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  905): pid=905, uid=1000
W/SensorService(  905): Active sensors: size = 0
W/SensorService(  905): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4278e0e0, eanble = 0, strlen(mName) = 36
W/SensorService(  905): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  905): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WifiService(  905): New client listening to asynchronous messages
,I/SensorManager(  905): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4278e0e0
E/ActivityThread(  905): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276cfc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276cfc0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  905): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  905): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  905): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  905): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  905): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  905): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  905): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  905): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  905): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  905): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  905): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  905): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] getTotalRam: 1873 Mb
D/PMS     (  905): acquireWL(42744ae0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42744ae0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): acquireWL(427725b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(427725b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1773): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1773): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1773): onScreenOff
,D/AutoSetting( 1341): service - mHandler: cancel location update
,D/AutoSetting( 1341): service -           changes count: 0
,D/AutoSetting( 1527): service - handleMessage() stop self
,D/AutoSetting( 1527): service - onDestroy() END
,D/AutoSetting( 1527): service - handleMessage() quit looper
,D/Process (  905): killProcessQuiet, pid=2160
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2160:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2160
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4279f1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=112011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4279f1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  905): Killing 3885:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  905): killProcessQuiet, pid=3885
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 3885
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Waited long enough for: ServiceRecord{427aefb0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  905): acquireWL(41b60850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{42403008: PendingIntentRecord{42684160 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=120076, Int=0
,D/PMS     (  905): releaseWL(41b60850): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428133e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(42854ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42854ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(428133e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428b0788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(428b0788): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42890908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(426ab9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4280e838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1220): Vacuum at: now=1454429708422 tag=VacuumService
,D/PMS     (  905): releaseWL(42890908): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(426ab9d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427d4d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(427d4d60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(42897578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  905): releaseWL(4280e838): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(42897578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427ab128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(427ab128): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4280c310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(4280c310): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4272e0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50,
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): acquireWL(427bdac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(427bdac8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427c8f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4272e0c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428460b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(428460b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1220): Scheduling Phenotype for one-off execution 5311 seconds from now (1454429709358)
,D/GetConfigurationSnapshotOperation( 1220): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1220): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1220): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1220): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1220): [NET] getaddrinfo-, 1
,D/libc    ( 1220): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =82aa +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1220): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1220): [NET] getaddrinfo-,err=8
D/libc    ( 1220): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1220): [NET] getaddrinfo-,err=8
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/LocationManagerService(  905): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=9 [11][1][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1220/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
,D/PMS     (  905): releaseWL(427c8f18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4281ea78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(4281ea78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(428252f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1131): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1131): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1131): nl80211: survey data missing!
E/wpa_supplicant( 1131): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1131): environment dirty rate=0 [0][0][0]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(428252f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(4287a200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4287a200): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4287f598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  905): sending alarm PendingIntent{427d25b8: PendingIntentRecord{42687178 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=135294, Int=0
,D/PMS     (  905): releaseWL(4287f598): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
,D/AutoSetting( 1341): service - handleMessage() stop self
,D/AutoSetting( 1341): service - handleMessage() quit looper
,D/AutoSetting( 1341): service - onDestroy() END
,D/Process (  905): killProcessQuiet, pid=3690
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3690:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3690
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(42885d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{425350c8: PendingIntentRecord{425d22b0 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140971, Int=0
,D/GpsLocationProvider(  905): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  905): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  905): acquireWL(42887028): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
D/PMS     (  905): releaseWL(42885d20): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-,err=8
D/libc    (  905): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  905): [NET] getaddrinfo-, 1
,D/libc    (  905): [NET] getaddrinfo_proxy+
,D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =3710 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=238
D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  905): [NET] getaddrinfo_proxy-, success
I/global  (  905): call createSocket() return a new socket.
D/libc    (  905): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  905): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  905): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  905): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  905): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  905):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  905): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  905): releaseWL(42887028): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  905): acquireWL(42911738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42911738): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42913248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{10027}
,V/AlarmManager(  905): sending alarm PendingIntent{426cc090: PendingIntentRecord{426719d0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=171029, Int=0
,D/PMS     (  905): releaseWL(42913248): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/PMS     (  905): acquireWL(42915028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=172010, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42915028): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  905): acquireWL(42917288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42917288): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42918b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=232011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42918b88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(4291ade8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4291ade8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(4291c340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4291c340): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  905): updateBatteryInfo
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1114): closing low battery warning: level=100
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(42921e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=292011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42921e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42924110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
,D/UsbnetService(  905): onReceive BATTERY_CHANGED
,D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/BatteryService(  905): n_update end
D/HtcPowerSaver(  905): updateBatteryInfo
,D/PMS     (  905): releaseWL(42924110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/Process (  905): killProcessQuiet, pid=4186
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 4186:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 4186
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(4292c2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4292c2a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(4292e0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=352011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4292e0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(429308f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429308f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(429321f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=412011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(429321f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(42934a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42934a60): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  905): acquireWL(42936360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=472011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42936360): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  905): acquireWL(429385c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429385c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  905): acquireWL(42939ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=532011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42939ec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  905): acquireWL(4293c140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4293c140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4293da40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=592011, Int=0
,D/PMS     (  905): releaseWL(4293da40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4293fca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4293fca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1238): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1238): sku_id=99
D/ContactMessageStore( 1238): start background delete task...
,D/ContactMessageStore( 1238): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/PMS     (  905): acquireWL(42942ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=652011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42942ae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42945060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42945060): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42946960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=712010, Int=0
,D/PMS     (  905): releaseWL(42946960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42948be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42948be0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4294a4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=772011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(4294a4e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4294cd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4294cd28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4294e628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=832011, Int=0
,D/PMS     (  905): releaseWL(4294e628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42950888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42950888): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(429521a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=892011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(429521a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42954408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42954408): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(42955f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/ConnectivityService(  905): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  905): sending alarm PendingIntent{41e504b0: PendingIntentRecord{42500218 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=780249, Int=0
,V/AlarmManager(  905): sending alarm PendingIntent{42540678: PendingIntentRecord{4275daf0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=945846, Int=0
,D/PMS     (  905): acquireWL(429606c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(429606c0): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): Done.
,D/ConnectivityService(  905): Setting timer for 720seconds
,I/ActivityManager(  905): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4415 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  905): sending alarm PendingIntent{4263e578: PendingIntentRecord{426da400 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454429798410, Int=10800000
V/AlarmManager(  905): sending alarm PendingIntent{41c95108: PendingIntentRecord{425d5cb8 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1454430086228, Int=1800000
,V/AlarmManager(  905): sending alarm PendingIntent{4244ddc0: PendingIntentRecord{42443e70 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454430518684, Int=900000
,D/PMS     (  905): acquireWL(4296b758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  905): releaseWL(42955f18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PowerUsageService( 4363): call getInstance()
D/PMS     (  905): acquireWL(4296e358): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2187 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(4296b758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PowerUsageList:PowerUsageHelper( 4363): MY_DEBUG = false
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.aurora (4415/10049)
,I/EventLogService( 2187): Aggregate from 1454429638658 (log), 1454428286183 (data)
W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(4296e358): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,W/BatSI   (  905): Couldn't get kernel wake lock stats
,D/Process (  905): killProcessQuiet, pid=4201
,I/ActivityManager(  905): Killing 4201:com.htc.task/u0a71 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Recipient 4201
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(428a8e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(428a8e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  905): updateBatteryInfo
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
,D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  905): << updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(428fc3a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1374 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (1374/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (1374/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023413
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023689
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023784
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023788
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023792
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360023795
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025055
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025070
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360027845
,D/PMS     (  905): releaseWL(428fc3a8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  905): acquireWL(42816c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000},
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=952010, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(42816c40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42855b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42855b70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  905): BroadcastReceiver::onReceive+
D/UsbnetService(  905): onReceive BATTERY_CHANGED
D/UsbnetService(  905):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  905): BroadcastReceiver::onReceive-
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1562): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1562): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1114): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  905): updateBatteryInfo
D/PMS     (  905): runPSCheck
D/HtcPowerSaver(  905): Checking...
I/HtcPowerSaver(  905): >> updateStatus
D/PowerUI ( 1114): closing low battery warning: level=100
D/PowerUI ( 1114): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  905): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  905): << updateStatus
,I/BatteryController( 1114): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  905): acquireWL(4289db40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,D/SmartSyncUtils( 4363): isEpsOn(), nState = 0
V/AlarmManager(  905): sending alarm PendingIntent{424bc8f8: PendingIntentRecord{427b1630 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454430593215, Int=0
D/PMS     (  905): acquireWL(4289ece8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4363 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4363): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/PMS     (  905): releaseWL(4289db40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/SmartSyncScreenOnOffTimeReceiver( 4363): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478616000
D/SmartSyncScreenOnOffTimeReceiver( 4363): SettingOffTime = 1454464800000, randomSettingOffTime = 1454471229000
D/SmartSyncScreenOnOffTimeReceiver( 4363): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4363): bNightModeTurnOffOnce = false
D/PMS     (  905): releaseWL(4289ece8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  905): acquireWL(42890800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42890800): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427a9298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1012011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427a9298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4297be68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4297be68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427dd780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1072011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427dd780): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(42820f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(42820f28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(4288daa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1132011, Int=0
,D/PMS     (  905): releaseWL(4288daa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(429723b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(429723b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  905): acquireWL(427c85f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1192011, Int=0
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  905): releaseWL(427c85f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(4282fcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(4282fcf8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  905): acquireWL(4291f168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 905 1000 WorkSource{1000}
,I/IntentController( 1114): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  905): sending alarm PendingIntent{41b92228: PendingIntentRecord{4215bbb0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1252011, Int=0
,D/PMS     (  905): releaseWL(4291f168): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  905): acquireWL(427e4960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  905): n_update end
,D/PMS     (  905): releaseWL(427e4960): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4434): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4434): ====startRecUseTime====
D/htc.customization.log.level( 4434):  is 
W/CustomizationLogLevel( 4434): Level value is invalid, use default level 2
D/CustomizationManager( 4434):  Read ACC file spent 0.132 (s)
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4434): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4434): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4434): Parsing tag category name = system
I/CustomizationCIDLoader( 4434): Parsing tag category name = application
I/CustomizationCIDLoader( 4434): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4434): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4434): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4434): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4434): Parsing tag category name = Settings
D/CustomizationManager( 4434):  Read CID file spent 0.188 (s)
D/CustomizationManager( 4434):  All configurations done spent 0.189 (s)
W/HtcNativeFlag( 4434): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4434): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4434): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4434): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  905): deletePackageAsUser: pkg=com.test.thalitest, pid=4434, uid=2000 user=0
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  905): Skipping PackageSetting{4226f418 com.example.hello/10397} due to missing metadata
W/PackageSettings(  905): Skipping PackageSetting{4227b040 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  905): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1114): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/DotMatrix( 1562): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1562): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  905): acquireWL(42a36640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1220 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42a36640): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
W/PackageManager(  905): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  905): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/VoicemailCleanupService( 1283): Cleaning up data for package: com.test.thalitest
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1341): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1341): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/IcingCorporaProvider( 2819): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  905): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4450 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1326): Unsupported attribute readOnly
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/IcingCorporaProvider( 2819): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4450): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4450): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4450): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4450): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4450): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4450): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4450): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4450): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4450): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4450): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4450): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4450): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4450): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4450): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4450): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4450): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4450): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4450): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4450): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4450): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4450): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4450): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4450): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4450): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4450): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4450): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4450): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4450): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4450): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4450): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4450): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4450): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4450): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4450): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4450): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4450): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4450): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4450): threadid=11: thread exiting with uncaught exception (group=0x4173ae30)
E/ActivityManager(  905): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4450): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4450): Process: com.google.android.apps.docs, PID: 4450
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
E/AndroidRuntime( 4450): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4450): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4450): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4450): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4450): 	at aho.run(AbstractDatabaseInstance.java:455)
E/SQLiteDatabase( 4450): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4450): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4450): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4450): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4450): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4450): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4450): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4450): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4450): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4450): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4450): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4450): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4450): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4450): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4450): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4450): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4450): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4450): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4450): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4450): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4450): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4450): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4450): Opened ClientFlag.db in read-only mode
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
D/Process ( 4450): killProcess, pid=4450
D/Process ( 4450): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  905): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4469 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  905): Recipient 4450
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.google.android.apps.docs (pid 4450) has died.
W/ContextImpl( 4469): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4483 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4469): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4469): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4469): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4469): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4469): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4469): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4469): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4469): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4469): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4469): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4469): threadid=10: thread exiting with uncaught exception (group=0x4173ae30)
E/ActivityManager(  905): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4469): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4469): Process: com.android.keychain, PID: 4469
E/AndroidRuntime( 4469): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4469): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4469): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4469): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4469): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4469): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4469): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4469): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4469): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4469): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  905): HtcErrorReportManager Begin---add error logs to dropbox
D/AppTag  ( 4483): getInstance(Context context)
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41bfdcb0 +
I/Prism.WidgetManager( 1271): onLoadItems() +
E/ErrorReport(  905): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  905): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454430862600.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  905): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  905): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  905): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  905): 	... 4 more
D/Process ( 4469): killProcess, pid=4469
D/Process ( 4469): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4483): getInstance(Context context)
D/AppTag  ( 4483): onCreate()
I/ActivityManager(  905): Recipient 4469
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Process com.android.keychain (pid 4469) has died.
W/ActivityManager(  905): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/PackageManager(  905): Unable to load service info ResolveInfo{42590fc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  905): acquireWL(4258e2f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4094 10160 null
D/PMS     (  905): releaseWL(4258e2f0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4121): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  905): killProcessQuiet, pid=3847
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3847:com.google.android.music:main/u0a154 (adj 15): empty #17
D/PackageBroadcastService( 2187): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2187): Clearing selected account for com.test.thalitest
I/ActivityManager(  905): Recipient 3847
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.music (pid 3847): Died!
D/ChimeraCfgMgr( 2187): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2187): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2187): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2187): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2187): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2187): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2187): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2187): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2187): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2187): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2187): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2187): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2187): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2187): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2187): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2187): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2187): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed

```
