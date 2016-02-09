#### Test 583805004f2b042_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/TelephonyReceiver( 1241): bind: true
--------- beginning of /dev/log/system
I/ActivityManager(  912): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3920 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=true
D/GenericMessagesProvider( 3740): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3740): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 3740): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3740): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 3740): DB info: errno = 2, errno message = No such file or directory
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.music (3898/10154)
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/SQLiteDatabase( 3740): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3740): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3740): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3740): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3740): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3740): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3740): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3740): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3740): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3740): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3740): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3740): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3740): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3740): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3740): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3740): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3740): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3740): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 3740): 	at dalvik.system.NativeStart.run(Native Method)
D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/DFPI.PIReciver( 3920): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3920): onHandleIntent
I/DFPI.ApkInstallService( 3920): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3920): check CID = HTC__032
I/DFPI.ApkInstallService( 3920): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  912): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  912): Resuming delayed broadcast
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/PackageManager(  912): Unable to load service info ResolveInfo{42b24be8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/MediaRouter( 3898): getSelectedRoute
I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3898, uid=10154, userID:0
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  912): Resuming delayed broadcast
I/HtcModeClient( 1523): handler message = 4011
E/HtcModeClient( 1523): Check connection and retry 5 times.
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/Process (  912): killProcessQuiet, pid=3676
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3937 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
I/ActivityManager(  912): Killing 3676:com.htc.android.worldclock/u0a90 (adj 15): empty #17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/ActivityManager(  912): Recipient 3676
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
I/ActivityManager(  912): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.musicenhancer (3937/10053)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.musicenhancer (3937/10053)
W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42c79f10 u0 ReceiverList{42c79eb0 3937 com.htc.musicenhancer/10053/u0 remote:42c79bb8}}
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3937): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  912): start
I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/PMS     (  912): acquireWL(42cdfca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cdfca0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(42ce4968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): acquireWL(42cea9e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42ce4968): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  912): releaseWL(42cea9e0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  912): applying state to connected service
D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(42cf5b80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cf5b80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42cf6d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cf6d40): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/cutils-trace( 3950): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3950): ====startRecUseTime====
D/htc.customization.log.level( 3950):  is 
W/CustomizationLogLevel( 3950): Level value is invalid, use default level 2
D/PMS     (  912): releaseWL(429d50a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/CustomizationManager( 3950):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3950): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3950): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3950): Parsing tag category name = system
I/CustomizationCIDLoader( 3950): Parsing tag category name = application
I/CustomizationCIDLoader( 3950): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3950): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3950): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3950): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3950): Parsing tag category name = Settings
D/CustomizationManager( 3950):  Read CID file spent 0.098 (s)
D/CustomizationManager( 3950):  All configurations done spent 0.098 (s)
W/HtcNativeFlag( 3950): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3950): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3950): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3950): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  912): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3950
I/Prism.ItemManager( 3725): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3725): loadItems() com.htc.launcher.pageview.WidgetManager@41fac0d8 +
I/Prism.WidgetManager( 3725): onLoadItems() +
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 +
I/Prism.WidgetManager( 1274): onLoadItems() +
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3968 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=3690
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3690:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3690
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3968): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  912): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3968): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3968): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3968): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 -
,I/Prism.WidgetManager( 3725): onLoadItems() -
,I/Prism.ItemManager( 3725): loadItems() com.htc.launcher.pageview.WidgetManager@41fac0d8 -
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1241): -- N1 =0
D/PhoneApp( 1241): -- N2 =0
D/PhoneApp( 1241): -- N3 =0
I/SocialFeedProvider( 1274): +disConnect socialManager
I/SocialFeedProvider( 1274): disconnect socialManager
I/SocialFeedProvider( 1274): -disConnect socialManager
I/ActivityManager(  912): Resuming delayed broadcast
D/DFPI.PIReciver( 3920): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  912): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3920): onHandleIntent
I/DFPI.ApkInstallService( 3920): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3920): check CID = HTC__032
I/DFPI.ApkInstallService( 3920): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  912): mEventCount = 450
,V/AlarmManager(  912): sending alarm PendingIntent{42a77f60: PendingIntentRecord{42a9d5f8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1455035740691, Int=0
,I/SocialManager[SocialBiLogHelper]( 3725): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3725): last commit ulog time 1455021437164
,I/SocialManager[SocialBiLogHelper]( 3725): skip commit this time
,D/Process (  912): killProcessQuiet, pid=3457
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  912): killProcessQuiet, pid=3706
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3457:com.htc.task/u0a71 (adj 15): empty #17
I/ActivityManager(  912): Killing 3706:com.qualcomm.timeservice/1000 (adj 15): empty #18
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3457
,I/ActivityManager(  912): Recipient 3706
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/ActivityManager(  912): Resuming delayed broadcast
,D/Process (  912): killProcessQuiet, pid=3758
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3758:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3968): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3968): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3968): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3968): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  912): Recipient 3758
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMed,iaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3990 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  912): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  912): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4003 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3920): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3920): onHandleIntent
I/DFPI.ApkInstallService( 3920): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3920): check CID = HTC__032
,I/DFPI.ApkInstallService( 3920): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 4003): [ NA ]- onCreate()
,I/EASAppSvc( 4003): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3990): put()
,D/Process (  912): killProcessQuiet, pid=3772
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3772:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/WifiService(  912): New client listening to asynchronous messages
,I/ActivityManager(  912): Recipient 3772
,I/EASAppSvc( 4003): [ NA ]- onDestroy()
,I/EASAppSvc( 4003): [ NA ]> uninitEASService
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.android.mail (4003/10064)
D/ConnectivityService(  912): getNetworkInfo networkType=0 called by com.htc.android.mail (4003/10064)
D/ConnectivityService(  912): getNetworkInfo networkType=55 called by com.htc.android.mail (4003/10064)
,I/EASRequestController( 4003): [ NA ]release
,I/EASAppSvc( 4003): [ NA ]< uninitEASService
,I/EASAppSvc( 4003): [ NA ]- onCreate()
,I/EASAppSvc( 4003): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.android.mail (4003/10064)
D/ConnectivityService(  912): getNetworkInfo networkType=0 called by com.htc.android.mail (4003/10064)
D/ConnectivityService(  912): getNetworkInfo networkType=55 called by com.htc.android.mail (4003/10064)
,D/ORMLib  ( 3990): put()
,I/EASAppSvc( 4003): [ NA ]- onDestroy()
,I/EASAppSvc( 4003): [ NA ]> uninitEASService
,I/EASRequestController( 4003): [ NA ]release
I/ActivityManager(  912): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4035 uid=10068 gids={50068, 3003, 5012}
,I/EASAppSvc( 4003): [ NA ]< uninitEASService
,D/Process (  912): killProcessQuiet, pid=3604
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3604:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/ORMLib  ( 3990): put()
,I/ActivityManager(  912): Recipient 3604
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42ba5020 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3968): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3968): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3968): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3968): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  912): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T],
,I/MediaStoreImporter( 3898): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3920): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3920): onHandleIntent
,I/DFPI.ApkInstallService( 3920): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3920): check CID = HTC__032
,I/DFPI.ApkInstallService( 3920): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3968): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3968): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3968): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3968): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3968): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3968): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3968): MODE_GSM access default DB
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  912): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3968): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3968): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3968): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3968): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,V/AlarmManager(  912): sending alarm PendingIntent{42199078: PendingIntentRecord{42933588 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=60908, Int=0
,I/MediaStoreImporter( 3898): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): acquireWL(42cdad78): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1523 10014 null
I/ActivityManager(  912): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  912): releaseWL(42cdad78): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/TelephonyReceiver( 1241): bind: false
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4062 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  912): acquireWL(42becaa0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
,D/Process (  912): killProcessQuiet, pid=3623
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 3623:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,D/WifiDataStallTracker(  912): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  912): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/PMS     (  912): releaseWL(42becaa0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  912): updateDataStallInfo: mDataStallTxRxSum={txSum=35 rxSum=28} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  912): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  912): onDataStallAlarm: tag=20096 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20097 delay=15s
I/ActivityManager(  912): Delay finish: com.htc.launcher/.receiver.BiLogReceiver
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3623
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  912): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1118): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42200790 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.updater 2 11 1 10
I/ActivityManager(  912): Resuming delayed broadcast
,I/RemoteViews( 1118): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42317c00 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  912): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4081 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
I/RemoteViews.Performance( 1118): com.htc.updater 7 10 1 10
,D/PMS     (  912): acquireWL(429b7398): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(429b7398): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 4081): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 6 times.
,I/ActivityManager(  912): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  912): acquireWL(4289ee38): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(4289ee38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4106 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/ActivityManager(  912): Killing 3790:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=3790
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3790
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  912): Client connection lost with reason: 4
,D/PMS     (  912): acquireWL(428be380): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(428be380): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 4081): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4081): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4081): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4081): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel   ( 4106): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4106): MmsConfig.loadMmsSettings
,W/dalvikvm( 4106): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4106): VFY: unable to resolve instance field 36
,W/dalvikvm( 4106): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4106): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/MmsCustomizationProvider( 3740): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/MmsCustomizationProvider( 3740): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4106): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4106): MmsConfig.loadFromDatabase
,E/Babel   ( 4106): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4106): MmsConfig.loadFromResources
,E/Babel   ( 4106): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4106): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4106, uid=10111, userID:0
,W/Settings( 4106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4106, uid=10111, userID:0
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4106, uid=10111, userID:0
D/PMS     (  912): acquireWL(4289f620): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
I/ActivityManager(  912): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4106): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  912): releaseWL(4289f620): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): acquireWL(42a45070): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
,I/ActivityManager(  912): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  912): releaseWL(42a45070): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  912): Resuming delayed broadcast
,D/Process (  912): killProcessQuiet, pid=3816
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3816:com.android.settings/1000 (adj 15): empty #17
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Recipient 3816
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  912): acquireWL(429697b8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(429697b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42b48870): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42b48870): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a923c8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42a923c8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42ab4bd0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ab4bd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c7b5c0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c7b5c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a8a250): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42a8a250): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42854dc0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42854dc0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{429b5980: PendingIntentRecord{42999c00 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1455035744026, Int=0
,D/PMS     (  912): acquireWL(42ba7af8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ba7af8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): [ScoreAP] + current TXpacket:65, mTXpacketCount:37, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  912): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 310 ms] updated apps [took 310 ms] 
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4150 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  912): acquireWL(42ac02e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/BatteryService(  912): n_update end
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(42ac02e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): acquireWL(42a06ca0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4150 10160 null
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
D/PMS     (  912): acquireWL(42a54258): PARTIAL_WAKE_LOCK  AsyncService 0x1 4150 10160 null
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(42a54258): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  912): acquireWL(42c745e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4150 10160 null
D/PMS     (  912): releaseWL(42a06ca0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4150/10160)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
D/PMS     (  912): releaseWL(42c745e8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4174 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  912): killProcessQuiet, pid=3655
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/HtcFingerPrintQuickLaunchProvider( 4174): -onCreate()
I/ActivityManager(  912): Killing 3655:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,V/Settings:HtcSettingsApplication( 4174): [4174/4174] onCreate()
,I/ActivityManager(  912): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4189 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=3394
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 3394:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3394
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3655
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4189, uid=10074, userID:0
,D/Finsky  ( 4189): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Settings:HtcWirelessFeatureFlags( 4174): id/is att sku: 99/false
D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (4189/10074)
,W/SystemReader( 4174): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4174): Cannot find support_harman, use default value instead
,W/SystemReader( 4174): Cannot find effect_manager_id, use default value instead
,D/WIFI_ICON( 1118): WifiActivity: 0
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,E/Settings:HtcWrapHeaderInfo( 4174): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4174): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4174): updateDevelopment, bPrefShow = true
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcUmcWidgetEnabler( 4174): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]support         :false
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/FingerprintManager( 4174): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
D/ConnectivityService(  912): getAllNetworkInfo called by com.android.vending (4189/10074)
I/ActivityManager(  912): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4174): isSupportVoWifi: null
E/ActivityThread( 4174): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 4189): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 4189): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 4189): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4189): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 4189): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 4189): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4189, uid=10074, userID:0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4174): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4174): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4174): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4174): [supportHomeButton]support         :false
,W/FingerprintManager( 4174): hasFingerprint() - sSensorCode = 0
,I/ActivityManager(  912): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 4174): isSupportVoWifi: null
E/ActivityThread( 4174): Failed to find provider info for com.htc.vowifi
,D/Ads     ( 4189): Skipping gmscore version check
,D/Finsky  ( 4189): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4189): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4189): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/dalvikvm( 4189): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/Finsky  ( 4189): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  912): killProcessQuiet, pid=3838
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3838:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  912): acquireWL(42becaa0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
I/ActivityManager(  912): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/PMS     (  912): releaseWL(42becaa0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  912): Recipient 3838
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): acquireWL(42bc00d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): acquireWL(42b68c70): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42bc00d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42b68c70): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42ae8408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  912): acquireWL(42ac02e8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  912): releaseWL(42ae8408): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42a59230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42a59230): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Delay finish: com.google.android.gsf/.settings.GoogleLocationSettings$LocationSettingsChangedListener
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,W/dalvikvm( 2188): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2188): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2188): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2188): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2188): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2188): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2188): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2188, uid=10029, userID:0
,I/PeopleDatabaseHelper( 2188): cleanUpNonGplusAccounts done.
,I/ActivityManager(  912): Resuming delayed broadcast
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/PMS     (  912): acquireWL(42832268): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(429d82e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(429d82e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(427bd220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(427bd220): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): acquireWL(4210b860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42832268): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(4210b860): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a95108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(42a95108): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(42a905e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4241 uid=10041 gids={50041}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42a905e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a4b0e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3990 10071 null
,D/PMS     (  912): acquireWL(42cb47d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3990 10071 null
,D/Process (  912): killProcessQuiet, pid=3428
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 3428:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
I/ActivityManager(  912): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 3990): java.lang.NullPointerException
W/System.err( 3990): java.lang.NullPointerException
W/System.err( 3990): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
,W/System.err( 3990): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3990): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3990): stopSelfResult true
D/PMS     (  912): releaseWL(42a4b0e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  912): releaseWL(42cb47d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  912): Resuming delayed broadcast
D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  912): Recipient 3428
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  912): Done.
,D/ConnectivityService(  912): Setting timer for 720seconds
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,D/LocationInitializer( 2188): Restart initialization of location
,E/MDM     ( 1224): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  912): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,D/PMS     (  912): acquireWL(42ca6398): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): releaseWL(42ca6398): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
E/TodoTaskNotifyService( 3990): java.lang.NullPointerException
,W/System.err( 3990): java.lang.NullPointerException
W/System.err( 3990): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3990): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3990): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  912): acquireWL(42b525c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3990 10071 null
D/PMS     (  912): acquireWL(42b8ea10): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3990 10071 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
D/PMS     (  912): releaseWL(42b525c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  912): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42b8ea10): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3990): stopSelfResult true
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): acquireWL(42a5b5d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3990 10071 null
D/PMS     (  912): acquireWL(42c4d608): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3990 10071 null
E/TodoTaskNotifyService( 3990): java.lang.NullPointerException
W/System.err( 3990): java.lang.NullPointerException
W/System.err( 3990): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3990): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3990): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3990): stopSelfResult true
I/ActivityManager(  912): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  912): releaseWL(42a5b5d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  912): releaseWL(42c4d608): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  912): Resuming delayed broadcast
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/PMS     (  912): acquireWL(42c9ea10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4106 10111 null
I/ActivityManager(  912): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  912): releaseWL(42c9ea10): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  912): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  912): acquireWL(42af9690): PARTIAL_WAKE_LOCK  AsyncService 0x1 4150 10160 null
,D/PMS     (  912): releaseWL(42af9690): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  912): Resuming delayed broadcast
,I/WSP     ( 1320): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1320): Weather sync is On
,D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2188): Null package name or gms related package.  Ignoreing.
,I/WSP     ( 1320): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 09 18:35:45 CET 2016
I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,I/Icing   ( 2188): updateResources: need to parse f{com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/PMS     (  912): acquireWL(42b46520): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1320 10055 null
,W/SQLiteConnectionPool( 2188): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/MediaManager( 3855): [DualLensScanUtil]	mmpCursor count is 0
,V/AlarmManager(  912): sending alarm PendingIntent{42a59a18: PendingIntentRecord{42addf50 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1455035745838, Int=0
,I/iu.UploadsManager( 2188): End new media; added: 0, uploading: 0, time: 42 ms
V/AlarmManager(  912): sending alarm PendingIntent{42b3b138: PendingIntentRecord{42aaff20 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1455035745880, Int=0
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2188): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  912): releaseWL(42ac02e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3855): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3990): update TASK shortcut>
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2188, uid=10029, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2188, uid=10029, userID:0
,I/CheckinService( 2188): Done disabling old GoogleServicesFramework version
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV2    ( 4081): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 2188): Google Analytics 8.4.89 is starting up.
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 7 times.
,I/GAV4    ( 4106): Thread[GAThread,5,main]: No campaign data found.
,I/SensorManager(  912): mEventCount = 600
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/Process (  912): killProcessQuiet, pid=3725
,I/ActivityManager(  912): Killing 3725:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3725
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/CalendarProvider2( 1523): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1523): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): acquireWL(42a63f98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/PMS     (  912): acquireWL(427dc630): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/PMS     (  912): releaseWL(42a63f98): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  912): releaseWL(427dc630): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  912): acquireWL(4289c578): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3898 10154 null
I/ActivityManager(  912): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3898): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3898, uid=10154, userID:0
,I/MusicLeanback( 3898): Conditions not met for autocaching.
I/MusicLeanback( 3898): Stop autocaching.
,W/ContextImpl( 3898): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  912): releaseWL(4289c578): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4301 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4301): Loading default preferences
,W/Resources( 4301): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  912): New client listening to asynchronous messages
,D/SyncApplication( 4301): Overriding preferences with custom values
,D/SyncApplication( 4301): Updating preferences succeeded
,E/SyncApplication( 4301): Application created.
D/VolumeInfo( 4301): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4301): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 4301): Found 0 mount point(s)
,V/VolumeInfo( 4301): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4301): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4301): getNewCalendarAuthority()...
D/SyncApplication( 4301): enableAppOperation()+
,D/VolumeInfo( 4301): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 4301): Can not create volume ID for unmounted volume null
D/SyncApplication( 4301): enableAppOperation()-
,D/HTCUtilities( 4301): isNeorSinged() + 
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4301, uid=10008, userID:0
W/PackageManager(  912): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4301, uid=10008, userID:0
W/PackageManager(  912): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4301): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4301): isNeorSinged() return false
,D/CDMountReceiver( 4301): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4301): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4301): enable CD Auto-mount: true
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4301): enable auto-mount
,D/HTCUtilities( 4301): enable auto-mount
I/ActivityManager(  912): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
D/MountService(  912): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  912): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  912): Resuming delayed broadcast
D/PMS     (  912): releaseWL(427a3f88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/ActivityManager(  912): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42275060 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 1 12 3 11
I/RemoteViews( 1118): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{42323848 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3855): [DualLensScanUtil]	mmpCursor count is 0
,D/Process (  912): killProcessQuiet, pid=4003
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Resuming delayed broadcast
I/ActivityManager(  912): Killing 4003:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4003
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  912): Client connection lost with reason: 4
,D/PMS     (  912): acquireWL(429f8930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(429f8930): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(42ad3438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): releaseWL(42ad3438): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(42b3ebf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  912): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4323 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42b3ebf0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/CalendarApplication( 4323): onCreate
D/ProviderChangeReceiver( 4323): ---------------------------------------------------
,D/ProviderChangeReceiver( 4323): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4323): start to updateAlertNotification!
,I/ActivityManager(  912): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4337 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  912): killProcessQuiet, pid=4035
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 4035:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4035
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 4323): No fired or scheduled alerts
,D/HtcAlertUtils( 4323): -- cancelReminderNotification --
,D/HtcAlertUtils( 4323): broadcastExistReminder!
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4337): [4337/4337] onCreate()
W/ContextImpl( 4337): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  912): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  912): Resuming delayed broadcast
,D/Process (  912): killProcessQuiet, pid=3920
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  912): Killing 3920:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 3920
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 8 times.
I/ActivityManager(  912): Waited long enough for: ServiceRecord{42c72618 u0 com.htc.musicenhancer/.EnhancerService}
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  912): acquireWL(42bd4a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42bd4a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  912): releaseWL(42b46520): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97,
,D/WifiNative-wlan0(  912):    returned true
,D/Finsky  ( 4189): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4189): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;,
D/PMS     (  912): acquireWL(42a59090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
V/AlarmManager(  912): sending alarm PendingIntent{42870af8: PendingIntentRecord{42b83628 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455035756864, Int=0
D/PMS     (  912): releaseWL(42a59090): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.android.vending (4189/10074)
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4189): [NET] getaddrinfo-,err=8
D/libc    ( 4189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4189): [NET] getaddrinfo-, 1
D/libc    ( 4189): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =ff63 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4189): [NET] getaddrinfo_proxy-, success
I/global  ( 4189): call createSocket() return a new socket.
D/libc    ( 4189): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4189): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4189): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4189): untagSocket(69) failed with errno -22
,D/Finsky  ( 4189): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,W/NetworkManagementSocketTagger( 4189): untagSocket(69) failed with errno -22
,D/WifiDataStallTracker(  912): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  912): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  912): updateDataStallInfo: mDataStallTxRxSum={txSum=61 rxSum=52} preTxRxSum={txSum=35 rxSum=28}
D/WifiDataStallTracker(  912): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  912): onDataStallAlarm: tag=20097 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20098 delay=15s
D/PMS     (  912): acquireWL(42becaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{42a3aa30: PendingIntentRecord{4287d250 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=76051, Int=0
D/PMS     (  912): releaseWL(42becaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 9 times.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4189): untagSocket(69) failed with errno -22
,D/ConnectivityService(  912): getNetworkInfo networkType=0 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.android.vending (4189/10074)
,D/Finsky  ( 4189): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  912): acquireWL(42b16f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{426d9008: PendingIntentRecord{42c5b878 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1455035759092, Int=0
,D/PMS     (  912): acquireWL(4289f780): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4189 10074 null
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,D/Finsky  ( 4189): [449] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/PMS     (  912): releaseWL(42b16f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/DeviceConnectionService( 1224): client connected with version: 8296000
D/Finsky  ( 4189): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 4189): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=12 [66][8][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [ScoreAP] + current TXpacket:139, mTXpacketCount:65, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  912): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/libc    ( 4189): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4189): [NET] getaddrinfo-,err=8
D/libc    ( 4189): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4189): [NET] getaddrinfo-, 1
,D/libc    ( 4189): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =5014 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 298
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4189): [NET] getaddrinfo_proxy-, success
,D/PMS     (  912): releaseWL(4289f780): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/PMS     (  912): acquireWL(42b40dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=78051, Int=0
,D/PMS     (  912): releaseWL(42b40dc8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1118): now=1455035760327 next=59673
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=23 [13][3][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 10 times.
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1320): service - mHandler: update timezone
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  912): killProcessQuiet, pid=3968
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3968:com.htc.sdm/u0a81 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3968
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): service - onCreate()
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1523): service - mHandler: update timezone
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1523): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1523): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{4235d5b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 7 2 11
,I/SensorManager(  912): mEventCount = 750
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 11 times.
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/WifiDataStallTracker(  912): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  912): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  912): acquireWL(42c9ce78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
D/WifiDataStallTracker(  912): updateDataStallInfo: mDataStallTxRxSum={txSum=112 rxSum=100} preTxRxSum={txSum=61 rxSum=52}
D/WifiDataStallTracker(  912): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  912): onDataStallAlarm: tag=20098 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20099 delay=15s
V/AlarmManager(  912): sending alarm PendingIntent{42978e10: PendingIntentRecord{4287d250 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=91057, Int=0
D/PMS     (  912): releaseWL(42c9ce78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42acc390): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42acc390): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c93480): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c93480): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a611d8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42a611d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42551a88): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42551a88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c4db90): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c4db90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 12 times.
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [ScoreAP] + current TXpacket:155, mTXpacketCount:139, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  912): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,I/HtcModeClient( 1523): handler message = 4011
,E/HtcModeClient( 1523): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1523): Don't start project servcice
,D/HtcModeClient( 1523): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1523): connectState: CONNECTION_READY = false
,D/SilentMusic( 1523): call stop
,D/HtcModeClient( 1523): close connection
,W/HtcModeClient( 1523): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1523): read the terminate packet, so break
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42bc5240 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  912): acquireWL(42abdb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10074}
,V/AlarmManager(  912): sending alarm PendingIntent{4295e710: PendingIntentRecord{42b030f8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1455035773335, Int=0
,I/ActivityManager(  912): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4371 uid=10078 gids={50078}
,V/AlarmManager(  912): sending alarm PendingIntent{42523010: PendingIntentRecord{4281ee80 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1455035779061, Int=60000
,D/PMS     (  912): releaseWL(42abdb28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4371): SMSBackupAgentService started
,D/SMSBackup( 4371): Checking restore status
,D/SMSBackup( 4371): Restore complete
,D/SMSBackup( 4371): cancelCheckAlarm
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
,D/SMSBackup( 4371): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/Finsky  ( 4189): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4189): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  912): killProcessQuiet, pid=4062
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4062:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4062
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  912): setLight #0: color=#25
,V/LightsService(  912): setLight #0: color=#22
,V/LightsService(  912): setLight #0: color=#18
,V/LightsService(  912): setLight #0: color=#14
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  912): mEventCount = 900
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WIFI_ICON( 1118): WifiActivity: 0
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  912): Going to sleep due to screen timeout...
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42714410
D/WirelessDisplayService(  912): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  912): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  912): disable: get sensor name = CM36282 Light sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42714410, eanble = 0, strlen(mName) = 59
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  912): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42453850
W/SensorService(  912): Listener[1] = com.htc.smartdim.sensor_eye@42a78888
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  912): mWirelessDisplayManager is null
W/BatSI   (  912): Couldn't get kernel wake lock stats
V/LightsService(  912): setLight #2: color=#0
D/qdlights(  912): set_light_buttons_func: on=0 brightness=0
V/LightsService(  912): setLight #0: color=#0
,D/SurfaceControl(  912): Excessive delay in blankDisplay() while turning screen off: 335ms
,W/PnPMgr  (  355): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/NfcService( 1256): ScreenObserver: OFF
,D/NfcService( 1256): applyRouting - 0
D/PMS     (  912): nativeSetInteractive:false
D/PMS     (  912): nativeSetInteractive:false done
D/PMS     (  912): nativeSetAutoSuspend:true
D/PMS     (  912): nativeSetAutoSuspend:true done
D/HABCtrl (  912): TPE algorithm. remove timeout.
D/PMS     (  912): OOBE c monitor 11
I/InputManager(  912): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  912): screenObserver, isScreenOn=false
I/InputMethodManagerService(  912): Disable input method client, pid=1274
,D/NfcService( 1256): applyRouting -2
,I/IntentController( 1118): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  912): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42cd60a0)
D/PMS     (  912): acquireWL(42cd9e08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  912): releaseWL(42cd9e08): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  912): wakingUp
,D/AlarmManager(  912): ACTION_SCREEN_ON
I/AlarmManager(  912): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  912): [AlarmQueuing] done recovering
I/AlarmManager(  912): [AlarmQueuing] recover EPS screen off blocked alarms
,I/AlarmManager(  912): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_ON
,V/KeyguardServiceDelegate(  912): **** SHOWN CALLED ****
,D/WifiDataStallTracker(  912): startDataStallAlarm: tag=20100 delay=15s
D/PMS     (  912): acquireWL(42cd7870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/WindowManager(  912): No lock screen! windowToken=null
D/PMN     (  912): onScreenOn
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0,
D/MtpService( 2405): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2405): [MTP][onReceive]-
,D/NfcService( 1256): applyRouting - 0
I/BatteryService(  912): n_update end
D/PMS     (  912): releaseWL(42cd7870): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/NfcService( 1256): applyRouting -2
,D/WirelessDisplayService(  912): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  912): acquireWL(41f2cf48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  912): releaseWL(41f2cf48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  912): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  912): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 1
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:On
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): BG scan when screen On
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): Match BG scan, scan!
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  912):    returned true
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/ClockThread( 1118): stop update clock
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
I/ActivityManager(  912): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4392 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  371): ParamSet string: screen_state=on
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WirelessDisplayService(  912): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  912): updateScreenOn: false
,W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4392): isEpsOn(), nState = 0
D/PMS     (  912): acquireWL(42be61e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4392 1000 null
,D/PMS     (  912): acquireWL(42be79f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42be79f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  912): acquireWL(42c855e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42be61e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  912): releaseWL(42c855e8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOn: 1455035787409
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOn: 1455035787409
D/SmartSyncUtils( 4392): getMobilePolicyEnabled, result = true
,I/SensorManager(  912): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42453850
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 2
W/SensorService(  912): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42453850, eanble = 0, strlen(mName) = 91
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  912): Listener[0] = com.htc.smartdim.sensor_eye@42a78888
,W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/Process (  912): killProcessQuiet, pid=3740
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMN     (  912): goingToSleep
I/ActivityManager(  912): Killing 3740:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/PMS     (  912): acquireWL(42c6d968): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 912 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
,I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420b2138
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  912): Recipient 3740
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  912): releaseWL(42c6d968): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
,D/AlarmManager(  912): ACTION_SCREEN_OFF
I/AlarmManager(  912): [AlarmQueuing] screen off now: 
I/AlarmManager(  912): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  912): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20100 mDataStallAlarmIntent=PendingIntent{42577510: PendingIntentRecord{4287d250 android broadcastIntent}}
,D/AutoSetting( 1320): service - onCreate()
,D/WifiNative-wlan0(  912): doBoolean: SET_SCREEN_ON 0
I/AlarmManager(  912): [AlarmQueuing] wifi connection: true
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): acquireWL(42b97490): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 912 1000 null
D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
D/TetherSettings( 4174): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4174): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4174): Cust_ConnectToPC   : Modem_Link>false
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/LocationManagerService(  912): request 427e7ae0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
D/        ( 4174): Cust_ConnectToPC   : spcsc>false
D/        ( 4174): Cust_ConnectToPC   : IPT>true
D/        ( 4174): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4174): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4174): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4174): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4174): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4174): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4174): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4174): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4174):  defaultType:0
W/ContextImpl( 4174): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4392): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4392): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4392): isEpsOn(), nState = 0
D/WifiService(  912): New client listening to asynchronous messages
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): SET_SCREEN_ON:Off
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [ScoreAP] + current TXpacket:155, mTXpacketCount:155, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  912): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a78888
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 1
W/SensorService(  912): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a78888, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  912): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  912): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  912): pid=912, uid=1000
W/SensorService(  912): Active sensors: size = 0
W/SensorService(  912): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42a78888, eanble = 0, strlen(mName) = 36
W/SensorService(  912): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  912): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  912): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42a78888
,E/ActivityThread(  912): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a78fc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42a78fc8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  912): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  912): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  912): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  912): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  912): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  912): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  912): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  912): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  912): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  912): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  912): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  912): 	at dalvik.system.NativeStart.main(Native Method)
,V/SRS_Proc(  371): ParamSet string: screen_state=off
,D/NetworkPolicy(  912): updateScreenOn: false
,D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,I/PhoneStatusBar( 1118): removeHeadsNotification.gc: 55
,D/PMS     (  912): acquireWL(42ca29b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  912): releaseWL(42ca29b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1568): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  912): acquireWL(42ca3f38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ca3f38): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1746): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1746): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1746): onScreenOff
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42b97490): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1179): nl80211: Event message available,
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=6 entropy=0
D/wpa_supplicant( 1179): Add randomness: count=7 entropy=1
,D/wpa_supplicant( 1179): Add randomness: count=8 entropy=2
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
,D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1179): Start print parameters
,I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
,I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
,I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
,I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=9 entropy=3
D/wpa_supplicant( 1179): Add randomness: count=10 entropy=4
,D/wpa_supplicant( 1179): Add randomness: count=11 entropy=5
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
,D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
,I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: DISCONNECTED -> INACTIVE
,D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42acf6b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42acf6b0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42acf6b0 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000107535392
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-58
I/wpa_supplicant( 1179): tsf=0000000107535420
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000107535431
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
,I/wpa_supplicant( 1179): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0
,D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 107535392, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 107535420, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 107535431, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/AutoSetting( 1523): service - handleMessage() stop self,
,D/AutoSetting( 1523): service - onDestroy() END
,D/AutoSetting( 1523): service - handleMessage() quit looper
,D/PMS     (  912): acquireWL(42afa978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  912): n_update end
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PMS     (  912): releaseWL(42afa978): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
,D/Process (  912): killProcessQuiet, pid=3937
,I/ActivityManager(  912): Killing 3937:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 3937
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42b94d78 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=12 entropy=6
D/wpa_supplicant( 1179): Add randomness: count=13 entropy=7
D/wpa_supplicant( 1179): Add randomness: count=14 entropy=8
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -58
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=15 entropy=9
D/wpa_supplicant( 1179): Add randomness: count=16 entropy=10
D/wpa_supplicant( 1179): Add randomness: count=17 entropy=11
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000124884664
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-58
I/wpa_supplicant( 1179): tsf=0000000124884690
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000124884702
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 124884664, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -58, 0,
V/ScoreHelper(  912): Only print Top 10 in ApScanList,
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 124884690, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 124884702, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42a74180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42a74180): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  912): killProcessQuiet, pid=4241
,I/ActivityManager(  912): Killing 4241:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4241
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(42af2930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  912): sending alarm PendingIntent{42aca638: PendingIntentRecord{42babe88 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123188, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{427deed0: PendingIntentRecord{42be2540 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136229, Int=0
,D/PMS     (  912): acquireWL(42af4ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(42c97b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c97b28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42af4ed8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42af2930): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42b269a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42b269a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42b2ba30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): acquireWL(42c906f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42bb7218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1455035818526 tag=VacuumService
,D/PMS     (  912): releaseWL(42b2ba30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c906f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42ce4620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42bb7218): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42ce4620): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42cec498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42cec498): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42cf03f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42cf03f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42cf4348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42cf4348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42cbbf90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/PMS     (  912): acquireWL(42cc4cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42cc4cb8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c1bf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42cbbf90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c21070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42c21070): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 2168 seconds from now (1455035819539)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory,
,D/PMS     (  912): acquireWL(42c32460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=138050, Int=0
,D/PMS     (  912): releaseWL(42c32460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/LocationManagerService(  912): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f7ff +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/PMS     (  912): releaseWL(42c1bf78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c3bc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42c3bc70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42c420e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=9 [11][1][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42c420e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  912): acquireWL(42d04138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{428776b0: PendingIntentRecord{42922268 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141559, Int=0
,D/GpsLocationProvider(  912): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  912): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  912): acquireWL(42d05420): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(42d04138): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =bf9d +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1179): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=18 entropy=12
D/wpa_supplicant( 1179): Add randomness: count=19 entropy=13
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/wpa_supplicant( 1179): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=20 entropy=14
D/wpa_supplicant( 1179): Add randomness: count=21 entropy=15
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0,] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE,
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  912): doString: LIST_DONGLES
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000141952015
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000141952041
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=2
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000124884702
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 141952015, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 141952041, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 124884702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults,
V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10,
,V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  912):  + computeScore(NG700): 1
,D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  912): == begin of scan result ==,
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiManager( 1224): getScanResults enter ,
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 51,
D/libc    (  363): [NET]res_nsend:resplen=238
D/libc    (  363): [NET]res_queryN: exit 3, ancount=10,
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  912): == begin of scan result ==,
D/libc    (  912): [NET] getaddrinfo_proxy-, success
I/global  (  912): call createSocket() return a new socket.
D/WifiStateMachine(  912): == (3) end of scan result ==,
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x35342e3139322e),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WirelessDisplayService(  912): getDiscoveryDongleList,
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/GpsLocationProvider(  912): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  912): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  912): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  912):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  912): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  912): releaseWL(42d05420): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=22 entropy=16
D/wpa_supplicant( 1179): Add randomness: count=23 entropy=17
D/wpa_supplicant( 1179): Add randomness: count=24 entropy=18
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=25 entropy=19
D/wpa_supplicant( 1179): Add randomness: count=26 entropy=20
D/wpa_supplicant( 1179): Add randomness: count=27 entropy=21
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
,I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (380) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000159334885
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000159334912
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1179): freq=2462
I/wpa_supplicant( 1179): level=-93
I/wpa_supplicant( 1179): tsf=0000000159334922
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1179): ssid=UPC0039325
I/wpa_supplicant( 1179): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 159334885, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 159334912, distance: ?(cm), distanceSd: ?(cm)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 2: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 159334922, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-93], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  912): acquireWL(42b981b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42b981b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42b97e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{10027}
,V/AlarmManager(  912): sending alarm PendingIntent{429a9ce0: PendingIntentRecord{427b97d8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=172179, Int=0
,D/PMS     (  912): releaseWL(42b97e48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=28 entropy=22
D/wpa_supplicant( 1179): Add randomness: count=29 entropy=23
D/wpa_supplicant( 1179): Add randomness: count=30 entropy=24
D/wpa_supplicant( 1179): Add randomness: count=31 entropy=25
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
,I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1179): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1179): clear disabled list - type=1
,I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-81
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=32 entropy=26
D/wpa_supplicant( 1179): Add randomness: count=33 entropy=27,
D/wpa_supplicant( 1179): Add randomness: count=34 entropy=28
D/wpa_supplicant( 1179): Add randomness: count=35 entropy=29
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (518) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000176724863
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000176724889
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1179): freq=2462
I/wpa_supplicant( 1179): level=-93
I/wpa_supplicant( 1179): tsf=0000000176724911
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC0039325
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-81
I/wpa_supplicant( 1179): tsf=0000000176724900
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 176724863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 176724889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 176724911, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -81, frequency: 2412, timestamp: 176724900, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 4 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-81], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-93], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (4) end of scan result ==
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (4) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42ab3748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42ab3748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter,
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=36 entropy=30
D/wpa_supplicant( 1179): Add randomness: count=37 entropy=31
D/wpa_supplicant( 1179): Add randomness: count=38 entropy=32
D/wpa_supplicant( 1179): Add randomness: count=39 entropy=33
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1179): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1179): [NULL] fc:94:e3:11:35:3a freq=2462 level=-93
D/wpa_supplicant( 1179): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=40 entropy=34
D/wpa_supplicant( 1179): Add randomness: count=41 entropy=35
D/wpa_supplicant( 1179): Add randomness: count=42 entropy=36
D/wpa_supplicant( 1179): Add randomness: count=43 entropy=37
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (518) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000194121937
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000194121964
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1179): freq=2462
I/wpa_supplicant( 1179): level=-93
I/wpa_supplicant( 1179): tsf=0000000194121984
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC0039325
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000194121974
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 194121937, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 194121964, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 194121984, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
,D/WifiStateMachine(  912): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 194121974, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 4 to mScanResults
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-93], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
,D/WifiStateMachine(  912): == (4) end of scan result ==
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (4) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(4289ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=198050, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(4289ef00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=44 entropy=38
D/wpa_supplicant( 1179): Add randomness: count=45 entropy=39
D/wpa_supplicant( 1179): Add randomness: count=46 entropy=40
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=47 entropy=41
D/wpa_supplicant( 1179): Add randomness: count=48 entropy=42
D/wpa_supplicant( 1179): Add randomness: count=49 entropy=43
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (518) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000194121937
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000211485350
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=3
I/wpa_supplicant( 1179): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1179): freq=2462
I/wpa_supplicant( 1179): level=-93
I/wpa_supplicant( 1179): tsf=0000000194121984
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=UPC0039325
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000211485362
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 194121937, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 211485350, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  912): 2: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -93, frequency: 2462, timestamp: 194121984, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 211485362, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 4 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
,V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  0 [-93], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
,D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  912): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == (4) end of scan result ==
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (4) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available,
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
,I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=50 entropy=44
D/wpa_supplicant( 1179): Add randomness: count=51 entropy=45
D/wpa_supplicant( 1179): Add randomness: count=52 entropy=46
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
,D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
,I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
,D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=53 entropy=47
D/wpa_supplicant( 1179): Add randomness: count=54 entropy=48
D/wpa_supplicant( 1179): Add randomness: count=55 entropy=49
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49,
I/wpa_supplicant( 1179): tsf=0000000228941995
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000228942022
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-82
I/wpa_supplicant( 1179): tsf=0000000228942033
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 228941995, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 228942022, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 228942033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=56 entropy=50
D/wpa_supplicant( 1179): Add randomness: count=57 entropy=51
D/wpa_supplicant( 1179): Add randomness: count=58 entropy=52
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
,I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=59 entropy=53
D/wpa_supplicant( 1179): Add randomness: count=60 entropy=54
D/wpa_supplicant( 1179): Add randomness: count=61 entropy=55
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000228941995
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000246294886
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-82
I/wpa_supplicant( 1179): tsf=0000000246294897
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 228941995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 246294886, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 246294897, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42ac96d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42ac96d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42b3b550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=258051, Int=0
,D/PMS     (  912): releaseWL(42b3b550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available,
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=62 entropy=56
,D/wpa_supplicant( 1179): Add randomness: count=63 entropy=57
D/wpa_supplicant( 1179): Add randomness: count=64 entropy=58
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
,D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
,I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
,D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=65 entropy=59
D/wpa_supplicant( 1179): Add randomness: count=66 entropy=60
D/wpa_supplicant( 1179): Add randomness: count=67 entropy=61
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
,I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000228941995
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000263704935
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-82
I/wpa_supplicant( 1179): tsf=0000000263704946
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 228941995, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 263704935, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 263704946, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-82], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=68 entropy=62
D/wpa_supplicant( 1179): Add randomness: count=69 entropy=63
D/wpa_supplicant( 1179): Add randomness: count=70 entropy=64
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=71 entropy=65
D/wpa_supplicant( 1179): Add randomness: count=72 entropy=66
D/wpa_supplicant( 1179): Add randomness: count=73 entropy=67
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  912): doString: LIST_DONGLES
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000281108852
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000281108880
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
,I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000281108891
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 281108852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 281108880, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 281108891, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42d015f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42d015f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42d118b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{42199078: PendingIntentRecord{42933588 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=294055, Int=0
,D/PMS     (  912): acquireWL(42bcf4d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 912 1000 null,
,I/ActivityManager(  912): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4443 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  912): sending alarm PendingIntent{4298d458: PendingIntentRecord{42991528 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1455035895084, Int=10800000
D/PMS     (  912): releaseWL(42d118b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42c94408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
,D/PMS     (  912): releaseWL(42bcf4d8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  912): releaseWL(42c94408): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.aurora (4443/10049)
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/Process (  912): killProcessQuiet, pid=4106
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4106:com.google.android.talk/u0a111 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 4106
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=74 entropy=68
D/wpa_supplicant( 1179): Add randomness: count=75 entropy=69
D/wpa_supplicant( 1179): Add randomness: count=76 entropy=70
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=77 entropy=71
D/wpa_supplicant( 1179): Add randomness: count=78 entropy=72
D/wpa_supplicant( 1179): Add randomness: count=79 entropy=73
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000281108852
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000298524961
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000298524972,
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 281108852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 298524961, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 298524972, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  912): acquireWL(42ba1dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42ba1dd0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=80 entropy=74
D/wpa_supplicant( 1179): Add randomness: count=81 entropy=75
D/wpa_supplicant( 1179): Add randomness: count=82 entropy=76
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
,D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49,
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=83 entropy=77
,D/wpa_supplicant( 1179): Add randomness: count=84 entropy=78
D/wpa_supplicant( 1179): Add randomness: count=85 entropy=79
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000315904895
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
,I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000315904921
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000315904932
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
V/ScoreHelper(  912): Only print Top 10 in ApScanList,
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 315904895, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 315904921, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 315904932, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): add 3 to mScanResults
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WirelessDisplayService(  912): getDiscoveryDongleList,
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/PMS     (  912): acquireWL(42d0b460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=318051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42d0b460): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=86 entropy=80
D/wpa_supplicant( 1179): Add randomness: count=87 entropy=81
D/wpa_supplicant( 1179): Add randomness: count=88 entropy=82
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-84
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=89 entropy=83
D/wpa_supplicant( 1179): Add randomness: count=90 entropy=84
D/wpa_supplicant( 1179): Add randomness: count=91 entropy=85
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000333212144
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000333212170
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-84
I/wpa_supplicant( 1179): tsf=0000000333212181
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiP2pService(  912): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 333212144, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-84], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
,D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 333212170, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -84, frequency: 2412, timestamp: 333212181, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  912): == begin of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=92 entropy=86
D/wpa_supplicant( 1179): Add randomness: count=93 entropy=87
D/wpa_supplicant( 1179): Add randomness: count=94 entropy=88
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 9
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1179): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=95 entropy=89
D/wpa_supplicant( 1179): Add randomness: count=96 entropy=90
D/wpa_supplicant( 1179): Add randomness: count=97 entropy=91
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len,=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): clear disabled list - type=1
I/wpa_supplicant( 1179): No suitable network found
W/wpa_supplicant( 1179): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1179): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000350502746
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-59
I/wpa_supplicant( 1179): tsf=0000000350502771
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-83
I/wpa_supplicant( 1179): tsf=0000000350502782
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos
I/wpa_supplicant( 1179): ####
D/WifiP2pService(  912): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 350502746, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  912): Only print Top 10 in ApScanList
V/ScoreHelper(  912):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  912):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-49], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  912):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  912):  + computeScore(NG700): 1
D/WifiStateMachine(  912): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 350502771, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 350502782, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiManager( 1224): getScanResults enter 
,D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==,
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Disconnect event
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,I/wpa_supplicant( 1179): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1179): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1179): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7864bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1179): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  912): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  912): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  912): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3,:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  912): Enter handleNetworkDisconnect
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
,D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  912):    returned true
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
D/DhcpStateMachine(  912): [RunningState] Stop DHCP
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS,
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585,
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20101 mDataStallAlarmIntent=null
D/WifiStateMachine(  912): Exit handleNetworkDisconnect
D/WifiPerfLock(  912): release()
,D/WifiStateMachine(  912): PerfLock released for exiting ConnectedState
D/ConnectivityService(  912): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  912): acquireWL(42bac330): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 912 1000 null
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  912):    returned true
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  912): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/UsbnetStateTracker(  912): isAvailable+-
D/UsbnetStateTracker(  912): reconnect
,D/UsbnetStateTracker(  912): isAvailable+-
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  912): default: reconnect()
D/MDST    (  912): default: setTeardownRequested(false)
D/MDST    (  912): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  912): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  912): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  912): doBoolean: SET pno 1
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  912): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  912): New client listening to asynchronous messages
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='1'
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1179): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1372): Read error: ssl=0x66102008: I/O error during system call, Connection timed out
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/ConnectivityService(  912): resetConnections(wlan0, 3)
D/libc    (  363): [NET] entry_id:7   entry:0xb82138d0  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb8217db8  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8217c88  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8217f70  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb820ec20  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8213458  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb82132d8  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
V/NativeCrypto( 1372): SSL shutdown failed: ssl=0x66102008: I/O error during system call, Broken pipe
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/PMS     (  912): acquireWL(42ce8870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/PMS     (  912): acquireWL(42b7a528): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  912): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): acquireWL(423968a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1179): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
D/wpa_supplicant( 1179): nl80211: Event message available
,D/wpa_supplicant( 1179): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: SCAN
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1179): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1179): Failed to initiate AP scan
,I/wpa_supplicant( 1179): Failed to initiate AP scan, Failed_to_scan_counter:1
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): reportInetCondition for net -1, percentage: 0 by  (1372/10029)
,D/BatSI   (  912): WIFI scan started for: 450a0300 uid:1000
D/WifiNative-wlan0(  912):    returned true
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:2
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42ce8870): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42b7a528): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
D/ConnectivityService(  912): handleInetConditionChange: no active default network - ignore
,D/PMS     (  912): releaseWL(423968a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: false
D/Tethering(  912): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  912): bSetPropertyMultiRAB:false
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  912): ipv4Default null
I/Tethering(  912): No IPv4 upstream interface, giving up.
D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
,D/GpsLocationProvider(  912): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/CaptivePortalTracker(  912): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  912): NoActiveNetworkState
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/PMS     (  912): acquireWL(42c2e670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(42c2e670): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1179): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1179): Failed to initiate AP scan
,I/wpa_supplicant( 1179): Failed to initiate AP scan, Failed_to_scan_counter:2
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2405/10021)
,I/ActivityManager(  912): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4465 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/ACRA    ( 4465): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4465): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4465): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4465): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4465): Preparing secondary program dexes.
V/DexLibLoader( 4465): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4465): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4465): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4465): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4465): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4465): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4465): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4465): Dex already copied
D/OdexVerifier( 4465): Odex verification is skipped.
,V/DexLibLoader( 4465): Creating class loader
,V/DexLibLoader( 4465): Finished creating class loader
V/DexLibLoader( 4465): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4465): Dex already copied
D/OdexVerifier( 4465): Odex verification is skipped.
V/DexLibLoader( 4465): Creating class loader
V/DexLibLoader( 4465): Finished creating class loader
V/DexLibLoader( 4465): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4465): Dex already copied
D/OdexVerifier( 4465): Odex verification is skipped.
,V/DexLibLoader( 4465): Creating class loader
,V/DexLibLoader( 4465): Finished creating class loader
V/DexLibLoader( 4465): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4465): Dex already copied
D/OdexVerifier( 4465): Odex verification is skipped.
,V/DexLibLoader( 4465): Creating class loader
V/DexLibLoader( 4465): Finished creating class loader
,V/DexLibLoader( 4465): Verifying classes from secondary dexes.
,D/DexLibLoader( 4465): DexLibLoader.ensureDexLoaded took 23 ms,
,W/dalvikvm( 4465): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1179): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1179): Failed to initiate AP scan
,I/wpa_supplicant( 1179): Failed to initiate AP scan, Failed_to_scan_counter:3,
,W/dalvikvm( 4465): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4465): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4465): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-49
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1179): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-82
D/wpa_supplicant( 1179): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=98 entropy=92
D/wpa_supplicant( 1179): Add randomness: count=99 entropy=93
D/wpa_supplicant( 1179): Add randomness: count=100 entropy=94
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1179):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1179): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1179): No APs found - clear blacklist and try again
E/wpa_supplicant( 1179): wlan0: BLACKLIST CLEAR 
D/WifiNative-wlan0(  912): doBoolean: SET pno 1
D/wpa_supplicant( 1179): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 3
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): selected network = 1
D/wpa_supplicant( 1179): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb78664e8  current_ssid=0x0
D/wpa_supplicant( 1179): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supp,licant( 1179): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1179): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1179): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1179): check if in concurrent case
I/wpa_supplicant( 1179): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1179): RSN: PMKSA cache search - network_ctx=0xb78664e8 try_opportunistic=0
D/wpa_supplicant( 1179): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1179): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1179): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1179): nl80211: Unsubscribe mgmt frames handle 0xb7865718 (mode change)
D/wpa_supplicant( 1179): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7865718
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1179):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179):   * freq=2412
D/wpa_supplicant( 1179):   * Auth Type 0
D/wpa_supplicant( 1179):   * WPA Versions 0x2
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1179): nl80211: Connect request send successfully
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1179): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1179): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  912):    returned false
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  912): doString: LIST_DONGLES
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1179): reply (376) for get BSS: id=0
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220,
I/wpa_supplicant( 1179): level=-49
I/wpa_supplicant( 1179): tsf=0000000357511672
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-58
I/wpa_supplicant( 1179): tsf=0000000357511695
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=4
I/wpa_supplicant( 1179): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-82
I/wpa_supplicant( 1179): tsf=0000000357511705
I/wpa_supplicant( 1179): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1179): ssid=Gonzos,
I/wpa_supplicant( 1179): ####
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WirelessDisplayService(  912): getDiscoveryDongleList
W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (3) end of scan result ==
D/WirelessDisplayService(  912): getDiscoveryDongleList
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == begin of scan result ==
,D/WifiStateMachine(  912): == (3) end of scan result ==
,D/WifiStateMachine(  912): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -49, frequency: 5220, timestamp: 357511672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 357511695, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2412, timestamp: 357511705, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 3 to mScanResults
D/BatSI   (  912): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,W/fb4a(:<default>):StaticBindingVerifier( 4465): Verify
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1179): nl80211: Event message available
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1179): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Connect event
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1179): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Add randomness: count=101 entropy=95
I/wpa_supplicant( 1179): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on association
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1179): EAPOL: enable timer tick
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1179): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): Get randomness: len=32 entropy=96
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  912): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  912): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  912): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  912): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  912): Enter handleAssociatedWithEvent
D/WifiStateMachine(  912): Associated
D/WifiStateMachine(  912): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Exit handleAssociatedWithEvent
,D/WifiStateMachine(  912): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb78659f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
,I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
,D/wpa_supplicant( 1179):    broadcast key
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1179): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1179): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1179): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1179): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=6
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): set send_ind_to_ndc = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1179): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1179): EAPOL authentication completed successfully
I/wpa_supplicant( 1179): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
,D/Tethering(  912): interfaceStatusChanged wlan0, true
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/WifiStateMachine(  912): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
,D/WifiService(  912): New client listening to asynchronous messages
D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  912):    returned true
D/DhcpStateMachine(  912): [StoppedState] Start DHCP
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 1
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1179): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiStateMachine(  912): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  912): acquireWL(42bfd538): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
D/WifiStateMachine(  912): handlePreDhcpSetup mBluetoothConnectionActive: false
,D/WifiNative-wlan0(  912):    returned null
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a298f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a298f8 target=com.android.internal.util.StateMachine$SmHandler }
,W/fb4a(:<default>):BaseAnalyticsConfig( 4465): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4465): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4465): Grow heap (frag case) to 9.518MB for 73240-byte allocation
,D/Process (  912): killProcessQuiet, pid=4150
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4150:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4150
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  912): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4484 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): Util - no network available!
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): service - onCreate()
,D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/LocationManagerService(  912): request 427e7ae0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4484): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4484): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  912): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4500 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,W/fb4a(:<default>):UserScope( 4465): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
W/fb4a(:<default>):ViewerContextManagerForUserScope( 4465): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4465): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
,I/ActivityManager(  912): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4521 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  912): killProcessQuiet, pid=3990
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  912): Killing 3990:com.htc.task/u0a71 (adj 15): empty #17
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4521): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4521): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4465): Grow heap (frag case) to 9.963MB for 84664-byte allocation
E/dalvikvm( 4465): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4465): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/dalvikvm-heap( 4465): Grow heap (frag case) to 9.979MB for 28144-byte allocation
,E/dalvikvm( 4465): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4465): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4465): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4465): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,E/dalvikvm( 4465): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4465): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4465): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/dalvikvm( 4465): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4465): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4465): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4465): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4465): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4465): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 4465): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
I/ActivityManager(  912): Recipient 3990
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 4465): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4465): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
,V/WebViewChromiumFactoryProvider( 4521): Binding Chromium to main looper Looper (main, tid 1) {41f36288}
,I/LibraryLoader( 4521): Expected native library version number "",actual native library version number ""
,I/chromium( 4521): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4521): Initializing chromium process, renderers=0
,D/PMS     (  912): acquireWL(42d5bf88): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  912): acquireWL(42d5c6e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,E/AudioManagerAndroid( 4521): BLUETOOTH permission is missing!
D/PMS     (  912): releaseWL(42d5c6e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4521): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4521): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4521): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4521): Local Branch: 
I/Adreno-EGL( 4521): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4521): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4521):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4465): Grow heap (frag case) to 10.078MB for 39954-byte allocation
,I/NSApplication( 4521): Starting up...
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
I/dalvikvm-heap( 4465): Grow heap (frag case) to 10.155MB for 79892-byte allocation
,I/ActivityManager(  912): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4558 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/ActivityManager(  912): Killing 4301:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/Process (  912): killProcessQuiet, pid=4301
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 4465): Grow heap (frag case) to 10.283MB for 75760-byte allocation
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d73220 u0 ReceiverList{42d73100 4465 com.facebook.katana/10027/u0 remote:42d723c0}}
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d73220 u0 ReceiverList{42d73100 4465 com.facebook.katana/10027/u0 remote:42d723c0}}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,W/BroadcastQueue(  912): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42d76b80 u0 ReceiverList{42d76b20 4465 com.facebook.katana/10027/u0 remote:42d76750}}
,D/PMS     (  912): acquireWL(42d7a558): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4558 10160 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,I/iu.UploadsManager( 2188): num queued entries: 0
,I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
D/PMS     (  912): acquireWL(42d80758): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4558 10160 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/PMS     (  912): releaseWL(42d7a558): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
I/ActivityManager(  912): Recipient 4301
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  912): Client connection lost with reason: 4
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  912): releaseWL(42d80758): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  912): killProcessQuiet, pid=3855
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 3855:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  912): Recipient 3855
,D/PMS     (  912): acquireWL(42d8e5c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42d8e5c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/dalvikvm-heap( 4558): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4465): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4465): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4465): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1179): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1179): EAPOL: disable timer tick
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(42bfd538): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=25 [4][1][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): gateway: /192.168.1.1
,D/WifiNative-wlan0(  912): doBoolean: DRIVER GATEWAY-ADD 16885952
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  912): VerifyingLinkState enter
D/WifiStateMachine(  912): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  912): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  912): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -59, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  912): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  912): default: teardown()
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiWatchdogStateMachine(  912): WAN detection
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = true<<<<<
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/MDST    (  912): default: setTeardownRequested(true)
D/MDST    (  912): default: setEnableApn apnType =default , enable=false
V/NetworkPolicy(  912): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/MDST    (  912): default: setTeardownRequested(true)
D/ConnectivityService(  912): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  912): Unexpected mtu value: android.net.wifi.WifiStateTracker@428c2010
,D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1179): Change stage from stage0 to stage3
D/WifiStateMachine(  912): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
D/WifiStateMachine(  912): syncGetConfiguredNetworks
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  912): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  912): acquireWL(42dc7f60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  912): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=100 [1][1][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/PMS     (  912): acquireWL(42dd2b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1455035737414 min interval config: 0 actual interval: 304023
D/PMS     (  912): acquireWL(42dd4068): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42dd2b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2188): Checking schedule, now: 1455036041445 next: 1455035767383
,I/CheckinService( 2188): active receiver: enabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2188, uid=10029, userID:0
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2188): Preparing to send checkin request
,I/EventLogService( 2188): Accumulating logs since 1455035733706
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  912): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(42dc7f60): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  912): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4617 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4617): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4617): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4617): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4617): install
,I/MultiDex( 4617): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4617): loading existing secondary dex files
,I/MultiDex( 4617): load found 3 secondary dex files
,I/MultiDex( 4617): install done
,W/dalvikvm( 4617): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4617): VFY: unable to resolve instance field 36
,W/dalvikvm( 4617): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4617): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4617): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4617): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4617): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,W/dalvikvm( 4617): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4617): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4617): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4617): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4617): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2188): Restart initialization of location
,E/MDM     ( 1224): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1372): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1372): Proximity feature is not enabled.
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  912): acquireWL(42d25110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42d25110): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,I/WVCdm   (  371): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  371): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4617): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  371): PrepareKeyRequest: nonce=2223791398
,I/WVCdm   (  371): CdmEngine::CloseSession
,D/PMS     (  912): releaseWL(42bac330): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  912): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=true
D/CaptivePortalTracker(  912): NoActiveNetworkState
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/PMS     (  912): acquireWL(42d24cb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
D/PMS     (  912): acquireWL(42abf0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,V/Tethering(  912): bSetPropertyMultiRAB:false
,D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
,I/Tethering(  912): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  912): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/Tethering(  912): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/Tethering(  912): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  912): Found interface wlan0
,D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/PMS     (  912): acquireWL(421126f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2405/10021)
D/PMS     (  912): releaseWL(421126f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  912): releaseWL(42d24cb0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  912): releaseWL(42abf0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1455035737414 min interval config: 0 actual interval: 305121
D/PMS     (  912): acquireWL(428f4e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(428f4e28): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [2][0][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/iu.UploadsManager( 2188): num queued entries: 0
,I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  912): acquireWL(42b255c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9c73 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 266
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,W/fb4a(:<default>):UserScope( 4465): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4465): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  912): acquireWL(42b0cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/PMS     (  912): acquireWL(42a8a2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,W/Settings( 4617): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/PMS     (  912): releaseWL(42b0cb50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/PMS     (  912): acquireWL(42bf90e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  912): acquireWL(42abc9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=25 [4][1][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): releaseWL(42b255c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42bf90e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42a58838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/PMS     (  912): releaseWL(42abc9d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42a58838): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1224): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =b368 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
E/fb4a(:<default>):LocalFbBroadcastManager( 4465): Called registerBroadcastReceiver twice.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 1433
D/libc    (  363): [NET]res_nsend:resplen=45
D/libc    (  363): [NET]res_queryN: exit 3, ancount=1
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/PMS     (  912): releaseWL(42d5bf88): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (4617/10029)
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1177746105
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2188): [NET] getaddrinfo-, 1
,D/libc    ( 2188): [NET] getaddrinfo_proxy+
V/NativeCrypto( 2188): SSL shutdown failed: ssl=0x65a9b738: I/O error during system call, Connection timed out
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8478 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=22 [9][2][0]
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2188): [NET] getaddrinfo_proxy-, success
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,D/libc    ( 1224): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 11(0x6578616d706c65),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2188): Sending checkin request (12276 bytes)
,W/PhenotypeConfigurator( 1224): Server returned 404
D/PMS     (  912): releaseWL(42a8a2a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(429c3ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(429c3ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=25 [24][6][0]
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,I/CheckinTask( 2188): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2188): Checking schedule, now: 1455036044289 next: 1455558981281
,I/CheckinService( 2188): active receiver: disabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,I/CheckinService( 2188): Checking schedule, now: 1455036044315 next: 1455558981281
,I/CheckinService( 2188): active receiver: disabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,D/CheckinService( 2188): Recording last checkin time for package unspecified as 1455036044321
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42dd4068): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =15f +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  912): Find DNS Address www.htc.com/23.59.123.86
,I/GAV2    ( 4521): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  912): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/Process (  912): killProcessQuiet, pid=4323
,I/ActivityManager(  912): Killing 4323:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  912): Recipient 4323
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  912): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4671 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4671): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4671): MmsConfig.loadMmsSettings
,W/dalvikvm( 4671): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4671): VFY: unable to resolve instance field 36
,W/dalvikvm( 4671): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4671): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  912): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4694 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4671, uid=10111, userID:0
,W/Settings( 4671): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4671, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4671, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4671, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4671, uid=10111, userID:0
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4671, uid=10111, userID:0
,D/PMS     (  912): acquireWL(42d94608): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4671 10111 null
,D/MessageFrequencyProvider( 4694): onCreate
,V/GetPrviateResource( 4694): GetPrviateResource
,V/GetPrviateResource( 4694): GetPrviateResource
,D/MmsCustomizationProvider( 4694): query uri: content://htc-mms-customization/mms-ua/ua_string
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  912): Resuming delayed broadcast
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/MmsCustomizationProvider( 4694): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/PMS     (  912): acquireWL(42de5c10): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
I/Babel   ( 4671): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4671): MmsConfig.loadFromDatabase
,E/Babel   ( 4671): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4671): MmsConfig.loadFromResources
,D/PMS     (  912): releaseWL(42d94608): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ProviderInstaller( 4671): Installed default security provider GmsCore_OpenSSL
E/Babel   ( 4671): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4671): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/MessageCustFlag( 4694): sense_version=6.0
,D/BTAccessoryUtil( 4694): createReceiver
,D/BTAccessoryUtil( 4694): registerReceiver return intent = null
D/MessageCustFlag( 4694): sku_id=99
,W/SystemReader( 4694): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4694): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4694): networkCode: 
,D/MessageCustFlag( 4694): sku_id=99
D/MmsConfig( 4694): SIE smsPri: null
,D/MmsConfig( 4694): networkCode: 
D/HtcTelephonyCapability( 4694): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4694): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4694): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4694): Cannot find qct_8960_interface, use default value instead
D/PMS     (  912): releaseWL(42de5c10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): acquireWL(42ac8388): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  912): acquireWL(42c3cc98): PARTIAL_WAKE_LOCK  AsyncService 0x1 4558 10160 null
,D/PMS     (  912): releaseWL(42ac8388): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42a72990): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c3cc98): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/PackageManager(  912): Unable to load service info ResolveInfo{42c8b028 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  912): releaseWL(42a72990): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  912): acquireWL(42c97938): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42c97938): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
I/ActivityManager(  912): Resuming delayed broadcast
D/ConnectivityService(  912): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/ActivityManager(  912): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
D/PMS     (  912): acquireWL(42cc5590): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42cc5590): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/PMS     (  912): acquireWL(42cc70f0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cc70f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageBroadcastService( 2188): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  912): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  912): acquireWL(42b811b0): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2188): updateResources: need to parse f{com.google.android.gms}
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 362 ms] updated apps [took 362 ms] 
D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  912): start
I/ActivityManager(  912): Resuming delayed broadcast
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(42cb3880): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cb3880): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(42c44a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42c44a58): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42cd2e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42cd2e20): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42c2e550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42c2e550): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 -
,D/PMS     (  912): acquireWL(42c177e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): releaseWL(42c177e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  912): releaseWL(42b811b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/Messaging( 4694): mNeedToUpdateDate2 start
,D/MmsConfig( 4694): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4694): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4694): 
D/MmsAsyncWorkHandler( 4694): HM tk = 20001
D/ReportIndicatorCache( 4694): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4694): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41f44298
,I/Messaging( 4694): mccmnc> 
D/DraftCache( 4694): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4694): [DraftCache/1] refresh
,D/MmsConfig( 4694): networkCode: 
,D/Messaging( 4694): ViewCache CreatePreloadOnlyConversationList
,D/PhoneStorageUtil( 4694): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4694): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4694): createReceiver
,D/MessageCustFlag( 4694): sense_version=6.0
,D/Jerry   ( 4694): start to preload cursor >>>>>>>
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 4694): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4694): TransactionService is going to be woken up.
,V/TransactionService( 4694): 1-Creating TransactionService
,V/TransactionService( 4694): onStartCommand: 1
,D/MmsSystemEventReceiver( 4694): unRegisterForConnectionStateChanges
V/TransactionService( 4694): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4694): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): device_type: 1
D/TransactionService( 4694): Force set service start id to 1
V/TransactionService( 4694): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4694): unRegisterForConnectionStateChanges
,D/TransactionService( 4694): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4694): Destroying TransactionService
,V/TransactionService( 4694): 4-Handling incoming message: { when=0 what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/Messaging( 4694): mNeedToUpdateDate2: false
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/Messaging( 4694): ViewCache CreatePreload
,D/Messaging( 4694): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4694): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4694): def_index: 0
,D/MsgPreferenceUtils( 4694): globalIndex = 1
,D/MsgPreferenceUtils( 4694): phone state: true
D/MsgPreferenceUtils( 4694): sd state: false
,D/MsgPreferenceUtils( 4694): vIndex = 0
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/DraftCache( 4694): [DraftCache/466] rebuildCache
,D/Messaging( 4694): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1241): URI_DRAFT
,D/DraftCache( 4694): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 4694): [DraftCache/466] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4694): 
D/MmsAsyncWorkHandler( 4694): HM tk = 20002
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1241): sku_id=99
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42c07c18 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/GAV4    ( 4671): Thread[GAThread,5,main]: No campaign data found.
,D/Process (  912): killProcessQuiet, pid=4337
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4337:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4337
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(42d67640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=378051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42d67640): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1320): service - mHandler: update timezone
D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
D/AutoSetting( 1320): service - onDestroy() END
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): service - onCreate()
,W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1523): service - mHandler: update timezone
,V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
,D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/DotMatrix( 1568): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1523): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1523): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41fca890 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 3 7 3 11
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/Process (  912): killProcessQuiet, pid=4081
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4081:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4081
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42cefb30 u0 com.htc.htclocationservice/.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AutoSetting( 1523): service - handleMessage() stop self
,D/AutoSetting( 1523): service - onDestroy() END
,D/AutoSetting( 1523): service - handleMessage() quit looper
D/Process (  912): killProcessQuiet, pid=4371
,D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  912): Killing 4371:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  912): Recipient 4371
,I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  912): acquireWL(42c878a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/PMS     (  912): releaseWL(42c878a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42c5e0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=438051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c5e0c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  912): acquireWL(42c37d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c37d68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  912): acquireWL(42c16988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=498051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c16988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  912): acquireWL(42c167f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c167f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42c0e4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=558051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42c0e4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c0e328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42c0e328): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  912): acquireWL(42becaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=618051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42becaa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
,D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/PMS     (  912): acquireWL(42be54e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42be54e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42be07a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=678051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42be07a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42bda420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42bda420): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42bcc578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=738051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42bcc578): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42bc7770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42bc7770): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42bc0128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=798051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42bc0128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42bb8dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42bb8dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(429f8540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(429f8540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42899430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=858051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42899430): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(421ea760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(421ea760): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(423d80e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=918051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(423d80e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42a5b918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42a5b918): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
,D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  912): updateBatteryInfo
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(428584c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/PMS     (  912): releaseWL(428584c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42a42500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=978051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42a42500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42897458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,D/ConnectivityService(  912): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  912): sending alarm PendingIntent{421c93d0: PendingIntentRecord{428cc7c8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=783348, Int=0
,V/AlarmManager(  912): sending alarm PendingIntent{41f37688: PendingIntentRecord{427cb2e8 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1455036615423, Int=900000
,V/AlarmManager(  912): sending alarm PendingIntent{422e1540: PendingIntentRecord{42c85280 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1455036687540, Int=0
,W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4392): call getInstance()
,D/SmartSyncUtils( 4392): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4392): MY_DEBUG = false
D/PMS     (  912): releaseWL(42897458): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  912): acquireWL(4296deb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4392 1000 null
D/ConnectivityService(  912): Done.
,D/SmartSyncScreenOnOffTimeReceiver( 4392): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4392): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4392): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4392): SettingOnTime = 1455084000000, randomSettingOnTime = 1455083980000
,D/SmartSyncScreenOnOffTimeReceiver( 4392): SettingOffTime = 1455069600000, randomSettingOffTime = 1455073454000
,D/ConnectivityService(  912): Setting timer for 720seconds
D/SmartSyncScreenOnOffTimeReceiver( 4392): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4392): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4392): bNightModeTurnOffOnce = false
W/BatSI   (  912): Couldn't get kernel wake lock stats
D/PMS     (  912): releaseWL(4296deb8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,W/BatSI   (  912): Couldn't get kernel wake lock stats
,D/PMS     (  912): acquireWL(429c9600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(429c9600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42884a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): releaseWL(42884a00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1118): closing low battery warning: level=100
,D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42bf0130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1038051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42bf0130): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42cf0270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42cf0270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42b16fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42b16fb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  912): acquireWL(42791eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1098051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42791eb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42c64238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
D/PMS     (  912): releaseWL(42c64238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  912): updateBatteryInfo
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/ContextImpl( 4392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,D/TetherSettings( 4174): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4174): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4174): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4174): Cust_ConnectToPC   : spcsc>false
D/        ( 4174): Cust_ConnectToPC   : IPT>true
,D/        ( 4174): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4174): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4174): Index of the first 1 = 3
W/ContextImpl( 4174): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 4174): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4174): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4174): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4174): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 4174): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 4174): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  912): acquireWL(42ba5e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1158051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42ba5e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  912): acquireWL(42b4aed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  912): n_update end
,D/PMS     (  912): releaseWL(42b4aed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  912): BroadcastReceiver::onReceive-
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  912): updateBatteryInfo
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Disconnect event
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1179): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  912): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getReasonFromEventString() 0
D/HTCRequest(  912): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  912): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  912): Enter handleNetworkDisconnect
D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1179): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1179): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7864bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1179): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplic,ant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiP2pService(  912): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  912): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
D/WifiNative-wlan0(  912):    returned true
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/DhcpStateMachine(  912): [RunningState] Stop DHCP
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
,D/Tethering(  912): interfaceStatusChanged wlan0, false
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/WifiStateMachine(  912): Exit handleNetworkDisconnect
D/WifiPerfLock(  912): release()
D/WifiStateMachine(  912): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiDataStallTracker(  912): stopDataStallAlarm: current tag=20102 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  912):    returned true
D/ConnectivityService(  912): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  912): Provision feature enable=false
D/PMS     (  912): acquireWL(42c89100): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 912 1000 null
D/ConnectivityService(  912): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiP2pService(  912): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/UsbnetStateTracker(  912): isAvailable+-
D/UsbnetStateTracker(  912): reconnect
,D/UsbnetStateTracker(  912): isAvailable+-
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doBoolean: SET pno 1
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/MDST    (  912): default: reconnect()
D/MDST    (  912): default: setTeardownRequested(false)
D/MDST    (  912): default: setEnableApn apnType =default , enable=true
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  912): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  912): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1179): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1179): nl80211: Event message available
D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
,D/wpa_supplicant( 1179): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
D/ConnectivityService(  912): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  912): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  912): handleConnectivityChange: resetting
,D/ConnectivityService(  912): resetConnections(wlan0, 3)
,V/NativeCrypto( 1372): Read error: ssl=0x64038b10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1372): SSL shutdown failed: ssl=0x64038b10: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:2   entry:0xb82130e8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8213410  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb82132a0  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8213198  removed 
,D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
D/PMS     (  912): acquireWL(42c66d78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  912): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  912): acquireWL(42c85e90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
D/ConnectivityService(  912): reportInetCondition for net -1, percentage: 0 by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/WifiStateMachine(  912): startScan Pid: 912 Uid 1000
D/WifiNative-wlan0(  912): doBoolean: SET pno 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1179): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: SCAN
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): wpa_supplicant_scan enter
I/wpa_supplicant( 1179): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1179): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1179): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1179): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  912):    returned true
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/PMS     (  912): releaseWL(42c66d78): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/BatSI   (  912): WIFI scan started for: 450a0300 uid:1000
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
,D/ConnectivityService(  912): mActiveDefaultNetwork: -1
,D/ConnectivityService(  912): handleInetConditionChange: no active default network - ignore
,D/PMS     (  912): releaseWL(42c85e90): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
D/CaptivePortalTracker(  912): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  912): NoActiveNetworkState
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  912): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=false
D/Tethering(  912): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  912): bSetPropertyMultiRAB:false
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,I/Tethering(  912): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  912): ipv4Default null
I/Tethering(  912): No IPv4 upstream interface, giving up.
D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/PMS     (  912): acquireWL(42ae4400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/PMS     (  912): releaseWL(42ae4400): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (2405/10021)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1320): Util - no network available!
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/AutoSetting( 1320): service - onCreate()
,D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
D/LocationManagerService(  912): request 427e7ae0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  912): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2188): num queued entries: 0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1179): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Received scan results (2 BSSes)
D/wpa_supplicant( 1179): nl80211: Survey data missing
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1179): Sorted scan results
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-50
I/wpa_supplicant( 1179): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-61
D/wpa_supplicant( 1179): BSS: last_scan_res_used=2/32 last_scan_full=0
D/wpa_supplicant( 1179): Add randomness: count=102 entropy=64
D/wpa_supplicant( 1179): Add randomness: count=103 entropy=65
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1179): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1179): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1179): wpa_supplicant_pick_network+
I/wpa_supplicant( 1179): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1179):    skip - blacklisted (count=1 limit=0)
I/wpa_supplicant( 1179): No APs found - clear blacklist and try again
E/wpa_supplicant( 1179): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1179): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1179): Selecting BSS from priority group 1
I/wpa_supplicant( 1179): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1179): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1179): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1179): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1179):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1179):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-61
I/wpa_supplicant( 1179): Start print parameters
I/wpa_supplicant( 1179): wpa_s->wpa_state is 3
I/wpa_supplicant( 1179): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1179): isConcurrentMode() is 0
I/wpa_supplicant( 1179): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1179): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1179): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1179): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1179): wpa_s->reassociate is 0
I/wpa_supplicant( 1179): wpa_s->is_screen_on 0
I/wpa_supplicant( 1179): wpa_s->ifname wlan0
I/wpa_supplicant( 1179): End print parameters
I/wpa_supplicant( 1179): selected network = 1
D/wpa_supplicant( 1179): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb78664e8  current_ssid=0x0
D/wpa_supplicant( 1179): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1179): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1179): TDLS: TDLS is ,allowed in the target BSS
I/wpa_supplicant( 1179): check if in concurrent case
I/wpa_supplicant( 1179): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiNative-wlan0(  912): doBoolean: SET pno 1
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1179): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1179): RSN: PMKSA cache search - network_ctx=0xb78664e8 try_opportunistic=0
D/wpa_supplicant( 1179): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1179): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1179): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1179): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1179): nl80211: Unsubscribe mgmt frames handle 0xb7865718 (mode change)
,D/wpa_supplicant( 1179): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7865718
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
,D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Register frame type=0xd0 nl_handle=0xb7865718
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1179): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1179):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1179):   * freq=2412
D/wpa_supplicant( 1179):   * Auth Type 0
D/wpa_supplicant( 1179):   * WPA Versions 0x2
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 46
,D/wpa_supplicant( 1179): nl80211: Connect request send successfully
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1179): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1179): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0(  912):    returned false
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  912): doString: LIST_DONGLES
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  912): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl(  912): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1179): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1179): reply (238) for get BSS: id=1
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1179): freq=2412
I/wpa_supplicant( 1179): level=-61
I/wpa_supplicant( 1179): tsf=0000001198814357
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG700
I/wpa_supplicant( 1179): ====
I/wpa_supplicant( 1179): id=5
I/wpa_supplicant( 1179): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1179): freq=5220
I/wpa_supplicant( 1179): level=-50
I/wpa_supplicant( 1179): tsf=0000000357511672,
I/wpa_supplicant( 1179): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1179): ssid=NG7005g
I/wpa_supplicant( 1179): ####
D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/WifiStateMachine(  912): == begin of scan result ==
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  912): == (2) end of scan result ==
,D/WifiStateMachine(  912): 0: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -61, frequency: 2412, timestamp: 1198814357, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/WifiStateMachine(  912): 1: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -50, frequency: 5220, timestamp: 357511672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  912): add 2 to mScanResults
D/BatSI   (  912): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  912): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  912): == begin of scan result ==
D/WifiStateMachine(  912): == (2) end of scan result ==
,D/WirelessDisplayService(  912): getDiscoveryDongleList
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): Wireless event: cmd=0x8b15 len=20
,D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1179): nl80211: Connect event
D/wpa_supplicant( 1179): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1179): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1179): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1179): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1179): Add randomness: count=104 entropy=66
I/wpa_supplicant( 1179): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1179): TDLS: Remove peers on association
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1179): EAPOL: enable timer tick
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1179): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): Get randomness: len=32 entropy=67
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
D/WifiMonitor(  912): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  912): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  912): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  912): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  912): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_s,upplicant( 1179): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiStateMachine(  912): Enter handleAssociatedWithEvent
D/WifiStateMachine(  912): Associated
D/Tethering(  912): interfaceLinkStateChanged wlan0, false
D/Tethering(  912): interfaceStatusChanged wlan0, false
D/WifiStateMachine(  912): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  912): Exit handleAssociatedWithEvent
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  912): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
D/Tethering(  912): interfaceStatusChanged wlan0, true
,D/Tethering(  912): [isWifi] getHotspotEnabled: false
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb78659f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1179):    addr=c0:ff:d4:d3:aa:48
D/WifiApDatabaseHandler(  912): updateConnectedAP...
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1179): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6ed2b4a key_idx=2 set_tx=0 seq_len=6 key_len=16
,D/wpa_supplicant( 1179):    broadcast key
D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1179): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1179): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1179): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1179): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13,
I/wpa_supplicant( 1179): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiStateMachine(  912): This record is existed, only update it...
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
E/wpa_supplicant( 1179): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1179): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1179): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1179): set send_ind_to_ndc = 0
I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1179): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1179): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1179): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1179): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1179): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1179): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1179): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1179): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1179): EAPOL authentication completed successfully
I/wpa_supplicant( 1179): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1179): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1179): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiApDatabaseHandler(  912): updateConnectedAP...
D/wpa_supplicant( 1179): nl80211: if_removed already cleared - ignore event
D/Tethering(  912): interfaceLinkStateChanged wlan0, true
,D/Tethering(  912): interfaceStatusChanged wlan0, true
D/Tethering(  912): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/WifiMonitor(  912): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  912): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
,D/WifiMonitor(  912): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED,
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...,
,D/WifiStateMachine(  912): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  912): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiApDatabaseHandler(  912): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  912): This record is existed, only update it...
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 4174): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  912): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  912): updateConnectedAP...
,D/WifiNative-wlan0(  912): doBoolean: SET pno 0
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  912):    returned true
,D/DhcpStateMachine(  912): [StoppedState] Start DHCP
,D/WifiStateMachine(  912): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
D/WifiStateMachine(  912): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  912): acquireWL(42ba16f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 912 1000 null
,D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 1
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 1
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:3
,D/WifiStateMachine(  912): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1179): nl80211: Event message available
D/wpa_supplicant( 1179): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1179): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 1
I/wpa_supplicant( 1179): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  912):    returned null
E/WifiStateMachine(  912): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  912): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  912):    returned null
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a298f8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42a298f8 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 1179): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1179): EAPOL: disable timer tick
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  912): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  912): doBoolean: DRIVER SETSUSPENDMODE 1
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  912):    returned true
,D/WifiNative-wlan0(  912): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1179): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  912):    returned true
D/WifiNative-wlan0(  912): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1179): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  912):    returned true
,D/WifiStateMachine(  912): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  912): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  912): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  912): releaseWL(42ba16f8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [3][0][0]
D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  912): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  912): doBoolean: SignalStrength 97
,D/WIFI_ICON( 1118): updateWifiState: RSSI_CHANGED -1 -> 3
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1179): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): gateway: /192.168.1.1
D/WifiNative-wlan0(  912): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1179): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1179): htc_wext_set_keepalive +
I/wpa_supplicant( 1179): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1179): getPrivFuncNum +	
I/wpa_supplicant( 1179): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1179): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1179): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1179): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1179): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  912):    returned true
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  912): VerifyingLinkState enter
D/WifiStateMachine(  912): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  912): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  912): VerifyingLinkState: enableIpv6,
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
,D/WifiStateMachine(  912): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -58, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
,V/NetworkPolicy(  912): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiDataStallTracker(  912): onReceive: action=android.net.wifi.STATE_CHANGE
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiDataStallTracker(  912): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiWatchdogStateMachine(  912): WAN detection
D/WifiStateTracker(  912): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  912): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/ConnectivityService(  912): Provision feature enable=false
D/ConnectivityService(  912): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  912): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  912): default: teardown()
D/MDST    (  912): default: setTeardownRequested(true)
D/MDST    (  912): default: setEnableApn apnType =default , enable=false
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  912): [NET] getaddrinfo-, SUCCESS
D/MDST    (  912): default: setTeardownRequested(true)
D/ConnectivityService(  912): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  912): Unexpected mtu value: android.net.wifi.WifiStateTracker@428c2010
D/ConnectivityService(  912): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/WISPrService( 4174): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1179): Change stage from stage0 to stage3
,D/WifiStateMachine(  912): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  912): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  912): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  912): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  912): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  912): handleConnectivityChange: resetting
D/Nat464Xlat(  912): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  912): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  912): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  912): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
,I/QuickSettingWifi( 1118): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WirelessDisplayService(  912): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  912):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/PMS     (  912): acquireWL(42b9b560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 912 1000 null
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
D/PMS     (  912): acquireWL(42b9c1f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42bd5eb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/PMS     (  912): releaseWL(42b9c1f0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1455036044321 min interval config: 0 actual interval: 839068
,I/CheckinService( 2188): Checking schedule, now: 1455036883394 next: 1455036074281
,I/CheckinService( 2188): active receiver: enabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2188, uid=10029, userID:0
D/ConnectivityService(  912): mActiveDefaultNetwork: WIFI
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
I/CheckinService( 2188): Preparing to send checkin request
,I/EventLogService( 2188): Accumulating logs since 1455036041478
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/PMS     (  912): releaseWL(42b9b560): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1372): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  371): CdmEngine::OpenSession
,I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  371): PrepareKeyRequest: nonce=3819585625
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4617): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4617): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4617): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4617): Local Branch: 
I/Adreno-EGL( 4617): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4617): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4617):                  aa63bbd948f41d15fc72f585e
,W/Settings( 4617): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  912): releaseWL(42c89100): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  912): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  912): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  912): [AlarmQueuing] connectivity wifi: true
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,V/Tethering(  912): bSetPropertyMultiRAB:false
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  912): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  912): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/CaptivePortalTracker(  912): NoActiveNetworkState
,I/Tethering(  912): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
,I/Tethering(  912): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
,I/Tethering(  912): ipv4Default 0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by  (912/1000)
D/PMS     (  912): acquireWL(42b4eff8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 912 1000 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,I/Tethering(  912): Found interface wlan0
D/Tethering(  912): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.setupwizard (4484/10079)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.backuptransport (1584/10029)
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/PMS     (  912): acquireWL(42c43000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 912 1000 null
D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  912): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
,I/NetworkMonitor( 3898): type=WIFI subType= reason=null isConnected=true
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/GpsLocationProvider(  912): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  912): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  912): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  912): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  912): getNetworkInfo networkType=1 called by com.google.android.music (3898/10154)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (912/1000)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/PMS     (  912): releaseWL(42c43000): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(42b4eff8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (4617/10029)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by  (2405/10021)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.facebook.katana (4465/10027)
I/WVCdm   (  371): CdmEngine::OpenSession
I/WVCdm   (  371): CdmEngine::QueryKeyControlInfo
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
I/WVCdm   (  371): CdmEngine::GenerateKeyRequest
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/WifiStateMachine(  912): It's IPV6 link-local unicast address, No need to broadcast it!
D/libc    (  912): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-, SUCCESS
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  912): [MLHD] enter handleMediaLinkEvent DefaultState
,D/AutoSetting( 1320): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/MobileConnectivityChangeReceiver( 4484): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4484): onReceive CONNECTIVITY_CHANGE networkType=1
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1320): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1320): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  912): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.magazines (4521/10151)
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.apps.plus (4558/10160)
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/PMS     (  912): acquireWL(42de3b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2188): Checkin interval check for package: unspecified last checkin: 1455036044321 min interval config: 0 actual interval: 840138
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  912): releaseWL(42de3b88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2188): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2188): num queued entries: 0
,I/iu.UploadsManager( 2188): num updated entries: 0
,I/iu.SyncManager( 2188): NEXT; no task
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/WVCdm   (  371): PrepareKeyRequest: nonce=1683457882
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1372): [NET] getaddrinfo-, 1
D/libc    ( 1372): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =3608 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  912): acquireWL(42c0c928): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,I/WVCdm   (  371): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1372): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2188): [NET] getaddrinfo-, 1
D/libc    ( 2188): [NET] getaddrinfo_proxy+
,V/NativeCrypto( 2188): SSL shutdown failed: ssl=0x6e83b578: I/O error during system call, Connection timed out
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =e495 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 128
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2188): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1372): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1372): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
D/libc    ( 2188): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2188): [NET] getaddrinfo-,err=8
,D/PMS     (  912): acquireWL(42cb8ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,D/PMS     (  912): releaseWL(42c0c928): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
,I/CheckinTask( 2188): Sending checkin request (12270 bytes)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: starting a change hold
D/PMS     (  912): releaseWL(42cb8ca0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): acquireWL(42d183f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1372 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
D/ConnectivityService(  912): reportInetCondition for net 1, percentage: 100 by  (1372/10029)
D/ConnectivityService(  912): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  912): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  912): getActiveNetworkInfo called by  (1372/10029)
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
D/PMS     (  912): releaseWL(42d183f0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  912): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  912): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=3 [29][1][0]
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2188): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  912): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2188): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  912): getNetworkInfo networkType=9 called by com.google.android.gms (2188/10029)
,D/WifiNative-wlan0(  912): doString: SIGNAL_POLL
,W/WifiHW  (  912): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1179): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1179): nl80211: survey data missing!
E/wpa_supplicant( 1179): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1179): environment dirty rate=0 [3][0][0]
D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,I/CheckinRequestBuilder( 2188): Classify the device as Phone.
,I/CheckinTask( 2188): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2188): Checking schedule, now: 1455036885586 next: 1455559822577
,I/CheckinService( 2188): active receiver: disabled
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
,W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
,I/CheckinService( 2188): Checking schedule, now: 1455036885616 next: 1455559822577
,I/CheckinService( 2188): active receiver: disabled
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
I/PackageManager(  912):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2188, uid=10029, userID:0
,D/CheckinService( 2188): Recording last checkin time for package unspecified as 1455036885621
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360023430
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024093
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024255
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024260
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024264
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360024268
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026887
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360026900
W/AlarmManager(  912): Converted elapesd time is over 1 year! when = 315360029585
,D/PMS     (  912): releaseWL(42bd5eb8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  912): getActiveNetworkInfo called by com.google.android.gms (2188/10029)
,D/GCM     ( 1372): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  912): [NET] getaddrinfo-,err=8
D/libc    (  912): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  912): [NET] getaddrinfo-, 1
,D/libc    (  912): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =133e +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  912): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  912): Find DNS Address www.htc.com/23.59.123.86
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/PMS     (  912): acquireWL(42d51ca8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4671 10111 null
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.645MB for 53840-byte allocation
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  912): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
,D/PMS     (  912): acquireWL(42db30a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
I/BatteryService(  912): n_update end
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/ActivityManager(  912): Resuming delayed broadcast
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
,D/PMS     (  912): releaseWL(42db30a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/ActivityManager(  912): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PMS     (  912): releaseWL(42d51ca8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  912): Resuming delayed broadcast
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1343): Unsupported attribute readOnly
,I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  912):   Scheme: "mmsto"
I/ActivityManager(  912): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  912): acquireWL(42e9f970): PARTIAL_WAKE_LOCK  AsyncService 0x1 4558 10160 null
D/PMS     (  912): acquireWL(42ea0f60): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42e9f970): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  912): releaseWL(42ea0f60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  912): acquireWL(42ea6b50): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ea6b50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,D/PMS     (  912): acquireWL(42eb43b8): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  912): releaseWL(42eb43b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,I/ActivityManager(  912): Delay finish: com.android.vending/com.google.android.finsky.widget.consumption.NowPlayingWidgetProvider,
,D/PMS     (  912): acquireWL(42ebaf48): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ebaf48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Resuming delayed broadcast
,E/PNP_UPDATERD(  355): inotify_add_watch failed. (No such file or directory)
D/PMS     (  912): acquireWL(42ec0420): PARTIAL_WAKE_LOCK  Icing 0x1 2188 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  912): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2188): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2188): updateResources: need to parse f{com.google.android.gms}
,W/PackageManager(  912): Unable to load service info ResolveInfo{42ec2ee8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
,I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 536 ms] updated apps [took 536 ms] 
I/ActivityManager(  912): Resuming delayed broadcast
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  912): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  912): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/RemoteDisplayProvider(  912): start
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
,I/HtcPowerSaver(  912): >> updateStatus
I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1118): closing low battery warning: level=100
I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  912): << updateStatus
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42c97bb0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/LocationProviderProxy(  912): applying state to connected service
D/PMS     (  912): acquireWL(42f1d070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  912): releaseWL(42f1d070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  912): applying state to connected service
,D/PMS     (  912): acquireWL(42ec99b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42ec99b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): acquireWL(42eab818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  912): releaseWL(42eab818): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2188): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2188): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  912): releaseWL(42ec0420): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41fc9d58 -
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/PMS     (  912): acquireWL(42dd22b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 912 1000 WorkSource{1000}
,V/AlarmManager(  912): sending alarm PendingIntent{41f49978: PendingIntentRecord{4270e8a0 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1218051, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  912): releaseWL(42dd22b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1320): service - mHandler: update timezone
D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1523): service - onCreate()
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  912): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  912): batLight: Full, plugged
V/LightsService(  912): setLight #8: color=#c8c800
D/qdlights(  912): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  912): setLight #8: color=#c800
D/qdlights(  912): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  912): [LedInfo] has indicator attribute
D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  912): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/DotMatrix( 1568): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
D/AutoSetting( 1523): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1523): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1523): service - mHandler: update timezone
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1523): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1523): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1523): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1118): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1118): release indeterminate drawable android.widget.OnDemandProgressBar{41f57340 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1118): com.htc.htclocationservice 2 7 3 11
,D/PMS     (  912): acquireWL(42d12600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  912): n_update end
,D/UsbnetService(  912): BroadcastReceiver::onReceive+
D/UsbnetService(  912): onReceive BATTERY_CHANGED
D/UsbnetService(  912):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  912): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1118): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1118): closing low battery warning: level=100
D/PowerUI ( 1118): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  912): releaseWL(42d12600): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  912): updateBatteryInfo
D/PMS     (  912): runPSCheck
D/HtcPowerSaver(  912): Checking...
I/HtcPowerSaver(  912): >> updateStatus
,I/HtcPowerSaver(  912): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  912): << updateStatus
,I/BatteryController( 1118): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  912): Waited long enough for: ServiceRecord{42ef2d18 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1523): service - handleMessage() stop self
,D/AutoSetting( 1523): service - onDestroy() END
,D/AutoSetting( 1523): service - handleMessage() quit looper
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4862): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4862): ====startRecUseTime====
D/htc.customization.log.level( 4862):  is 
W/CustomizationLogLevel( 4862): Level value is invalid, use default level 2
D/CustomizationManager( 4862):  Read ACC file spent 0.053 (s)
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4862): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4862): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4862): Parsing tag category name = system
I/CustomizationCIDLoader( 4862): Parsing tag category name = application
I/CustomizationCIDLoader( 4862): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4862): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4862): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4862): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4862): Parsing tag category name = Settings
D/CustomizationManager( 4862):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4862):  All configurations done spent 0.091 (s)
W/HtcNativeFlag( 4862): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4862): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4862): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4862): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  912): deletePackageAsUser: pkg=com.test.thalitest, pid=4862, uid=2000 user=0
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  912): Skipping PackageSetting{42613328 com.example.hello/10397} due to missing metadata
W/PackageSettings(  912): Skipping PackageSetting{4261bd70 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  912): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  912): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  912): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1343): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  912): acquireWL(42f1d070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PMS     (  912): releaseWL(42f1d070): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
W/AccTypeManager( 1343): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1343): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/IcingCorporaProvider( 2842): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1343): Unsupported attribute readOnly
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "sms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/ActivityManager(  912): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4876 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "smsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  912): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/IcingCorporaProvider( 2842): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mms"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  912):   Action: "android.intent.action.SENDTO"
I/PackageManager(  912):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  912):   Scheme: "mmsto"
I/PackageManager(  912): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/PackageManager(  912): Unable to load service info ResolveInfo{42dc72e0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  912): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  912): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  912): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  912): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  912): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  912): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  912): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  912): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  912): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  912): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  912): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  912): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4876): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4876): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4876): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4876): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4876): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4876): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4876): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4876): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4876): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4876): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4876): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4876): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4876): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4876): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4876): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4876): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4876): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4876): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4876): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4876): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4876): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4876): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4876): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4876): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4876): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4876): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4876): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4876): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4876): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4876): threadid=11: thread exiting with uncaught exception (group=0x41b04e30)
E/ActivityManager(  912): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4876): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4876): Process: com.google.android.apps.docs, PID: 4876
E/AndroidRuntime( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4876): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4876): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4876): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4876): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4876): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
E/SQLiteDatabase( 4876): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4876): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4876): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4876): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4876): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4876): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4876): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4876): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4876): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4876): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4876): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4876): Opened ClientFlag.db in read-only mode
D/Process ( 4876): killProcess, pid=4876
D/Process ( 4876): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  912): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4894 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  912): Recipient 4876
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.apps.docs (pid 4876) has died.
D/RemoteDisplayProvider(  912): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  912): start
W/AtomicFile(  912): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  912): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4894): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4894): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4894): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4894): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4894): threadid=10: thread exiting with uncaught exception (group=0x41b04e30)
E/AndroidRuntime( 4894): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4894): Process: com.android.keychain, PID: 4894
E/AndroidRuntime( 4894): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4894): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4894): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4894): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4894): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4894): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4894): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4894): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  912): App crashed! Process: com.android.keychain
I/ActivityManager(  912): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4908 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  912): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4894): killProcess, pid=4894
D/Process ( 4894): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  912): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  912): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1455036952154.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  912): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  912): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  912): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  912): 	... 4 more
I/ActivityManager(  912): Recipient 4894
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.android.keychain (pid 4894) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4908): getInstance(Context context)
D/AppTag  ( 4908): getInstance(Context context)
D/AppTag  ( 4908): onCreate()
D/PMS     (  912): acquireWL(42b658b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4558 10160 null
D/PMS     (  912): releaseWL(42b658b8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  912): killProcessQuiet, pid=4443
W/dalvikvm( 4189): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  912): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  912): Killing 4443:com.htc.aurora/u0a49 (adj 15): empty #17
I/ActivityManager(  912): Recipient 4443
D/PackageBroadcastService( 2188): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2188): Clearing selected account for com.test.thalitest
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2188): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2188): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2188): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2188): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2188): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2188): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2188): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2188): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2188): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2188): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2188): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2188): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2188): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2188): App measurement is starting up, version: 8489
I/GMPM-SVC( 2188): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/ActivityManager(  912): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 2188): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2188): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x65709d18
E/DriveAsyncService( 2188): disk I/O error (code 3850)
E/DriveAsyncService( 2188): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2188): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2188): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2188): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2188): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2188): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2188): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 2188): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2188): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x6e4fd300
W/dalvikvm( 2188): threadid=48: thread exiting with uncaught exception (group=0x41b04e30)
E/AndroidRuntime( 2188): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2188): Process: com.google.android.gms, PID: 2188
E/AndroidRuntime( 2188): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2188): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2188): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2188): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2188): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2188): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 2188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2188): Module APK com.google.android.play.games already loaded
E/ActivityManager(  912): App crashed! Process: com.google.android.gms
D/Process ( 2188): killProcess, pid=2188
D/Process ( 2188): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  912): Can't write: system_app_crash
E/DropBoxManagerService(  912): java.io.FileNotFoundException: /data/system/dropbox/drop145.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  912): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  912): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  912): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  912): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  912): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  912): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  912): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  912): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  912): 	... 5 more
I/ActivityManager(  912): Recipient 2188
I/DisplayManagerService(  912): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  912): Process com.google.android.gms (pid 2188) has died.
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
D/WifiService(  912): Client connection lost with reason: 4
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 10999ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20999ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30998ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 40998ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 40997ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 50997ms
W/ActivityManager(  912): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 50997ms

```
