#### Test 5563415007e42e9_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  908): Resuming delayed broadcast
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=1, flag=1, pid=2639, uid=10049, userID:0
I/ActivityManager(  908): Start proc com.htc.music:mediaplaybackservice for broadcast com.htc.music/.MediaButtonIntentReceiver: pid=2657 uid=10052 gids={50052, 3003, 5012, 1028, 1015, 3002, 3001, 2001, 1023}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.aurora, clsName=com.htc.aurora.download.DownloadReceiver, state=2, flag=1, pid=2639, uid=10049, userID:0
--------- beginning of /dev/log/main
D/Process (  908): killProcessQuiet, pid=2347
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2347:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2347
D/Process (  908): killProcessQuiet, pid=2363
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2363:com.qualcomm.privinit/1000 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2363
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/MediaFocusControl(  908):   Remote Control   registerMediaButtonIntent() for PendingIntent{4246ec60: PendingIntentRecord{42448288 com.htc.music broadcastIntent}}
D/DotMatrix( 1578): [EventService] onClientChange, clearing: true
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] onClientChange, currEventType: 26
D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
V/Avrcp   ( 1642): New genId = 1, clearing = 1
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 312
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative send RSSIChange intent, SameSignalLevelCount =2
D/Process (  908): killProcessQuiet, pid=2136
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.cronus.CronusReceiver: pid=2674 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
I/ActivityManager(  908): Killing 2136:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:23, mTXpacketCount:0, avgLinkspeed:62,mAvgTxRate54
D/WifiStateMachine(  908): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED 3 -> 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  908): Recipient 2136
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=2687 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  908): killProcessQuiet, pid=2422
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2422:com.htc.calendar/u0a13 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2422
D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1238): -- N1 =0
D/PhoneApp( 1238): -- N2 =0
D/PhoneApp( 1238): -- N3 =0
W/ContextImpl( 2687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
D/PowerUsageService( 2687): call getInstance()
W/ContextImpl( 2687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncServiceReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.htc.htcpowermanager/.smartsync.SmartSyncServiceReceiver
D/PowerUsageList:PowerUsageHelper( 2687): MY_DEBUG = false
D/SmartSyncUtils( 2687): getMobilePolicyEnabled, result = true
W/ContextImpl( 2687): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.startService:228 com.htc.htcpowermanager.smartsync.SmartSyncServiceService.onHandleIntent:75 android.app.IntentService$ServiceHandler.handleMessage:65 
V/AlarmManager(  908): sending alarm PendingIntent{42309958: PendingIntentRecord{426e9b70 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452527784271, Int=900000
I/ActivityManager(  908): Resuming delayed broadcast
W/ContextImpl( 2687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/ContextImpl( 2687): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/Process (  908): killProcessQuiet, pid=2453
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.BOOT_COMPLETED, data: null
I/ActivityManager(  908): Killing 2453:com.google.android.configupdater/u0a16 (adj 15): empty #17
I/WSP     ( 1339): [Receiver] EVENT - BOOT COMPLETED, is settings existed? true
D/AutoSetting( 1339): receiver - intent: android.intent.action.BOOT_COMPLETED
D/HtcAppUPService( 1339): CustomizationReceiver  receieve: android.intent.action.BOOT_COMPLETED
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 2453
D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.bootcomplete
D/AutoSetting( 1339): service - onStartCommand() boot completed, remove cache
D/AutoSetting( 1339): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1339): service - handleMessage() setting current location null
D/AutoSetting( 1339): service - handleMessage() removing cache
D/AutoSetting( 1339): service - AddressCache: clean up all cache
D/HtcAppUPService( 1339): HtcUPService onCreate()
D/HtcAppUPService( 1339): DatabaseHelper [DatabaseHelper constructor]
D/HtcAppUPService( 1339): PolicyStore [Init] Get cached policy bundle
D/HtcAppUPService( 1339): HtcUPService onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.upservice.action.BOOT_COMPLETED cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@41c15cf8
I/ActivityManager(  908): Start proc com.htc.video for broadcast com.htc.video/com.htc.videowidget.videoDMC.DLNAReceiver: pid=2711 uid=10057 gids={50057, 2001, 3002, 3003, 5012, 1028, 1015, 1023}
D/HtcAppUPService( 1339): HtcUPServicePreference Is policy store first run: false
D/HtcAppUPService( 1339): appid: tellhtc_client, category: usage_report, key: enable, value: 1, due date: -1, current time: 1452527784378, default value: null
D/HtcAppUPService( 1339): HtcUPServicePreference Upload schedule enable? false
W/dalvikvm( 1339): VFY: unable to resolve static field 680 (common_google_play_services_unknown_issue) in Lcom/google/android/gms/R$string;
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
E/GooglePlayServicesUtil( 1339): The Google Play services resources were not found. Check your project configuration to ensure that the resources are included.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  908): killProcessQuiet, pid=2483
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.lmw for broadcast com.htc.lmw/.StorageBroadcastReceiver: pid=2729 uid=10060 gids={50060, 1028, 1015, 3003, 5012, 1023}
I/ActivityManager(  908): Killing 2483:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MediaScannerReceiver( 2434): onReceive Intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.media/.MediaScannerReceiver (has extras) }
D/MediaProviderUtils( 2434): [scanEx]volume:internal,action:android.intent.action.BOOT_COMPLETED
W/LMW     ( 2729): [2742][ActionDeviceStorageHandler] onActionBootComplete++
D/MediaProviderUtils( 2434): [scanEx]volume:customize,action:android.intent.action.BOOT_COMPLETED
W/LMW     ( 2729): [2742][ActionDeviceStorageHandler] onActionBootComplete--
D/MediaProviderUtils( 2434): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
D/MediaProviderUtils( 2434): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
D/MediaProviderUtils( 2434): [scanEx]volume:external,action:android.intent.action.MEDIA_MOUNTED
I/ActivityManager(  908): Recipient 2483
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 1339): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
E/cutils-trace( 2699): Error opening trace file: No such file or directory (2)
W/dalvikvm( 1339): VFY: unable to resolve instance field 36
W/dalvikvm( 1339): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/JNIHelp ( 1339): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/FeatureList( 1339): feature
D/FeatureList( 1339): type
D/FeatureList( 1339): description
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key zz_hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Bundle  ( 1339): Key hdkapi_opensense expected Integer but value was a java.lang.String.  The default value 0 was returned.
W/Bundle  ( 1339): Attempt to cast generated internal exception:
W/Bundle  ( 1339): java.lang.ClassCastException: java.lang.String cannot be cast to java.lang.Integer
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:1000)
W/Bundle  ( 1339): 	at android.os.Bundle.getInt(Bundle.java:982)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
W/Bundle  ( 1339): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/Bundle  ( 1339): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Bundle  ( 1339): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Bundle  ( 1339): 	at android.os.Looper.loop(Looper.java:157)
W/Bundle  ( 1339): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MediaScannerServiceEx( 2434): [3] stop task - current task is null
D/MediaScannerServiceEx( 2434): [4] stop task - current task is null
D/MediaScannerServiceEx( 2434): [5] stop task - current task is null
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+internal
D/MtpReceiver( 2434): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2434): [MP][DEBUG][MtpReceiver] requestFullScanForMTP
D/MtpReceiver( 2434): [MP][DEBUG][MtpReceiver] requestFullScanForMTP dir = /storage/emulated/0
D/MtpReceiver( 2434): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2434): [MTP][handleMessage][startService]
D/PMS     (  908): acquireWL(41deb780): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2434 10021 null
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
I/ProviderInstaller( 1339): Installed default security provider GmsCore_OpenSSL
D/HtcAppUPService( 1339): HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.BOOT_COMPLETED
D/MtpReceiver( 2434): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MediaProvider( 2434): bindService() MTP Service Connection.
D/HtcAppUPService( 1339): HtcUPServiceHandler [##] send STOPSELF message, startId = 1, return true
I/ActivityManager(  908): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.transaction.MmsSystemEventReceiver: pid=2752 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
D/MtpReceiver( 2434): [MTP][handleMessage]-
D/HtcAppUPService( 1339): HtcUPServiceHandler call stopSelfResult() startId = 1, reurn true
D/HtcAppUPService( 1339): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@41c15cf8
D/CustomizationManager( 2699): ====startRecUseTime====
D/htc.customization.log.level( 2699):  is 
W/CustomizationLogLevel( 2699): Level value is invalid, use default level 2
D/MtpService( 2434): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpService( 2434): addStorageInternal without MtpServer
D/MtpService( 2434): [MTP][onCreate]-
D/MtpService( 2434): [MTP] startForeground
D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2434): updating state; isCurrentUser=true, mMtpLocked=false
D/MediaScannerServiceEx( 2434): getDefaultLocale =en_GB
I/RemoteViews( 1115): com.android.providers.media (false,0)
D/MediaScannerServiceEx( 2434): [scan]+internal,/system/media
D/MediaScanner( 2434): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
D/MtpDatabase( 2434): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  908): acquireWL(42703da0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2185 10029 null
D/MtpService( 2434): starting MTP server in MTP mode
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ad8f50 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MtpService( 2434): addStorageInternal 65537 /storage/emulated/0
I/RemoteViews.Performance( 1115): com.android.providers.media 1 14 1 10
I/RemoteViews( 1115): com.android.providers.media (false,0)
D/MtpService( 2434): [checkStorageState] Storage state - mounted
D/MtpService( 2434): [addStorageToMtpLocked] MtpAddStorage - /storage/emulated/0
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ae7460 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MessageFrequencyProvider( 2752): onCreate
I/RemoteViews.Performance( 1115): com.android.providers.media 1 13 1 15
V/GetPrviateResource( 2752): GetPrviateResource
V/GetPrviateResource( 2752): GetPrviateResource
I/iu.UploadsManager( 2185): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/CustomizationManager( 2699):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2699): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2699): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2699): Parsing tag category name = system
I/CustomizationCIDLoader( 2699): Parsing tag category name = application
I/CustomizationCIDLoader( 2699): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2699): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2699): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2699): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2699): Parsing tag category name = Settings
D/CustomizationManager( 2699):  Read CID file spent 0.114 (s)
D/CustomizationManager( 2699):  All configurations done spent 0.114 (s)
W/HtcNativeFlag( 2699): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2699): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2699): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2699): Fail to get flag for type 'language', use default value: -1
D/MessageCustFlag( 2752): sense_version=6.0
D/BTAccessoryUtil( 2752): createReceiver
D/BTAccessoryUtil( 2752): registerReceiver return intent = null
D/MessageCustFlag( 2752): sku_id=99
W/SystemReader( 2752): Cannot find message_ambs_application_id, use default value instead
D/Messaging( 2752): supportCMAS(SIE)/init? false/true
D/MmsConfig( 2752): networkCode: 
D/MessageCustFlag( 2752): sku_id=99
D/MmsConfig( 2752): SIE smsPri: null
D/MmsConfig( 2752): networkCode: 
D/HtcTelephonyCapability( 2752): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 2752): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 2752): getRATByHtcTelephonyCapability:1
W/SystemReader( 2752): Cannot find qct_8960_interface, use default value instead
V/MmsSystemEventReceiver( 2752): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/ExchangePolicystatus( 2752): onReceive()
D/ExchangePolicystatus( 2752): onReceive(): ACTION_BOOT_COMPLETED
D/MessageUtils( 2752): Text messaging allow status = allow
D/Messaging( 2752): EAS allow SMS !!!
D/ExchangePolicystatus( 2752): onReceive(): get [Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.htc.sense.mms/.PolicyReceiver (has extras) }]
D/Messaging( 2752): EAS allow SMS !!!
W/CpuWake (  908): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  908): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  908): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  908): acquireHCC(4270ab40): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 908 1000 null
I/ActivityManager(  908): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2699
D/PMS     (  908): acquireHCC(4270b088): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 908 1000 null
D/PMS     (  908): acquireWL(4270c140): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 2752 10065 null
I/Intent  (  908): @test_code: getHtcIntentFlag: 0 obj: 1114678792
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d15228
I/SocialFeedProvider( 1269): +onPause
D/PMS     (  908): acquireWL(4270db68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 908 1000 null
I/SocialFeedProvider( 1269): -onPause
D/MediaScanner( 2434):  prescan time: 128ms
D/MediaScanner( 2434):     scan time: 45ms
D/MediaScanner( 2434): postscan time: 0ms
D/MediaScanner( 2434):    total time: 173ms
D/MediaScanner( 2434): -----------------------------------------------------------------
D/MediaScanner( 2434): firstscan(media) time: 29ms
D/MediaScanner( 2434): secondscan(non-media) time: 10ms
D/MediaScanner( 2434):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Total]    File(Image+Video+Audio+Others) in database : 360
D/MediaScannerServiceEx( 2434): [scan]-
I/ActivityManager(  908): Start proc com.htc.reportagent for broadcast com.htc.reportagent/.receiver.PolicyReceiver: pid=2781 uid=10066 gids={50066, 3003, 5012, 1007, 1028, 1015}
D/Process (  908): killProcessQuiet, pid=2501
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2501:com.htc.fm/u0a24 (adj 15): empty #17
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
V/SmsReceiverService( 2752): onStart: #1, @1101985576
V/SmsReceiverService( 2752): action: android.intent.action.BOOT_COMPLETED
D/SmsReceiverService( 2752): isCbm: false
D/SmsReceiverService( 2752): isDiscard: false
D/SettingsManager( 2752): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a99070
I/ActivityManager(  908): Recipient 2501
V/SmsReceiverService( 2752): handleBootCompleted
I/ActivityManager(  908): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2796 uid=10397 gids={50397, 3003, 5012}
D/MediaProvider( 2434): [delete][39]
D/MediaProvider( 2434): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/PluginProvider( 1339): Begin Apply Batch
E/PluginProvider( 1339): conflict when insert feature, ignored
D/MediaProvider( 2434): [recoverParentNodes] - 0
D/MediaProvider( 2434): [update][17]
D/MediaScannerServiceEx( 2434): [scan] Recover Parent Node is finished!
D/TAG     ( 2434): mWakeLock.release() at scan()
D/PMS     (  908): releaseWL(41deb780): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+customize
D/PMS     (  908): acquireWL(42718b10): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2434 10021 null
I/TrimMemoryManager( 1269): [trimMemory] 20
I/iu.UploadsManager( 2185): End new media; added: 0, uploading: 0, time: 176 ms
D/PMS     (  908): releaseWL(42703da0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
I/ActivityManager(  908): Delay finish: com.htc.reportagent/.receiver.PolicyReceiver
D/MyReportAgent( 2781): ReportService [##] onCreate(), this = com.htc.reportagent.ReportService@41a9a930
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1238): sku_id=99
D/MyReportAgent( 2781): ReportService [##] onStartCommand(), flags = 0, startId = 1, intent = Intent { act=com.htc.reportagent.action.BOOT_COMPLETE cmp=com.htc.reportagent/.ReportService }, this = com.htc.reportagent.ReportService@41a9a930
D/MediaScannerServiceEx( 2434): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2434): [scan]+internal,/system/customize/resource
D/MediaScanner( 2434): =====scanDirectories===== volumeName = internal , scanAllFile = true , layer = -1
D/MyReportAgent( 2781): ReportServiceHandler.onHandleIntent() intent is com.htc.reportagent.action.BOOT_COMPLETE
D/SmsReceiverService( 2752): OutBoxSize = 0
D/SmsReceiverService( 2752): sendFirstQueuedMessage start: 0
D/MessageCustFlag( 2752): sku_id=99
V/WebViewChromiumFactoryProvider( 2796): Binding Chromium to main looper Looper (main, tid 1) {41a91360}
I/LibraryLoader( 2796): Expected native library version number "",actual native library version number ""
I/chromium( 2796): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
D/UPolicy ( 2781): IUserBehaviorLoggingService reference is gotten !
I/BrowserStartupController( 2796): Initializing chromium process, renderers=0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1238): sku_id=99
E/AudioManagerAndroid( 2796): BLUETOOTH permission is missing!
D/PMS     (  908): acquireWL(4271de70): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  908): acquireWL(4271e778): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  908): releaseWL(4271e778): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/SmsReceiverService( 2752): sendFirstQueuedMessage end cnt> 0
I/Adreno-EGL( 2796): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2796): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2796): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2796): Local Branch: 
I/Adreno-EGL( 2796): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2796): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2796):                  aa63bbd948f41d15fc72f585e
D/MyReportAgent( 2781): ReportServiceHandler on boot complete event 
D/SpaceBufferUtil( 2752): > createBufferFile()
D/SpaceBufferUtil( 2752): bufferFile: /data/data/com.htc.sense.mms/bufferFileForMms
D/SpaceBufferUtil( 2752): < createBufferFile()
W/chromium( 2796): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
V/MyReportAgent( 2781): ReportServiceHandler unregister the PowerConnected Listener
D/MediaScanner( 2434):  prescan time: 61ms
D/MediaScanner( 2434):     scan time: 19ms
D/MediaScanner( 2434): postscan time: 0ms
D/MediaScanner( 2434):    total time: 80ms
D/MediaScanner( 2434): -----------------------------------------------------------------
D/MediaScanner( 2434): firstscan(media) time: 9ms
D/MediaScanner( 2434): secondscan(non-media) time: 10ms
D/MediaScanner( 2434):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Total]    File(Image+Video+Audio+Others) in database : 360
D/MediaScannerServiceEx( 2434): [scan]-
W/dalvikvm( 2796): VFY: unable to resolve virtual method 145: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2796): VFY: unable to resolve virtual method 140: Landroid/webkit/CookieManager;.flush ()V
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.reportagent, clsName=com.htc.reportagent.receiver.PowerConnectedReceiver, state=2, flag=1, pid=2781, uid=10066, userID:0
D/MediaProvider( 2434): [delete][6]
D/MediaProvider( 2434): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
W/dalvikvm( 2796): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2796): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2796): VFY: unable to resolve virtual method 198: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/MediaProvider( 2434): [recoverParentNodes] - 0
D/MediaProvider( 2434): [update][3]
D/MediaScannerServiceEx( 2434): [scan] Recover Parent Node is finished!
W/dalvikvm( 2796): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2796): VFY: unable to resolve virtual method 156: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2796): VFY: unable to resolve virtual method 161: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/TAG     ( 2434): mWakeLock.release() at scan()
D/SystemWebViewEngine( 2796): CordovaWebView is running on device made by: HTC
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2434): ignoreDirectories[ 0 ] = /storage/ext_sd
D/MediaScannerServiceEx( 2434): ignoreDirectories[ 1 ] = /storage/usb
D/PMS     (  908): releaseWL(42718b10): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
D/MediaScannerServiceEx( 2434): [AliveExtStorageRows]+65537, 11223344
D/MediaProvider( 2434): [update][8]#0#
D/MediaProvider( 2434): [update][5]#0#
D/MediaProvider( 2434): [update][7]#0#
,D/MediaScannerServiceEx( 2434): [deleteRowsEqualVolid]+65537
D/MediaProvider( 2434): [delete][6]#0#
D/MediaScannerServiceEx( 2434): [deleteRowsEqualVolid]-0
D/MediaProvider( 2434): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
D/MtpService( 2434): [sendStorageAdded] Already send to MTP: /storage/emulated/0
D/MediaProvider( 2434): [update][20]#1#
D/MediaScannerServiceEx( 2434): [AliveExtStorageRows]-0, 0, 0
D/MediaScannerServiceEx( 2434): [deleteNonUseAlbumArts]+
D/MediaScannerServiceEx( 2434): [deleteNonUseAlbumArts]-
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@41c7d690
E/MediaProvider( 2434): no database for attached volume content://media/external
D/PMS     (  908): acquireWL(42312e40): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2434 10021 null
W/AwContents( 2796): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  908): Disable input method client, pid=1269
W/ResourceType( 2796): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2796): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ad5d10, mServedView=org.apache.cordova.engine.SystemWebView{41a9dfb0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 2796): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  908): Displayed com.example.hello/.MainActivity: +283ms
I/InputMethodManagerService(  908): Enable input method client, pid=2796
D/PMS     (  908): releaseWL(4270db68): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/MediaScannerServiceEx( 2434): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2434): [scan]+external,/storage/emulated/0
D/MediaScanner( 2434): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2434): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2434): Ignore scan directories /storage/usb
D/MediaScanner( 2434): Ignore scan directories null
E/AndroidProtocolHandler( 2796): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 2796): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 2796): Set native->JS mode to OnlineEventsBridgeMode
,D/PluginProvider( 1339): apply Batch success
,I/[PluginManager]RegisterService( 1339): Notify Carousel that a new TabPlugin has been installed!
,D/MediaScanner( 2434):  prescan time: 385ms
D/MediaScanner( 2434):     scan time: 388ms
D/MediaScanner( 2434): postscan time: 2ms
D/MediaScanner( 2434):    total time: 775ms
D/MediaScanner( 2434): -----------------------------------------------------------------
D/MediaScanner( 2434): firstscan(media) time: 286ms
D/MediaScanner( 2434): secondscan(non-media) time: 102ms
D/MediaScanner( 2434):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Total]    File(Image+Video+Audio+Others) in database : 1411
,D/MediaScannerServiceEx( 2434): [scan]-
,D/MediaProvider( 2434): [delete][8]
,D/MediaProvider( 2434): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2434): [recoverParentNodes] - 0
D/MediaProvider( 2434): [update][4]
D/MediaScannerServiceEx( 2434): [scan] Recover Parent Node is finished!
,D/MediaScannerServiceEx( 2434): [updateImage]+
,D/MediaScannerServiceEx( 2434): [updateImage]-0
,D/TAG     ( 2434): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2434): [3] scan finished
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 1, path: /storage/ext_sd
D/MediaScannerServiceEx( 2434): ignoreDirectories[ 0 ] = /storage/emulated/0
,D/MediaScannerServiceEx( 2434): ignoreDirectories[ 1 ] = /storage/usb
,E/MediaScannerServiceEx( 2434): Process mounted intent for unmounted storage/storage/ext_sd
,D/MediaScannerServiceEx( 2434): [disAliveExtStorageRows]+131073
D/PMS     (  908): releaseWL(42312e40): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,D/MediaProvider( 2434): [sendStorageAddedIfNeed]: /storage/ext_sd : unmounted
,D/MediaProvider( 2434): [update][5]#1#
,D/MediaProvider( 2434): [update][4]#0#
D/MediaScannerServiceEx( 2434): [disAliveExtStorageRows]--1
,D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,null
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 2, path: /storage/usb
D/MediaScannerServiceEx( 2434): ignoreDirectories[ 0 ] = /storage/emulated/0
,D/MediaScannerServiceEx( 2434): ignoreDirectories[ 1 ] = /storage/ext_sd
,E/MediaScannerServiceEx( 2434): Process mounted intent for unmounted storage/storage/usb
,D/MediaScannerServiceEx( 2434): [disAliveExtStorageRows]+196609
,D/MediaProvider( 2434): [sendStorageAddedIfNeed]: /storage/usb : unmounted
,D/MediaProvider( 2434): [update][3]#1#
,D/MediaProvider( 2434): [update][4]#0#
D/MediaScannerServiceEx( 2434): [disAliveExtStorageRows]--1
,D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,null
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage]+external
D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage] volume: external, action: android.intent.action.MEDIA_MOUNTED, Id: 0, path: /storage/emulated/0
D/MediaScannerServiceEx( 2434): ignoreDirectories[ 0 ] = /storage/ext_sd
,D/MediaScannerServiceEx( 2434): ignoreDirectories[ 1 ] = /storage/usb
,D/MediaScannerServiceEx( 2434): [AliveExtStorageRows]+65537, 11223344
,D/MediaProvider( 2434): [update][6]#0#
,D/MediaProvider( 2434): [update][5]#0#
,D/MediaProvider( 2434): [update][6]#0#
,D/MediaScannerServiceEx( 2434): [deleteRowsEqualVolid]+65537
,D/MediaProvider( 2434): [delete][6]#0#
,D/MediaScannerServiceEx( 2434): [deleteRowsEqualVolid]-0
,D/MediaProvider( 2434): [sendStorageAddedIfNeed]: /storage/emulated/0 : mounted
,D/MtpService( 2434): [sendStorageAdded] Already send to MTP: /storage/emulated/0
,D/MediaProvider( 2434): [update][6]#1#
D/MediaScannerServiceEx( 2434): [AliveExtStorageRows]-0, 0, 0
,D/MediaScannerServiceEx( 2434): [deleteNonUseAlbumArts]+
D/MediaScannerServiceEx( 2434): [deleteNonUseAlbumArts]-
,D/MediaScannerServiceEx( 2434): [ServiceHandler][handleMessage][EXTERNAL]-android.intent.action.MEDIA_MOUNTED,[Ljava.lang.String;@41e705b8
,E/MediaProvider( 2434): no database for attached volume content://media/external
D/PMS     (  908): acquireWL(42795640): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 2434 10021 null
,D/MediaScannerServiceEx( 2434): getDefaultLocale =en_GB
D/MediaScannerServiceEx( 2434): [scan]+external,/storage/emulated/0
D/MediaScanner( 2434): =====scanDirectories===== volumeName = external , scanAllFile = true , layer = -1
D/MediaScanner( 2434): Ignore scan directories /storage/ext_sd
D/MediaScanner( 2434): Ignore scan directories /storage/usb
,D/MediaScanner( 2434): Ignore scan directories null
,D/MediaScanner( 2434):  prescan time: 84ms
D/MediaScanner( 2434):     scan time: 417ms
D/MediaScanner( 2434): postscan time: 2ms
D/MediaScanner( 2434):    total time: 503ms
D/MediaScanner( 2434): -----------------------------------------------------------------
D/MediaScanner( 2434): firstscan(media) time: 300ms
D/MediaScanner( 2434): secondscan(non-media) time: 117ms
D/MediaScanner( 2434):  [Update]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Insert]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Delete]   Image: 0 Video: 0 Audio: 0 Other: 0
D/MediaScanner( 2434):  [Total]    File(Image+Video+Audio+Others) in database : 1411
,D/MediaScannerServiceEx( 2434): [scan]-
,D/MediaProvider( 2434): [delete][7]
,D/MediaProvider( 2434): [recoverParentNodes] + parent != 0 and parent not in (SELECT DISTINCT _id from files where format = 12289)
D/MediaProvider( 2434): [recoverParentNodes] - 0
D/MediaProvider( 2434): [update][4]
D/MediaScannerServiceEx( 2434): [scan] Recover Parent Node is finished!
,D/MediaScannerServiceEx( 2434): [updateImage]+
,D/MediaScannerServiceEx( 2434): [updateImage]-0
,D/TAG     ( 2434): mWakeLock.release() at scan()
,D/MediaScannerServiceEx( 2434): [6] scan finished
D/PMS     (  908): releaseWL(42795640): PARTIAL_WAKE_LOCK  MediaScannerService 0x1 null
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 1 times.
,D/Messaging( 2752): mNeedToUpdateDate2 start
,D/MmsConfig( 2752): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 2752): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 2752): 
D/MmsAsyncWorkHandler( 2752): HM tk = 20001
,D/ReportIndicatorCache( 2752): MSG_QUERY_REPORTS >>
,I/Messaging( 2752): mccmnc> 
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/DraftCache( 2752): [DraftCache/1] DraftCache.constructor
D/DraftCache( 2752): [DraftCache/1] refresh
,D/MmsConfig( 2752): networkCode: 
,D/Messaging( 2752): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1238): sku_id=99
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 2752): [DraftCache/223] rebuildCache
D/PhoneStorageUtil( 2752): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 2752): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 2752): createReceiver
D/Messaging( 2752): mNeedToUpdateDate2: false
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MessageCustFlag( 2752): sense_version=6.0
,D/Jerry   ( 2752): start to preload cursor >>>>>>>
,D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
W/CpuWake (  908): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  908): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  908): >>release mCpuPerf_Freq wakelock
W/CpuWake (  908): <<release mCpuPerf_Freq wakelock
D/PMS     (  908): releaseHCC(4270ab40): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  908): releaseHCC(4270b088): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
D/Messaging( 2752): Reset downloading state: 0
V/MmsSystemEventReceiver( 2752): TransactionService is going to be woken up.
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/Jerry   ( 1238): URI_DRAFT
V/TransactionService( 2752): 1-Creating TransactionService
V/TransactionService( 2752): onStartCommand: 1
D/MmsSystemEventReceiver( 2752): unRegisterForConnectionStateChanges
V/TransactionService( 2752): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 2752): Loading previous transactions.
D/DraftCache( 2752): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 2752): [DraftCache/223] rebuildCache time: 2
D/MmsAsyncWorkHandler( 2752): 
D/MmsAsyncWorkHandler( 2752): HM tk = 20002
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/AccFlag ( 1238): device_type: 1
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/TransactionService( 2752): Force set service start id to 1
V/TransactionService( 2752): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 2752): unRegisterForConnectionStateChanges
D/TransactionService( 2752): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 2752): Destroying TransactionService
D/DotMatrix( 1700): [CoverService] onDestroy, version: 1.3
V/TransactionService( 2752): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/SensorManager( 1700): unregisterListenerImpl++: listener = com.htc.dotmatrix.CoverService$7@41aaa9a8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/Messaging( 2752): ViewCache CreatePreload
D/Messaging( 2752): ViewCache CreatePreloadOnlyMultipleOpsList
W/SensorService(  908): pid=1700, uid=10046
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.dotmatrix.CoverService$7@41aaa9a8, eanble = 0, strlen(mName) = 41
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@420e0360
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/DotMatrix( 1700): [CoverService] unregisterCallContentObserver()
D/Cust_MMSMS( 2752): _has_set_default_values_2=true
D/Process (  908): killProcessQuiet, pid=1700
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Messaging( 2752): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1238): sku_id=99
,I/ActivityManager(  908): Killing 1700:com.htc.dotmatrix/u0a46 (adj 15): empty #17
D/MsgPreferenceUtils( 2752): def_index: 0
D/MsgPreferenceUtils( 2752): globalIndex = 1
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
D/MsgPreferenceUtils( 2752): phone state: true
D/MsgPreferenceUtils( 2752): sd state: false
,D/MsgPreferenceUtils( 2752): vIndex = 0
I/ActivityManager(  908): Recipient 1700
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  908): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
D/ConnectivityService(  908): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/AlarmManager(  908): sending alarm PendingIntent{425d5c50: PendingIntentRecord{4264e8d0 com.android.providers.calendar broadcastIntent}}, i=com.android.providers.calendar.intent.CalendarProvider2, t=2, cnt=1, w=34917, Int=0
,D/PMS     (  908): releaseWL(4271de70): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,V/SmsReceiverService( 2752): updateNotificationAndShortcutStatus: 
,D/MessagingNotification( 2752): New incoming message, can't cancel notification now
,D/MessagingNotification( 2752): newMsgCnt: 0, false
,I/ActivityManager(  908): Resuming delayed broadcast
,D/HtcBroadcastReceiver( 1238): onReceive: android.intent.action.BOOT_COMPLETED
,D/Process (  908): killProcessQuiet, pid=2515
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2515:com.htc.HTCSpeaker/u0a26 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2515
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=2870 uid=10078 gids={50078}
,D/PMS     (  908): releaseWL(4270c140): PARTIAL_WAKE_LOCK  StartingAlertService_0 0x1 null
,D/SMSBackup( 2870): Got ACTION_BOOT_COMPLETED event
,D/SMSBackup( 2870): setCheckAlarm
,D/SMSBackup( 2870): Next check is scheduled at 60s from now
,D/Process (  908): killProcessQuiet, pid=2528
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 2528:com.google.android.onetimeinitializer/u0a31 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2528
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.stk, clsName=com.android.stk.StkLauncherActivity, state=2, flag=1, pid=1238, uid=1001, userID:0
,I/ActivityManager(  908): Start proc com.htc.showme for broadcast com.htc.showme/.sync.BootCompletedReceiver: pid=2882 uid=10083 gids={50083, 3003, 5012, 1028, 1015}
,I/[AppShowMeDebug]BootCompletedReceiver( 2882): received boot complete
,I/[AppShowMeDebug]BootCompletedReceiver( 2882): push flag is false, skip check
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=2897 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  908): killProcessQuiet, pid=2542,
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2542:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2542
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.htc.updater/.UpdaterBootCompleteReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=2911 uid=10086 gids={50086, 3003, 5012, 3001, 1028, 3002, 1015}
,D/Process (  908): killProcessQuiet, pid=2569
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2569:com.htc.csrecommend/u0a36 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2569
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=2926 uid=10032 gids={50032, 3003, 5012}
D/LocationManagerService(  908): getProviders()=[passive]
,I/ContactAccountLoggerTas( 2911): canRun() : Opted Out
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.googlequicksearchbox, clsName=com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$ApplicationLaunchReceiver, state=1, flag=1, pid=2911, uid=10086, userID:0
,I/Velvet.VelvetFactory( 2911): refreshing search history.
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver
,W/GAV2    ( 2911): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 2911): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 2911): canRun() : Opted Out
,W/dalvikvm( 2911): method Lcom/google/android/search/core/state/QueryState;.a incorrectly overrides package-private method with same name in Lcfl;
,D/WifiService(  908): New client listening to asynchronous messages
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.googlequicksearchbox (pid 2911): Registered
,I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/MediaRouter( 2911): Found default route: MediaRouter.RouteInfo{ uniqueId=android/kb:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.googlequicksearchbox (2911/10086)
,D/libc    ( 2911): [NET] getaddrinfo+,hn 13(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 2911): [NET] getaddrinfo-,err=8
D/libc    ( 2911): [NET] getaddrinfo+,hn 13(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2911): [NET] getaddrinfo-, 1
D/libc    ( 2911): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 13(0x7777772e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =d967 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/Process (  908): killProcessQuiet, pid=2581
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/MediaRouter( 2911): getSelectedRoute
I/ActivityManager(  908): Killing 2581:com.htc.home.personalize/1000 (adj 15): empty #17
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 156
D/libc    (  363): [NET]res_nsend:resplen=47
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2911): [NET] getaddrinfo_proxy-, success
,I/ActivityManager(  908): Recipient 2581
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1508): handler message = 4009
,I/HtcModeClient( 1508): start to setup the connection
,D/libc    ( 2911): [NET] getaddrinfo+,hn 13(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 2911): [NET] getaddrinfo-,err=8
,I/ContactAccountLoggerTas( 2911): canRun() : Opted Out
,D/MyReportAgent( 2781): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@41a9a930
,D/Process (  908): killProcessQuiet, pid=2596
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 2596:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  908): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=2965 uid=10090 gids={50090, 3003, 5012, 1028}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=5 [18][1][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/ActivityManager(  908): Recipient 2596
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
,I/WorldClock.Global( 2965): isHtcDevice = true
D/PMS     (  908): acquireWL(42590138): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 2965 10090 null
,W/WorldClock.AlarmService( 2965): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
,I/WorldClock.AlarmUtils( 2965): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 2965): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 2965): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1115): receive(android.intent.action.ALARM_CHANGED,1,false)
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(42590138): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
,I/ActivityManager(  908): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/WorldClock.Global( 2965): isHtcDevice = true
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=2985 uid=10091 gids={50091, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=2613
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2613:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2613
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/OmaCPPushReceiverV2( 2985): initialCheck: sku=99, result=false
,D/Process (  908): killProcessQuiet, pid=2625
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=2997 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  908): Killing 2625:com.htc.aurora/u0a49 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2625
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3012 uid=10098 gids={50098, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=2639
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2639:com.htc.aurora:remote/u0a49 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2639
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3012): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3012 dbg=false s=true
,I/DeviceManagement( 3012): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
,I/DeviceManagement( 3012): WorkflowService: Starting workflow service
,I/ActivityManager(  908): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 3012): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41abc670] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3012): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3012): BootCompletedWorkflow: Boot completed
I/DeviceManagement( 3012): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3012): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3012): BackgroundController: *** Update after boot...
,I/DeviceManagement( 3012): SessionStateController: Checking invariants...
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/DeviceManagement( 3012): BackgroundController: Invariants are unchanged.
,I/DeviceManagement( 3012): SessionStateController: Checking invariants...
,V/AlarmManager(  908): sending alarm PendingIntent{4234a1d0: PendingIntentRecord{424eec98 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20673, Int=1800000
,V/AlarmManager(  908): sending alarm PendingIntent{424587d8: PendingIntentRecord{42525418 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=37959, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{4239f110: PendingIntentRecord{424ec538 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1452510000000, Int=86400000
,D/Process (  908): killProcessQuiet, pid=2657
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2657:com.htc.music:mediaplaybackservice/u0a52 (adj 15): empty #17
,I/DeviceManagement( 3012): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2657
,I/DeviceManagement( 3012): Perf: *** Cache update - start...
,I/DeviceManagement( 3012): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3012): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3012): EnabledAppController: Enabled app scan is pending...
,I/DeviceManagement( 3012): Perf: Scan enabled apps - start...
,I/DeviceManagement( 3012): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
,I/SensorManager(  908): mEventCount = 150
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
,I/DeviceManagement( 3012): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
,I/DeviceManagement( 3012): EnabledAppBuilder: Found 9 DM enabled apps.
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
,I/DeviceManagement( 3012): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
,I/DeviceManagement( 3012): Perf: Scan enabled apps - complete: 735 ms
I/DeviceManagement( 3012): Perf: *** Enabled app cache update - complete: 736 ms
,I/DeviceManagement( 3012): Perf: *** Config cache update - start...
I/DeviceManagement( 3012): ConfigCacheController: *** Updating config cache...
,I/DeviceManagement( 3012): ConfigCacheController: *** Updating stale config cache entries...
I/DeviceManagement( 3012): ConfigCacheController: *** Update config cache: updating 0 entries...
,I/DeviceManagement( 3012): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3012): AlarmController: Scheduling TTL alarm for: 2016.01.11 at 17:04:19.664 CET (due to: com.htc.reportagent)
,I/DeviceManagement( 3012): Perf: *** Config cache update - complete: 15 ms
,I/DeviceManagement( 3012): Perf: *** Cache update - complete: 754 ms
,I/DeviceManagement( 3012): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@41abc670]
,I/DeviceManagement( 3012): WorkflowService: Stopping workflow service
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3012, uid=10098, userID:0
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3031 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
D/Process (  908): killProcessQuiet, pid=2674
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2674:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2674
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 2 times.
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/PMS     (  908): acquireWL(42594c90): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42594c90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3031): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/PMS     (  908): acquireWL(4255e488): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=3031, uid=10107, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=3031, uid=10107, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=3031, uid=10107, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=3031, uid=10107, userID:0
,I/Icing   ( 2185): Storage manager: low false usage 2.14MB avail 8.75GB capacity 9.23GB
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,I/Gmail   ( 3031): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3031): calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,I/Gmail   ( 3031): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3031): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Icing   ( 2185): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 2185): Internal init done: storage state 0
,I/Icing   ( 2185): Post-init done
,D/PMS     (  908): releaseWL(4255e488): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=3031, uid=10107, userID:0
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3068 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=2687
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2687:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2687
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/htcbackup-core( 3068): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3068): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3068): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3012): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3012): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.autobot.cargps.provider, com.htc.smartdim, com.htc.android.htcsetupwizard, com.htc.android.htcloglevel, com.android.providers.settings, com.qualcomm.privinit, com.android.settings, com.android.location.fused, com.qualcomm.timeservice, com.htc.feedback, com.htc.home.personalize, com.android.inputdevices, com.android.keychain, com.htc.drive.activator, com.htc.checkinprovider, com.htc.lockscreen, com.htc.cirmodule, com.htc.usage, com.android.CSDFunctionG, com.htc.htcpowermanager, com.htc.backup, android, com.htc.guide, com.htc.backupreset, com.htc.mirrorlinkserver]
,I/DeviceManagement( 3012): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 3012): WorkflowService: Starting workflow service
I/DeviceManagement( 3012): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41dbd940] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3012): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3012): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3012): SessionStateController: Checking invariants...
,W/ContextImpl( 3068): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b15608 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,I/RemoteViews.Performance( 1115): com.htc.backup 2 8 5 15
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b1e950 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
I/DeviceManagement( 3012): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/DeviceManagement( 3012): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41dbd940]
,I/DeviceManagement( 3012): WorkflowService: Stopping workflow service
,I/RemoteViews.Performance( 1115): com.htc.backup 1 4 6 4
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 0 1 1 4
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 0 1 1 4
,I/RemoteViews.Performance( 1115): com.htc.backup 1 9 21 21
,I/htcbackup-core( 3068): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3091 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,V/AlarmManager(  908): sending alarm PendingIntent{42431d90: PendingIntentRecord{4243a500 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=20, w=1440901414353, Int=604800000
,W/dalvikvm( 3068): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 3 4 15
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 1 2 0 4
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 1 2 0 4
,I/RemoteViews( 1115): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1115): com.htc.backup 1 1 1 4
,I/RemoteViews.Performance( 1115): com.htc.backup 2 13 21
,D/UPolicy ( 3068): IUserBehaviorLoggingService reference is gotten !
,D/Process (  908): killProcessQuiet, pid=2711
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 2711:com.htc.video/u0a57 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2711
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 3091): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3091): MmsConfig.loadMmsSettings
,W/dalvikvm( 3091): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3091): VFY: unable to resolve instance field 36
,W/dalvikvm( 3091): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3091): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GAV2    ( 2911): Thread[GAThread,5,main]: No campaign data found.
,D/MmsCustomizationProvider( 2752): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2752): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3091): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3091): MmsConfig.loadFromDatabase
,I/GAv4-SVC( 2185): Google Analytics 8.4.89 is starting up.
,E/Babel   ( 3091): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3091): MmsConfig.loadFromResources
,E/Babel   ( 3091): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3091): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3091, uid=10111, userID:0
,W/Settings( 3091): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3091, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3091, uid=10111, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3091, uid=10111, userID:0
,V/Babel   ( 3091): babel boot account: thalitester@gmail.com
,V/Babel   ( 3091): babel boot account: SMS
,I/ActivityManager(  908): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3123 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ProviderInstaller( 3091): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  908): sending alarm PendingIntent{42795dc8: PendingIntentRecord{428d7848 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=40873, Int=0
,V/AlarmManager(  908): sending alarm PendingIntent{424e4850: PendingIntentRecord{42576f20 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=40877, Int=0
,D/Process (  908): killProcessQuiet, pid=2729
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3140 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  908): Killing 2729:com.htc.lmw/u0a60 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2729
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Delay finish: com.htc.htccupd/.HtcCupdReceiver
,I/HtcCupdXmlParser( 3140): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
D/ActivityThread( 3140): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/HtcCupdXmlParser( 3140): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
,I/AlarmManager(  908): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
,I/AlarmManager(  908): [AlarmQueuing] post alarm-list load task
,I/AlarmManager(  908): [AlarmQueuing] init alarm queuing list
,I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3154 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=2781
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 2781:com.htc.reportagent/u0a66 (adj 15): empty #17
D/ResetNotifyBootCompleteReceiver( 1238): Receive bootcomplete intent
W/ContextImpl( 1238): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/ActivityManager(  908): Recipient 2781
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@426f7da0
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.htc.aurora
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@426d4b60
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/AlarmManager(  908): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42624f48
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  908): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  908): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  908): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3167 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/AppTag  ( 3167): getInstance(Context context)
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/AppTag  ( 3167): getInstance(Context context)
D/AppTag  ( 3167): onCreate()
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/Process (  908): killProcessQuiet, pid=2870
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/QXDM2SD:HtcNative( 1238): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
I/ActivityManager(  908): Killing 2870:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
I/ActivityManager(  908): Recipient 2870
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3181 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/PackageManager(  908): Unable to load service info ResolveInfo{425d8100 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
,V/Settings:HtcSettingsApplication( 3181): [3181/3181] onCreate()
W/ContextImpl( 3181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  908): start
,D/Process (  908): killProcessQuiet, pid=2882
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  908): Killing 2882:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3194 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  908): Killing 2897:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  908): killProcessQuiet, pid=2897
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 2882
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2897
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  908): sending alarm PendingIntent{425d1e98: PendingIntentRecord{4263ff40 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=40724, Int=259200000
,V/AlarmManager(  908): sending alarm PendingIntent{41fedfb8: PendingIntentRecord{42703488 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452527794628, Int=0
,D/HtcFingerPrintQuickLaunchProvider( 3194): -onCreate()
,V/Settings:HtcSettingsApplication( 3194): [3194/3194] onCreate()
W/ContextImpl( 3194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/TetherSettings( 3194): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3194): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3194): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3194): Cust_ConnectToPC   : spcsc>false
D/        ( 3194): Cust_ConnectToPC   : IPT>true
,D/        ( 3194): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3194): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/iu.UploadsManager( 2185): End new media; added: 0, uploading: 0, time: 61 ms
D/TetherSettings( 3194): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3194): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3194): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3194): Cust_ConnectToPC   : spcsc>false
D/        ( 3194): Cust_ConnectToPC   : IPT>true
D/        ( 3194): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3194): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3194): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3194): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3194): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 3194): setISNotification
,D/SmartNS_Utility( 3194): usb_cable_connect = 1
,D/SmartNS_Utility( 3194): usb_denied = 0
,I/SmartNS_PSService( 3194): usb notificaiton:true
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3194): usb_cable_connect = 1
D/SmartNS_Utility( 3194): usb_denied = 0
,I/SmartNS_PSService( 3194): usb notificaiton:true
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3194/1000)
D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  908): bSetPropertyMultiRAB:false
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3194/1000)
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/Process (  908): killProcessQuiet, pid=2926
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 2926:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/RemoteViews( 1115): com.android.settings (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41aee558 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  908): Recipient 2926
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews.Performance( 1115): com.android.settings 2 8 0 10
I/RemoteViews( 1115): com.android.settings (true,33751552)
,I/ActivityManager(  908): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3210 uid=9987 gids={49987}
I/RemoteViews.Performance( 1115): com.android.settings 1 0 10
,I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4228cdf8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4228cdf8, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@420e0360
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@4228cdf8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  908): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@4228cdf8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{423e9158 u0 ReceiverList{42388b78 908 system/1000/u0 local:41da20f8}}
,D/NfcUiccLockService( 3210): -- To check whether previous opened channel needed to be closed ...
,D/Process (  908): killProcessQuiet, pid=2965
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3224 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  908): Killing 2965:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2965
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 3
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4228cdf8, eanble = 1, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10
W/SensorService(  908): Listener[1] = com.android.server.power.DisplayPowerController$10@420e0360
W/SensorService(  908): Listener[2] = com.htc.smartdim.sensor_eye@4228cdf8
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  908): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3236 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2985
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2985:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 2985
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 3236): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 3236): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 3236): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 3236): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3236/10168)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3236): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/YouTube ( 3236): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3236): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/YouTube ( 3236): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b21bd0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,D/YouTube ( 3236): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.youtube (pid 3236): Registered
,I/MediaRouter( 3236): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/YouTube ( 3236): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.google.android.youtube (3236/10168)
I/GoogleConversionPing( 3236): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1452527795&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/libc    ( 3236): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3236): [NET] getaddrinfo-,err=8
D/libc    ( 3236): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3236): [NET] getaddrinfo-, 1
D/libc    ( 3236): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8c31 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/YouTube ( 3236): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3236): [NET] getaddrinfo_proxy-, success
,D/YouTube ( 3236): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3236): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3236): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3236): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3236): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  908): Delay finish: com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver
,D/MediaRouter( 3236): getSelectedRoute
,D/YouTube ( 3236): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
,D/YouTube ( 3236): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
,D/YouTube ( 3236): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3236/10168)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3236/10168)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.youtube (3236/10168)
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3286 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=2997
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 2997:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2997
,I/GoogleConversionPing( 3236): Ping responded with response code 200
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b21bd0 -
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3286, uid=10074, userID:0
,D/Finsky  ( 3286): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3286/10074)
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3286/10074)
,D/Finsky  ( 3286): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3286): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3286): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3286, uid=10074, userID:0
,D/Volley  ( 3286): [307] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3286): [300] DiskBasedCache.clear: Cache cleared.
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
D/Ads     ( 3286): Skipping gmscore version check
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [5][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/Process (  908): killProcessQuiet, pid=2210
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/WifiNative-wlan0(  908):    returned true
I/ActivityManager(  908): Killing 2210:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,I/ActivityManager(  908): Delaying start of: ServiceRecord{42627418 u0 com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService}
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 2210
D/Finsky  ( 3286): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3286): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3286): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  908): Delaying start of: ServiceRecord{42791c90 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
,D/PhoneApp( 1238): -- N2 =0
,D/PhoneApp( 1238): -- N3 =0
,W/dalvikvm( 2185): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2185): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2185): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2185): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/FileApkUtils( 2185): Spent 19ms computing apk sha1.
,D/FileApkUtils( 2185): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/DexOptUtils( 2185): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2185): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 2185): Reading stored module config
,D/GmsModuleFndr( 2185): Beginning GMS chimera module scan
,W/asset   ( 2185): Copying FileAsset 0x66548f88 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
,D/ChimeraCfgMgr( 2185): Beginning module configuration check
,D/ChimeraCfgMgr( 2185): Module APKs unchanged, check complete
,D/Finsky  ( 3286): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42626590): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2185 10029 null
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,D/PMS     (  908): acquireWL(4278c738): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42626590): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
,D/PMS     (  908): releaseWL(4278c738): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,W/InstanceID/Rpc( 2185): Found 10029
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{428d95d8 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
,E/dalvikvm( 2185): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 2185): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2185): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2185): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2185): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2185): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
W/dalvikvm( 2185): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2185): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,E/dalvikvm( 1221): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1221): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1221): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1221): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
E/dalvikvm( 2185): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 2185): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
W/dalvikvm( 1221): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1221): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
W/dalvikvm( 1221): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1221): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(423efcb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,E/dalvikvm( 2185): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 2185): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 2185): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  908): acquireWL(427afcf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42708bd8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(423efcb0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42611a18): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 2185): COMPAT: Multi user not supported
,D/GCM     ( 1369): COMPAT: Multi user not supported
,I/CheckinService( 2185): Checkin interval check for package: unspecified last checkin: 1452525949258 min interval config: 0 actual interval: 1847449
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,I/GCoreUlr( 2185): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 2185): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 1221): DispatchingService.onCreate()
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/PMS     (  908): acquireWL(426a63c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2185): onCreate
D/PMS     (  908): releaseWL(427afcf8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/SystemUpdateService( 2185): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2185, uid=10029, userID:0
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 3 times.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
,V/AuthZen ( 2185): Handling intent: android.intent.action.BOOT_COMPLETED
,W/dalvikvm( 1369): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1369): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1369): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
D/PMS     (  908): acquireWL(42698e18): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2185, uid=10029, userID:0
D/PMS     (  908): acquireWL(425db8d8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2185, uid=10029, userID:0
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/SystemUpdateService( 2185): cancelUpdate (empty URL)
,I/SystemUpdateService( 2185): active receiver: disabled
,W/dalvikvm( 1369): VFY: unable to resolve instance field 161
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2185, uid=10029, userID:0
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/AuthZenEventHandler( 2185): Handling event: android.intent.action.BOOT_COMPLETED,
D/PMS     (  908): releaseWL(42698e18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/WifiService(  908): New client listening to asynchronous messages
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
I/CheckinService( 2185): Checking schedule, now: 1452527796838 next: 1453048886231
I/CheckinService( 2185): active receiver: disabled
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/GCoreUlr( 1221): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,I/GAV2    ( 3031): Thread[GAThread,5,main]: No campaign data found.
,I/EventLogService( 2185): Aggregate from 1452525945851 (log), 1452525939559 (data)
,D/SystemUpdateService( 2185): onDestroy
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,D/PMS     (  908): releaseWL(42708bd8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42611a18): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1369): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2185): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,E/BaseAppContext( 2185): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 2185): Fetching signing key...
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/PMS     (  908): acquireWL(42786090): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/GCM     ( 1369): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1221, uid=10029, userID:0
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a97 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,I/AuthZen ( 2185): Signing key fetched successfully!
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,I/GCoreUlr( 1221): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  908): acquireWL(427db170): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1221): Unbound from all location providers
,I/GCoreUlr( 1221): Place inference reporting - stopped
,D/AuthZenTransactionCache( 2185): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2185): Clearing transaction cache
D/PMS     (  908): releaseWL(427db170): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(425db8d8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
,D/PMS     (  908): releaseWL(426a63c0): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,D/libc    ( 1369): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,I/ActivityManager(  908): Resuming delayed broadcast
,I/GCM     ( 1369): GCM config loaded
I/GCoreUlr( 1221): DispatchingService.onDestroy()
,I/GCoreUlr( 1221): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1221): Unbound from all location providers
,I/GCoreUlr( 1221): Place inference reporting - stopped
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
D/PMS     (  908): acquireWL(4276f070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4276f070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/PMS     (  908): acquireWL(426bece8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/PMS     (  908): releaseWL(42786090): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/PMS     (  908): releaseWL(426bece8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4265a028): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
,D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/ConnectivityService(  908): handleInetConditionChange: currently in hold - not setting new end evt
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(4265a028): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(4262e8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,I/ActivityManager(  908): Resuming delayed broadcast
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/PMS     (  908): acquireWL(424e4638): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 908 1000 WorkSource{10029}
,D/PMS     (  908): releaseWL(4262e8b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/BootCompletedReceiver( 2185): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2185): Got an BootCompleted event.
,D/BootCompletedReceiver( 2185): Will NOT schedule AdAttestation signal task because it's disabled.
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(423b4ed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(423b4ed0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 1369): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  908): acquireWL(4235b5b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1369 10029 null
,D/PMS     (  908): releaseWL(4235b5b8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1221): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AutoSetting( 1339): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 3194): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3194): Cust_ConnectToPC   : Internet_Sharing>true
D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/        ( 3194): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3194): Cust_ConnectToPC   : spcsc>false
D/        ( 3194): Cust_ConnectToPC   : IPT>true
D/        ( 3194): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3194): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3194): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3194): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3194): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3194): onReceive:android.intent.action.USER_PRESENT
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(426899f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,I/SmartNS_PSService( 3194): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3194): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3194):  defaultType:0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/ContextImpl( 3194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.settings/.PSReceiver
D/PMS     (  908): releaseWL(424e4638): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,I/ActivityManager(  908): Resuming delayed broadcast
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(42623638): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 908 1000 WorkSource{10029}
,D/PMS     (  908): releaseWL(426899f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(42798cd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42798cd8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(425ad8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(425ad8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  908): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3376 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3376): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3376): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3376): Loading: swewebviewchromium
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
,D/PMS     (  908): acquireWL(424c5778): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,D/PMS     (  908): releaseWL(42623638): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  908): releaseWL(424c5778): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,I/LibraryLoader( 3376): Time to load native libraries: 42 ms (timestamps 7623-7665)
,I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3376): Initializing chromium process, renderers=9
I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
,I/chromium( 3376): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
,D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/Adreno-EGL( 3376): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3376): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3376): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3376): Local Branch: 
I/Adreno-EGL( 3376): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3376): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3376):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1284): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1508): SIM state: ABSENT
I/SIMStateChangeReceiver( 1508): phoneType = 0
,I/SIMStateChangeReceiver( 1508): remove notification
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3415 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  908): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3427 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  908): killProcessQuiet, pid=3031
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3031:com.google.android.gm/u0a107 (adj 15): empty #17
,W/SystemReader( 2752): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2752): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2752): onReceive()
D/ExchangePolicystatus( 2752): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2752): onReceive(): else
,D/Process (  908): killProcessQuiet, pid=3068
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  908): Killing 3068:com.htc.backup/1000 (adj 15): empty #17
D/HtcBroadcastReceiver( 1238): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/ActivityManager(  908): Recipient 3068
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3031
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3443 uid=10041 gids={50041}
,D/AccTypeManager( 3427): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  908): killProcessQuiet, pid=3012
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3459 uid=10078 gids={50078}
I/ActivityManager(  908): Killing 3012:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/AccTypeManager( 3427): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3427): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3427): Unsupported attribute readOnly
,D/SMSBackup( 3459): Got a database change event
,D/Process (  908): killProcessQuiet, pid=3091
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3091:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3427): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3427): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3427): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3471 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  908): Recipient 3012
,W/WeatherUtility( 1115): can't get weather sync account
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/ExternalAccountType( 3427): Unsupported attribute readOnly
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,D/CalendarApplication( 3471): onCreate
D/ProviderChangeReceiver( 3471): ---------------------------------------------------
,D/ProviderChangeReceiver( 3471): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3471): start to updateAlertNotification!
D/AlertService( 3471): No fired or scheduled alerts
,D/HtcAlertUtils( 3471): -- cancelReminderNotification --
W/ContextImpl( 3181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/HtcAlertUtils( 3471): broadcastExistReminder!
D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3123
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3123:com.htc.backupreset/1000 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3091
,I/ActivityManager(  908): Recipient 3123
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/LocationInitializer( 2185): Restart initialization of location
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1369): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1369): Proximity feature is not enabled.
,E/MDM     ( 1221): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): acquireWL(42623350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42623350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
I/ActivityManager(  908): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3492 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  908): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3492): can't get weather sync account
,W/WeatherRequest( 3492): request cur loc, but there is no sys cur
,W/Settings( 3492): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 10 17
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:57, mTXpacketCount:23, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  908): [ScoreAP] + fetchRssiAndLinkSpeedNative: Update RSSI:-54 and linkspeed:72 in database
,D/WifiApDatabaseHandler(  908): updateConnectedAP...
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3507 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3140
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3140:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3140
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3507): Database version: 95
,W/ContextImpl( 3507): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3507): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3507): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3507): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3507): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3507, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 3507): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/MediaRouter( 3507): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (3507/10154)
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (2434/10021)
I/NetworkMonitor( 3507): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  908): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3528 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3507): getSelectedRoute
,I/NetworkMonitor( 3507): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (3507/10154)
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3507, uid=10154, userID:0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42436d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(42436d30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  908): killProcessQuiet, pid=3154
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  908): Killing 3154:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3154
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3528): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3528): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3528): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3528): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3528): Preparing secondary program dexes.
V/DexLibLoader( 3528): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3528): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3528): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3528): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3528): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3528): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3528): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 3528): Dex already copied
D/OdexVerifier( 3528): Odex verification is skipped.
,V/DexLibLoader( 3528): Creating class loader
,V/DexLibLoader( 3528): Finished creating class loader
,V/DexLibLoader( 3528): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3528): Dex already copied
D/OdexVerifier( 3528): Odex verification is skipped.
,V/DexLibLoader( 3528): Creating class loader
,V/DexLibLoader( 3528): Finished creating class loader
,V/DexLibLoader( 3528): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3528): Dex already copied
D/OdexVerifier( 3528): Odex verification is skipped.
,V/DexLibLoader( 3528): Creating class loader
,V/DexLibLoader( 3528): Finished creating class loader
,V/DexLibLoader( 3528): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 3528): Dex already copied
,D/OdexVerifier( 3528): Odex verification is skipped.
,V/DexLibLoader( 3528): Creating class loader
,V/DexLibLoader( 3528): Finished creating class loader
,V/DexLibLoader( 3528): Verifying classes from secondary dexes.
,D/DexLibLoader( 3528): DexLibLoader.ensureDexLoaded took 151 ms
,W/dalvikvm( 3528): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3528): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3528): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  908): mEventCount = 300
,W/fb4a(:<default>):StaticBindingVerifier( 3528): Verify
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 4 times.
,D/WifiService(  908): New client listening to asynchronous messages
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (3528/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3528): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3528): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  908): killProcessQuiet, pid=3167
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3167:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3167
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1339): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  908): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3548 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1339): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1339): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1339): service - handleMessage() setting current location null
,D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1339): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/MobileConnectivityChangeReceiver( 3548): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3548): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3548): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3548): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  908): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3561 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3210
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/fb4a(:<default>):UserScope( 3528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/ActivityManager(  908): Killing 3210:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (3548/10079)
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3528): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/ActivityManager(  908): Recipient 3210
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/fb4a(:<default>):UserScope( 3528): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (3548/10079)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.setupwizard (3548/10079)
D/PMS     (  908): acquireWL(426b3340): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(427a27c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/CheckinService( 2185): Checkin interval check for package: unspecified last checkin: 1452525949258 min interval config: 0 actual interval: 1852993
,W/ContextImpl( 3528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/PMS     (  908): releaseWL(426b3340): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/CheckinService( 2185): Checking schedule, now: 1452527802258 next: 1452525979231
,I/CheckinService( 2185): active receiver: enabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2185, uid=10029, userID:0
,I/CheckinService( 2185): Preparing to send checkin request
,I/EventLogService( 2185): Accumulating logs since 1452527796998
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,E/dalvikvm( 3528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3528): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3528): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3528): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3528): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3528): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3528): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3528): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3528): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3528): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3528): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3528): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3528): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3528): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  908): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3580 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3224
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3224:com.android.smith/u0a163 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3224
,I/CheckinRequestBuilder( 2185): Checkin reason type: 8 attempt count: 1
D/WifiService(  908): New client listening to asynchronous messages
I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2185): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm-heap( 3528): Grow heap (frag case) to 9.929MB for 39954-byte allocation
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,V/AlarmManager(  908): sending alarm PendingIntent{41d26928: PendingIntentRecord{424213c0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49617, Int=0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,I/dalvikvm-heap( 3528): Grow heap (frag case) to 10.001MB for 79892-byte allocation
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 3580): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3580): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3528): Grow heap (frag case) to 10.076MB for 84664-byte allocation
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2185/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (3580/10151)
V/WebViewChromiumFactoryProvider( 3580): Binding Chromium to main looper Looper (main, tid 1) {41a91e98}
I/LibraryLoader( 3580): Expected native library version number "",actual native library version number ""
I/chromium( 3580): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3580): Initializing chromium process, renderers=0
,D/PMS     (  908): acquireWL(42588140): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  908): acquireWL(4255e420): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 3580): BLUETOOTH permission is missing!
D/PMS     (  908): releaseWL(42588140): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3580): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3580): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3580): Local Branch: 
I/Adreno-EGL( 3580): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3580): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3580):                  aa63bbd948f41d15fc72f585e
,W/dalvikvm( 1369): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1369): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1369): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,I/NSApplication( 3580): Starting up...
,I/dalvikvm-heap( 3528): Grow heap (frag case) to 10.288MB for 75760-byte allocation
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (3580/10151)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.magazines (3580/10151)
,D/libc    ( 1369): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1369): [NET] getaddrinfo-, 1
D/libc    ( 1369): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =933f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/Process (  908): killProcessQuiet, pid=3236
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3622 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  908): Killing 3236:com.google.android.youtube/u0a168 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (3528/10027)
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423b8c00 u0 ReceiverList{4242fd98 3528 com.facebook.katana/10027/u0 remote:42537248}}
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423b8c00 u0 ReceiverList{4242fd98 3528 com.facebook.katana/10027/u0 remote:42537248}}
W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4237c718 u0 ReceiverList{42392040 3528 com.facebook.katana/10027/u0 remote:42463a20}}
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (3528/10027)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (3528/10027)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.facebook.katana (3528/10027)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 54
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1369): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1369): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,D/PMS     (  908): acquireWL(425a1e08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Recipient 3236
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  908): Client com.google.android.youtube (pid 3236): Died!
,D/PMS     (  908): releaseWL(425a1e08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1369): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
D/libc    ( 1369): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1369): [NET] getaddrinfo-,err=8
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3528): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [8][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
,D/PMS     (  908): acquireWL(423accc0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3622 10160 null
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0],
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
D/PMS     (  908): acquireWL(42403c68): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3622 10160 null
D/PMS     (  908): releaseWL(423accc0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,D/PMS     (  908): releaseWL(42403c68): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  908): killProcessQuiet, pid=3286
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/iu.SyncManager( 2185): SYNC; picasa accounts
I/ActivityManager(  908): Killing 3286:com.android.vending/u0a74 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3286
,D/NetworkLogImpl( 2185): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2185): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029),
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
I/iu.UploadsManager( 2185): num queued entries: 0
I/iu.UploadsManager( 2185): num updated entries: 0
I/iu.SyncManager( 2185): NEXT; no task
,D/AlertReceiver( 3471): beginStartingService
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/PMS     (  908): acquireWL(42714db0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3471 10013 null
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/ConnectivityService(  908): reportInetCondition for net 1, percentage: 100 by  (1369/10029)
D/ConnectivityService(  908): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  908): handleInetConditionChange: starting a change hold
,D/AlertService( 3471): start to updateAlertNotification!
,I/dalvikvm-heap( 3622): Grow heap (frag case) to 15.214MB for 1821008-byte allocation
,W/WeatherUtility( 3492): can't get weather sync account
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3657 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 3492): request cur loc, but there is no sys cur
,W/Settings( 3492): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AlertService( 3471): No fired or scheduled alerts
,D/HtcAlertUtils( 3471): -- cancelReminderNotification --
,D/HtcAlertUtils( 3471): broadcastExistReminder!
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3471): stopSelfResult true
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,D/PMS     (  908): releaseWL(42714db0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 0 6 17
,D/PMS     (  908): acquireWL(42522500): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3657 10071 null
,D/PMS     (  908): acquireWL(426458d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3657 10071 null
,D/PMS     (  908): releaseWL(42522500): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,I/ActivityManager(  908): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3672 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 3657): update TASK shortcut>
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): releaseWL(426458d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WorldClock.Global( 3672): isHtcDevice = true
,I/ActivityManager(  908): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3684 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
W/NotifyReceiver( 3657): stopSelfResult true
,W/ContextImpl( 3181): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3672): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.Global( 3672): isHtcDevice = true
,I/WorldClock.AlarmUtils( 3672): Cancel any alarm from alarm manager
,I/ActivityManager(  908): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3698 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 3672): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1115): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/Process (  908): killProcessQuiet, pid=3194
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3194:com.android.settings/1000 (adj 15): empty #17
,D/TimeService( 3698): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452527803261
,W/dalvikvm( 3684): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/Process (  908): killProcessQuiet, pid=3376
,W/dalvikvm( 3684): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/MultiDex( 3684): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 3684): install
,I/ActivityManager(  908): Killing 3376:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/MultiDex( 3684): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3684): loading existing secondary dex files
,I/MultiDex( 3684): load found 3 secondary dex files
D/PMS     (  908): acquireWL(427904c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427904c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/MultiDex( 3684): install done
,I/CheckinService( 2185): Checkin interval check for package: unspecified last checkin: 1452525949258 min interval config: 0 actual interval: 1854031
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
I/ActivityManager(  908): Recipient 3194
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(4278b3e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2185 10029 null
,W/dalvikvm( 3684): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3684): VFY: unable to resolve instance field 36
,W/dalvikvm( 3684): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  908): acquireWL(4278b398): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,V/JNIHelp ( 3684): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
D/PMS     (  908): releaseWL(4278b3e8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  908): releaseWL(4278b398): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3723 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Recipient 3376
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3723): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3723): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3723): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42734328): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3657 10071 null
,D/PMS     (  908): acquireWL(42715590): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3657 10071 null
,D/PMS     (  908): releaseWL(42734328): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{426e8350 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/TodoTaskshortcut( 3657): update TASK shortcut>
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/ConnectivityService(  908): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  908): sendGeneralBroadcast, restrictEnable=false
I/ActivityManager(  908): Resuming delayed broadcast
D/ConnectivityService(  908): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 3684): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  908): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3740 uid=10082 gids={50082, 3003, 5012}
D/PMS     (  908): releaseWL(42715590): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/Process (  908): killProcessQuiet, pid=3415
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3415:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/NotifyReceiver( 3657): stopSelfResult true
I/ActivityManager(  908): Recipient 3415
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 3684): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 3684): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 3684): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 3684): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
,W/dalvikvm( 3684): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 3684): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 3684): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  908): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3753 uid=10082 gids={50082, 3003, 5012}
,D/Process (  908): killProcessQuiet, pid=3427
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3427:com.htc.contacts/u0a44 (adj 15): empty #17
,D/SMSBackup( 3459): Got a database change event
,I/ActivityManager(  908): Recipient 3427
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3765 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  908): killProcessQuiet, pid=3507
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3507:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/WVCdm   (  370): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  370): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 3684): Install completed successfully. count=14 extracted=0
,I/ImageRamCache( 3765): create image Cache, size: 31457280.
I/ImageRamCache( 3765): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3765): create image Cache, size: 12582912.
,I/FeedSettings( 3765): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3765): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3765): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3765): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3765): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3765): loadGridSize() with Alternative
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  908): Client com.google.android.music (pid 3507): Died!
I/ActivityManager(  908): Recipient 3507
,D/CustomHighlightReceiver( 3765): [custom highlight] onReceive
,D/MessagingShortcutReceiver( 2752): keep hiding shortcut bubble
D/MessagingShortcut( 2752): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2752): After query: 0
,D/MessagingShortcut( 2752): mPresentUnreadCount: -1
,D/MessagingShortcut( 2752): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2752): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] reorderNotification, total:0
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/CustomHighlightService( 3765): [custom highlight] onHandleIntent
,D/NewsDB  ( 3765): set custom highlight []
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3657): update TASK shortcut>
,D/HtcBroadcastReceiver( 1238): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  908): Resuming delayed broadcast
,D/WVCdm   (  370): PrepareKeyRequest: nonce=316261918
,D/CustomHighlightService( 3765): [custom highlight] set tags 
,D/Process (  908): killProcessQuiet, pid=3528
I/ActivityManager(  908): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3782 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  908): Killing 3528:com.facebook.katana/u0a27 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
E/MDM     ( 1221): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2185): Restart initialization of location
I/ActivityManager(  908): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3798 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  908): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1369): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1369): Proximity feature is not enabled.
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,D/SMSBackup( 3459): Got a database change event
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): acquireWL(42238cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42238cb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
D/MtpReceiver( 2434): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2434): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2434): [MTP][handleMessage][startService]
D/MtpReceiver( 2434): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2434): [MTP][handleMessage]-
,I/ActivityManager(  908): Recipient 3528
D/WifiService(  908): Client connection lost with reason: 4
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MtpService( 2434): [MTP] startForeground
I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3815 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1115): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1115): com.android.providers.media 1 1 10
,I/RemoteViews( 1115): com.android.providers.media (false,0)
,D/MtpService( 2434): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews.Performance( 1115): com.android.providers.media 2 1 15
,D/MtpDatabase( 2434): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  908): acquireWL(42570f10): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2185 10029 null
,D/MtpService( 2434): [isMtpConnected] connected: true
,D/PMS     (  908): acquireWL(4220f620): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3622 10160 null
D/MdScBoot( 3782): [878.1.] 30@-165615 -> 40@-165643
,D/Process (  908): killProcessQuiet, pid=3548
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3548:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3548
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Settings( 3684): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/SyncApplication( 3815): Loading default preferences
D/PMS     (  908): releaseWL(4220f620): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/Process (  908): killProcessQuiet, pid=3561
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Resources( 3815): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
I/ActivityManager(  908): Killing 3561:com.android.chrome/u0a96 (adj 15): empty #17
,I/iu.UploadsManager( 2185): End new media; added: 0, uploading: 0, time: 86 ms
,D/MessagingNotification( 2752): New incoming message, can't cancel notification now
,D/MessagingNotification( 2752): newMsgCnt: 0, false
I/ActivityManager(  908): Recipient 3561
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  908): releaseWL(42570f10): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 3815): Overriding preferences with custom values
,D/SyncApplication( 3815): Updating preferences succeeded
,E/SyncApplication( 3815): Application created.
D/VolumeInfo( 3815): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3815): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3815): Found 0 mount point(s)
,V/VolumeInfo( 3815): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3815): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3815): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3815): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3815): getNewCalendarAuthority()...
,D/SyncApplication( 3815): enableAppOperation()+
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3815, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3815, uid=10008, userID:0
,W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3815): enableAppOperation()-
D/HTCUtilities( 3815): isNeorSinged() + 
,D/HTCUtilities( 3815): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3815): isNeorSinged() return false
D/CDMountReceiver( 3815): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3815): USB connected to PC
,D/FOTAReceiver( 3815): onReceive() enter 
,D/FOTAReceiver( 3815): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  908): killProcessQuiet, pid=3580
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  908): killProcessQuiet, pid=3471
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3837 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 3580:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
I/ActivityManager(  908): Killing 3471:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3471
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (3684/10029)
,D/HtcFingerPrintQuickLaunchProvider( 3837): -onCreate()
,V/Settings:HtcSettingsApplication( 3837): [3837/3837] onCreate()
D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
,D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  908): Recipient 3580
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3837): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3837): usb_cable_connect = 1
D/SmartNS_Utility( 3837): usb_denied = 0
I/SmartNS_NSReceiver( 3837): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3837): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3837): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3837): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3837):  defaultType:0
,I/SmartNS_PSService( 3837): fail notificaiton:false
,D/SmartNS_Utility( 3837): usb_cable_connect = 1
D/SmartNS_Utility( 3837): usb_denied = 0
,I/SmartNS_PSService( 3837): usb notificaiton:true
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,V/Tethering(  908): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3837): usb_cable_connect = 1
D/SmartNS_Utility( 3837): usb_denied = 0
,I/SmartNS_PSService( 3837): usb notificaiton:true
,V/Tethering(  908): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  908): bSetPropertyMultiRAB:false
,I/RemoteViews( 1115): com.android.settings (true,33751552)
D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3837/1000)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.settings (3837/1000)
I/RemoteViews.Performance( 1115): com.android.settings 2 1 10
D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3837): usb_cable_connect = 1
D/SmartNS_Utility( 3837): usb_denied = 0
D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
W/WeatherUtility( 3492): can't get weather sync account
I/SmartNS_PSService( 3837): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3837): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1269): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1269): com.google.android.googlequicksearchbox 0 0 5
,I/RemoteViews( 1115): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1115): com.android.settings 1 1 10
,I/ActivityManager(  908): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3854 uid=10032 gids={50032, 3003, 5012}
,W/WeatherRequest( 3492): request cur loc, but there is no sys cur
,W/Settings( 3492): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/Adreno-EGL( 3684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3684): Local Branch: 
I/Adreno-EGL( 3684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3684):                  aa63bbd948f41d15fc72f585e
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 7 17
,I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3672
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3672:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  908): Recipient 3672
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3872 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  908): acquireWL(426b5de8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 3872): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3872 dbg=false s=true
,I/DeviceManagement( 3872): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3887 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3181
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3181:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3181
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): releaseWL(426b5de8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 3684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3684): Local Branch: 
I/Adreno-EGL( 3684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3684):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  908): acquireWL(426c09c8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 3684): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3684): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3684): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3684): Local Branch: 
I/Adreno-EGL( 3684): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3684): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3684):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  370): CdmEngine::OpenSession
,I/WVCdm   (  370): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  370): CdmEngine::GenerateKeyRequest
D/PMS     (  908): releaseWL(426c09c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(426376d8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426376d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  908): acquireWL(4271c070): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4271c070): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WVCdm   (  370): PrepareKeyRequest: nonce=3532932691
,I/WVCdm   (  370): CdmEngine::CloseSession
,D/PMS     (  908): acquireWL(42795f50): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42795f50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  908): acquireWL(428d77d8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(428d77d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427b1700): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(427b1700): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4279b500): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4279b500): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427966c0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (3887/10100)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.apps.docs (3887/10100)
,W/GAV2    ( 3887): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/PMS     (  908): releaseWL(427966c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 527 ms] updated apps [took 527 ms] 
D/PMS     (  908): acquireWL(42793980): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3913 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/CheckinRequestBuilder( 2185): Classify the device as Phone.
,I/htcbackup-core( 3913): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2185): [NET] getaddrinfo-,err=8
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2185): [NET] getaddrinfo-, 1
D/libc    ( 2185): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c98d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2185): [NET] getaddrinfo_proxy-, success
,W/ContextImpl( 3913): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
I/DeviceManagement( 3872): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/DeviceManagement( 3872): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.autobot.cargps.provider, com.htc.smartdim, com.htc.android.htcsetupwizard, com.htc.android.htcloglevel, com.android.providers.settings, com.qualcomm.privinit, com.android.settings, com.android.location.fused, com.qualcomm.timeservice, com.htc.feedback, com.htc.home.personalize, com.android.inputdevices, com.android.keychain, com.htc.drive.activator, com.htc.checkinprovider, com.htc.lockscreen, com.htc.cirmodule, com.htc.usage, com.android.CSDFunctionG, com.htc.htcpowermanager, com.htc.backup, android, com.htc.guide, com.htc.backupreset, com.htc.mirrorlinkserver]
I/DeviceManagement( 3872): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
D/Process (  908): killProcessQuiet, pid=3698
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/DeviceManagement( 3872): WorkflowService: Starting workflow service
I/ActivityManager(  908): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3934 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  908): Killing 3698:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/DeviceManagement( 3872): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41acd7b0] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3872): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3872): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  908): Recipient 3698
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2185): [NET] getaddrinfo-,err=8
,I/DeviceManagement( 3872): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3872): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3934):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  908): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2185): [NET] getaddrinfo-,err=8
D/libc    ( 2185): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2185): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2185): Sending checkin request (12431 bytes)
,I/DeviceManagement( 3872): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/GAV2    ( 3887): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  908): Resuming delayed broadcast
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/PMS     (  908): acquireWL(4262e7c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3622 10160 null
D/PMS     (  908): releaseWL(4262e7c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/DeviceManagement( 3872): SessionStateController: Checking invariants...
,D/Process (  908): killProcessQuiet, pid=3723
,I/ActivityManager(  908): Killing 3723:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Recipient 3723
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3872): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
I/ActivityManager(  908): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3955 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3740
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3740:com.htc.stock/u0a82 (adj 15): empty #17
,I/DeviceManagement( 3872): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41acd7b0]
,I/DeviceManagement( 3872): WorkflowService: Stopping workflow service
,D/Process (  908): killProcessQuiet, pid=3753
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Recipient 3740
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Killing 3753:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3753
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=6 [15][1][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3955, uid=10074, userID:0
,D/Finsky  ( 3955): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3955/10074)
,D/Settings:HtcWirelessFeatureFlags( 3837): id/is att sku: 99/false
,W/SystemReader( 3837): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3837): Cannot find support_harman, use default value instead
,W/SystemReader( 3837): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3837): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3837): The wrap header doesn't exist in header list.
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcWrapHeaderInfo( 3837): updateDevelopment, bPrefShow = true
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,E/Settings:HtcUmcWidgetEnabler( 3837): isSupportMusicChannel(): false
,D/ConnectivityService(  908): getAllNetworkInfo called by com.android.vending (3955/10074)
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]support         :false
,D/Finsky  ( 3955): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/FingerprintManager( 3837): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,E/Settings:HtcVoWifiWidgetEnabler( 3837): isSupportVoWifi: null
I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3837): Failed to find provider info for com.htc.vowifi
W/Settings( 3955): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3955): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,I/CheckinRequestBuilder( 2185): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  908): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2185): Failed to find provider info for com.google.android.wearable.settings
,W/dalvikvm( 3955): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3955, uid=10074, userID:0
,D/Ads     ( 3955): Skipping gmscore version check
,D/Finsky  ( 3955): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3955): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3955): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,D/PMS     (  908): releaseWL(4255e420): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Loading module APK com.google.android.play.games
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3837): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3837): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3837): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3837): [supportHomeButton]support         :false
,D/Finsky  ( 3955): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 3955): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/FingerprintManager( 3837): hasFingerprint() - sSensorCode = 0
,I/ActivityManager(  908): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3837): isSupportVoWifi: null
E/ActivityThread( 3837): Failed to find provider info for com.htc.vowifi
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/dalvikvm( 2185): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2185): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 2185): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 2185): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,D/Process (  908): killProcessQuiet, pid=3765
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3765:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 3765
,D/ConnectivityService(  908): getNetworkInfo networkType=9 called by com.google.android.gms (2185/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 2185): Submit a task: k
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 2185): Processing package: com.example.hello
,I/CheckinRequestBuilder( 2185): Classify the device as Phone.
,D/GassUtils( 2185): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 2185): Found info for package com.example.hello in db.
D/PMS     (  908): acquireWL(41e03598): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1508 10014 null
,D/PMS     (  908): releaseWL(41e03598): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
W/BaseAppContext( 2185): Using Auth Proxy for data requests.
W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,I/Icing   ( 2185): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,I/CheckinTask( 2185): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2185): Checking schedule, now: 1452527805839 next: 1453050742832
,I/CheckinService( 2185): active receiver: disabled
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,W/BaseAppContext( 2185): Using Auth Proxy for data requests.
,D/PMS     (  908): acquireWL(425f2630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/CheckinService( 2185): Recording last checkin time for package unspecified as 1452527805921
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=4008 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/PMS     (  908): releaseWL(427a27c0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(425f2630): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/Icing   ( 2185): Loaded CLD2 Version V2.0 - 20141016
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2185): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2185): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2185): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2185, uid=10029, userID:0
D/PMS     (  908): acquireWL(42716738): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4008 1000 null
W/ContextImpl( 4008): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/WeatherUtility( 1115): can't get weather sync account
,D/PowerUsageService( 4008): call getInstance()
,D/WeatherUtility( 1339): Weather sync is On
,D/WSP     ( 1339): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3492): can't get weather sync account
,I/ActivityManager(  908): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4027 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
D/PowerUsageList:PowerUsageHelper( 4008): MY_DEBUG = false
,I/PeopleDatabaseHelper( 2185): cleanUpNonGplusAccounts done.
W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/WeatherRequest( 3492): request cur loc, but there is no sys cur
,W/Settings( 3492): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 11 17
,I/Icing   ( 2185): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,W/dalvikvm( 2185): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
W/BatSI   (  908): Couldn't get kernel wake lock stats
,W/BatSI   (  908): Couldn't get kernel wake lock stats
,I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4047 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 4047): Database version: 95
,W/ContextImpl( 4047): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4047): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4047): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4047): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4047): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4047, uid=10154, userID:0
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
,D/MediaRouterService(  908): Client com.google.android.music (pid 4047): Registered
,D/WifiDisplayAdapter(  908): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  908):     Client/Owner: Client
D/WifiDisplayAdapter(  908):     GroupId: 
D/WifiDisplayAdapter(  908):     Passphrase: 
D/WifiDisplayAdapter(  908):     SessionId: 0
D/WifiDisplayAdapter(  908):     IP Address: }
I/MediaRouter( 4047): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.music (4047/10154)
,I/NetworkMonitor( 4047): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2185, uid=10029, userID:0
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 4047): getSelectedRoute
,I/NetworkMonitor( 4047): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.google.android.music (4047/10154)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4047, uid=10154, userID:0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
D/PMS     (  908): acquireWL(42794288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
D/PMS     (  908): releaseWL(42794288): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
D/Process (  908): killProcessQuiet, pid=2752
,D/TelephonyReceiver( 1238): bind: true
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
I/ActivityManager(  908): Killing 2752:com.htc.sense.mms/u0a65 (adj 15): empty #17
I/ActivityManager(  908): remove PR=com.htc.sense.mms/.util.GenericMessagesProvider oop
,I/ActivityManager(  908): Remove died provider record at: com.htc.sense.mms(2752)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  908): Recipient 2752
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4068 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
I/HtcModeClient( 1508): handler message = 4011
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
E/HtcModeClient( 1508): Check connection and retry 5 times.
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  908): Start proc com.htc.sense.mms for restart com.htc.sense.mms: pid=4080 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/DFPI.PIReciver( 4068): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,W/Prism.AllAppsManager( 1269): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 4068): onHandleIntent
I/DFPI.ApkInstallService( 4068): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4068): check CID = HTC__032
,I/DFPI.ApkInstallService( 4068): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Resuming delayed broadcast
,W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/Process (  908): killProcessQuiet, pid=3657
,D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/PackageManager(  908):   Scheme: "sms"
I/ActivityManager(  908): Killing 3657:com.htc.task/u0a71 (adj 15): empty #17
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/MessageFrequencyProvider( 4080): onCreate
,I/ActivityManager(  908): Recipient 3657
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/Launcher( 1269): Deferring update until onResume
,D/Launcher( 1269): waitUntilResume // bindAppsUpdated
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,V/GetPrviateResource( 4080): GetPrviateResource
,V/GetPrviateResource( 4080): GetPrviateResource
,E/ExternalAccountType( 1327): Unsupported attribute readOnly
,I/ActivityManager(  908): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4096 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
,D/GenericMessagesProvider( 4080): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 4080): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 4080): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4080): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 4080): DB info: errno = 2, errno message = No such file or directory
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 4080): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4080): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4080): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4080): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 4080): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 4080): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 4080): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,W/System.err( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 4080): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4080): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4080): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4080): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 4080): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 4080): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  908): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  908):   Scheme: "mmsto"
,D/MessageCustFlag( 4080): sense_version=6.0
,D/BTAccessoryUtil( 4080): createReceiver
,D/BTAccessoryUtil( 4080): registerReceiver return intent = null
D/MessageCustFlag( 4080): sku_id=99
,W/SystemReader( 4080): Cannot find message_ambs_application_id, use default value instead
,I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
,D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/Process (  908): killProcessQuiet, pid=3782
D/Messaging( 4080): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4080): networkCode: 
D/MessageCustFlag( 4080): sku_id=99
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/MmsConfig( 4080): SIE smsPri: null
,D/MmsConfig( 4080): networkCode: 
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (4096/10053)
I/ActivityManager(  908): Killing 3782:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.musicenhancer (4096/10053)
,W/BroadcastQueue(  908): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{4265c3d0 u0 ReceiverList{425fa0a8 4096 com.htc.musicenhancer/10053/u0 remote:4271c380}}
D/HtcTelephonyCapability( 4080): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4080): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4080): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4080): Cannot find qct_8960_interface, use default value instead
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4096): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 3782
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/PackageManager(  908): Unable to load service info ResolveInfo{425fe590 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  908): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  908): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  908): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  908): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  908): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  908): 	at dalvik.system.NativeStart.main(Native Method)
V/AlarmManager(  908): sending alarm PendingIntent{42574a20: PendingIntentRecord{42732710 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452527807155, Int=0
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4115 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  908): killProcessQuiet, pid=3798
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3798:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3798
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4115): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4115): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 4115): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
,I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,I/SoundPicker( 4115): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
D/PMS     (  908): releaseWL(42793980): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
D/RemoteDisplayProvider(  908): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) },
,D/RemoteDisplayProvider(  908): start
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3443
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  908): Killing 3443:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/GCoreNlp( 1221): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  908): Recipient 3443
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DFPI.PIReciver( 4068): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/LocationProviderProxy(  908): applying state to connected service
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/PMS     (  908): acquireWL(428e0bd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/DFPI.ApkInstallService( 4068): onHandleIntent
,I/DFPI.ApkInstallService( 4068): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4068): check CID = HTC__032
,I/DFPI.ApkInstallService( 4068): There is no Demo.apk in sd card or phone storage
D/PMS     (  908): releaseWL(428e0bd8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
,D/LocationProviderProxy(  908): applying state to connected service
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] startService
D/PMS     (  908): acquireWL(42658a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(42658a78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 4115): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4115): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4115): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/PMS     (  908): acquireWL(428f63b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(428f63b0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426308f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,D/PMS     (  908): releaseWL(426308f0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,D/AutoSetting( 1339): service - mRequestRunnable: screen on delay 10s, request NLP now
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
D/AutoSetting( 1339): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1339): service - requestNLP() NetworkLocationProvider not enabled
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4133 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoTaskReceiver
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  908): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4146 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/DFPI.PIReciver( 4068): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4068): onHandleIntent
,I/DFPI.ApkInstallService( 4068): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4068): check CID = HTC__032
,I/DFPI.ApkInstallService( 4068): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/Process (  908): killProcessQuiet, pid=3459
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Resuming delayed broadcast
I/ActivityManager(  908): Killing 3459:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3459
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] startService
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 4115): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4115): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4115): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/EASAppSvc( 4146): [ NA ]- onCreate()
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/EASAppSvc( 4146): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,D/ORMLib  ( 4133): put()
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/EASAppSvc( 4146): [ NA ]- onDestroy()
,I/EASAppSvc( 4146): [ NA ]> uninitEASService
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
D/WifiService(  908): New client listening to asynchronous messages
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (4146/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (4146/10064)
,D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (4146/10064)
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 4047): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/DFPI.PIReciver( 4068): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4068): onHandleIntent
,I/DFPI.ApkInstallService( 4068): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4068): check CID = HTC__032
,I/DFPI.ApkInstallService( 4068): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  908): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4115): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4115): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4115): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4115): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4115): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/ActivityManager(  908): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 4115): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4115): MODE_GSM access default DB
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/EASRequestController( 4146): [ NA ]release
,I/EASAppSvc( 4146): [ NA ]< uninitEASService
,I/EASAppSvc( 4146): [ NA ]- onCreate()
,I/EASAppSvc( 4146): [ NA ]> onUpgrade: version = 63
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.htc.android.mail (4146/10064)
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4115): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.htc.android.mail (4146/10064)
D/ConnectivityService(  908): getNetworkInfo networkType=55 called by com.htc.android.mail (4146/10064)
,D/ORMLib  ( 4133): put()
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/EASAppSvc( 4146): [ NA ]- onDestroy()
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/EASAppSvc( 4146): [ NA ]> uninitEASService,
D/PMS     (  908): releaseWL(42716738): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/EASRequestController( 4146): [ NA ]release
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/ActivityManager(  908): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4183 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4115): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/EASAppSvc( 4146): [ NA ]< uninitEASService
,I/SoundPicker( 4115): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4115): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/Process (  908): killProcessQuiet, pid=3815
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3815:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3815
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
D/ORMLib  ( 4133): put()
,I/MediaStoreImporter( 4047): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3854
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  908): acquireWL(42731a20): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1508 10014 null
I/ActivityManager(  908): Killing 3854:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  908): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ActivityManager(  908): Recipient 3854
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(42731a20): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1238): bind: false
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
I/ActivityManager(  908): Resuming delayed broadcast
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  908): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4206 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(426c7538): PARTIAL_WAKE_LOCK  NetworkStats 0x1 908 1000 null
,D/Process (  908): killProcessQuiet, pid=3887
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3887:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3887
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  908): releaseWL(426c7538): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=55 rxSum=45} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19564 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19565 delay=15s
,I/ActivityManager(  908): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4222 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b21bd0 +
,I/Prism.WidgetManager( 1269): onLoadItems() +
,W/GAV2    ( 4222): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  908): acquireWL(4246ee30): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4246ee30): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(423f7828): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  908): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e68d90 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  908): Resuming delayed broadcast
,I/RemoteViews.Performance( 1115): com.htc.updater 2 12 1 10
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
D/PMS     (  908): releaseWL(423f7828): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e2d328 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.updater 0 8 1 10
,D/Process (  908): killProcessQuiet, pid=3913
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4249 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  908): Killing 3913:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3913
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 4222): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4222): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/Gmail   ( 4222): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4222): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/Prism.WidgetManager( 1269): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1269): onLoadItems() -
,I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b21bd0 -
,I/Babel   ( 4249): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4249): MmsConfig.loadMmsSettings
,W/dalvikvm( 4249): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4249): VFY: unable to resolve instance field 36
,W/dalvikvm( 4249): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4249): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/MmsCustomizationProvider( 4080): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4080): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4249): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4249): MmsConfig.loadFromDatabase
,E/Babel   ( 4249): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4249): MmsConfig.loadFromResources
,E/Babel   ( 4249): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4249): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4249, uid=10111, userID:0
,W/Settings( 4249): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4249, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4249, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4249, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4249, uid=10111, userID:0
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4249, uid=10111, userID:0
D/PMS     (  908): acquireWL(422cc7e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4249 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4249): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  908): releaseWL(422cc7e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(42235510): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4249 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(42235510): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=3934
,I/ActivityManager(  908): Killing 3934:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Recipient 3934
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(4282b320): PARTIAL_WAKE_LOCK  AsyncService 0x1 3622 10160 null
,D/PMS     (  908): releaseWL(4282b320): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PhoneApp( 1238): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1238): -- N1 =0
D/Messaging( 4080): mNeedToUpdateDate2 start
,D/MmsConfig( 4080): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4080): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4080): 
D/MmsAsyncWorkHandler( 4080): HM tk = 20001
,D/ReportIndicatorCache( 4080): MSG_QUERY_REPORTS >>
D/PhoneApp( 1238): -- N2 =0
D/SettingsManager( 4080): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41a9d800
,D/PhoneApp( 1238): -- N3 =0
,I/Messaging( 4080): mccmnc> 
,I/ActivityManager(  908): Resuming delayed broadcast
D/DraftCache( 4080): [DraftCache/1] DraftCache.constructor
D/DraftCache( 4080): [DraftCache/1] refresh
D/MmsConfig( 4080): networkCode: 
D/Messaging( 4080): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
W/dalvikvm( 3955): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/MessageCustFlag( 4080): sense_version=6.0
,D/Jerry   ( 4080): start to preload cursor >>>>>>>
D/PhoneStorageUtil( 4080): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4080): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4080): createReceiver
,D/Messaging( 4080): mNeedToUpdateDate2: false
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1238):  phoneType = -1
,D/TelephUtils( 1238): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1238): Update uri=content://mms, match=0
,V/MmsProvider( 1238): selection=st=129 AND m_type!=134
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/Messaging( 4080): Reset downloading state: 0
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
V/MmsSystemEventReceiver( 4080): TransactionService is going to be woken up.
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/Messaging( 4080): ViewCache CreatePreload
,D/Messaging( 4080): ViewCache CreatePreloadOnlyMultipleOpsList
I/ActivityManager(  908): Delaying start of: ServiceRecord{42564ed0 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/Cust_MMSMS( 4080): _has_set_default_values_2=true
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1238): sku_id=99,
,D/PMS     (  908): acquireWL(42833b68): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
D/DraftCache( 4080): [DraftCache/403] rebuildCache
D/MsgPreferenceUtils( 4080): def_index: 0
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1238):  phoneType = -1
D/MmsSmsV2Provider( 1238): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/MsgPreferenceUtils( 4080): globalIndex = 1
D/Messaging( 4080): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/MsgPreferenceUtils( 4080): phone state: true
D/MsgPreferenceUtils( 4080): sd state: false
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MsgPreferenceUtils( 4080): vIndex = 0
,D/Jerry   ( 1238): URI_DRAFT
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2185, uid=10029, userID:0
D/DraftCache( 4080): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4080): [DraftCache/403] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4080): 
D/MmsAsyncWorkHandler( 4080): HM tk = 20002
,V/TransactionService( 4080): 1-Creating TransactionService
,D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1238): sku_id=99
D/PMS     (  908): releaseWL(42833b68): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428380a8): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
V/TransactionService( 4080): onStartCommand: 1
D/MmsSystemEventReceiver( 4080): unRegisterForConnectionStateChanges
V/TransactionService( 4080): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4080): Loading previous transactions.
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1238): sku_id=99
D/TelephUtils( 1238): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/AccFlag ( 1238): device_type: 1
D/TransactionService( 4080): Force set service start id to 1
V/TransactionService( 4080): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 4080): unRegisterForConnectionStateChanges
D/TransactionService( 4080): stopSelfResult: true, mLastHandledServiceId: 1
V/TransactionService( 4080): Destroying TransactionService
V/TransactionService( 4080): 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SocialFeedProvider( 1269): +disConnect socialManager
I/SocialFeedProvider( 1269): disconnect socialManager
,I/SocialFeedProvider( 1269): -disConnect socialManager
,D/Process (  908): killProcessQuiet, pid=3872
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3872:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3872
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(428380a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(4283e118): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4249 10111 null
,I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  908): releaseWL(4283e118): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(4283f7c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(4283f7c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42845b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
I/ActivityManager(  908): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42845b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
D/PMS     (  908): acquireWL(4284f370): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): acquireWL(4284fcb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4284f370): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): releaseWL(4284fcb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4330 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  908): Resuming delayed broadcast
,V/AlarmManager(  908): sending alarm PendingIntent{4255e960: PendingIntentRecord{424fe1a8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452527810396, Int=0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ImageRamCache( 4330): create image Cache, size: 31457280.
I/ImageRamCache( 4330): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 4330): create image Cache, size: 12582912.
,I/FeedSettings( 4330): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4330): GroupBudget 0.500000 0.380000
,I/FeedSettings( 4330): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 4330): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4330): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4330): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 4330): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4330): last commit ulog time 1452509393704
,I/SocialManager[SocialBiLogHelper]( 4330): skip commit this time
,D/Process (  908): killProcessQuiet, pid=4008
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4008:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  908): acquireWL(427955f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
I/ActivityManager(  908): Recipient 4008
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(427955f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(42790a60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
D/PMS     (  908): releaseWL(42790a60): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): acquireWL(42773ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42773ef8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42750848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(42750848): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42731a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4349 uid=10041 gids={50041}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42731a20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): Sampling interval elapsed, updating statistics ..
,D/Process (  908): killProcessQuiet, pid=3492
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Killing 3492:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,D/PMS     (  908): acquireWL(42440900): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4133 10071 null
,D/ConnectivityService(  908): Done.
D/ConnectivityService(  908): Setting timer for 720seconds
,D/PMS     (  908): acquireWL(42403d90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4133 10071 null
,D/PMS     (  908): releaseWL(42440900): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  908): acquireWL(4234b8e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4133 10071 null
,D/PMS     (  908): acquireWL(42403d90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4133 10071 null
E/TodoTaskNotifyService( 4133): java.lang.NullPointerException
,W/System.err( 4133): java.lang.NullPointerException
W/System.err( 4133): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4133): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4133): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4133): stopSelfResult false
E/TodoTaskNotifyService( 4133): java.lang.NullPointerException
W/System.err( 4133): java.lang.NullPointerException
W/System.err( 4133): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4133): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4133): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4133): mStartingService is null
,W/NotifyReceiver( 4133): stopSelfResult true
I/ActivityManager(  908): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  908): releaseWL(4234b8e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  908): releaseWL(42403d90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
E/TodoTaskNotifyService( 4133): java.lang.NullPointerException
,W/System.err( 4133): java.lang.NullPointerException
W/System.err( 4133): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
D/PMS     (  908): acquireWL(41f70e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4133 10071 null
D/PMS     (  908): acquireWL(41e5dbd8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4133 10071 null
D/PMS     (  908): releaseWL(41f70e08): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  908): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
W/System.err( 4133): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4133): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4133): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4133): stopSelfResult true
D/PMS     (  908): releaseWL(41e5dbd8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
I/ActivityManager(  908): Recipient 3492
,D/LocationInitializer( 2185): Restart initialization of location
,E/MDM     ( 1221): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1369): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1369): Proximity feature is not enabled.
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,W/GCoreFlp( 1221): No location to return for getLastLocation()
,W/FusedLocationProvider( 1221): location=null
D/PMS     (  908): acquireWL(422b9290): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  908): Resuming delayed broadcast
D/PMS     (  908): releaseWL(422b9290): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (2185/10029)
,D/GCM     ( 1369): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  908): acquireWL(4221fc18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4249 10111 null
I/ActivityManager(  908): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  908): releaseWL(4221fc18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  908): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  908): Resuming delayed broadcast
,I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  908): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  908): acquireWL(4204c4e0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4204c4e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41e4fe70): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41e4fe70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(41aa1318): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(41aa1318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  908): acquireWL(42874608): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/SensorManager(  908): mEventCount = 450
,D/PMS     (  908): releaseWL(42874608): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42876050): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42876050): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428777e0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(428777e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42878c20): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42878c20): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4287a060): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4287a060): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4287b4a0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4287b4a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 285 ms] updated apps [took 285 ms] 
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  908): acquireWL(42885050): PARTIAL_WAKE_LOCK  AsyncService 0x1 3622 10160 null
,D/PMS     (  908): releaseWL(42885050): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  908): Resuming delayed broadcast
,I/WSP     ( 1339): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1339): Weather sync is On
,D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2185): Null package name or gms related package.  Ignoreing.
D/PMS     (  908): releaseWL(42575940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10055}
,I/ActivityManager(  908): Delay finish: com.htc.task/.TodoReceiver
,I/WSP     ( 1339): [Receiver] next auto-sync alarm event is 60 mins later, at time: Mon Jan 11 17:56:51 CET 2016
D/PMS     (  908): acquireWL(42889990): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2185): updateResources: need to parse f{com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/PMS     (  908): acquireWL(42890be0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1339 10055 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/TodoTaskshortcut( 4133): update TASK shortcut>
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(42897108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41cd6f28: PendingIntentRecord{42487a70 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58631, Int=0
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 6 times.
,V/AlarmManager(  908): sending alarm PendingIntent{42570638: PendingIntentRecord{4251a8d8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452527811967, Int=0
,I/Icing   ( 2185): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2185): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  908): releaseWL(42889990): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  908): killProcessQuiet, pid=4146
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4146:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4146
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  908): Client connection lost with reason: 4
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/GAV2    ( 4222): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  908): sending alarm PendingIntent{42478b18: PendingIntentRecord{424cc398 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452527813789, Int=0
,I/GAV4    ( 4249): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  908): sending alarm PendingIntent{4253d240: PendingIntentRecord{42446640 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452527813831, Int=0
,I/iu.UploadsManager( 2185): End new media; added: 0, uploading: 0, time: 72 ms
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:85, mTXpacketCount:57, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  908): acquireWL(428ae8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(428ae8a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,I/CalendarProvider2( 1508): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1508): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): acquireWL(428b4468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(428b4468): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428bafa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
D/PMS     (  908): acquireWL(428bf1a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 908 1000 null
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
D/ConnectivityService(  908): getActiveNetworkInfo called by  (908/1000)
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
D/PMS     (  908): acquireWL(428c17a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 908 1000 null
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(428bf1a0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  908): releaseWL(428c17a8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  908): acquireWL(428c9480): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4047 10154 null
I/ActivityManager(  908): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,D/PMS     (  908): releaseWL(428bafa0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4047): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4047): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/MusicLeanback( 4047): Conditions not met for autocaching.
,I/MusicLeanback( 4047): Stop autocaching.
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4047, uid=10154, userID:0
D/PMS     (  908): releaseWL(428c9480): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4402 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4402): Loading default preferences
,W/Resources( 4402): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  908): New client listening to asynchronous messages
,D/SyncApplication( 4402): Overriding preferences with custom values
,D/SyncApplication( 4402): Updating preferences succeeded
,E/SyncApplication( 4402): Application created.
D/VolumeInfo( 4402): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4402): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4402): Found 0 mount point(s)
,V/VolumeInfo( 4402): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4402): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4402): getNewCalendarAuthority()...
,D/SyncApplication( 4402): enableAppOperation()+
D/VolumeInfo( 4402): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4402): Can not create volume ID for unmounted volume null
D/SyncApplication( 4402): enableAppOperation()-
,D/HTCUtilities( 4402): isNeorSinged() + 
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4402, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4402, uid=10008, userID:0
W/PackageManager(  908): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4402): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4402): isNeorSinged() return false
,D/CDMountReceiver( 4402): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4402): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4402): enable CD Auto-mount: true
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/HTCUtilities( 4402): enable auto-mount
,D/HTCUtilities( 4402): enable auto-mount
,I/ActivityManager(  908): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  908): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  908): Resuming delayed broadcast
,D/PMS     (  908): releaseWL(42897108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e41270 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 2 16 5 11
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
I/ActivityManager(  908): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41c32518 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 0 10 3 16
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/CheckinService( 2185): Done disabling old GoogleServicesFramework version
I/PackageManager(  908):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2185, uid=10029, userID:0
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 7 times.
,W/MediaManager( 4027): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  908): Resuming delayed broadcast
,I/ActivityManager(  908): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4426 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/Process (  908): killProcessQuiet, pid=4068
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4068:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4068
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 4426): onCreate
D/ProviderChangeReceiver( 4426): ---------------------------------------------------
,D/ProviderChangeReceiver( 4426): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4426): start to updateAlertNotification!
,D/Process (  908): killProcessQuiet, pid=4115
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  908): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4440 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  908): Killing 4115:com.htc.sdm/u0a81 (adj 15): empty #17
,D/AlertService( 4426): No fired or scheduled alerts
,D/HtcAlertUtils( 4426): -- cancelReminderNotification --
,D/HtcAlertUtils( 4426): broadcastExistReminder!
I/ActivityManager(  908): Recipient 4115
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4440): [4440/4440] onCreate()
W/ContextImpl( 4440): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  908): Resuming delayed broadcast
,D/Process (  908): killProcessQuiet, pid=4183
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  908): Killing 4183:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4183
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/SensorManager(  908): mEventCount = 600
,D/PMS     (  908): acquireWL(427a9620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=67243, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(427a9620): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/ClockThread( 1115): now=1452527820462 next=59538
,D/PMS     (  908): acquireWL(42796178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{41f530c8: PendingIntentRecord{423ab350 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527820501, Int=0
,D/PMS     (  908): releaseWL(42796178): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3955): [407] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3955): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/PMS     (  908): releaseWL(42890be0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 8 times.
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{427159d0 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  908): acquireWL(41d04bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{42542770: PendingIntentRecord{42525418 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=70553, Int=0
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=55 rxSum=45} preTxRxSum={txSum=55 rxSum=45}
D/WifiDataStallTracker(  908): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19565 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19566 delay=15s
D/PMS     (  908): releaseWL(41d04bc0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(422dcc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(422dcc80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Finsky  ( 3955): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  908): acquireWL(41bb8d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,W/dalvikvm( 3955): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  908): sending alarm PendingIntent{427a01b0: PendingIntentRecord{426bec70 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527826125, Int=0
D/PMS     (  908): releaseWL(41bb8d98): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.android.vending (3955/10074)
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3955): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3955): [NET] getaddrinfo-,err=8
D/libc    ( 3955): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3955): [NET] getaddrinfo-, 1
D/libc    ( 3955): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8287 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3955): [NET] getaddrinfo_proxy-, success
I/global  ( 3955): call createSocket() return a new socket.
D/libc    ( 3955): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3955): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=14 [7][1][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/libc    ( 3955): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3955): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SensorManager(  908): mEventCount = 750
,W/NetworkManagementSocketTagger( 3955): untagSocket(69) failed with errno -22
,D/Finsky  ( 3955): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 9 times.
,W/NetworkManagementSocketTagger( 3955): untagSocket(69) failed with errno -22
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 3955): untagSocket(69) failed with errno -22
,D/ConnectivityService(  908): getNetworkInfo networkType=0 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/ConnectivityService(  908): getNetworkInfo networkType=1 called by com.android.vending (3955/10074)
,D/Finsky  ( 3955): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  908): acquireWL(4260cfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{42559270: PendingIntentRecord{427aa4e8 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1452527828490, Int=0
,D/PMS     (  908): acquireWL(424a5770): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3955 10074 null
,D/WearableService( 1221): callingUid 10029, callindPid: 1221
,D/Finsky  ( 3955): [417] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1221): client connected with version: 8296000
D/PMS     (  908): releaseWL(4260cfa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3955): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3955): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3955): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3955): [NET] getaddrinfo-,err=8
D/libc    ( 3955): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3955): [NET] getaddrinfo-, 1
,D/libc    ( 3955): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b4af +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
,D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3955): [NET] getaddrinfo_proxy-, success
,D/PMS     (  908): releaseWL(424a5770): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=4 [66][3][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:162, mTXpacketCount:85, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 10 times.
,D/AutoSetting( 1339): service - mHandler: update timezone
,D/AutoSetting( 1339): service - handleMessage() stop self
,D/AutoSetting( 1339): service - handleMessage() quit looper
,D/AutoSetting( 1339): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=4206
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  908): Killing 4206:com.htc.updater/u0a85 (adj 15): empty #17
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1508): service - onCreate()
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  908): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1508): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1508): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1508): service - mHandler: update timezone
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1508): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1508): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1508): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1578): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
I/ActivityManager(  908): Recipient 4206
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41ab8050 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 9 2 11
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  908): acquireWL(425a4728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
,D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(425a4728): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  908): mEventCount = 900
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 11 times.
,D/PMS     (  908): acquireWL(425bddd0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425bddd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=127 rxSum=112} preTxRxSum={txSum=55 rxSum=45}
D/WifiDataStallTracker(  908): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19566 Sent 0 pkts since last received, < watchdogTrigger=5
D/PMS     (  908): acquireWL(42859400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{4247c278: PendingIntentRecord{42525418 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=85564, Int=0
D/PMS     (  908): acquireWL(4271a7d0): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42859400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19567 delay=15s
,D/PMS     (  908): releaseWL(4271a7d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42802348): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42802348): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72,
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97",
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times.
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  908): mEventCount = 1050
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiStateMachine(  908): [ScoreAP] + current TXpacket:163, mTXpacketCount:162, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  908): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1508): handler message = 4011
,E/HtcModeClient( 1508): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1508): Don't start project servcice
,D/HtcModeClient( 1508): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1508): connectState: CONNECTION_READY = false
,D/SilentMusic( 1508): call stop
,D/HtcModeClient( 1508): close connection
,W/HtcModeClient( 1508): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1508): read the terminate packet, so break
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4275df18 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/PMS     (  908): acquireWL(42853148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10074}
,V/AlarmManager(  908): sending alarm PendingIntent{42421308: PendingIntentRecord{423ab350 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452527842682, Int=0
,I/ActivityManager(  908): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4471 uid=10078 gids={50078}
,V/AlarmManager(  908): sending alarm PendingIntent{41ab65a8: PendingIntentRecord{42364430 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452527848044, Int=60000
,D/PMS     (  908): releaseWL(42853148): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4471): SMSBackupAgentService started
,D/SMSBackup( 4471): Checking restore status
,D/SMSBackup( 4471): Restore complete
,D/SMSBackup( 4471): cancelCheckAlarm
,D/SMSBackup( 4471): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/Finsky  ( 3955): [407] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3955): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  908): killProcessQuiet, pid=4080
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4080:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4080
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/LightsService(  908): setLight #0: color=#26
,V/LightsService(  908): setLight #0: color=#23
,V/LightsService(  908): setLight #0: color=#19
,V/LightsService(  908): setLight #0: color=#14
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WifiDataStallTracker(  908): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  908): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  908): updateDataStallInfo: mDataStallTxRxSum={txSum=127 rxSum=112} preTxRxSum={txSum=127 rxSum=112}
D/WifiDataStallTracker(  908): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  908): onDataStallAlarm: tag=19567 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19568 delay=15s
D/PMS     (  908): acquireWL(42775438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
V/AlarmManager(  908): sending alarm PendingIntent{425b6318: PendingIntentRecord{42525418 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=100570, Int=0
D/PMS     (  908): releaseWL(42775438): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  908): mEventCount = 1200
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  908):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  908): Going to sleep due to screen timeout...
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@420e0360
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  908): mThumbnailWidth=360, mThumbnailHeight=640
,W/BatSI   (  908): Couldn't get kernel wake lock stats
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@420e0360, eanble = 0, strlen(mName) = 59
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  908): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10
W/SensorService(  908): Listener[1] = com.htc.smartdim.sensor_eye@4228cdf8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  908): setLight #2: color=#0
D/qdlights(  908): set_light_buttons_func: on=0 brightness=0
V/LightsService(  908): setLight #0: color=#0
,W/PMS     (  908): mWirelessDisplayManager is null
D/WirelessDisplayService(  908): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,D/SurfaceControl(  908): Excessive delay in blankDisplay() while turning screen off: 342ms
D/PMS     (  908): nativeSetInteractive:false
D/PMS     (  908): nativeSetInteractive:false done
D/PMS     (  908): nativeSetAutoSuspend:true
D/PMS     (  908): nativeSetAutoSuspend:true done
D/HABCtrl (  908): TPE algorithm. remove timeout.
D/PMS     (  908): OOBE c monitor 11
I/InputManager(  908): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  908): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  908): Disable input method client, pid=2796
D/NfcService( 1251): ScreenObserver: OFF
,D/NfcService( 1251): applyRouting - 0
,D/NfcService( 1251): applyRouting -2
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  908): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@428fe548)
D/PMS     (  908): acquireWL(4264ac98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  908): acquireWL(428fe0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(428fe0a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/ResourceType( 2796): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 2796): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=null, mServedView=org.apache.cordova.engine.SystemWebView{41a9dfb0 VFEDH.C. .F...... 0,0-720,1134 #64}
D/PMN     (  908): wakingUp
D/PMS     (  908): releaseWL(4264ac98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/KeyguardServiceDelegate(  908): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/WindowManager(  908): No lock screen! windowToken=null
D/PMN     (  908): onScreenOn
D/HtcPowerSaver(  908): updateBatteryInfo
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  908): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  908): BroadcastReceiver::onReceive+
D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,D/MtpService( 2434): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2434): [MTP][onReceive]-
,D/NfcService( 1251): applyRouting - 0
,D/AutoSetting( 1339): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1251): applyRouting -2
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
D/PMS     (  908): acquireWL(425de728): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1251 1027 null
D/PMS     (  908): releaseWL(425de728): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  908): ACTION_SCREEN_ON
I/AlarmManager(  908): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done recovering
I/AlarmManager(  908): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  908): [AlarmQueuing] done EPS screen off alarm recovering
,I/ClockThread( 1115): stop update clock
,D/AutoSetting( 1339): service - onCreate()
D/TetherSettings( 3837): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3837): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3837): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3837): Cust_ConnectToPC   : spcsc>false
D/        ( 3837): Cust_ConnectToPC   : IPT>true
D/        ( 3837): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3837): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3837): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3837): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  908): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  908): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  908): startDataStallAlarm: tag=19569 delay=15s
,D/AutoSetting( 1339): service - AddressCache: using context: com.htc.Weather
I/PSReceiver( 3837): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:On
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING (1)+
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,W/ContextImpl( 3837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/wpa_supplicant( 1133): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/SmartNS_PSService( 3837): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3837): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3837):  defaultType:0
,D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/WIFI_ICON( 1115): WifiActivity: 0
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/LocationManagerService(  908): request 4246e8e8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  908): provider request: passive ProviderRequest[ON interval=0]
,V/SRS_Proc(  370): ParamSet string: screen_state=on
,D/WirelessDisplayService(  908): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/NotificationService(  908): batLight: Full, plugged
V/LightsService(  908): setLight #8: color=#c8c800
D/qdlights(  908): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  908): setLight #8: color=#c800
D/qdlights(  908): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  908): [LedInfo] has indicator attribute
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  908): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  908): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  908): doBoolean: SignalStrength 97
,D/NetworkPolicy(  908): updateScreenOn: false
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1133): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  908): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4495 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  908): acquireWL(428a6398): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(428a6398): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4253e0d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1770): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): onScreenOn: 1452527856506
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1770): onScreenOn: 1452527856507
D/PMS     (  908): releaseWL(4253e0d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10
,W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
,W/SensorService(  908): Active sensors: size = 2
W/SensorService(  908): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41c75b10, eanble = 0, strlen(mName) = 91
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  908): Listener[0] = com.htc.smartdim.sensor_eye@4228cdf8
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  908): goingToSleep
D/PMS     (  908): acquireWL(42630fb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 908 1000 null
W/ContextImpl( 4495): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  908): ACTION_SCREEN_OFF
I/AlarmManager(  908): [AlarmQueuing] screen off now: 
I/AlarmManager(  908): [AlarmQueuing] data connection: true
,I/AlarmManager(  908): [AlarmQueuing] wifi connection: true
,D/WifiDataStallTracker(  908): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  908): stopDataStallAlarm: current tag=19569 mDataStallAlarmIntent=PendingIntent{424df538: PendingIntentRecord{42525418 android broadcastIntent}}
,D/WifiNative-wlan0(  908): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  908): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/PMS     (  908): releaseWL(42630fb8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): acquireWL(42735b68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 908 1000 null
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1133): SET_SCREEN_ON:Off
I/wpa_supplicant( 1133): htc_wext_set_keepalive +
I/wpa_supplicant( 1133): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1133): getPrivFuncNum +	
I/wpa_supplicant( 1133): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1133): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1133): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1133): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1133): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  908):    returned true
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/NetworkPolicy(  908): updateScreenOn: false
,D/ContactMessageStore( 1238): start background delete task...
D/ContactMessageStore( 1238): size: 0 , 0
,D/ContactMessageStore( 1238): Background delete complete
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
D/PMS     (  908): acquireWL(428160e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4495 1000 null
,D/wpa_supplicant( 1133): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  908):    returned true
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(42735b68): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/PMS     (  908): releaseWL(428160e0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4495): getMobilePolicyEnabled, result = true
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
I/PhoneStatusBar( 1115): removeHeadsNotification.gc: 55
,W/ContextImpl( 4495): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4495): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
D/WifiService(  908): New client listening to asynchronous messages
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4228cdf8
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 1
W/SensorService(  908): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4228cdf8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  908): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  908): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  908): pid=908, uid=1000
W/SensorService(  908): Active sensors: size = 0
W/SensorService(  908): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4228cdf8, eanble = 0, strlen(mName) = 36
W/SensorService(  908): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  908): void android::SensorService::listenerSensor(const char*, int32_t)--:
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,I/SensorManager(  908): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4228cdf8
E/ActivityThread(  908): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42335db8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42335db8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  908): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  908): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  908): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  908): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  908): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  908): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  908): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  908): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  908): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  908): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  908): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  908): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  908): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  908): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  908): acquireWL(4267b6a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4267b6a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427d7010): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1770): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): onScreenOff
,D/PMS     (  908): releaseWL(427d7010): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1770): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1770): onScreenOff
,D/AutoSetting( 1339): service - mHandler: cancel location update
,D/AutoSetting( 1339): service -           changes count: 0
,D/AutoSetting( 1508): service - handleMessage() stop self
,D/AutoSetting( 1508): service - onDestroy() END
,D/AutoSetting( 1508): service - handleMessage() quit looper
,D/Process (  908): killProcessQuiet, pid=3684
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 3684:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 3684
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1238): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  908): killProcessQuiet, pid=4096
,I/ActivityManager(  908): Killing 4096:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  908): Recipient 4096
,D/PMS     (  908): acquireWL(42873450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{42034dc0: PendingIntentRecord{4263f0f8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=117798, Int=0
,D/PMS     (  908): acquireWL(4288fe00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42873450): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0],
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL,
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL",
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): acquireWL(42616d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42616d48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(4288fe00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428dc520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(428dc520): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42839a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(42885578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428a8660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1221): Vacuum at: now=1452527870820 tag=VacuumService
,D/PMS     (  908): releaseWL(42839a48): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(42885578): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42801970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(42801970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(4268c840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  908): releaseWL(428a8660): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(4268c840): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42650308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(42650308): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(426f5de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/PMS     (  908): releaseWL(426f5de8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  908): acquireWL(426f3fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): acquireWL(425fbda0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(425fbda0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428fa400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): releaseWL(426f3fe8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(428f91a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(428f91a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  908): Waited long enough for: ServiceRecord{4272e598 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1221): Scheduling Phenotype for one-off execution 2880 seconds from now (1452527871673)
,D/GetConfigurationSnapshotOperation( 1221): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1221): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1221): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1221): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1221): [NET] getaddrinfo-, 1
,D/libc    ( 1221): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4c16 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1221): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
D/libc    ( 1221): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1221): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  908): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by com.google.android.gms (1221/10029)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
,D/PMS     (  908): releaseWL(428fa400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(42834170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
,W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(42834170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  908): acquireWL(427abd30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1369 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
,W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1133): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  908): doString: SIGNAL_POLL
W/WifiHW  (  908): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1133): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1133): nl80211: survey data missing!
E/wpa_supplicant( 1133): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1133): environment dirty rate=0 [0][0][0]
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023665
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023804
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023877
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023880
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023884
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360023888
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025193
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360025207
W/AlarmManager(  908): Converted elapesd time is over 1 year! when = 315360028237
,D/PMS     (  908): releaseWL(427abd30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  908): acquireWL(4234f078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=127243, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4234f078): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(41bce5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
,D/UsbnetService(  908): onReceive BATTERY_CHANGED
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
I/BatteryService(  908): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  908): updateBatteryInfo
D/PMS     (  908): releaseWL(41bce5d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
I/HtcPowerSaver(  908): >> updateStatus
,I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42306960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  908): sending alarm PendingIntent{425b7ff8: PendingIntentRecord{425c22e0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=133962, Int=0
,D/PMS     (  908): releaseWL(42306960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  908): getActiveNetworkInfo called by  (1369/10029)
,D/AutoSetting( 1339): service - handleMessage() stop self
,D/AutoSetting( 1339): service - handleMessage() quit looper
,D/AutoSetting( 1339): service - onDestroy() END
,D/Process (  908): killProcessQuiet, pid=4330
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4330:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4330
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  908): acquireWL(427221e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{4239f888: PendingIntentRecord{424d5ab8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141065, Int=0
,D/GpsLocationProvider(  908): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  908): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  908): acquireWL(42638fa0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 908 1000 null
D/PMS     (  908): releaseWL(427221e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  908): [NET] getaddrinfo-,err=8
D/libc    (  908): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  908): [NET] getaddrinfo-, 1
,D/libc    (  908): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =1598 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE,
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=243
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  908): [NET] getaddrinfo_proxy-, success
I/global  (  908): call createSocket() return a new socket.
D/libc    (  908): [NET] getaddrinfo+,hn 14(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  908): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  908): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  908): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  908): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  908):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  908): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  908): releaseWL(42638fa0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  908): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  908): acquireWL(42438cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42438cf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  908): acquireWL(4235fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{10027}
,V/AlarmManager(  908): sending alarm PendingIntent{425e7890: PendingIntentRecord{425afbe8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=169871, Int=0
,D/PMS     (  908): releaseWL(4235fb50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1238): switchBindHtcMsgCursor: null
,D/PMS     (  908): acquireWL(4258ee68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=187242, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4258ee68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42801e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42801e28): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(422609d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  908): BroadcastReceiver::onReceive+
I/BatteryService(  908): n_update end
D/UsbnetService(  908): onReceive BATTERY_CHANGED
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  908):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  908): BroadcastReceiver::onReceive-
,D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  908): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  908): releaseWL(422609d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  908): runPSCheck
D/HtcPowerSaver(  908): Checking...
,I/HtcPowerSaver(  908): >> updateStatus
D/DotMatrix( 1578): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1578): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  908): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  908): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(4288aa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=247242, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(4288aa40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425e7008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425e7008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  908): acquireWL(423326e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=307242, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(423326e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(42482118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(42482118): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/Process (  908): killProcessQuiet, pid=4349
,D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  908): Killing 4349:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  908): Recipient 4349
,I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  908): acquireWL(42812d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 908 1000 WorkSource{1000}
,V/AlarmManager(  908): sending alarm PendingIntent{41ebace8: PendingIntentRecord{41e51b80 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=367242, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  908): releaseWL(42812d78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  908): acquireWL(425f36b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  908): n_update end
,D/PMS     (  908): releaseWL(425f36b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,TIME-OUT KILL (timeout was 360000ms),E/cutils-trace( 4540): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4540): ====startRecUseTime====
D/htc.customization.log.level( 4540):  is 
W/CustomizationLogLevel( 4540): Level value is invalid, use default level 2
D/CustomizationManager( 4540):  Read ACC file spent 0.123 (s)
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4540): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4540): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4540): Parsing tag category name = system
I/CustomizationCIDLoader( 4540): Parsing tag category name = application
I/CustomizationCIDLoader( 4540): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4540): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4540): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4540): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4540): Parsing tag category name = Settings
D/CustomizationManager( 4540):  Read CID file spent 0.177 (s)
D/CustomizationManager( 4540):  All configurations done spent 0.177 (s)
W/HtcNativeFlag( 4540): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4540): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4540): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4540): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  908): deletePackageAsUser: pkg=com.example.hello, pid=4540, uid=2000 user=0
I/ActivityManager(  908): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
D/Process (  908): killProcessQuiet, pid=2796
I/ActivityManager(  908): Killing 2796:com.example.hello/u0a397 (adj 0): stop com.example.hello
D/Process (  908): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  908): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  908):   Force finishing activity ActivityRecord{423b77e8 u0 com.example.hello/.MainActivity t2}
W/PackageSettings(  908): Skipping PackageSetting{4220aab8 com.test.thalitest/10389} due to missing metadata
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  908): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1208): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  908): Got RemoteException sending setActive(false) notification to pid 2796 uid 10397
I/ActivityManager(  908): Force stopping com.example.hello appid=10397 user=0: pkg removed
D/DotMatrix( 1578): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1578): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1578): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/WindowState(  908): WIN DEATH: Window{42438650 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  908): acquireWL(42766740): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1221 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1221): Ignoring removeGeofence because network location is disabled.
W/SQLiteConnectionPool( 2185): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/PMS     (  908): releaseWL(42766740): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/VoicemailCleanupService( 1284): Cleaning up data for package: com.example.hello
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/Launcher( 1269): Deferring update until onResume
D/Launcher( 1269): waitUntilResume // bindAppsRemoved
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1251): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/InputMethodManagerService(  908): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Prism.PackageStateRece_( 1269): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "sms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "smsto"
I/IcingCorporaProvider( 2911): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mms"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/PackageManager(  908):   Action: "android.intent.action.SENDTO"
I/PackageManager(  908):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  908):   Scheme: "mmsto"
I/PackageManager(  908): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1238 :
I/ActivityManager(  908): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4555 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/ExternalAccountType( 1327): Unsupported attribute readOnly
D/PhoneApp( 1238): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  908): acquireWL(426e5838): PARTIAL_WAKE_LOCK  Icing 0x1 2185 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2911): UpdateCorporaTask done [took 266 ms] updated apps [took 266 ms] 
D/PMS     (  908): acquireWL(425b8ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  908): n_update end
D/PMS     (  908): releaseWL(425b8ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
E/SQLiteDatabase( 4555): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4555): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4555): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4555): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4555): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4555): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4555): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4555): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4555): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4555): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4555): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4555): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4555): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4555): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4555): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4555): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4555): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4555): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4555): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4555): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4555): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4555): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4555): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4555): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4555): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4555): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4555): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4555): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4555): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4555): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4555): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4555): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4555): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4555): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4555): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4555): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4555): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4555): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4555): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4555): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4555): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4555): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4555): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4555): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4555): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4555): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4555): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4555): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4555): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4555): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4555): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4555): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4555): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4555): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4555): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4555): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4555): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4555): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4555): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4555): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4555): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4555): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4555): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4555): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4555): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4555): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4555): threadid=11: thread exiting with uncaught exception (group=0x4165ce30)
E/ActivityManager(  908): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4555): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4555): Process: com.google.android.apps.docs, PID: 4555
E/AndroidRuntime( 4555): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4555): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4555): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4555): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4555): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4555): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4555): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4555): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4555): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 4555): killProcess, pid=4555
D/Process ( 4555): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  908): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4575 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Recipient 4555
I/ActivityManager(  908): Process com.google.android.apps.docs (pid 4555) has died.
W/ContextImpl( 4575): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  908): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4588 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4575): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4575): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4575): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4575): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4575): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4575): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4575): threadid=10: thread exiting with uncaught exception (group=0x4165ce30)
E/AndroidRuntime( 4575): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4575): Process: com.android.keychain, PID: 4575
E/AndroidRuntime( 4575): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4575): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4575): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4575): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4575): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4575): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4575): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4575): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4575): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  908): App crashed! Process: com.android.keychain
D/ErrorReport(  908): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4575): killProcess, pid=4575
D/Process ( 4575): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
D/AppTag  ( 4588): getInstance(Context context)
E/ErrorReport(  908): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  908): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452528157744.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  908): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  908): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  908): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  908): 	... 4 more
I/ActivityManager(  908): Recipient 4575
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  908): Process com.android.keychain (pid 4575) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4588): getInstance(Context context)
D/AppTag  ( 4588): onCreate()
D/PMS     (  908): acquireWL(428511d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3622 10160 null
D/PMS     (  908): releaseWL(428511d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3955): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2185): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 2185): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2185): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2185): Module APK com.google.android.play.games already loaded
I/ActivityManager(  908): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2185): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 2185): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2185): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2185): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e274008
E/SQLiteDBG( 2185): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x652dc370
W/dalvikvm( 2185): threadid=45: thread exiting with uncaught exception (group=0x4165ce30)
E/DriveAsyncService( 2185): disk I/O error (code 3850)
E/DriveAsyncService( 2185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2185): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2185): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2185): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2185): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2185): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2185): Process: com.google.android.gms, PID: 2185
E/AndroidRuntime( 2185): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2185): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2185): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2185): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2185): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2185): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2185): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2185): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2185): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2185): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  908): App crashed! Process: com.google.android.gms
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 2185): killProcess, pid=2185
E/SQLiteDatabase( 2185): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2185): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/SQLiteOpenHelper( 2185): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2185): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2185): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2185): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2185): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2185): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2185): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2185): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2185): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2185): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1269): loadItems() com.htc.launcher.pageview.WidgetManager@41b21bd0 +
I/Prism.WidgetManager( 1269): onLoadItems() +
D/PMS     (  908): handleWLDeath(426e5838): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  908): Recipient 2185
I/DisplayManagerService(  908): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  908): Client connection lost with reason: 4
I/ActivityManager(  908): Process com.google.android.gms (pid 2185) has died.
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20999ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20998ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20998ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20997ms
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30997ms
I/ActivityManager(  908): Resuming delayed broadcast
E/SQLiteLog( 1369): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1369): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63ef1ad8
W/ActivityManager(  908): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30988ms
W/dalvikvm( 1369): threadid=1: thread exiting with uncaught exception (group=0x4165ce30)
E/AndroidRuntime( 1369): FATAL EXCEPTION: main
E/AndroidRuntime( 1369): Process: com.google.process.gapps, PID: 1369
E/AndroidRuntime( 1369): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1369): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1369): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1369): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1369): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1369): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1369): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1369): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1369): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1369): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1369): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1369): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1369): 	... 10 more
E/ActivityManager(  908): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  908): Can't write: system_app_crash
E/DropBoxManagerService(  908): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  908): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  908): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  908): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  908): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  908): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  908): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  908): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  908): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  908): 	... 5 more
D/Process ( 1369): killProcess, pid=1369
D/Process ( 1369): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  908): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4621 uid=10098 gids={50098, 3003, 5012}

```
