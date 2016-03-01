#### Test 61248225a3bd1fe_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
W/PackageManager(  984): Unable to load service info ResolveInfo{42e7b3f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  984): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  984): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  984): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  984): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  984): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  984): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  984): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  984): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  984): 	at dalvik.system.NativeStart.main(Native Method)
,--------- beginning of /dev/log/system
D/RemoteDisplayProvider(  984): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  984): start
I/ContactAccountLoggerTas( 3146): canRun() : Opted Out
W/asset   ( 3146): Copying FileAsset 0x66f7a068 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/GAV2    ( 2974): Thread[GAThread,5,main]: No campaign data found.
D/PMS     (  984): acquireWL(42da40e0): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 3146): UpdateCorporaTask done [took 996 ms] updated apps [took 996 ms] 
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42fe7130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): releaseWL(4306cd78): PARTIAL_WAKE_LOCK  *sync*/com.htc.task.dm/com.google/***** 0x1 WorkSource{10068}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): acquireWL(42ec6a50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 984 1000 WorkSource{10100}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  984): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=3225 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  984): releaseWL(42fe7130): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42ef4358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
D/MyReportAgent( 2991): ReportService [##] onDestroy(), this =com.htc.reportagent.ReportService@422dc790
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/Process (  984): killProcessQuiet, pid=2600
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 2600:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/PMS     (  984): releaseWL(42eccae0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.cloudprint.cloudprintprovider/com.google/***** 0x1 WorkSource{10097}
D/Process (  984): killProcessQuiet, pid=2863
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Process (  984): killProcessQuiet, pid=2389
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  984): Killing 2863:com.google.android.syncadapters.calendar/u0a108 (adj 15): empty #17
I/ActivityManager(  984): Killing 2389:com.google.android.videos/u0a165 (adj 15): empty #18
E/cutils-trace( 3217): Error opening trace file: No such file or directory (2)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
I/ActivityManager(  984): Recipient 2863
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  984): Recipient 2389
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  984): Client com.google.android.videos (pid 2389): Died!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): acquireWL(42f13490): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 984 1000 WorkSource{10029}
D/PMS     (  984): releaseWL(42ef4358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/ActivityManager(  984): Recipient 2600
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42df3358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42df3358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@4235dd10 +
I/Prism.WidgetManager( 1274): onLoadItems() +
I/RemindersSync( 2208): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=213:priority=5:group=main]
D/CustomizationManager( 3217): ====startRecUseTime====
D/htc.customization.log.level( 3217):  is 
W/CustomizationLogLevel( 3217): Level value is invalid, use default level 2
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(430e6538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42f13490): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 WorkSource{10029}
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  984): acquireWL(42e1c368): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 984 1000 WorkSource{10029}
D/PMS     (  984): releaseWL(430e6538): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42f7b018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42f7b018): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/CustomizationManager( 3217):  Read ACC file spent 0.073 (s)
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3217): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3217): Parsing tag category name = system
I/CustomizationCIDLoader( 3217): Parsing tag category name = application
I/CustomizationCIDLoader( 3217): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3217): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3217): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3217): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3217): Parsing tag category name = Settings
D/CustomizationManager( 3217):  Read CID file spent 0.120 (s)
D/CustomizationManager( 3217):  All configurations done spent 0.120 (s)
W/HtcNativeFlag( 3217): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3217): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3217): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3217): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  984): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  984): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  984): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  984): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  984): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  984): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  984): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3217
D/PMS     (  984): acquireHCC(43073080): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 984 1000 null
W/asset   (  984): Copying FileAsset 0x62bb8d68 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  984): @test_code: getHtcIntentFlag: 0 obj: 1122921576
D/PMS     (  984): acquireHCC(4300fa90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 984 1000 null
D/PMS     (  984): acquireWL(43089778): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 984 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42735c20
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
I/ActivityManager(  984): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3250 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
W/asset   ( 3250): Copying FileAsset 0x5c7b1988 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1274): [trimMemory] 20
I/ActivityManager(  984): Waited long enough for: ServiceRecord{42de14c0 u0 com.htc.autobot/.htcmodeclient.HtcModeService}
V/WebViewChromiumFactoryProvider( 3250): Binding Chromium to main looper Looper (main, tid 1) {422c57c0}
I/LibraryLoader( 3250): Expected native library version number "",actual native library version number ""
I/chromium( 3250): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  984): Resuming delayed broadcast
I/BrowserStartupController( 3250): Initializing chromium process, renderers=0
D/PMS     (  984): acquireWL(42ec7260): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  984): acquireWL(43051598): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  984): java.lang.Throwable: stack dump
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  984): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  984): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ed1448:true
D/BluetoothAdapter( 3250): 1110302080: getState(). Returning 12
D/PMS     (  984): releaseWL(42ec7260): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  984): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3272 uid=10090 gids={50090, 3003, 5012, 1028}
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(430d0eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (3225/10100)
I/Adreno-EGL( 3250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3250): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3250): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3250): Local Branch: 
I/Adreno-EGL( 3250): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3250): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3250):                  aa63bbd948f41d15fc72f585e
W/GAV2    ( 3225): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (3225/10100)
D/PMS     (  984): releaseWL(430d0eb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  984): acquireWL(430df0e8): PARTIAL_WAKE_LOCK  SyncManager 0x1 3225 10100 null
D/WifiService(  984): acquireWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42fd9430}
W/chromium( 3250): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/BaseAppContext( 1225): Using Auth Proxy for data requests.
W/dalvikvm( 3250): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3250): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 3250): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3250): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3250): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 1225): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1225): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/dalvikvm( 3250): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3250): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3250): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
E/BaseAppContext( 1225): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/SystemWebViewEngine( 3250): CordovaWebView is running on device made by: HTC
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42f25e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  984): Delay finish: com.htc.android.worldclock/.alarmclock.AlarmReceiver
I/WorldClock.Global( 3272): isHtcDevice = true
D/PMS     (  984): acquireWL(42f93480): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 3272 10090 null
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): releaseWL(42f25e10): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/HtcModeClient( 1528): handler message = 4011
E/HtcModeClient( 1528): Check connection and retry 3 times.
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1163): Change stage from stage0 to stage3
I/wpa_supplicant( 1163): Don't scan again before 3 minutes, avoid too many scan when stage change frequently
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
W/WorldClock.AlarmService( 3272): updateAlarms: AlarmUtils.disableExpiredAlarms fail e = java.lang.NullPointerException
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/libc    ( 3225): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 4
D/libc    ( 3225): [NET] getaddrinfo-,err=8
D/libc    ( 3225): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    ( 3225): [NET] getaddrinfo-, 1
D/libc    ( 3225): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x73736c2e677374),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =7618 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
I/WorldClock.AlarmUtils( 3272): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/WorldClock.AlarmUtils( 3272): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3272): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
W/AwContents( 3250): nativeOnDraw failed; clearing to background color.
E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@4235dd10 -
I/ActivityManager(  984): Resuming delayed broadcast
D/PMS     (  984): releaseWL(42f93480): PARTIAL_WAKE_LOCK  AlarmAlertWakeLock_600 0x1 null
I/ActivityManager(  984): Delay finish: com.htc.android.worldclock/.stopwatch.StopwatchReceiver
I/InputMethodManagerService(  984): Disable input method client, pid=1274
W/ResourceType( 3250): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3250): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@4230f1f0, mServedView=org.apache.cordova.engine.SystemWebView{422d50a0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  984): Enable input method client, pid=3250
W/XT9_C   ( 1211): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1211): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1211): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/WorldClock.Global( 3272): isHtcDevice = true
W/AwContents( 3250): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Delay finish: com.htc.android.worldclock/.timer.TimerReceiver
I/ActivityManager(  984): Displayed com.example.hello/.MainActivity: +339ms
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Start proc com.htc.mobiledata for broadcast com.htc.mobiledata/com.htc.omacp.OmaCPPushReceiver: pid=3336 uid=10091 gids={50091, 3003, 5012}
D/PMS     (  984): releaseWL(43089778): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/OmaCPPushReceiverV2( 3336): initialCheck: sku=99, result=false
I/ActivityManager(  984): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3348 uid=10091 gids={50091, 3003, 5012}
D/Process (  984): killProcessQuiet, pid=2826
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 2826:com.htc.sense.mms/u0a65 (adj 15): empty #17
I/ActivityManager(  984): Recipient 2826
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
I/Icing   ( 2208): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.BootCompletedReceiver: pid=3365 uid=10098 gids={50098, 3003, 5012}
D/Process (  984): killProcessQuiet, pid=2991
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 2991:com.htc.reportagent/u0a66 (adj 15): empty #17
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Recipient 2991
E/AndroidProtocolHandler( 3250): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 263
D/libc    (  363): [NET]res_nsend:resplen=49
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3225): [NET] getaddrinfo_proxy-, success
I/global  ( 3225): call createSocket() return a new socket.
D/libc    ( 3225): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 3225): [NET] getaddrinfo-, SUCCESS
I/chromium( 3250): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/Icing   ( 2208): Loaded CLD2 Version V2.0 - 20141016
I/DeviceManagement( 3365): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3365 dbg=false s=true
I/DeviceManagement( 3365): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.BootCompletedWorkflow] args=[null]
I/DeviceManagement( 3365): WorkflowService: Starting workflow service
I/DeviceManagement( 3365): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@422f9460] args=[Bundle[EMPTY_PARCEL]]
I/DeviceManagement( 3365): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3365): BootCompletedWorkflow: Boot completed
I/ActivityManager(  984): Delay finish: com.htc.cs.dm/.receiver.BootCompletedReceiver
I/DeviceManagement( 3365): BootCompletedWorkflow: ==================================================
I/DeviceManagement( 3365): ModelRegistry: Loading model meta data from resources...
D/JsMessageQueue( 3250): Set native->JS mode to OnlineEventsBridgeMode
I/DeviceManagement( 3365): BackgroundController: *** Update after boot...
I/DeviceManagement( 3365): SessionStateController: Checking invariants...
I/DeviceManagement( 3365): BackgroundController: Invariants are unchanged.
I/DeviceManagement( 3365): SessionStateController: Checking invariants...
D/jxcore_app_log( 3250): JniHelper::setJavaVM(0x41e89010), pthread_self() = 1658584192
D/JX-Cordova( 3250): jxcore cordova android initializing
I/Icing   ( 2208): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
I/DeviceManagement( 3365): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
D/PMS     (  984): releaseWL(42da40e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Delay finish: com.google.android.gm/.GoogleMailDeviceStartupReceiver
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GoogleMailWidgetProvider, state=2, flag=1, pid=2906, uid=10107, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.widget.GmailWidgetProvider, state=1, flag=1, pid=2906, uid=10107, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGoogleMail, state=2, flag=1, pid=2906, uid=10107, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.CreateShortcutActivityGmail, state=1, flag=1, pid=2906, uid=10107, userID:0
I/ActivityManager(  984): Resuming delayed broadcast
W/jxcore-log( 3250): Initializing JXcore engine
W/jxcore-log( 3250): JXcore engine is ready
I/ActivityManager(  984): Delay finish: com.google.android.gm/.MailIntentReceiver
W/jxcore-log( 3250): Starting JXcore engine
V/AlarmManager(  984): sending alarm PendingIntent{42bed430: PendingIntentRecord{42ef9aa8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1456842796824, Int=0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gm, clsName=com.google.android.gm.ComposeActivityGmail, state=1, flag=1, pid=2906, uid=10107, userID:0
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Start proc com.htc.backup for broadcast com.htc.backup/.receiver.ScheduleBackupReceiver: pid=3389 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DeviceManagement( 3365): Perf: *** Cache update - start...
I/DeviceManagement( 3365): Perf: *** Enabled app cache update - start...
I/DeviceManagement( 3365): EnabledAppController: *** Updating enabled app database...
I/DeviceManagement( 3365): EnabledAppController: Enabled app scan is pending...
I/DeviceManagement( 3365): Perf: Scan enabled apps - start...
W/jxcore-log( 3250): Platform android
W/jxcore-log( 3250): 
W/jxcore-log( 3250): Process ARCH arm
W/jxcore-log( 3250): 
I/DeviceManagement( 3365): EnabledAppBuilder: Examining 251 installed apps for DM enabled apps...
,I/iu.UploadsManager( 2208): End new media; added: 0, uploading: 0, time: 210 ms
D/libc    ( 1225): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b1f7 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
,I/jxcore-log( 3250): JXcore Cordova bridge is ready!
I/jxcore-log( 3250): 
,W/jxcore-log( 3250): JXcore engine is started
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.reportagent, versionKey=687983cc-3a99-4a94-8c51-4a06dce9d091, versionCode=621000240, versionName=6.0.787896
,D/libc    ( 1225): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,I/htcbackup-core( 3389): ModelRegistry: Loading model meta data from resources...
,E/jxcore-log( 3250): >> HTC-HTC Desire 820
E/jxcore-log( 3250): 
,I/jxcore-log( 3250): Total memory 1964650496
I/jxcore-log( 3250): 
I/jxcore-log( 3250): Free memory 620388352
I/jxcore-log( 3250): 
I/jxcore-log( 3250): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3250): 
,W/ContextImpl( 3389): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/jxcore-log( 3250): userPath [ 'www', 'www' ]
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): Size 720 1184
I/jxcore-log( 3250): 
D/libc    ( 3225): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 4
D/libc    ( 3225): [NET] getaddrinfo-,err=8
D/libc    ( 3225): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 1024
D/libc    ( 3225): [NET] getaddrinfo-, 1
,D/libc    ( 3225): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646f63732e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f7e9 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,I/jxcore-log( 3250): Screen Brightness 142
I/jxcore-log( 3250): 
,E/jxcore-log( 3250): Dummy Error Log.
E/jxcore-log( 3250): 
W/ContextImpl( 3389): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,W/ContextImpl( 3389): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.backup.receiver.ClearEngineStatusReceiver.onReceive:59 android.app.ActivityThread.handleReceiver:2687 
I/DeviceManagement( 3365): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/ActivityManager(  984): Delay finish: com.htc.backup/.receiver.ClearEngineStatusReceiver
I/DeviceManagement( 3365): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.mirrorlinkserver, com.htc.backup, com.htc.checkinprovider, com.htc.backupreset, com.htc.htcpowermanager, com.htc.cirmodule, com.qualcomm.timeservice, com.android.CSDFunctionG, com.htc.lockscreen, com.htc.drive.activator, com.android.keychain, com.android.providers.settings, com.android.settings, com.htc.usage, android, com.htc.android.htcloglevel, com.android.inputdevices, com.android.location.fused, com.htc.autobot.cargps.provider, com.htc.android.htcsetupwizard, com.htc.home.personalize, com.qualcomm.privinit, com.htc.smartdim, com.htc.feedback, com.htc.guide]
D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
I/RemoteViews( 1117): com.htc.backup (true,33751552)
I/DeviceManagement( 3365): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{423515a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.backup 3 12 4 15
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4235a8f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1117): com.htc.backup 1 3 5 4
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1117): com.htc.backup 1 1 1 4
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1117): com.htc.backup 1 1 0 4
,I/RemoteViews.Performance( 1117): com.htc.backup 1 7 17 21
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 281
D/libc    (  363): [NET]res_nsend:resplen=129
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=6
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3225): [NET] getaddrinfo_proxy-, success
I/global  ( 3225): call createSocket() return a new socket.
D/libc    ( 3225): [NET] getaddrinfo+,hn 14(0x36342e3233332e),sn(),family 0,flags 4
,D/libc    ( 3225): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=3 [27][1][0]
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  984):    returned true
D/WifiStateMachine(  984): [ScoreAP] + current TXpacket:220, mTXpacketCount:28, avgLinkspeed:72,mAvgTxRate54
,D/WifiStateMachine(  984): [ScoreAP] + TX packet increase one time, don't update TX rate in DB
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.dm, versionKey=b5b04a47-d585-4433-9a63-6f3f39989144, versionCode=234300090, versionName=2.1.784944
D/libc    ( 1225): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.aurora, versionKey=ddcde851-94d3-4ce2-896c-ddafd2987e4a, versionCode=333000980, versionName=3.0.820350
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, versionCode=658031431, versionName=6.3.855736
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs, versionKey=c6ccd8f9-a6ae-4693-84eb-554f8aa4ba17, versionCode=639001000, versionName=6.0.811021
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, versionCode=129300230, versionName=1.1.840085
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, versionCode=441001820, versionName=4.0.840038
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.csrecommend, versionKey=f26b54be-e9ca-4494-ba25-56712573f3ab, versionCode=231000600, versionName=2.0.787746
,I/DeviceManagement( 3365): EnabledAppMetaData: *** Found DM enabled app: appID=com.htc.sense.socialnetwork.facebook, versionKey=2adae5da-a4df-4cc3-b772-ea9aaa6301b2, versionCode=658001308, versionName=6.0.849536
,I/GCoreUlr( 1225): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/DeviceManagement( 3365): EnabledAppBuilder: Found 9 DM enabled apps.
,I/GCoreUlr( 1225): DispatchingService.onCreate()
,I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.reportagent
,I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.dm
,I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.aurora
,I/jxcore-log( 3250): getBuffer is called!!!!
I/jxcore-log( 3250): 
,I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.launcher
,I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42db9540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42e1c368): PARTIAL_WAKE_LOCK  *sync*/com.google.android.location.reporting/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [10][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.cs.pushclient
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.backup
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  984): acquireWL(42e52908): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.csrecommend
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  984): acquireWL(42d55888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 984 1000 WorkSource{10029}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
I/DeviceManagement( 3365): EnabledAppController: Nothing appears to have changed for appID=com.htc.sense.socialnetwork.facebook
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0,
I/DeviceManagement( 3365): Perf: Scan enabled apps - complete: 854 ms
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
I/DeviceManagement( 3365): Perf: *** Enabled app cache update - complete: 855 ms
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/DeviceManagement( 3365): Perf: *** Config cache update - start...
,D/PMS     (  984): releaseWL(42db9540): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/DeviceManagement( 3365): ConfigCacheController: *** Updating config cache...
I/DeviceManagement( 3365): ConfigCacheController: *** Updating stale config cache entries...
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42cbd098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42cbd098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GCoreUlr( 1225): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/dalvikvm( 3365): VFY: unable to resolve static method 10661: Lcom/sun/net/httpserver/HttpServer;.create (Ljava/net/InetSocketAddress;I)Lcom/sun/net/httpserver/HttpServer;
I/GCoreUlr( 1225): Unbound from all location providers
I/GCoreUlr( 1225): Place inference reporting - stopped
W/dalvikvm( 3365): VFY: unable to resolve virtual method 10666: Lcom/sun/net/httpserver/HttpServer;.stop (I)V
,W/dalvikvm( 3365): Link of class 'Lorg/restlet/engine/connector/HttpServerHelper$1;' failed
D/PMS     (  984): acquireWL(42db7b08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(42db7b08): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(42e52908): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42d57f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  984): releaseWL(42d55888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
W/System.err( 3365): Starting the internal HTTP client
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/GCoreUlr( 1225): DispatchingService.onDestroy()
I/GCoreUlr( 1225): Stopping handler for UlrDispSvcFast
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
I/DeviceManagement( 3365): ConfigCacheController: Getting config update from server: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.launcher/versions/b354e2de-d3af-4a3f-b5dc-8239e0d5da72/cid/MDoxNToyMDE1LTEyLTI0VDA5OjIwOjU2LjA5NFo
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): acquireWL(42ca46b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/GCoreUlr( 1225): Unbound from all location providers
,I/GCoreUlr( 1225): Place inference reporting - stopped
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
D/PMS     (  984): acquireWL(42db8f08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 984 1000 WorkSource{10029}
D/PMS     (  984): releaseWL(42ca46b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  984): releaseWL(42d57f78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42eb3b40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42eb3b40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DeviceManagement( 3365): DeviceClientResource: Active network...
I/DeviceManagement( 3365):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/BuildInfo( 3365): Created new instance: com.htc.cs.lib.hms.BuildInfo@426c6820
I/DeviceManagement( 3365): Version: Hello, this is: cs-lib-hms/1.3.4.6 (release)
,E/Auth.Api.Credentials( 2208): [CredentialSyncAdapter] Unknown sync event.
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
,D/libc    ( 3365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
,D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42f44450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42db8f08): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  984): acquireWL(42ca5fd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 984 1000 WorkSource{10160}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/ActivityManager(  984): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=3417 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/PMS     (  984): releaseWL(42f44450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3365): [NET] getaddrinfo-,err=8
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =4659 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/CpuWake (  984): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  984): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  984): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  984): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  984): >>release mCpuPerf_Freq wakelock
W/CpuWake (  984): <<release mCpuPerf_Freq wakelock
D/PMS     (  984): releaseHCC(43073080): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  984): releaseHCC(4300fa90): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42f3af30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42f3af30): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=204
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
D/PMS     (  984): acquireWL(42e459f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3417 10160 null
,D/PMS     (  984): acquireWL(42e7d568): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3417 10160 null
,D/PMS     (  984): releaseWL(42e459f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (3417/10160)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.plus (3417/10160)
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42ed5de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  984): releaseWL(42ca5fd0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): acquireWL(430e7788): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 984 1000 WorkSource{10029}
,D/PMS     (  984): releaseWL(42ed5de8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42f10ef0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42f10ef0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  984): releaseWL(42e7d568): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  984): killProcessQuiet, pid=2974
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 2974:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360052144
W/AlarmManager(  984): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42fc2530: PendingIntentRecord{42de04b8 com.google.android.gms startService}}) : type=2 triggerAtTime=315360052144 win=-1 tElapsed=315360052144 maxElapsed=551880052142 interval=0 standalone=false
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028823
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028959
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029206
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029209
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029215
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029222
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030820
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030840
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360034486
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(43017ef8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  984): releaseWL(430e7788): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1163): Change stage from stage3 to stage0
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
D/PMS     (  984): acquireWL(42e4bd20): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 984 1000 WorkSource{10029}
D/PMS     (  984): releaseWL(43017ef8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42e33bb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42e33bb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  984): Recipient 2974
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42c17d20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  984): releaseWL(42e4bd20): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.reminders/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  984): acquireWL(42b2e368): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 984 1000 WorkSource{10108}
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  984): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=3446 uid=10108 gids={50108, 3003, 5012}
,D/PMS     (  984): releaseWL(42c17d20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/AbstractGoogleClient( 3446): Application name is not set. Call Builder#setApplicationName.
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(427fa468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(427fa468): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/DeviceManagement( 3365): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3365): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3365): DeviceClientResourceController: handleDirectives: []
,W/dalvikvm( 3365): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;)
,W/dalvikvm( 3365): VFY: unable to resolve virtual method 8166: Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;.schemaFor (Ljava/lang/Class;)Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.smile.SmileFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3365): VFY: unable to resolve new-instance 808 (Lcom/fasterxml/jackson/dataformat/smile/SmileFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3365): VFY: unable to resolve static method 11799: Ljavax/xml/stream/XMLInputFactory;.newFactory ()Ljavax/xml/stream/XMLInputFactory;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.yaml.YAMLFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
,W/dalvikvm( 3365): VFY: unable to resolve new-instance 811 (Lcom/fasterxml/jackson/dataformat/yaml/YAMLFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvFactory', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectMapper
W/dalvikvm( 3365): VFY: unable to resolve new-instance 805 (Lcom/fasterxml/jackson/dataformat/csv/CsvFactory;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectReader
W/dalvikvm( 3365): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.createObjectWriter
W/dalvikvm( 3365): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
E/dalvikvm( 3365): Could not find class 'com.fasterxml.jackson.dataformat.csv.CsvMapper', referenced from method org.restlet.ext.jackson.JacksonRepresentation.getCsvSchema
,W/dalvikvm( 3365): VFY: unable to resolve check-cast 806 (Lcom/fasterxml/jackson/dataformat/csv/CsvMapper;) in Lorg/restlet/ext/jackson/JacksonRepresentation;
W/dalvikvm( 3365): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
,W/dalvikvm( 3365): VFY: unable to find class referenced in signature (Lcom/fasterxml/jackson/dataformat/csv/CsvSchema;)
I/System.out( 3365): isCompatible false
I/System.out( 3365): createObjectMapper
I/System.out( 3365): isCompatible false
,I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
,I/System.out( 3365): isCompatible false
,I/DeviceManagement( 3365): ConfigCacheController: Getting config update from server: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.cs.pushclient/versions/c0b07203-b6aa-4cf1-944f-7ae27c536a6b/cid/MDoxOjIwMTMtMTItMjBUMDk6MzY6NTguNjI2Wg
,I/DeviceManagement( 3365): DeviceClientResource: Active network...
I/DeviceManagement( 3365):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=6 [31][2][0]
D/libc    ( 3365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3365): [NET] getaddrinfo-,err=8
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =21c8 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
,D/libc    ( 3446): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3446): [NET] getaddrinfo-,err=8
D/libc    ( 3446): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3446): [NET] getaddrinfo-, 1
,D/libc    ( 3446): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6962 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3446): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (3225/10100)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.apps.docs (3225/10100)
,W/GAV2    ( 3225): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  984): killProcessQuiet, pid=3029
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiService(  984): releaseWifiLockLocked: WifiLock{SyncManager type=1 binder=android.os.BinderProxy@42fd9430}
D/PMS     (  984): releaseWL(430df0e8): PARTIAL_WAKE_LOCK  SyncManager 0x1 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42cde8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
D/PMS     (  984): releaseWL(42ec6a50): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.docs/com.google/***** 0x1 WorkSource{10100}
D/PMS     (  984): releaseWL(42cde8d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  984): Killing 3029:com.htc.cloudstorage.drive/u0a69 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3029
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  984): releaseWL(43051598): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/DeviceManagement( 3365): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3365): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3365): DeviceClientResourceController: handleDirectives: []
I/System.out( 3365): isCompatible false
I/System.out( 3365): createObjectMapper
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
,I/System.out( 3365): isCompatible false
,V/CalendarSyncAdapter( 3446): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-03-25T00:00:00.000Z, updatedMin=2016-02-15T23:58:22.671Z}
,I/DeviceManagement( 3365): ConfigCacheController: Getting config update from server: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, nextUri=https://dm.htcsense.com/devices/v3/and/apps/com.htc.backup/versions/f14176fb-9327-4d08-a3c6-5749fcce54ec/cid/MDo0OjIwMTUtMDQtMjNUMjA6NTQ6MDcuMzczWg
,I/DeviceManagement( 3365): DeviceClientResource: Active network...
I/DeviceManagement( 3365):   NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1163): environment dirty rate=8 [35][3][0]
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.cs.dm (3365/10098)
,D/CalendarSyncAdapter( 3446): Found 0 events marked dirty & lastSynced
D/libc    ( 3365): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
,D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x6c6f63616c686f),sn(),family 0,flags 1024
D/libc    (  363): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET]_files_getaddrinfo, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 4
D/libc    ( 3365): [NET] getaddrinfo-,err=8
D/libc    ( 3365): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
D/libc    ( 3365): [NET] getaddrinfo-, 1
,D/libc    ( 3365): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 15(0x646d2e68746373),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =40f2 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3365): [NET] getaddrinfo_proxy-, success
,I/GAV2    ( 3146): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/PMS     (  984): acquireWL(42baf098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
,D/PMS     (  984): releaseWL(42b2e368): PARTIAL_WAKE_LOCK  *sync*/com.android.calendar/com.google/***** 0x1 WorkSource{10108}
,D/PMS     (  984): releaseWL(42baf098): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  984): killProcessQuiet, pid=3073
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 3073:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3073
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  984): mEventCount = 300
,I/DeviceManagement( 3365): DMServiceClientResourceController: handleDirectives: []
I/DeviceManagement( 3365): ServiceClientResourceController: handleDirectives: []
,I/DeviceManagement( 3365): DeviceClientResourceController: handleDirectives: []
I/System.out( 3365): isCompatible false
I/System.out( 3365): createObjectMapper
I/System.out( 3365): isCompatible false
,I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false
I/System.out( 3365): isCompatible false,
I/System.out( 3365): isCompatible false
,I/System.out( 3365): isCompatible false
,I/DeviceManagement( 3365): ConfigCacheController: *** Update config cache: updating 3 entries...
,I/DeviceManagement( 3365): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.launcher, versionKey=b354e2de-d3af-4a3f-b5dc-8239e0d5da72, statusCode=0, authCode=0>
,I/DeviceManagement( 3365): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.cs.pushclient, versionKey=c0b07203-b6aa-4cf1-944f-7ae27c536a6b, statusCode=0, authCode=0>
,I/DeviceManagement( 3365): ConfigCacheController:   update entry: <ConfigCacheSpec: appID=com.htc.backup, versionKey=f14176fb-9327-4d08-a3c6-5749fcce54ec, statusCode=0, authCode=0>
,I/DeviceManagement( 3365): ConfigCacheController: No changes need to be broadcasted.
,I/DeviceManagement( 3365): AlarmController: Scheduling TTL alarm for: 2016.03.01 at 18:53:55.824 CET (due to: com.htc.aurora)
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.htc.cs.dm, clsName=com.htc.cs.dm.receiver.NetworkChangeReceiver, state=2, flag=1, pid=3365, uid=10098, userID:0
,I/DeviceManagement( 3365): Perf: *** Config cache update - complete: 2458 ms
,I/DeviceManagement( 3365): Perf: *** Cache update - complete: 3314 ms
,I/DeviceManagement( 3365): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.workflow.BootCompletedWorkflow@422f9460]
I/DeviceManagement( 3365): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42681b70] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3365): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3365): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3365): SessionStateController: Checking invariants...
,I/DeviceManagement( 3365): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3365): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@42681b70]
,I/DeviceManagement( 3365): WorkflowService: Stopping workflow service
I/ActivityManager(  984): Resuming delayed broadcast
,I/ActivityManager(  984): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.service.BootReceiver: pid=3473 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  984): killProcessQuiet, pid=2299
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 2299:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 2299
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  984): doString: SIGNAL_POLL
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: survey data missing!
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1163): environment dirty rate=11 [9][1][0]
I/wpa_supplicant( 1163): Change stage from stage0 to stage3
,I/wpa_supplicant( 1163): Don't scan again before 3 minutes, avoid too many scan when stage change frequently
D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  984): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  984): doBoolean: SignalStrength 97
,W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  984):    returned true
,I/htcbackup-core( 3389): CommonUtil: Scheduling Auto-Backup Promotion Notification: interval start=[2015.08.23 at 04:23:34.353 CEST] interval end=[2015.08.30 at 04:23:34.353 CEST]
,V/AlarmManager(  984): sending alarm PendingIntent{42e37b10: PendingIntentRecord{430d82e0 com.htc.backup startService}}, i=com.htc.backup.scheduleAutoBackupNotification, t=0, cnt=27, w=1440901414353, Int=604800000
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,W/dalvikvm( 3389): VFY: unable to resolve static method 33789: Lcom/htc/htcjavaflag/HtcBuildFlag;.getHtc_Sense_Version ()Ljava/lang/String;
,I/RemoteViews.Performance( 1117): com.htc.backup 1 2 15
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.htc.backup, id: 100, tag: null, isClearable: true
,I/RemoteViews.Performance( 1117): com.htc.backup 0 2 0 4
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1117): com.htc.backup 1 1 1 4
,I/RemoteViews( 1117): com.htc.backup (true,33751552)
,I/RemoteViews.Performance( 1117): com.htc.backup 1 2 0 4
,I/RemoteViews.Performance( 1117): com.htc.backup 3 12 21
,W/dalvikvm( 3473): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3473): VFY: unable to resolve instance field 36
,W/dalvikvm( 3473): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3473): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Babel   ( 3473): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3473): MmsConfig.loadMmsSettings
,D/UPolicy ( 3389): IUserBehaviorLoggingService reference is gotten !
,D/Process (  984): killProcessQuiet, pid=3102
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 3102:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  984): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=3498 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,V/AlarmManager(  984): sending alarm PendingIntent{42b00e58: PendingIntentRecord{42addee0 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1456842800514, Int=0
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3473, uid=10111, userID:0
,I/ActivityManager(  984): Recipient 3102
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Settings( 3473): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
,D/MessageFrequencyProvider( 3498): onCreate
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3473, uid=10111, userID:0
,V/GetPrviateResource( 3498): GetPrviateResource
V/GetPrviateResource( 3498): GetPrviateResource
,D/MmsCustomizationProvider( 3498): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3498): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3473): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3473): MmsConfig.loadFromDatabase
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3473, uid=10111, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3473, uid=10111, userID:0
,E/Babel   ( 3473): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3473): MmsConfig.loadFromResources
,I/ProviderInstaller( 3473): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 3473): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3473): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,V/Babel   ( 3473): babel boot account: thalitester@gmail.com
,V/Babel   ( 3473): babel boot account: SMS
,D/Process (  984): killProcessQuiet, pid=2879
D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  984): killProcessQuiet, pid=3118
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Start proc com.htc.backupreset for broadcast com.htc.backupreset/.receiver.BackupResetReceiver: pid=3519 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  984): Killing 2879:com.htc.showme/u0a83 (adj 15): empty #17
I/ActivityManager(  984): Killing 3118:com.htc.mms.backupagent/u0a78 (adj 15): empty #18
,I/ActivityManager(  984): Recipient 3118
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Recipient 2879
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MessageCustFlag( 3498): sense_version=6.0
,D/BTAccessoryUtil( 3498): createReceiver
,D/BTAccessoryUtil( 3498): registerReceiver return intent = null
V/AlarmManager(  984): sending alarm PendingIntent{42e6a480: PendingIntentRecord{42eb1218 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=54470, Int=259200000
V/AlarmManager(  984): sending alarm PendingIntent{424aa678: PendingIntentRecord{42c539e0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=54676, Int=0
D/MessageCustFlag( 3498): sku_id=99
W/SystemReader( 3498): Cannot find message_ambs_application_id, use default value instead
V/AlarmManager(  984): sending alarm PendingIntent{42f26a10: PendingIntentRecord{42f0f910 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=54530, Int=0
V/AlarmManager(  984): sending alarm PendingIntent{4309f6c8: PendingIntentRecord{42ec4550 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.UPDATE_NOTIFICATION, t=2, cnt=1, w=54707, Int=0
D/Messaging( 3498): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3498): networkCode: 
D/MessageCustFlag( 3498): sku_id=99
D/MmsConfig( 3498): SIE smsPri: null
D/MmsConfig( 3498): networkCode: 
,D/HtcTelephonyCapability( 3498): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3498): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 3498): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3498): Cannot find qct_8960_interface, use default value instead
,I/ActivityManager(  984): Start proc com.htc.htccupd for broadcast com.htc.htccupd/.HtcCupdReceiver: pid=3535 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  984): killProcessQuiet, pid=3132
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 3132:com.htc.updater/u0a85 (adj 15): empty #17
,D/libc    ( 2208): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
,D/libc    ( 2208): [NET] getaddrinfo-,err=8
D/libc    ( 2208): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
D/libc    ( 2208): [NET] getaddrinfo-, 1
,D/libc    ( 2208): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6657 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/ResetNotifyBootCompleteReceiver( 1241): Receive bootcomplete intent
,W/ContextImpl( 1241): Implicit intents with startService are not safe: Intent { act=com.htc.resetnotify.resetnotifyservice } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.resetnotify.BootCompleteReceiver.onReceive:57 
,I/HtcCupdXmlParser( 3535): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdalarmgroup.so: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  984): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.weekly.AlarmReceiver: pid=3551 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
,D/ActivityThread( 3535): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,I/ActivityManager(  984): Recipient 3132
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 1241): Grow heap (frag case) to 12.416MB for 2097144-byte allocation
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=102
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2208): [NET] getaddrinfo_proxy-, success
,D/AppTag  ( 3551): getInstance(Context context)
,D/AppTag  ( 3551): getInstance(Context context)
D/libc    ( 2208): [NET] getaddrinfo+,hn 24(0x73736c2e676f6f),sn(),family 0,flags 4
,D/libc    ( 2208): [NET] getaddrinfo-,err=8
,D/AppTag  ( 3551): onCreate()
,I/GAV2    ( 3225): Thread[GAThread,5,main]: No campaign data found.
,D/QXDM2SD:HtcNative( 1241): JNI lib [/system/lib/libhtcqxdm2sd.so] exists: true
,I/ActivityManager(  984): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3567 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  984): killProcessQuiet, pid=3161
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 3161:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/HtcCupdXmlParser( 3535): java.io.FileNotFoundException: /data/data/com.htc.htccupd/lib/libcupdepsalarmqueuinglist.so: open failed: ENOENT (No such file or directory)
I/ActivityManager(  984): Recipient 3161
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 3567): [3567/3567] onCreate()
W/ContextImpl( 3567): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  984): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
I/AlarmManager(  984): [AlarmQueuing] AlarmListUpdateReceiver onReceive: com.htc.intent.action.CUPD_CONF_CHANGED
I/AlarmManager(  984): [AlarmQueuing] post alarm-list load task
I/AlarmManager(  984): [AlarmQueuing] init alarm queuing list
,I/HtcModeClient( 1528): handler message = 4011
,E/HtcModeClient( 1528): Check connection and retry 4 times.
,I/ActivityManager(  984): Start proc com.htc.providers.settings:remote for content provider com.htc.providers.settings/.HtcCupdProvider: pid=3581 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  984): Resuming delayed broadcast
,I/ActivityManager(  984): Start proc com.android.settings for broadcast com.android.settings/.framework.app.HtcIntentReceiver: pid=3593 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  984): killProcessQuiet, pid=3055
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  984): Killing 3055:com.google.android.apps.cloudprint/u0a97 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3055
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  984): killProcessQuiet, pid=3042
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:13474 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:13550 
I/ActivityManager(  984): Killing 3042:com.google.android.apps.cloudprint:sync/u0a97 (adj 15): depends on provider com.google.android.apps.cloudprint/.printdialog.database.CloudPrintContentProvider in dying proc com.google.android.apps.cloudprint
,I/ActivityManager(  984): Recipient 3042
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3593): -onCreate()
,I/AlarmManager(  984): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42e37fb8
,V/Settings:HtcSettingsApplication( 3593): [3593/3593] onCreate()
W/ContextImpl( 3593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  984): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
,I/AlarmManager(  984): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@430dec48
,I/ActivityManager(  984): Resuming delayed broadcast
,D/TetherSettings( 3593): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3593): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3593): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3593): Cust_ConnectToPC   : spcsc>false
D/        ( 3593): Cust_ConnectToPC   : IPT>true
,D/        ( 3593): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3593): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3593): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3593): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3593): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3593): Cust_ConnectToPC   : spcsc>false
D/        ( 3593): Cust_ConnectToPC   : IPT>true
D/        ( 3593): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3593): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3593): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3593): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3593): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 3593): setISNotification
,D/SmartNS_Utility( 3593): usb_cable_connect = 1
,D/SmartNS_Utility( 3593): usb_denied = 0
,I/SmartNS_PSService( 3593): usb notificaiton:true
,V/Tethering(  984): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  984): bSetPropertyMultiRAB:false
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.android.settings (3593/1000)
D/SmartNS_Utility( 3593): usb_cable_connect = 1
D/SmartNS_Utility( 3593): usb_denied = 0
I/SmartNS_PSService( 3593): usb notificaiton:true
,V/Tethering(  984): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  984): bSetPropertyMultiRAB:false
D/ConnectivityService(  984): getActiveNetworkInfo called by com.android.settings (3593/1000)
,I/AlarmManager(  984): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@43031908
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  984): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.sina.weibo
,I/AlarmManager(  984): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  984): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  984): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
,I/AlarmManager(  984): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028823
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028959
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029206
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029209
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029215
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029222
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030820
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030840
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360034486
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360052144
,I/ActivityManager(  984): Killing 3088:com.htc.task.gtask/u0a68 (adj 15): empty #17
,D/Process (  984): killProcessQuiet, pid=3088
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/ContextImpl(  984): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
,I/RemoteViews( 1117): com.android.settings (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4245e910 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.android.settings 1 6 0 10
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Recipient 3088
,I/RemoteViews( 1117): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1117): com.android.settings 1 1 10
I/ActivityManager(  984): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3608 uid=9987 gids={49987}
,D/Process (  984): killProcessQuiet, pid=3272
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  984): Killing 3272:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/SensorManager(  984): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42bd53d8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  984): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 2
W/SensorService(  984): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  984): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bd53d8, eanble = 1, strlen(mName) = 36
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  984): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424e4ec8
W/SensorService(  984): Listener[1] = com.android.server.power.DisplayPowerController$10@4294ddd8
W/SensorService(  984): Listener[2] = com.htc.smartdim.sensor_eye@42bd53d8
,W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  984): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42bd53d8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  984): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  984): enable: get sensor name = CM36282 Proximity sensor
I/ActivityManager(  984): Recipient 3272
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/BroadcastQueue(  984): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42cc6d48 u0 ReceiverList{42dee7a8 984 system/1000/u0 local:428635c8}}
,D/NfcUiccLockService( 3608): -- To check whether previous opened channel needed to be closed ...
,I/ActivityManager(  984): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3622 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
,D/Process (  984): killProcessQuiet, pid=3336
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 3336:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3336
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SensorService(  984): pid=984, uid=1000
W/SensorService(  984): Active sensors: size = 3
W/SensorService(  984): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  984): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  984): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  984): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42bd53d8, eanble = 1, strlen(mName) = 36
W/SensorService(  984): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  984): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@424e4ec8
W/SensorService(  984): Listener[1] = com.android.server.power.DisplayPowerController$10@4294ddd8
W/SensorService(  984): Listener[2] = com.htc.smartdim.sensor_eye@42bd53d8
,W/SensorService(  984): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/ActivityManager(  984): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3634 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
,D/Process (  984): killProcessQuiet, pid=3348
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  984): Killing 3348:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  984): Recipient 3348
,E/YouTube ( 3634): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc    ( 3634): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
,D/libc    ( 3634): [NET] getaddrinfo-, SUCCESS
,D/YouTube ( 3634): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.youtube (3634/10168)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/BluetoothManagerService(  984): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  984): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42c68198 mBinding = false
,W/HtcDLNAServiceManager(  984): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  984): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  984): Settings:Agentvalue: 0
,W/Settings:Agent(  984): >> traceCallingStack()
W/Settings:Agent(  984): Process.myPid(): 984
W/Settings:Agent(  984): Process.myTid(): 1349
,W/Settings:Agent(  984): Process.myUid(): 1000
W/Settings:Agent(  984): 
,W/Settings:Agent(  984): 
,W/System.err(  984): java.lang.Throwable: stack dump
,W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  984): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  984): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  984): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  984): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  984): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  984): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  984): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  984): 
,W/Settings:Agent(  984): << traceCallingStack(): 9(ms)
,D/YouTube ( 3634): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3634): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/BluetoothManagerService(  984): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  984): Sending off request.
D/BluetoothAdapterState( 1608): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1608): Setting state to 13
I/BluetoothAdapterState( 1608): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1608): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  984): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 1608): onBluetoothDisable()
I/bt-btm  ( 1608): BTM_SetDiscoverability
I/bt-btm  ( 1608): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1608): btm_ble_set_discoverability (BREDR not sup)flag=0x4
,D/bt-btm  ( 1608): br_edr_supported=0x0
I/bt-btm  ( 1608): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1608): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1608): btm_ble_update_adv_flag new=0x4
,D/bt-btm  ( 1608): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1608): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1608): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1608): BTM_SetConnectability
I/bt-btm  ( 1608): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1608): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1608): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/BTIF_CORE( 1608): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1608): HAL bt_hal_cbacks->wake_state_changed_cb
,I/BluetoothAdapterState( 1608): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/WifiManager( 3250): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
D/BluetoothRemoteDevices( 1608): Wake lock Aquired
I/bt-btif ( 1608): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1608): adapterPropertyChangedCallback with type:7 len:4
,D/WifiStateMachine(  984): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothManagerService(  984): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  984): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
W/HtcDLNAServiceManager(  984): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  984): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  984): Settings:Agentvalue: 0
D/BluetoothManagerService(  984): Bluetooth State Change Intent: 12 -> 13
W/Settings:Agent(  984): >> traceCallingStack()
W/Settings:Agent(  984): Process.myPid(): 984
W/Settings:Agent(  984): Process.myTid(): 995
W/Settings:Agent(  984): Process.myUid(): 1000
W/Settings:Agent(  984): 
W/Settings:Agent(  984): 
,W/System.err(  984): java.lang.Throwable: stack dump
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothAdapterProperties( 1608): Scan Mode:20
W/System.err(  984): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  984): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  984): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
D/BluetoothAdapterState( 1608): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
W/System.err(  984): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  984): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  984): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,W/System.err(  984): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
V/BluetoothPbapReceiver( 1608): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1608): ***********state = 13
,W/System.err(  984): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
I/bt-btif ( 1608): BTA_JvDeleteRecord
D/PMS     (  984): acquireWL(42d1c7b8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1608 1002 null
D/WifiService(  984): setWifiEnabled: false pid=3250, uid=10397
E/WifiService(  984): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  984): isSprintWifiRestricted(): false
I/WifiService(  984): isMdmWifiRestricted(): false
D/WifiSettingsStore(  984): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  984): New client listening to asynchronous messages
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:15
,I/bt-btif ( 1608): BTA_JvRfcommStopServer
D/bt-btm  ( 1608): BTM_FreeSCN 
E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btif ( 1608): BTA_JvDeleteRecord
I/bt-btif ( 1608): BTA_JvRfcommStopServer
D/bt-btm  ( 1608): BTM_FreeSCN 
,I/bt-btif ( 1608): BTA_JvDeleteRecord
I/bt-btif ( 1608): BTA_JvRfcommStopServer
D/bt-btm  ( 1608): BTM_FreeSCN 
I/bt-btm  ( 1608): BTM_SEC_CLR[13]: id 52
I/bt-btif ( 1608): BTA_JvDeleteRecord
I/bt-btif ( 1608): BTA_JvRfcommStopServer
D/bt-btm  ( 1608): BTM_FreeSCN 
,I/bt-btif ( 1608): BTA_JvDeleteRecord
I/bt-btif ( 1608): BTA_JvRfcommStopServer
D/bt-btm  ( 1608): BTM_FreeSCN 
I/bt-btif ( 1608): SDP_DeleteRecord o
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:14
I/bt-btif ( 1608): BTA_JvRfcommStopServer
,D/bt-btm  ( 1608): BTM_FreeSCN 
E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1608): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1608): BTM_SEC_CLR[15]: id 54
,D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1608): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1608): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:10
,E/bt-btif ( 1608): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1608): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1608): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1608): Write Extended Inquiry Response to controller
,I/bt-btm  ( 1608): Write Extended Inquiry Response to controller
I/bt-btm  ( 1608): Write Extended Inquiry Response to controller
I/bt-btm  ( 1608): Write Extended Inquiry Response to controller
I/bt-btm  ( 1608): BTM_SetDiscoverability
I/bt-btm  ( 1608): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1608): btm_ble_set_discoverability (BREDR not sup)flag=0x4
,D/bt-btm  ( 1608): br_edr_supported=0x0
I/bt-btm  ( 1608): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1608): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1608): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1608): btm_ble_update_adv_flag old=0x4
,I/bt-btm  ( 1608): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1608): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1608): BTM_SetConnectability
I/bt-btm  ( 1608): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1608): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 1608): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1608): BTM_IsInquiryActive
I/bt-btm  ( 1608): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1608): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1608): BTM_FreeSCN 
I/bt-btm  ( 1608): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1608): BTM_FreeSCN 
I/bt-btm  ( 1608): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1608): AVRC_Close handle:0
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1608): SDP_DeleteRecord ok, num_records:3
,W/bt-l2cap( 1608): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1608): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1608): GATT_Deregister gatt_if=3
I/bt-att  ( 1608): GATT_Deregister gatt_if=4
V/BluetoothSapService( 1608): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/System.err(  984): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
E/BtOppRfcommListener( 1608): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1779): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@422f1158
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): onDeInitialized
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): getNotificationManager
D/BluetoothMasReceiver( 1608): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1608): SapReceiver onReceive 
V/BluetoothSapReceiver( 1608): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1608):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1608): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  984): 
D/PMS     (  984): acquireWL(42b54aa0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1225 10029 null
D/PMS     (  984): acquireWL(42a04d48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3593 1000 null
W/ContextImpl( 3593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  984): releaseWL(42b54aa0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,W/Settings:Agent(  984): << traceCallingStack(): 16(ms)
,V/BluetoothPbapService( 1608): Pbap Service closeService in
D/PMS     (  984): releaseWL(42a04d48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  984): acquireWL(42573b98): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3593 1000 null
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  984): java.lang.Throwable: stack dump
D/BluetoothManagerService(  984): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423c7228:true
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  984): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 3593): new LocationAgent instance!!
,D/HtcTagManager( 3593): HtcTagManager construction complete
,I/ActivityManager(  984): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3667 uid=10040 gids={50040, 3002, 3001}
I/jxcore-log( 3250): ****TEST TOOK:  5129  ms ****
I/jxcore-log( 3250): 
I/jxcore-log( 3250): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3250): 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1779): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1779):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1779): writeLinkLossAlertLevelAll: 0, false
D/WirelessDisplayService(  984): getMirrorDisplayStatus:falsecurState:1
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1779):  + mTag.getPrimaryDeviceList() = []
V/BluetoothPbapService( 1608): successfully stopped pbap service
V/BluetoothPbapService( 1608): Pbap Service closeService out
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1779): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm
D/BluetoothManagerService(  984): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1779): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1779): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1779): shutdownStateMachine
D/WifiPerfLock(  984): release()
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1779): init: null
D/WifiStateMachine(  984): PerfLock released for exiting ConnectedState
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1779): setPendingRequestAlarm: false, mContext = null, null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1779): Exit IdleState
D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/BluetoothAdapter( 3593): 1110664136: getState(). Returning 13
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  984):    returned true
D/BluetoothInputDevice( 3593): BluetoothInputDevice()
D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothManagerService(  984): registerStateChangeCallback+
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  984):    returned true
D/ConnectivityService(  984): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  984): acquireWL(42984130): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 984 1000 null
I/BtOppRfcommListener( 1608): stopping Accept Thread
D/BluetoothManagerService(  984): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42397d08:true
I/BtOppRfcommListener( 1608): BluetoothSocket listen thread finished
D/BluetoothAdapter( 3593): 1110664136: getState(). Returning 13
D/BluetoothInputDevice( 3593): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3593): Bluetooth service connected
W/BluetoothInputDevice( 3593): Proxy not attached to service
D/BluetoothPan( 3593): BluetoothPan()
D/libc    (  984): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-, SUCCESS
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  984): Registered receivers: 7
V/BluetoothSapService( 1608): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1608): state: 13
D/BluetoothAdapter( 3593): 1110664136: getState(). Returning 13
D/BluetoothPan( 3593): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3593): Bluetooth service connected
D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  984): Registered receivers: 8
D/BluetoothMap( 3593): Create BluetoothMap proxy object
D/PhoneStatusBar( 1117): removeIcon slot=bluetooth index=12 viewIndex=0
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  984): Registered receivers: 9
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine(  984): [RunningState] Stop DHCP
D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiP2pService(  984): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028823
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028959
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029206
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029209
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029215
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029222
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030820
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030840
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360034486
,W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360052144
D/WifiDataStallTracker(  984): stopDataStallAlarm: current tag=24621 mDataStallAlarmIntent=PendingIntent{42bfde98: PendingIntentRecord{42b986d0 android broadcastIntent}}
D/WifiNative-wlan0(  984): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapter( 1608): 1110358904: getState(). Returning 13
V/BluetoothSapService( 1608): Stopping SAP server process
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
E/BluetoothMap( 3593): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiNative-wlan0(  984):    returned null
E/WifiStateMachine(  984): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  984): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
D/libc    (  984): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  984): [NET] getaddrinfo-, SUCCESS
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  984):    returned null
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  984): Registered receivers: 10
D/BluetoothSap( 3593): BluetoothSap() call bindService
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  984): isAvailable+-
D/UsbnetStateTracker(  984): reconnect
D/UsbnetStateTracker(  984): isAvailable+-
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
,D/BluetoothPbap( 3593): BluetoothPbap()
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  984): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  984): Provision feature enable=false
D/ConnectivityService(  984): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
W/ContextImpl( 3593): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  984): default: reconnect()
D/MDST    (  984): default: setTeardownRequested(false)
D/MDST    (  984): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  984): InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): P2pDisablingState
D/WifiP2pService(  984): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  984): Registered receivers: 11
D/BluetoothAdapter( 3593): 1110664136: getState(). Returning 13
,D/BluetoothPbap( 3593): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3593): Bluetooth service connected
D/LocalBluetoothProfileManager( 3593): LocalBluetoothProfileManager construction complete
,D/WifiStateMachine(  984): Call handleNetworkDisconnect() in SupplicantStoppingState
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDisplayController(  984): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  984): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  984): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  984): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  984): set wifi.miracastlock to 0 for disconnect case
I/WifiDisplayController(  984): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  984): updateConnection
I/WifiDisplayController(  984): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  984): updateConnection enter step 4
D/WifiP2pService(  984): p2p socket connection lost
D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
D/WifiP2pService(  984): P2pDisabledState
D/WifiP2pService(  984): P2pDisabledState{ when=-5ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  984):  WFD CtrlPort: 0
D/WifiP2pService(  984):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): DefaultState{ when=-5ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  984):  WFD CtrlPort: 0
D/WifiP2pService(  984):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  984): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  984): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  984): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/BluetoothSapService( 1608): Sap Service closeSapService in
V/BluetoothSapService( 1608): Close listen Socket : 
V/BluetoothSapService( 1608): Close rfcomm Socket : 
V/BluetoothSapService( 1608): Close sapd  Socket : 
,V/BluetoothSapReceiver( 1608): BluetoothSapReceiver deinit
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  984): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1163): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1163): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 61
V/AudioService(  984): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  984):     Client/Owner: Client
V/AudioService(  984):     GroupId: 
V/AudioService(  984):     Passphrase: 
V/AudioService(  984):     SessionId: 0
V/AudioService(  984):     IP Address: }
D/HtcEffectManagerBase(  984): onEventChanged id=5 status=false
,D/HtcEffectManager(  984): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/WifiNative-wlan0(  984):    returned true
D/HtcEffectManager(  984): convertEffect before=902
,D/HtcEffectManager(  984): convertEffect after=902
,D/WifiNative-wlan0(  984): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  984): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1163): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1163): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  984):    returned true
V/BluetoothSapService( 1608): successfully stopped Sap service
,D/DockEventReceiver( 3593): finishStartingService: stopping service
,D/SapServerProfile( 3593): Bluetooth service connected
,V/BluetoothSapService( 1608): Sap Service closeSapService out
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  984): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  984): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiDisplayController(  984): Failed to set WFD info with reason 2.
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/WifiP2pService(  984): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  984): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  984): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  984): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  984): handleConnectivityChange: resetting
,D/ConnectivityService(  984): resetConnections(wlan0, 3)
D/SapServerProfile( 3593): Bluetooth service disconnected
V/BluetoothPbapService( 1608): Pbap Service onDestroy
V/BluetoothPbapService( 1608): Pbap Service closeService in
V/BluetoothPbapService( 1608): Pbap Service closeService out
,D/WISPrService( 3593): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-p2p0(  984): doBoolean: TERMINATE
W/WifiHW  (  984): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1163): Supplicant Terminat @ wpa_supplicant_deinit function
D/libc    (  363): [NET] entry_id:8   entry:0xb779be48  removed 
D/libc    (  363): [NET] entry_id:9   entry:0xb779c078  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb779b378  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb779bc18  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb779fdb8  removed 
D/libc    (  363): [NET] entry_id:11   entry:0xb7796af8  removed 
D/libc    (  363): [NET] entry_id:12   entry:0xb779c3f0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb779ff70  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb779b9c8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7796c20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb779b458  removed 
D/libc    (  363): [NET] entry_id:10   entry:0xb779c200  removed 
D/wpa_supplicant( 1163): TDLS: Tear down peers
I/wpa_supplicant( 1163): wpa_driver_nl80211_disconnect(reason_code=3)
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
,D/WifiNative-p2p0(  984):    returned true
V/BluetoothSapService( 1608): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@42325ab0
V/BluetoothSapService( 1608): Sap Service closeSapService in
V/BluetoothSapService( 1608): Close listen Socket : 
V/BluetoothSapService( 1608): Close rfcomm Socket : 
V/BluetoothSapService( 1608): Close sapd  Socket : 
V/BluetoothSapService( 1608): Sap Service closeSapService out
,V/BluetoothSapService( 1608): ***onDestroyed***
D/PMS     (  984): releaseWL(42573b98): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/ConnectivityService(  984): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  984): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  984): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/HtcBtWidget_BTWidgetProvider( 3667): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3667): updateWidget(context) for widget: 
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  984): [MLHD] Error! unhandled message 1 { when=-2ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,D/WISPrService( 3593): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiService(  984): New client listening to asynchronous messages
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  984): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1608): Shutdown
,D/WISPrService( 3593): >>>>>WISPrService start isConnected = false<<<<<
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  984): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  984): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  984): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  984): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  984): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  984): acquireWL(42e7b7e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 984 1000 null
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  984): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
D/WISPrService( 3593): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  984): startScan Pid: 984 Uid 1000
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1163): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
I/wpa_supplicant( 1163): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  984): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  984): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/wpa_supplicant( 1163): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  984): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  984): WifiMonitor:getBSSIDFromString BSSIDf4:f2:6d:22:99:3e
D/HTCRequest(  984): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
,D/HTCRequest(  984): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  984): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  984): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
D/HTCRequest(  984): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1 ssid='NG700' freq=2437
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/HTCRequest(  984): WifiMonitor:getFreqFromEventString() 2437
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/WifiMonitor(  984): notifyNetworkStateChange. wifiSsid ='NG700' freq=2437
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1163): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8a95bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1163):    addr=f4:f2:6d:22:99:3e
E/wpa_supplicant( 1163): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1163): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
,I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1163): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1163): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/wpa_supplicant( 1163): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1163): htc_wext_set_TX_TRACKING - ret = 0
,D/wpa_supplicant( 1163): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1163): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1163): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1163): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 18
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  984): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
D/HTCRequest(  984): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  984): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
,D/Tethering(  984): interfaceStatusChanged wlan0, false
D/Tethering(  984): [isWifi] getHotspotEnabled: false
,D/BluetoothMasReceiver( 1608): Bluetooth STATE CHANGED to 13
,D/Process (  984): killProcessQuiet, pid=2906
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
,D/Tethering(  984): interfaceStatusChanged wlan0, false
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Tethering(  984): [isWifi] getHotspotEnabled: false
,I/ActivityManager(  984): Killing 2906:com.google.android.gm/u0a107 (adj 15): empty #17
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1779): Received state change = 13
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1779): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@422f1158
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1779): deinitLeServices: null
D/ConnectivityService(  984): mActiveDefaultNetwork: -1
,D/YouTube ( 3634): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  984): releaseWL(42e7b7e8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,D/Process (  984): killProcessQuiet, pid=3225
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/WifiService(  984): New client listening to asynchronous messages
,I/ActivityManager(  984): Killing 3225:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/AuthorizationBluetoothService( 1364): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  984): Recipient 2906
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/bt-btif ( 1608): ag scb idx 1 not allocated
,W/bt-btif ( 1608): ag scb idx 2 not allocated
E/bt-btif ( 1608): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1608): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1608): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1608): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1608): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1608): L2CAP - PSM: 0x0019 not found for deregistration
,D/YouTube ( 3634): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,W/bt-l2cap( 1608): L2CAP - PSM: 0x0017 not found for deregistration
,I/ActivityManager(  984): Recipient 3225
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
,D/MediaRouterService(  984): Client com.google.android.youtube (pid 3634): Registered
,I/MediaRouter( 3634): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/bt_userial_mct( 1608): userial_close userial_thread_created userial_running is 1 
D/WifiDisplayAdapter(  984): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  984):     Client/Owner: Client
D/WifiDisplayAdapter(  984):     GroupId: 
D/WifiDisplayAdapter(  984):     Passphrase: 
D/WifiDisplayAdapter(  984):     SessionId: 0
D/WifiDisplayAdapter(  984):     IP Address: }
D/YouTube ( 3634): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3634): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1456842802&data=screen_name%3D%3CAndroid_YT_Open_App%3E
,D/ConnectivityService(  984): getNetworkInfo networkType=0 called by com.google.android.youtube (3634/10168)
D/libc    ( 3634): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3634): [NET] getaddrinfo-,err=8
D/libc    ( 3634): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3634): [NET] getaddrinfo-, 1
D/libc    ( 3634): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =98d0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET]Querying server xid =98d0 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  363): [NET]res_nsend:ECONNREFUSED
D/libc    (  363): [NET] -----res_nsend exit-1: xid=98d0, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3634): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3634): Error sending ping
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3634): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3634): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/MediaRouter( 3634): getSelectedRoute
,D/YouTube ( 3634): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/YouTube ( 3634): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.youtube (3634/10168)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.youtube (3634/10168)
,I/ActivityManager(  984): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3712 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.youtube (3634/10168)
,D/YouTube ( 3634): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
,D/YouTube ( 3634): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3634): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
,D/YouTube ( 3634): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,D/Process (  984): killProcessQuiet, pid=3446
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/YouTube ( 3634): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
I/ActivityManager(  984): Killing 3446:com.google.android.syncadapters.calendar/u0a108 (adj 15): empty #17
,I/ActivityManager(  984): Recipient 3446
,I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1163): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1163): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1163): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  984): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  984): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/YouTube ( 3634): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
,E/cutils-trace( 3686): Error opening trace file: No such file or directory (2)
,D/wpa_supplicant( 1163): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1163): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1163): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1163): nl80211: Unsubscribe mgmt frames handle 0xb8a96718 (mode change)
I/wpa_supplicant( 1163): htc_wext_command_deinit +
I/wpa_supplicant( 1163): htc_wext_command_deinit -
E/wpa_supplicant( 1163): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 1163): wlan0: CTRL-EVENT-TERMINATING 
E/WifiStateMachine(  984): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
D/Tethering(  984): interfaceLinkStateChanged wlan0, false
,D/Tethering(  984): interfaceStatusChanged wlan0, false
D/Tethering(  984): [isWifi] getHotspotEnabled: false
E/WifiStateMachine(  984): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  984): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  984): [wpa_ctrl_close] ctrl=0x6272db40
,I/wpa_ctrl(  984): [wpa_ctrl_close] ctrl=0x62798a40
,W/WifiHW  (  984): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  984): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  984): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  984): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  984):    returned false
,D/WifiStateMachine(  984): Enter handleNetworkDisconnect
,W/Settings( 3473): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  984): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  984): WIFI Trun OFF
,D/WirelessDisplayService(  984): getDiscoveryDongleList
,I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
,D/WifiStateMachine(  984): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  984): Exit handleNetworkDisconnect
,E/WifiStateMachine(  984): [MLHD] Error! unhandled message 6 { when=-27ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  984): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  984): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,W/Settings( 1225): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  984): acquireWL(430498e8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 984 1000 null
D/WifiStateTracker(  984): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3593): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3593): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/YouTube ( 3634): apps.youtube.datalib.offline.b.run:89 Queuing stored offline request.
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.youtube (3634/10168)
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3712, uid=10074, userID:0
,D/YouTube ( 3634): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,D/Finsky  ( 3712): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
D/ConnectivityService(  984): getAllNetworkInfo called by com.android.vending (3712/10074)
,D/CustomizationManager( 3686): ====startRecUseTime====
D/htc.customization.log.level( 3686):  is 
,W/CustomizationLogLevel( 3686): Level value is invalid, use default level 2
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  984): getAllNetworkInfo called by com.android.vending (3712/10074)
,D/Finsky  ( 3712): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3712): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3712): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Messaging( 3498): mNeedToUpdateDate2 start
,D/MmsConfig( 3498): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3498): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3498): 
D/MmsAsyncWorkHandler( 3498): HM tk = 20001
,D/ReportIndicatorCache( 3498): MSG_QUERY_REPORTS >>
,I/bt-btif ( 1608): HAL bt_hal_cbacks->adapter_state_changed_cb
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/SettingsManager( 3498): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@422d9fe0
,D/BluetoothAdapterState( 1608): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1608): Received stop request...Stopping profile...
,I/Messaging( 3498): mccmnc> 
,D/BluetoothHeadset(  984): Proxy object disconnected
,D/BluetoothHeadset( 1241): Proxy object disconnected
D/BluetoothHeadset( 1117): Proxy object disconnected
D/A2dpService( 1608): Received stop request...Stopping profile...
D/A2dpStateMachine( 1608): doQuit
I/QuickSettingMiniLite( 1117): btListener.disconnect:HEADSET
D/A2dpStateMachine( 1608): Exit Disconnected: -1
,D/BluetoothAdapterState( 1608): Stopping profile services that were post enabled
D/BluetoothPhoneService( 1241): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset( 1241): Proxy object disconnected
,D/BluetoothA2dp(  984): Proxy object disconnected
,D/HidService( 1608): Received stop request...Stopping profile...
,D/DraftCache( 3498): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3498): [DraftCache/1] refresh
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,D/AccFlag ( 1241): sku_id=99
,D/HealthService( 1608): Received stop request...Stopping profile...
,D/MmsConfig( 3498): networkCode: 
,D/BluetoothAdapterService( 1608): Profile still running: com.android.bluetooth.hdp.HealthService
D/Messaging( 3498): ViewCache CreatePreloadOnlyConversationList
D/PanService( 1608): Received stop request...Stopping profile...
D/PanService( 1608): stop
,D/PanService( 1608): stop: mTetherAc send disconnect
,D/BluetoothTethering(  984): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  984): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  984): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  984): BluetoothPAN Proxy object disconnected
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/BluetoothHeadsetServiceJni( 1608): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1608): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1608): Profile still running: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 1608): handleDebugAction() action=null
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
D/CustomizationManager( 3686):  Read ACC file spent 0.067 (s)
D/BtGatt.GattService( 1608): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1608): stop()
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__032
D/A2dpStateMachine( 1608): cleanup
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__J15
D/PhoneStorageUtil( 3498): HtcWrapEnvironment.getSupportedStorages() >1
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__016
D/PhoneStorageUtil( 3498): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/PhoneStorageUtil( 3498): createReceiver
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 3686): Parsing tag item name = HTC__002
D/MessageCustFlag( 3498): sense_version=6.0
D/Avrcp   ( 1608): Unregistering previous receiver
,D/CIDMapFileReader( 3686): Parsing tag item name = HTC__031
D/BluetoothAdapterService( 1608): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1608): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1608): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1608): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1608): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1608): Cleaning up Bluetooth Health Interface...
,V/CustomizationCIDLoader( 3686): full path : /system/customize/CID/HTC__032.xml
D/Jerry   ( 3498): start to preload cursor >>>>>>>
,I/CustomizationCIDLoader( 3686): Parsing tag category name = system
I/CustomizationCIDLoader( 3686): Parsing tag category name = application
,D/DraftCache( 3498): [DraftCache/307] rebuildCache
I/CustomizationCIDLoader( 3686): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3686): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3686): Parsing tag category name = AudioService
,W/BluetoothHealthServiceJni( 1608): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 1608): Profile still running: com.android.bluetooth.gatt.GattService
D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
V/MmsProvider( 1241): Update uri=content://mms, match=0
V/MmsProvider( 1241): selection=st=129 AND m_type!=134
W/BluetoothPanServiceJni( 1608): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1608): Cleaning up Bluetooth PAN callback object
,I/CustomizationCIDLoader( 3686): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3686): Parsing tag category name = Settings
D/CustomizationManager( 3686):  Read CID file spent 0.132 (s)
,D/CustomizationManager( 3686):  All configurations done spent 0.133 (s)
,D/Messaging( 3498): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3498): TransactionService is going to be woken up.
W/HtcNativeFlag( 3686): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3686): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3686): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3686): Fail to get flag for type 'language', use default value: -1
W/dalvikvm( 3712): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3712): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,V/TransactionService( 3498): 1-Creating TransactionService
D/PanService( 1608): CMD_CHANNEL_DISCONNECTED
,D/PanService( 1608): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterState( 1608): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1608): Setting state to 10
I/BluetoothAdapterState( 1608): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1608): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  984): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  984): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 1608): Entering OffState
D/BluetoothManagerService(  984): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  984): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
V/TransactionService( 3498): onStartCommand: 1
,D/MmsSystemEventReceiver( 3498): unRegisterForConnectionStateChanges
V/TransactionService( 3498): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3498): Loading previous transactions.
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/BluetoothA2dp(  984): onBluetoothStateChange: up=false
,D/Messaging( 3498): mNeedToUpdateDate2: false
,D/BluetoothPbap( 3593): onBluetoothStateChange: up=false
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
D/AccFlag ( 1241): device_type: 1
,E/BluetoothPbap( 3593): 
E/BluetoothPbap( 3593): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@4234b660
E/BluetoothPbap( 3593): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3593): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3593): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3593): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3593): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset(  984): onBluetoothStateChange: up=false
,E/BluetoothPan( 3593): 
E/BluetoothPan( 3593): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@42344040
E/BluetoothPan( 3593): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3593): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3593): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3593): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3593): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3593): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3593): 
E/BluetoothInputDevice( 3593): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@42342aa8
E/BluetoothInputDevice( 3593): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3593): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3593): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3593): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3593): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3593): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1117): onBluetoothStateChange: up=false
D/TransactionService( 3498): Force set service start id to 1
V/TransactionService( 3498): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3498): unRegisterForConnectionStateChanges
D/TransactionService( 3498): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3498): Destroying TransactionService
,D/BluetoothMap( 3593): onBluetoothStateChange: up=false
,E/BluetoothMap( 3593): 
E/BluetoothMap( 3593): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@423453c0
E/BluetoothMap( 3593): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3593): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3593): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3593): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3593): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3593): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3593): 	at dalvik.system.NativeStart.run(Native Method)
V/TransactionService( 3498): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/BluetoothSap( 3593): onBluetoothStateChange on: false
,W/dalvikvm( 3712): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/BluetoothManagerService(  984): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  984): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 3593): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42336e30
,D/BluetoothAdapter( 3593): onBluetoothServiceDown: done
D/BluetoothAdapter( 1608): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@422e9fe8
D/BluetoothDevice( 1608): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 1608): onBluetoothServiceDown: done
D/BluetoothAdapter( 1241): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425700e0
,D/BluetoothAdapter( 1241): onBluetoothServiceDown: done
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1241):  phoneType = -1
D/BluetoothAdapter( 1225): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42605b20
D/BluetoothAdapter( 1225): onBluetoothServiceDown: done
D/BluetoothAdapter(  984): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42c68198
D/BluetoothAdapter(  984): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1779): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@422f1a28
,D/BluetoothAdapter( 1779): onBluetoothServiceDown: done
D/BluetoothAdapter( 1117): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@426b81c8
,D/BluetoothAdapter( 1117): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1257): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4239d600
,D/BluetoothAdapter( 1257): onBluetoothServiceDown: done
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3712, uid=10074, userID:0
D/BluetoothAdapter( 3250): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@422de7e8
D/BluetoothAdapter( 3250): onBluetoothServiceDown: done
D/BluetoothManagerService(  984): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42c68198 mBinding = false
D/BluetoothManagerService(  984): Sending unbind request.
,D/BluetoothManagerService(  984): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 1608): Cleaning up adapter native....
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
I/bt-btif ( 1608): HAL bt_hal_cbacks->thread_evt_cb
,D/Jerry   ( 1241): URI_DRAFT
D/BluetoothAdapterService( 1608): Done cleaning up adapter native....
D/BluetoothAdapterService(1110340728)( 1608): ****onDestroy()********
,D/BtGatt.GattService( 1608): cleanup()
W/bt-btif ( 1608): GATTC Module not enabled/already disabled
,W/bt-btif ( 1608): GATTS Module not enabled/already disabled
,D/PMS     (  984): releaseWL(42d1c7b8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothMasReceiver( 1608): Bluetooth STATE CHANGED to 10
D/NfcHandover( 1257): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 3593): setBluetoothStateOff
D/HtcTagManager( 3593): stopProxy
,W/BluetoothEventManager( 3593): unregister mProfileBroadcastReceiver fail
,V/BluetoothMasService( 1608): onDestroy: mIsEmailEnabled: true
D/BluetoothAdapter( 1225): 1113600856: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1225): 1113600856: getState() :  mService = null. Returning STATE_OFF
,W/BluetoothHeadset( 1117): Proxy not attached to service
D/DraftCache( 3498): hasDraft() = false mNeedNotifyChange = true
I/QuickSettingMiniLite( 1117): updateLiteState:no connect device!
D/DraftCache( 3498): [DraftCache/307] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 3498): 
D/MmsAsyncWorkHandler( 3498): HM tk = 20002
D/Messaging( 3498): ViewCache CreatePreload
,D/Messaging( 3498): ViewCache CreatePreloadOnlyMultipleOpsList
D/PMS     (  984): acquireWL(430de120): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1225 10029 null
D/PackageManager(  984): deletePackageAsUser: pkg=com.example.hello, pid=3686, uid=2000 user=0
,D/PMS     (  984): releaseWL(430de120): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/TetherPref( 3593): persistRestoreBluetoothState false
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Cust_MMSMS( 3498): _has_set_default_values_2=true
D/PMS     (  984): acquireWL(42e35c10): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3593 1000 null
W/ContextImpl( 3593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/Messaging( 3498): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/HtcBtWidget_BTWidgetProvider( 3667): onBTStateChanged() for widget: 
,D/DockEventReceiver( 3593): finishStartingService: stopping service
,D/HtcBtWidget_BTWidgetProvider( 3667): updateWidget(context) for widget: 
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/AccFlag ( 1241): sku_id=99
,D/Volley  ( 3712): [352] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3712): [345] DiskBasedCache.clear: Cache cleared.
D/PMS     (  984): releaseWL(42e35c10): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  984): acquireWL(42e198f8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3593 1000 null
,D/Ads     ( 3712): Skipping gmscore version check
,D/MsgPreferenceUtils( 3498): def_index: 0
,W/asset   (  984): Copying FileAsset 0x65acd310 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  984): releaseWL(42e198f8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,W/PackageSettings(  984): Skipping PackageSetting{42955f38 com.test.thalitest/10389} due to missing metadata
,D/Process (  984): killProcessQuiet, pid=3250
,D/BluetoothAdapter( 1117): 1113033696: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1241): sku_id=99
I/ActivityManager(  984): Force stopping com.example.hello appid=10397 user=0: pkg removed
I/ActivityManager(  984): Killing 3250:com.example.hello/u0a397 (adj 0): stop com.example.hello
W/ActivityManager(  984): Force removing ActivityRecord{43072b28 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  984): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  984): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/FeedHostManager( 1274): [onResume]
,I/FeedProviderManager( 1274): onResume
I/SocialFeedProvider( 1274): +onResume
I/SocialFeedProvider( 1274): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1274): -onResume
,W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
,D/MsgPreferenceUtils( 3498): globalIndex = 1
D/PMS     (  984): acquireWL(42fcfbe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028823
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028959
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029206
D/PMS     (  984): releaseWL(42fcfbe8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,W/InputDispatcher(  984): channel '42ef7e10 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  984): channel '42ef7e10 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowManager(  984): WINDOW DIED Window{42ef7e10 u0 com.example.hello/com.example.hello.MainActivity}
,W/InputDispatcher(  984): Attempted to unregister already unregistered input channel '42ef7e10 com.example.hello.MainActivity (s)'
,I/ConnectivityHelper( 1274): [getCurrentConnectionType] no network connection,
,D/BluetoothMasReceiver( 1608): Bluetooth STATE CHANGED to 10
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029209
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029215
D/WifiService(  984): Client connection lost with reason: 4
D/ConnectivityService(  984): getActiveNetworkInfo called by com.htc.launcher (1274/10076)
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029222
I/ActivityManager(  984): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030820
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030840
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360034486
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360052144
W/WindowManager(  984): Failed looking up window
W/WindowManager(  984): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@43014980 does not exist
W/WindowManager(  984): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  984): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  984): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  984): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  984): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  984): WIN DEATH: null
D/Finsky  ( 3712): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3712): [1] Libraries$2.run: Finished loading 1 libraries.
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1779): Received state change = 10
D/MsgPreferenceUtils( 3498): phone state: true
D/MsgPreferenceUtils( 3498): sd state: false
D/MsgPreferenceUtils( 3498): vIndex = 0
,I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "sms"
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "smsto"
,I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  984): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42e30760:true
W/System.err(  984): java.lang.Throwable: stack dump
W/System.err(  984): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/Finsky  ( 3712): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/System.err(  984): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  984): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  984): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3567): new LocationAgent instance!!
,D/Process (  984): killProcessQuiet, pid=3365
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  984): Killing 3365:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/HtcTagManager( 3567): HtcTagManager construction complete
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3567): BluetoothInputDevice()
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3567): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3567): Bluetooth service connected
D/BluetoothManagerService(  984): Registered receivers: 12
W/BluetoothInputDevice( 3567): Proxy not attached to service
D/BluetoothPan( 3567): BluetoothPan()
D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  984): Registered receivers: 13
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3567): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3567): Bluetooth service connected
D/BluetoothMap( 3567): Create BluetoothMap proxy object
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mms"
,D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  984): Registered receivers: 14
,I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1330): Unsupported attribute readOnly
,E/BluetoothMap( 3567): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  984): registerStateChangeCallback+
D/BluetoothSap( 3567): BluetoothSap() call bindService
,D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  984): Registered receivers: 15
,D/Finsky  ( 3712): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ContextImpl( 3567): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3567): BluetoothPbap()
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  984):   Scheme: "mmsto"
,D/BluetoothManagerService(  984): registerStateChangeCallback+
,D/BluetoothManagerService(  984): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3567): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3567): Bluetooth service connected
D/LocalBluetoothProfileManager( 3567): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3567): 1110394704: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3567): setBluetoothStateOff
D/HtcTagManager( 3567): stopProxy
W/BluetoothEventManager( 3567): unregister mProfileBroadcastReceiver fail
,D/BluetoothManagerService(  984): Registered receivers: 16
I/ActivityManager(  984): Resuming delayed broadcast
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/ConnectivityService(  984): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "sms"
,D/AuthorizationBluetoothService( 1364): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Process (  984): killProcessQuiet, pid=3473
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  984): Killing 3473:com.google.android.talk/u0a111 (adj 15): empty #17
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "smsto"
,I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,V/Tethering(  984): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Process (  984): killProcessQuiet, pid=3389
,D/Process (  984): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  984): Recipient 3473
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Killing 3389:com.htc.backup/1000 (adj 15): empty #17
,D/Tethering(  984): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  984): bSetPropertyMultiRAB:false
,D/Tethering(  984): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  984): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/Tethering(  984): ipv4Default null
I/Tethering(  984): No IPv4 upstream interface, giving up.
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mms"
,D/Tethering(  984): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.backuptransport (1575/10029)
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/dalvikvm( 2208): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2208): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2208): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
,W/dalvikvm( 2208): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/PackageManager(  984):   Action: "android.intent.action.SENDTO"
I/PackageManager(  984):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  984):   Scheme: "mmsto"
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
I/PackageManager(  984): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  984): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/ActivityManager(  984): Recipient 3365
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/FileApkUtils( 2208): Spent 20ms computing apk sha1.
,D/FileApkUtils( 2208): Module already staged or being staged:chimera-modules/MapsModule.apk
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
,D/DexOptUtils( 2208): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 2208): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 2208): Reading stored module config
D/PMS     (  984): acquireWL(42e6b818): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2208 10029 null
I/ActivityManager(  984): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
,D/GmsModuleFndr( 2208): Beginning GMS chimera module scan
,W/asset   ( 2208): Copying FileAsset 0x65aca190 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/PMS     (  984): acquireWL(42d09400): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 2208): Beginning module configuration check
,D/ChimeraCfgMgr( 2208): Module APKs unchanged, check complete
D/PMS     (  984): releaseWL(42e6b818): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
I/ActivityManager(  984): Resuming delayed broadcast
D/PMS     (  984): releaseWL(42d09400): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,W/Netd    (  363): No subsystem found in netlink event
I/DisplayManagerService(  984): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  984): Recipient 3389
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,V/Tethering(  984): remove iface:wlan0
D/Tethering(  984): interfaceRemoved wlan0
,E/Tethering(  984): attempting to remove unknown iface (wlan0), ignoring
,W/InstanceID/Rpc( 2208): Found 10029
,W/InputMethodManagerService(  984): Got RemoteException sending setActive(false) notification to pid 3250 uid 10397
,W/Binder  ( 1211): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1211): java.lang.NullPointerException
W/Binder  ( 1211): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1211): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1211): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1211): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  984): Enable input method client, pid=1274
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  984): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
,E/dalvikvm( 2208): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 2208): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2208): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2208): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2208): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2208): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 2208): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 2208): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 2208): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  984): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
,E/dalvikvm( 2208): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 2208): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
E/dalvikvm( 1225): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1225): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
,W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1225): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  984): Resuming delayed broadcast
D/PMS     (  984): acquireWL(42f8d160): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 2208): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 2208): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 2208): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 2208): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 2208): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  984): acquireWL(42f1f538): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
,D/Tethering(  984): interfaceLinkStateChanged p2p0, false
,D/Tethering(  984): interfaceStatusChanged p2p0, false
,D/Tethering(  984): [isWifi] getHotspotEnabled: false
D/PMS     (  984): releaseWL(42f8d160): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 2208): COMPAT: Multi user not supported
D/PMS     (  984): acquireWL(4302ce38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2208): Checkin interval check for package: unspecified last checkin: 1456764464980 min interval config: 0 actual interval: 78338675
,W/dalvikvm( 1364): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,I/ActivityManager(  984): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
I/GCoreUlr( 2208): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/CheckinService( 2208): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 1225): DispatchingService.onCreate()
,W/dalvikvm( 2208): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2208, uid=10029, userID:0
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2208, uid=10029, userID:0
W/dalvikvm( 2208): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/SQLiteDatabase( 1364): Failed to open database '/data/data/com.google.android.gms/databases/ns.db'.
E/SQLiteDatabase( 1364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:67)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:409)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:416)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:329)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:213)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/SQLiteDatabase( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 1364): 	at dalvik.system.NativeStart.main(Native Method)
D/SystemUpdateService( 2208): onCreate
E/SharedPreferencesImpl( 1225): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
E/SQLiteOpenHelper( 1364): Couldn't open ns.db for writing (will try read-only):
E/SQLiteOpenHelper( 1364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.open(S,QLiteConnection.java:221)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.nts.k.a(SourceFile:67)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:409)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.nts.h.<init>(SourceFile:416)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.nts.h.a(SourceFile:329)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:213)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/SQLiteOpenHelper( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 1364): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 1364): Opened ns.db in read-only mode
E/GCoreUlr( 1225): Error opening datastore
E/GCoreUlr( 1225): com.google.android.gms.leveldb.LevelDbIoErrorException: IO error: /data/data/com.google.android.gms/app_ulr_db/LOCK: Read-only file system
E/GCoreUlr( 1225): 	at com.google.android.gms.leveldb.LevelDb.nativeOpen(Native Method)
E/GCoreUlr( 1225): 	at com.google.android.gms.leveldb.LevelDb.a(SourceFile:140)
E/GCoreUlr( 1225): 	at com.google.android.location.reporting.b.a.a(SourceFile:81)
E/GCoreUlr( 1225): 	at com.google.android.location.reporting.service.DispatchingService.onCreate(SourceFile:392)
E/GCoreUlr( 1225): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/GCoreUlr( 1225): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/GCoreUlr( 1225): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/GCoreUlr( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GCoreUlr( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/GCoreUlr( 1225): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/GCoreUlr( 1225): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/GCoreUlr( 1225): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/GCoreUlr( 1225): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/GCoreUlr( 1225): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/GCoreUlr( 1225): 	at dalvik.system.NativeStart.main(Native Method)
I/GCoreUlr( 1225): DispatchingService.onDestroy()
D/SystemUpdateService( 2208): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
F/PackageManager(  984): Unable to backup user packages state file, current changes will be lost at reboot
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
W/dalvikvm( 2208): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
W/Netd    (  363): No subsystem found in netlink event
E/SQLiteDatabase( 1364): Failed to open database '/data/data/com.google.android.gms/databases/gcm_registrar.db'.
E/SQLiteDatabase( 1364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.br.<init>(SourceFile:169)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.br.<init>(SourceFile:160)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.br.a(SourceFile:154)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.bj.a(SourceFile:409)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:214)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/SQLiteDatabase( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 1364): 	at dalvik.system.NativeStart.main(Native Method)
V/Tethering(  984): remove iface:p2p0
D/Tethering(  984): interfaceRemoved p2p0
E/GCM-RS  ( 1364): Failed to open database
E/Tethering(  984): attempting to remove unknown iface (p2p0), ignoring
W/dalvikvm( 1364): VFY: unable to resolve instance field 161
D/ErrorReport(  984): HtcErrorReportManager Begin---add error logs to dropbox
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
E/ErrorReport(  984): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  984): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1456842803710.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  984): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  984): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  984): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  984): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  984): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  984): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  984): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:12243)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:12090)
E/ErrorReport(  984): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1067)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  984): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  984): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  984): 	... 18 more
,V/AuthZen ( 2208): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
D/PMS     (  984): acquireWL(4302f720): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
D/PMS     (  984): releaseWL(4302f720): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
D/WifiService(  984): New client listening to asynchronous messages
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/PMS     (  984): acquireWL(42db17c8): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
W/PackageManager(  984): Unable to load service info ResolveInfo{42ca1888 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  984): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  984): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  984): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  984): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  984): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  984): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  984): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  984): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  984): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  984): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  984): 	at dalvik.system.NativeStart.main(Native Method)
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2208, uid=10029, userID:0
I/CheckinService( 2208): Checking schedule, now: 1456842803748 next: 1457287401930
I/CheckinService( 2208): active receiver: disabled
I/SystemUpdateService( 2208): cancelUpdate (empty URL)
I/SystemUpdateService( 2208): active receiver: disabled
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2208, uid=10029, userID:0
D/PMS     (  984): releaseWL(42db17c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2208, uid=10029, userID:0
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
D/AuthZenEventHandler( 2208): Handling event: android.intent.action.BOOT_COMPLETED
W/dalvikvm( 2208): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/SharedPreferencesImpl( 2208): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/update.xml to backup file /data/data/com.google.android.gms/shared_prefs/update.xml.bak
W/BaseAppContext( 2208): Using Auth Proxy for data requests.
W/dalvikvm( 1364): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 2208): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2208, uid=10029, userID:0
D/ConnectivityService(  984): getActiveNetworkInfo called by com.google.android.gms (2208/10029)
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2208, uid=10029, userID:0
D/PMS     (  984): acquireWL(430dedb8): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2208, uid=10029, userID:0
,F/PackageManager(  984): Unable to backup user packages state file, current changes will be lost at reboot
,I/AuthZen ( 2208): Fetching signing key...
D/PMS     (  984): releaseWL(4302ce38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/ErrorReport(  984): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  984): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  984): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1456842803780.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  984): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  984): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  984): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  984): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  984): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  984): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  984): 	at android.util.Log.wtf(Log.java:256)
E/ErrorReport(  984): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1134)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:12243)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:12090)
E/ErrorReport(  984): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1067)
E/ErrorReport(  984): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  984): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  984): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  984): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  984): 	... 18 more
D/PMS     (  984): releaseWL(430dedb8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  984):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2208, uid=10029, userID:0
,D/SystemUpdateService( 2208): onDestroy
,E/SharedPreferencesImpl( 2208): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/update.xml to backup file /data/data/com.google.android.gms/shared_prefs/update.xml.bak
D/PMS     (  984): acquireWL(42fb55d8): PARTIAL_WAKE_LOCK  Icing 0x1 2208 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  984): releaseWL(42f1f538): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 1364): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,E/SQLiteDatabase( 2208): Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
E/SQLiteDatabase( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.keyservice.j.a(SourceFile:140)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.keyservice.g.d(SourceFile:224)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.keyservice.g.a(SourceFile:79)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.b.d.b(SourceFile:219)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:91)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteDatabase( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PMS     (  984): releaseWL(42fb55d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
E/SQLiteOpenHelper( 2208): Couldn't open keys.db for writing (will try read-only):
E/SQLiteOpenHelper( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.keyservice.j.a(SourceFile:140)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.keyservice.g.d(SourceFile:224)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.keyservice.g.a(SourceFile:79)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.b.d.b(SourceFile:219)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:91)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteOpenHelper( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1364): Failed to open database '/data/data/com.google.android.gms/databases/rmq.db'.
E/SQLiteDatabase( 1364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLi,teDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteDatabase( 1364): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.access$1800(ActivityThread.java:153)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/SQLiteDatabase( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 1364): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 2208): Opened keys.db in read-only mode
E/SQLiteOpenHelper( 1364): Couldn't open rmq.db for writing (will try read-only):
E/SQLiteOpenHelper( 1364): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 1364): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 1364): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1364): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.bx.b(SourceFile:537)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.e.<init>(SourceFile:204)
E/SQLiteOpenHelper( 1364): 	at com.google.android.gms.gcm.GcmService.onCreate(SourceFile:232)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2861)
E/SQLiteOpenHelper( 1364): 	at android.app.Activi,tyThread.access$1800(ActivityThread.java:153)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1440)
E/SQLiteOpenHelper( 1364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1364): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 1364): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 1364): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 1364): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 1364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 1364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 1364): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 1364): Opened rmq.db in read-only mode
I/AuthZen ( 2208): Signing key fetched successfully!
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/PMS     (  984): acquireWL(42f4b478): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1364 10029 WorkSource{10029 com.google.android.gms}
W/BaseAppContext( 2208): Using Auth Proxy for data requests.
D/GCM     ( 1364): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1364): [NET] getaddrinfo-,err=8
D/libc    ( 1364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1364): [NET] getaddrinfo-, 1
D/libc    ( 1364): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2424 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/libc    (  363): [NET]Querying server xid =2424 (# 1) address = 192.168.1.1 (try=2,nscount=1)
D/libc    (  363): [NET]res_nsend:ECONNREFUSED
D/libc    (  363): [NET] -----res_nsend exit-1: xid=2424, total retry = 3 times, errno=111,v_circuit=0-----
D/libc    (  363): [NET]res_queryN: exit 2
D/libc    (  363): [NET]_dns_getaddrinfo- 6, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 1364): [NET] getaddrinfo_proxy-
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
E/SQLiteDatabase( 2208): Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
E/SQLiteDatabase( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteDatabase( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2208): Couldn't open keys.db for writing (will try read-only):
E/SQLiteOpenHelper( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.keyservice.j.c(SourceFile:228)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:186)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:258)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:209)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:202)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:148)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/SQLiteOpenHelper( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 2208): Opened keys.db in read-only mode
E/SQLiteDatabase( 2208): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.playlog.store.d.b(SourceFile:291)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.playlog.store.r.a(SourceFile:504)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.app.service.BootCompletedBroadcastService.onHandleIntent(SourceFile:130)
E/SQLiteDatabase( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2208): Couldn't open playlog.db for writing (will try read-only):
E/SQLiteOpenHelper( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.playlog.store.d.b(SourceFile:291)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.playlog.store.r.a(SourceFile:504)
E/SQLiteOpenHelper( 2208): 	at com.google.android.gms.app.service.BootCompletedBroadcastService.onHandleIntent(SourceFile:130)
E/SQLiteOpenHelper( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  984): reportInetCondition for net -1, percentage: 0 by  (1364/10029)
D/ConnectivityService(  984): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/PMS     (  984): releaseWL(42f4b478): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (1364/10029)
D/AuthZenTransactionCache( 2208): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2208): Clearing transaction cache
E/AuthZenTransactionCache( 2208): Error while clearing cache
E/AuthZenTransactionCache( 2208): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/auth.authzen.store.transactions_v2: open failed: EROFS (Read-only file system)
E/AuthZenTransactionCache( 2208): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/AuthZenTransactionCache( 2208): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/AuthZenTransactionCache( 2208): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/AuthZenTransactionCache( 2208): 	at com.google.android.gms.auth.c.h.a(SourceFile:96)
E/AuthZenTransactionCache( 2208): 	at com.google.android.gms.auth.authzen.transaction.x.b(SourceFile:263)
E/AuthZenTransactionCache( 2208): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:154)
E/AuthZenTransactionCache( 2208): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZenTransactionCache( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZenTransactionCache( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZenTransactionCache( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/AuthZenTransactionCache( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AuthZenTransactionCache( 2208): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/AuthZenTransactionCache( 2208): 	at libcore.io.Posix.open(Native Method)
E/AuthZenTransactionCache( 2208): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/AuthZenTransactionCache( 2208): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/AuthZenTransactionCache( 2208): 	... 10 more
E/SQLiteLog( 2208): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2208): (14) os_unix.c:30190: (2) open(/data/data/com.google.android.gms/databases/playlog.db-wal) - 
,E/SQLiteLog( 2208): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
I/ActivityManager(  984): Resuming delayed broadcast
I/ActivityManager(  984): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
E/SQLiteDatabase( 2208): Failed to open database '/data/data/com.google.android.gms/databases/auth.credentials.credential_store'.
E/SQLiteDatabase( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:66)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(SourceFile:187)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:137)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:185)
E/SQLiteDatabase( 2208): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:98)
E/SQLiteDatabase( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 2208): threadid=44: thread exiting with uncaught exception (group=0x41e9ae30)
,E/AndroidRuntime( 2208): FATAL EXCEPTION: IntentService[CredentialSyncReceiverService]
E/AndroidRuntime( 2208): Process: com.google.android.gms, PID: 2208
E/AndroidRuntime( 2208): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 2208): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 2208): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2208): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2208): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:66)
E/AndroidRuntime( 2208): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(SourceFile:187)
E/AndroidRuntime( 2208): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:137)
E/AndroidRuntime( 2208): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:185)
E/AndroidRuntime( 2208): 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:98)
E/AndroidRuntime( 2208): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2208): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2208): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2208): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  984): App crashed! Process: com.google.android.gms
,E/DropBoxManagerService(  984): Can't write: system_app_crash
E/DropBoxManagerService(  984): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  984): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  984): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  984): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  984): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  984): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  984): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  984): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  984): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  984): 	... 5 more
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  984): Resuming delayed broadcast
,D/RemoteDisplayProvider(  984): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  984): start
,I/AlarmManager(  984): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  984): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  984): DelayedCaptiveCheckState
D/CaptivePortalTracker(  984): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  984): NoActiveNetworkState
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
,D/ChimeraCfgMgr( 2208): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 2208): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2208): Got an BootCompleted event.
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028823
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360028959
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029206
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029209
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029215
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360029222
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030820
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360030840
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360034486
W/AlarmManager(  984): Converted elapesd time is over 1 year! when = 315360052144
,D/BootCompletedReceiver( 2208): Will NOT schedule AdAttestation signal task because it's disabled.
,D/ConnectivityService(  984): getNetworkInfo networkType=1 called by  (984/1000)
,W/AtomicFile(  984): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  984): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  984): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  984): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  984): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  984): acquireWL(42ef0730): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 984 1000 null
W/AppWidgetServiceImpl(  984): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  984): releaseWL(42ef0730): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/SharedPreferencesImpl( 1225): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/bootCount.xml to backup file /data/data/com.google.android.gms/shared_prefs/bootCount.xml.bak
,W/dalvikvm( 1364): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 1364): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/PMS     (  984): acquireWL(4300ea10): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1364 10029 null
,V/GLSActivity( 1364): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  984): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  984): releaseWL(4300ea10): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  984): Resuming delayed broadcast
,D/PersistentNotificationBroadcastReceiver( 1225): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) },
,I/ActivityManager(  984): Delay finish: com.google.android.gms/.people.sync.focus.ContactsSyncBroadcastReceiver
,I/ActivityManager(  984): Resuming delayed broadcast
,I/ActivityManager(  984): Delay finish: com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
,W/AtomicFile(  984): Couldn't rename file /data/system/sync/pending.xml to backup file /data/system/sync/pending.xml.bak
,W/SyncManager(  984): Error writing pending operations
W/SyncManager(  984): java.io.IOException: Couldn't create directory /data/system/sync/pending.xml
W/SyncManager(  984): 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
W/SyncManager(  984): 	at com.android.server.content.SyncStorageEngine.writePendingOperationsLocked(SyncStorageEngine.java:2414)
W/SyncManager(  984): 	at com.android.server.content.SyncStorageEngine.appendPendingOperationLocked(SyncStorageEngine.java:2463)
W/SyncManager(  984): 	at com.android.server.content.SyncStorageEngine.insertIntoPending(SyncStorageEngine.java:964)
W/SyncManager(  984): 	at com.android.server.content.SyncQueue.add(SyncQueue.java:125)
W/SyncManager(  984): 	at com.android.server.content.SyncQueue.add(SyncQueue.java:85)
W/SyncManager(  984): 	at com.android.server.content.SyncManager.scheduleSyncOperation(SyncManager.java:1048)
W/SyncManager(  984): 	at com.android.server.content.SyncManager.scheduleSync(SyncManager.java:865)
W/SyncManager(  984): 	at com.android.server.content.ContentService.sync(ContentService.java:380)
W/SyncManager(  984): 	at android.content.IContentService$Stub.onTransact(IContentService.java:132)
W/SyncManager(  984): 	at com.android.server.content.ContentService.onTransact(ContentService.java:141)
W/SyncManager(  984): 	at android.os.Binder.execTransact(Binder.java:412)
W/SyncManager(  984): 	at dalvik.system.NativeStart.run(Native Method)
D/ConnectivityService(  984): getActiveNetworkInfo called by  (984/1000)
D/PMS     (  984): acquireWL(42ed6728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 984 1000 null
I/ActivityManager(  984): Resuming delayed broadcast
,D/PMS     (  984): releaseWL(42ed6728): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3593): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3593): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3593): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3593): Cust_ConnectToPC   : spcsc>false
D/        ( 3593): Cust_ConnectToPC   : IPT>true
D/        ( 3593): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3593): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3593): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3593): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3593): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3593): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3593): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  984): Delay finish: com.android.settings/.PSReceiver
W/Settings( 3593): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3593):  defaultType:0
I/ActivityManager(  984): Resuming delayed broadcast
,I/ActivityManager(  984): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3831 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3831): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3831): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3831): Loading: swewebviewchromium
,I/LibraryLoader( 3831): Time to load native libraries: 41 ms (timestamps 4400-4441)
,I/LibraryLoader( 3831): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3831): Initializing chromium process, renderers=9
,I/LibraryLoader( 3831): Expected native library version number "",actual native library version number ""
,I/chromium( 3831): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  984): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3849 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  984): sending alarm PendingIntent{4238e258: PendingIntentRecord{42bb9cb8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=58541, Int=0

```
